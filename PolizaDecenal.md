# Guía del Agente LLM - Sistema Decenal Oracle DB

## Descripción General

El sistema Decenal es un módulo especializado dentro de la base de datos Oracle Tronador que maneja seguros de responsabilidad civil decenal y todo riesgo constructor. Este documento proporciona información técnica.

## Arquitectura del Sistema

### Componentes Principales

#### 1. Packages Principales
- **SIM_PCK_DECENAL_TOOLS**: Package principal con herramientas y utilidades decenales
- **SIM_PCK_DECENAL**: Package core con funcionalidades de cálculo y procesamiento
- **SIM_PCK_DECENAL_COMIS**: Manejo de comisiones decenales

#### 2. Tablas Específicas Decenal

##### Tablas de Control y Procesamiento
- **SIM_DECENAL_ACTUALIZARC**: Control de actualización de pólizas RC
  - `NUM_SECU_POL`: Número secuencial de póliza
  - `MCA_ACTUALIZA`: Marca de actualización ('N', 'S', 'A')
  - `FECHA_ORIGEN`: Fecha de origen del registro
  - `FECHA_ACTUALIZA`: Fecha de actualización

- **SIM_DECENAL_CONEXPAS**: Conexión con pasarela de pagos
  - `NUM_SECU_POL`: Número secuencial de póliza
  - `NUM_POL1`: Número de póliza definitiva
  - `FECHA_ORIGEN`: Fecha de origen
  - `FECHA_ACTUALIZA`: Fecha de actualización
  - `OBSERVACIONES`: Log de observaciones

- **SIM_DECENAL_RECAUDO**: Control de recaudos y pagos
  - `NUM_SECU_POL`: Número secuencial de póliza
  - `MCA_CONVERSION`: Estado de conversión ('N', 'W', 'R')
  - `FECHA_REGISTRO`: Fecha de registro
  - `FECHA_PAGO`: Fecha de pago
  - `FECHA_PROCESAMIENTO`: Fecha de procesamiento
  - `LOG_DEL_PROCESO`: Log detallado del proceso

##### Tablas de Anticipos y Saldos
- **SIM_ANTICIPOS_DEC_SALDO**: Saldos de anticipos decenales
- **SIM_ANTICIPOS_DEC_SALDO_COM**: Comisiones de anticipos decenales
- **SIM_ANTICIPOS_DEC**: Anticipos decenales principales

##### Tablas de Reportes
- **SIM_REPORTE_DECENAL**: Reportes del sistema decenal
- **SIM_PARAM_DECENAL**: Parámetros de configuración decenal

## Funcionalidades Principales

### 1. Gestión de Pólizas RC (Responsabilidad Civil)

#### Procedimiento: `proc_ins_decenal_polizasrc`
**Propósito**: Inserta pólizas RC en el sistema de control decenal
**Parámetros**:
- `ip_numsecupol`: Número secuencial de póliza

**Lógica**:
- Verifica si el tipo de póliza es RC (TIPOPOL = '3')
- Inserta registro en `SIM_DECENAL_ACTUALIZARC` con marca 'N'

#### Procedimiento: `proc_asociar_polizasrc`
**Propósito**: Asocia pólizas RC con pólizas decenales
**Funcionalidad**:
- Procesa pólizas pendientes (MCA_ACTUALIZA='N')
- Valida estado de póliza (anulada/provisional)
- Actualiza marcas según el resultado del procesamiento

### 2. Asociación de Números de Póliza

#### Procedimiento: `proc_asocia_numpolrc`
**Propósito**: Asocia números de póliza RC con pólizas decenales
**Parámetros**:
- `ip_numsecupol`: Número secuencial de póliza
- `ip_numend`: Número de endoso
- `Op_Resultado`: Resultado de la operación
- `Op_Arrerrores`: Array de errores

**Proceso**:
1. Obtiene datos de la póliza RC
2. Busca la póliza decenal correspondiente
3. Actualiza o inserta el campo `NUM_POL1_RC` en la póliza decenal

### 3. Conexión con Pasarela de Pagos

#### Procedimiento: `proc_conecta_pasarela`
**Propósito**: Actualiza saldos de negocios pagados desde pasarela
**Funcionalidad**:
- Identifica pólizas con situación 'CT' (Cobrado Total) o 'PP'
- Actualiza tablas de saldos y comisiones
- Registra logs de procesamiento
- Actualiza préstamos generados por comisiones

### 4. Impresión de Pólizas RC

#### Procedimiento: `Proc_RC_Imp`
**Propósito**: Genera datos para impresión de pólizas RC/Decenal
**Parámetros**:
- `Ip_Nronegocio`: Número de póliza o cotización
- `Ip_Numend`: Número de endoso
- `Ip_Codries`: Código de riesgo
- `Ip_Tiponeg`: Tipo de negocio ('P' Póliza, 'C' Cotización)

**Secciones de Datos Generadas**:
- Datos generales de la póliza
- Información del tomador
- Fechas de vigencia
- Asegurados y beneficiarios
- Agentes
- Datos de riesgo (proyecto, etapa, dirección, etc.)
- Amparos y coberturas
- Valores a pagar

### 5. Validación de Vigencias

#### Procedimiento: `proc_valida_vig_decenal`
**Propósito**: Valida modificaciones de vigencia en pólizas RC/Decenal
**Restricciones**:
- No permite modificar vigencias de pólizas RC o Decenal ya emitidas
- Aplica solo para CIA=3, SECC=81, RAMO=160

### 6. Actualización de Marcas RC

#### Procedimiento: `PROC_ACTUALIZA_MARCAS_RC`
**Propósito**: Actualiza marcas de pólizas RC anuladas o rehabilitadas
**Funcionalidad**:
- Identifica anulaciones RC (COD_END=14, SUB_COD_END=6)
- Identifica rehabilitaciones RC (COD_END=14, SUB_COD_END=9)
- Actualiza o elimina referencias en pólizas decenales

### 7. Validación de Recaudos

#### Procedimiento: `proc_valida_recaudo`
**Propósito**: Valida y procesa recaudos de pólizas decenales
**Estados de Conversión**:
- 'N': Nuevo/Pendiente
- 'W': En proceso (Waiting)
- 'R': Registrado/Completado

**Proceso**:
1. Procesa pólizas marcadas como 'W'
2. Ejecuta cálculo de anticipos
3. Valida facturas con situación 'CT'
4. Actualiza estados según resultado

## Tipos de Pólizas Decenal

### Códigos de Tipo de Póliza (TIPOPOL)
- **1**: DECENAL - Seguro decenal estándar
- **2**: TODO RIESGO - Cobertura todo riesgo constructor
- **3**: RC - Responsabilidad civil

### Estructura de Riesgos
Los riesgos en pólizas decenales incluyen:
- **MANZANA**: Proyecto/Manzana
- **NUM_ETAPAS**: Número de etapas
- **DIRECC_RIES**: Dirección del riesgo
- **CPOS_RIES**: Ciudad del riesgo
- **TXT_CONJUNTO**: Conjunto/Agrupación
- **UEI1-UEI5**: Unidades específicas (Torre/Edificio/Casa)
- **VLR_ASEG_REC**: Valor asegurado reconstrucción
- **VLR_ASEG_VTA**: Valor asegurado venta

## Parámetros de Configuración

### Tabla C9999909 - Parámetros Decenal
- **COD_TAB = 'DECENAL'**: Configuración general decenal
- **COD_TAB = 'DECENAL_IMP'**: Parámetros de impresión
- **COD_TAB = 'DECENAL_END_ANT'**: Configuración de endosos de anticipo

## Estados y Situaciones

### Estados de Facturación (A2990700.COD_SITUACION)
- **CT**: Cobrado Total
- **PP**: Pago Parcial
- **PE**: Pendiente

### Marcas de Control
- **MCA_ACTUALIZA**: 'N' (No procesado), 'S' (Procesado), 'A' (Anulado)
- **MCA_CONVERSION**: 'N' (Nuevo), 'W' (Esperando), 'R' (Registrado)

## Procedimientos de Mantenimiento

### Poblado de Tabla de Recaudo
```sql
PROCEDURE proc_poblar_tabla_recaudo
```
Inserta pólizas pendientes de procesamiento en `SIM_DECENAL_RECAUDO`

### Post Conversión CT
```sql
PROCEDURE proc_post_ct_conversion(ip_numsecupol IN NUMBER)
```
Actualiza estado de pólizas después de conversión a CT

## Logging y Auditoría

El sistema utiliza varios mecanismos de logging:
- **SIM_PROC_LOG**: Logging general del sistema
- **Sim_Pck_Decenal.ins_log_decenal**: Log específico decenal
- **Sim_Pck_Decenal.Upd_log_decenal**: Actualización de logs

## Integración con Otros Sistemas

### Conexión con Prestamos
- Actualización de préstamos por comisiones de anticipo
- Procedimiento: `sim_pck_decenal.proc_act_prestamo`

### Integración con Terceros
- Validación de datos de terceros
- Package: `PCK999_TERCEROS`

### Cálculo de Reservas
- Fórmulas RPND (Reserva Prima No Devengada)
- Package: `SIM_PCK_CB200351`

## Casos de Uso Comunes

### 1. Consulta de Estado de Póliza Decenal
```sql
SELECT t.num_secu_pol, t.mca_actualiza, t.fecha_origen, t.fecha_actualiza
FROM SIM_DECENAL_ACTUALIZARC t
WHERE t.num_secu_pol = [NUMERO_POLIZA];
```

### 2. Verificación de Pagos
```sql
SELECT r.num_secu_pol, r.mca_conversion, r.fecha_pago, r.log_del_proceso
FROM SIM_DECENAL_RECAUDO r
WHERE r.num_secu_pol = [NUMERO_POLIZA];
```

### 3. Consulta de Asociación RC-Decenal
```sql
SELECT a.num_secu_pol, a.valor_campo as num_pol_rc
FROM a2000020 a
WHERE a.cod_campo = 'NUM_POL1_RC'
AND a.num_secu_pol = [NUMERO_POLIZA_DECENAL];
```

## Mensajes de Error Comunes

- **-20011**: No se encontró la póliza RC/Decenal
- **-20001**: No se puede modificar la vigencia RC o Decenal
- **-20000**: Error general del sistema

## Consideraciones Técnicas

1. **Transaccionalidad**: Todos los procedimientos manejan commits explícitos
2. **Manejo de Excepciones**: Implementación robusta de manejo de errores
3. **Logging Detallado**: Registro completo de operaciones para auditoría
4. **Validaciones de Negocio**: Múltiples validaciones según reglas del negocio decenal


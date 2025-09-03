# Poliza de Arrendamiento Individual

Identificación del producto:

- COD_CIA: 3
- COD_SECC: 37
- COD_RAMO: 486

# 1. Generaridades

Arrendamiento póliza individual

### Funcionamiento de las indemnizaciones

**El seguro de arrendamiento póliza individual,** se administra en el Libertador, pero se reportan los siniestros al módulo de Simón, para realizar los pagos y la contabilidad.

### Datos variables del producto:

- CONS_SAI - Consecutivo siniestro SAI
- FECHA_PAGO - Fecha de pago

### Causas apertura siniestro

Las causas que maneja la póliza de arrendamiento para la creación de siniestros son las siguientes:

- 993 - Incumplimiento contrato de arrendamiento
- 994 - Muerte del arrendatario
- 995 - Desocupación del inmueble
- 996 - Mal uso del inmueble

### Causas modificación siniestro

Las causas que maneja la póliza de arrendamiento para la modificación de siniestros son las siguientes:

Las causas que maneja la póliza de arrendamiento para la modificación de siniestros son las siguientes:

- 1 - Error aviso
- 12 - Desestimiento del asegurado

### Causas anulación de siniestros

La única causa que maneja la póliza de arrendamiento para la anulación de siniestros es la siguiente:

- 12 - Error en el aviso

### Consecuencias

Las consecuencias que maneja la póliza de arrendamiento para la creación de siniestros son las siguientes:

- 45 - Mora en el pago del arrendamiento
- 46 - No pago de servicios públicos
- 64 - Daños al inmueble

### Coberturas

Las coberturas que se poseen en la póliza de arrendamiento son las siguientes:

- 715 - Básico de arrendamiento
    - 716 - Canon de arrendamiento
    - 717 - Cuotas de administración
- 718 - Servicios públicos
- 719 - Daños y faltantes

### Expedientes

Los tipos de expedientes que maneja la póliza de arrendamiento para indemnizaciones son los siguientes:

- ARR - Gastos por arrendamiento
- DYF - Daños y faltantes
- SEP - Servicios públicos
- RES - Recobros y subrogaciones
- WRS - Reintegro de siniestros
- GSJ - Otros gastos jurídicos de siniestros

### Causa Consecuencia Cobertura

Combinaciones permitidas para causas, consecuencias, coberturas y tipos de expedientes:

- Causa 993 - Consecuencia 45 - Cobertura 716 - Expediente ARR - Concepto Reserva 60
- Causa 993 - Consecuencia 45 - Cobertura 716 - Expediente RES - Concepto Reserva 60
- Causa 993 - Consecuencia 45 - Cobertura 716 - Expediente WRS - Concepto Reserva 60
- Causa 993 - Consecuencia 45 - Cobertura 716 - Expediente GSJ - Concepto Reserva 62
- Causa 993 - Consecuencia 45 - Cobertura 717 - Expediente ARR - Concepto Reserva 60
- Causa 993 - Consecuencia 45 - Cobertura 717 - Expediente RES - Concepto Reserva 60
- Causa 993 - Consecuencia 45 - Cobertura 717 - Expediente WRS - Concepto Reserva 60
- Causa 993 - Consecuencia 45 - Cobertura 717 - Expediente GSJ - Concepto Reserva 62
- Causa 994 - Consecuencia 45 - Cobertura 716 - Expediente ARR - Concepto Reserva 60
- Causa 994 - Consecuencia 45 - Cobertura 716 - Expediente RES - Concepto Reserva 60
- Causa 994 - Consecuencia 45 - Cobertura 716 - Expediente WRS - Concepto Reserva 60
- Causa 994 - Consecuencia 45 - Cobertura 716 - Expediente GSJ - Concepto Reserva 62
- Causa 994 - Consecuencia 45 - Cobertura 717 - Expediente ARR - Concepto Reserva 60
- Causa 994 - Consecuencia 45 - Cobertura 717 - Expediente RES - Concepto Reserva 60
- Causa 994 - Consecuencia 45 - Cobertura 717 - Expediente WRS - Concepto Reserva 60
- Causa 994 - Consecuencia 45 - Cobertura 717 - Expediente GSJ - Concepto Reserva 62
- Causa 995 - Consecuencia 45 - Cobertura 716 - Expediente ARR - Concepto Reserva 60
- Causa 995 - Consecuencia 45 - Cobertura 716 - Expediente RES - Concepto Reserva 60
- Causa 995 - Consecuencia 45 - Cobertura 716 - Expediente WRS - Concepto Reserva 60
- Causa 995 - Consecuencia 45 - Cobertura 716 - Expediente GSJ - Concepto Reserva 62
- Causa 995 - Consecuencia 46 - Cobertura 717 - Expediente ARR - Concepto Reserva 60
- Causa 995 - Consecuencia 46 - Cobertura 717 - Expediente RES - Concepto Reserva 60
- Causa 995 - Consecuencia 46 - Cobertura 717 - Expediente WRS - Concepto Reserva 60
- Causa 995 - Consecuencia 46 - Cobertura 717 - Expediente GSJ - Concepto Reserva 62
- Causa 995 - Consecuencia 46 - Cobertura 718 - Expediente SEP - Concepto Reserva 60
- Causa 995 - Consecuencia 46 - Cobertura 718 - Expediente RES - Concepto Reserva 60
- Causa 995 - Consecuencia 46 - Cobertura 718 - Expediente WRS - Concepto Reserva 60
- Causa 995 - Consecuencia 46 - Cobertura 718 - Expediente GSJ - Concepto Reserva 62
- Causa 996 - Consecuencia 64 - Cobertura 719 - Expediente DYF - Concepto Reserva 60
- Causa 996 - Consecuencia 64 - Cobertura 719 - Expediente RES - Concepto Reserva 60
- Causa 996 - Consecuencia 64 - Cobertura 719 - Expediente WRS - Concepto Reserva 60
- Causa 996 - Consecuencia 64 - Cobertura 719 - Expediente GSJ - Concepto Reserva 62

### Concepto liquidación

Conceptos de liquidación para el concepto de reserva 60:

- 295 - INGRESO X RECOBRO Y REINTEGROS
- 311 - HONORARIOS ABOG.EXT.SEG.GRALES
- 312 - HONOR.ABOG.EXT.PROC.CIVIL/CONT
- 321 - VR.PAGADO POR CRUCE PRIMA SEG.
- 329 - VALOR PAGO AL ASEG.SEG.GRALES
- 330 - HONORARIOS AJUST.SIN.SEG.GRALS
- 331 - GTOS.AJUSTADORES SEG. GENERALS
- 333 - SERVICIOS DE INVESTIG.STROS
- 336 - GASTOS INVESTIGACION STROS.
- 338 - SERVICIOS REPARAC.DAnOS SEG.GR
- 364 - PASAJES AEREOS BAJA TEMPORADA
- 398 - COASEGURO ACEPTADO
- 445 - SER.HOTEL NO INSCRITO REGNALTU
- 454 - HONORARIOS REEMBOLSOS SINITROS
- 573 - SERVICIO DE TRANSPORTE AEROLIN
- 574 - TASA AEROPORTUARIA
- 731 - OTROS SERVICIOS
- 737 - SERVICIOS HOTELEROS 10%

### Código de texto y subcódigo de texto para liquidación

Los códigos de texto y subcódigo de texto se utilizan para estadísticas de liquidaciones, se definen para cada producto, los definidos para arrendamiento son:

- 1 - 1 PAGO TOTAL FACTURA
- 1 - 2 PAGO PARCIAL FACTURA
- 1 - 3 REINTEGRO SINIESTROS
- 1 - 4 RECOBROS DE SINIESTROS

## Estructura de tablas

- SIM_CARGA_CONTROL_PROCESO - Tabla de control para registrar la ejecución de la interfaz.
- SIM_CARGA_SINIESTROS - Tabla con la información de apertura, modificación y cambio de estado de siniestros
- SIM_CARGA_SINIESTROS_JN - Tabla de auditoría para registrar los cambios de la información
- SIM_CARGA_SINIESTROS_HI - Tabla de histórico, a esta tabla se pasan los registros de la tabla SIM_CARGA_SINIESTROS cuando se vayan borrando luego de un mes de procesados
- SIM_CARGA_VAR_SINIESTROS - Tabla con la información para cargar los datos variables del siniestro o modificarlos
- SIM_CARGA_VAR_SINIESTROS_JN - Tabla de auditoría
- SIM_CARGA_VAR_SINIESTROS_HI - Tabla de históricos
- SIM_CARGA_EXPEDIENTES - Tabla con la información para cargar los datos de creación y modificación de expedientes
- SIM_CARGA_EXPEDIENTES_JN - Tabla de auditoría
- SIM_CARGA_EXPEDIENTES_HI - Tabla de históricos
- SIM_CARGA_VAR_EXPEDIENTES - Tabla con la información para la creación o modificación de datos variables del expediente
- SIM_CARGA_VAR_EXPEDIENTES_JN - Tabla de auditoría
- SIM_CARGA_VAR_EXPEDIENTES_HI - Tabla de históricos
- SIM_CARGA_RESERVAS - Tabla con la información para la creación o modificación de la reserva
- SIM_CARGA_RESERVAS_JN - Tabla de auditoría
- SIM_CARGA_RESERVAS_HI - Tabla de históricos
- SIM_CARGA_LIQUIDACIONES - Tabla con la información para la creación de liquidaciones
- SIM_CARGA_LIQUIDACIONES_JN - Tabla de auditoría
- SIM_CARGA_LIQUIDACIONES_HI - Tabla de históricos
- SIM_CARGA_DET_LIQUIDACIONES - Tabla con la información del detalle de las liquidaciones
- SIM_CARGA_DET_LIQUIDACIONES_JN - Tabla de auditoría
- SIM_CARGA_DET_LIQUIDACIONES_HI - Tabla de históricos
- SIM_CARGA_VAR_LIQUIDACIONES - Tabla con la información de los datos variables de las liquidaciones
- SIM_CARGA_VAR_LIQUIDACIONES_JN - Tabla de auditoría
- SIM_CARGA_VAR_LIQUIDACIONES_HI - Tabla de históricos
- SIM_CARGA_ERRORES - Tabla con el detalle de los errores presentados en el proceso, para todas las tablas implicadas
- SIM_CARGA_ERRORES_JN - Tabla de auditoría - Que no se encuentra en uso
- SIM_CARGA_ERRORES_HI - Tabla de históricos - Que no se encuentra en uso

### **SIM_CARGA_CONTROL_PROCESO**

Tabla que almacena la ejecución de las interfaces.

- SECUENCIA - Secuencia de la tabla que debe ser tomada de SEQ_SIM_CAR_CONTROL
- FECHA - Fecha de inicio de la ejecución
- ESTADO - Indica el estado del proceso I-Iniciado T-Terminado
- COD_CIA - Código de la compañía
- COD_SECC - Código de la sección
- COD_RAMO - Código del ramo o producto
- SINIESTROS_CREADOS - Cantidad de siniestros creados en el proceso
- SINIESTROS_ERROR - Cantidad de siniestros creados con error en el proceso
- SINIESTROS_MODIFICADOS - Cantidad de siniestros modificados o con cambio de estado realizado
- SINIESTROS_NO_MOD - Cantidad de siniestros no modificados o a los cuales no se les pudo cambiar el estado
- EXPEDIENTES_CREADOS - Cantidad de expedientes creados
- EXPEDIENTES_ERROR - Cantidad de expedientes que no pudieron ser creados
- EXPEDIENTES_MODIFICADOS - Cantidad de expedientes modificados
- EXPEDIENTES_NO_MOD - Cantidad de expedientes que no se pudieron modificar
- RESERVAS_CREADAS - Cantidad de reservas creadas
- RESERVAS_ERROR - Cantidad de reservas que no se pudieron crear
- LIQUIDACIONES_CREADAS - Cantidad de liquidaciones creadas
- LIQUIDACIONES_ERROR - Cantidad de liquidaciones procesadas con error
- USUARIO_CREACION - Usuario que realiza la ejecución de la interfaz
- FECHA_CREACION - Fecha de ejecución de la interfaz
- USUARIO_MODIFICACION - Usuario que modifica la ejecución del proceso
- FECHA_MODIFICACION - Fecha de modificación de la ejecución del proceso
- PROCESO - Proceso 70 apertura siniestro, 79 objeción, 75 modificación, 78 cambio estado
- SEC_PROCESO - Sale de la solicitud de ejecución IP_PROCESO.P_SUBPROCESO, sirve para identificar ejecuciones puntuales
- FECHA_FIN - Fecha de terminación de ejecución de la interfaz

### **SIM_CARGA_SINIESTROS**

Tabla que recibe la información necesaria para poblar la tabla de siniestros A7000900, dependiendo del proceso, se tienen los datos que deben ser no nulos para permitir procesar correctamente la solicitud.

- SECUENCIA - Secuencia de la tabla que debe ser tomada de SEQ_SIM_CAR_SINI
- PROCESO - Proceso 70 apertura siniestro, 79 objeción, 75 modificación, 78 cambio estado
- ENT_COLOCADORA - Código de la entidad colocadora 25-Libertador
- SISTEMA_ORIGEN - Código del sistema origen 7-Libertador
- COD_CIA - Código de la compañía 3-Seguros Comerciales
- COD_SECC - Código de la sección 37-Arrendamiento
- COD_RAMO - Código del ramo o producto 486-Seguro Arrendamiento
- NUM_POL1 - Número normal de la póliza NUM_POL1
- POL_PRINCIPAL - Indicador de póliza principal (S o NULL) NULL para arrendamiento
- FECHA_SINI - Fecha en que ocurre el siniestro
- HORA_SINI - Hora de ocurrencia del siniestro (Formato HH:MI)
- FECHA_DENU_SINI - Fecha en que se denuncia el siniestro
- COD_CAUSA_SINI - Código de la causa del siniestro
- TDOC_TERCERO_TOM - Tipo documento del tomador de la póliza
- NDOC_TERCERO_TOM - Número documento del tomador de la póliza
- TDOC_TERCERO_ASEG - Tipo documento del asegurado de la póliza
- NDOC_TERCERO_ASEG - Documento del asegurado de la póliza
- COD_RIES - Código del riesgo. Valor por defecto 1
- DESC_SINI - Descripción del siniestro
- FECHA_FORMALIZAC - Fecha de formalización del siniestro cuando se recibe toda la documentación
- MCA_MAS_POLIZ - Marca de afecta más pólizas (Null por defecto)
- TIPO_DEC - Tipo de denuncia (Por defecto D - Definitivo)
- COD_USER - Usuario que realiza la invocación
- LONGITUD - Coordenada geográfica de la longitud del siniestro
- LATITUD - Coordenada geográfica de la latitud
- ALTITUD - Coordenada geográfica de la altitud
- NUM_SINI - Número de siniestro SIMON
- COD_CAUSA_MODI - Código de la causa de modificación al siniestro
- FECHA_MODI - Fecha en que se modifica el siniestro
- COD_CAUSA_BAJA - Código de la causa de baja del siniestro
- FECHA_BAJA - Fecha en que se modifica el siniestro
- COD_CAUSA_REAP - Código de la causa de reapertura del siniestro
- FECHA_REAPERTURA - Fecha en que se realiza la reapertura del siniestro
- ESTADO_SINIESTRO - Estado al que debe pasarse el siniestro en caso de cambio de estado
- SIM_USUARIO - Usuario tronador, sale de la tabla USUARIO campo CODIGO_USUARIO
- MCA_PROCESO - Nulo valor inicial, N no procesado, S procesado correctamente, C procesado correctamente con controles técnicos a autorizar
- FECHA_PROCESO - Fecha en que se procesa la información
- MCA_PROCESO_TER - Marca de procesado por parte de la aplicación del tercero que inicialmente ingresa la información para leer el número de siniestro
- FECHA_PROCESO_TER - Fecha en que procesa la información el tercero
- USUARIO_CREACION - Usuario de base de datos que realiza la inserción del registro
- FECHA_CREACION - Fecha en la que se crea el registro
- USUARIO_MODIFICACION - Usuario que realiza la última modificación al registro
- FECHA_MODIFICACION - Fecha de modificación del registro
- SEC_CONTROL - Campo utilizado para evitar problemas con ejecuciones concurrentes se debe ingresar nulo

### **SIM_CARGA_VAR_SINIESTROS**

En esta tabla se recibe la información para alimentar la tabla de datos variables A7000025, y por esto la información depende de la parametrización del producto.

- SECUENCIA_CAR_SINI - Secuencia que viene de la tabla SIM_CARGA_SINIESTROS, indica cual es el siniestro para el que aplica el dato variable
- CONSECUTIVO - Secuencia manual para indicar la cantidad de datos variables enviados
- PROCESO - Proceso 70 apertura siniestro, 75 modificación
- COD_CIA - Código de la compañía
- COD_SECC - Código de la sección
- COD_RAMO - Código del ramo o producto
- NUM_POL1 - Número normal de la póliza NUM_POL1
- NUM_SINI - Número del siniestro para modificaciones
- COD_NIVEL - Depende de la definición del producto
- COD_GRUPO - Por defecto 1 a menos que el nivel acepte varios datos variables como puede ser reclamantes, beneficiarios, etc
- COD_CAMPO - Nombre del campo parametrizado como dato variable
- VALOR_CAMPO - Valor a almacenar para el dato variable
- MCA_PROCESO - Nulo valor inicial, N no procesado, S procesado correctamente, C procesado correctamente con controles técnicos a autorizar
- FECHA_PROCESO - Fecha en que se procesa la información
- MCA_PROCESO_TER - Marca de procesado por parte de la aplicación del tercero que inicialmente ingresa la información para leer el número de siniestro
- FECHA_PROCESO_TER - Fecha en que procesa la información el tercero
- USUARIO_CREACION - Usuario Oracle que realiza la inserción del registro
- FECHA_CREACION - Fecha en la que se crea el registro
- USUARIO_MODIFICACION - Usuario que realiza la última modificación al registro
- FECHA_MODIFICACION - Fecha de modificación del registro
- SEC_CONTROL - Campo utilizado para evitar problemas con ejecuciones concurrentes se debe ingresar nulo

### **SIM_CARGA_EXPEDIENTES**

En esta tabla se recibe la información para alimentar la tabla de expedientes A7001000, y por esto la información depende de la parametrización del producto.

- SECUENCIA - Secuencia de la tabla que debe ser tomada de SEQ_SIM_CAR_EXPED
- SECUENCIA_CAR_SINI - Secuencia que viene de la tabla SIM_CARGA_SINIESTROS, se requiere cuando el proceso corresponde a apertura de siniestro.
- PROCESO - Proceso 70 apertura siniestro, 771 creación expedientes, 772 modificación expedientes, 773 anulación de expedientes, 774 reapertura de expedientes, 775 creación de expedientes de Recupero.
- SISTEMA_ORIGEN - Código del sistema origen
- COD_CIA - Código de la compañía
- COD_SECC - Código de la sección
- COD_RAMO - Código del ramo o producto
- NUM_SINI - Número del siniestro para modificaciones
- TIPO_EXPED - Tipo de expediente a crear o modificar.
- NRO_EXPED - Número de expediente creado, o número de expediente a modificar reserva
- FEC_APER_EXP - Fecha de apertura del expediente
- COD_USER - Código del usuario que realiza la creación o modificación
- COD_AGEN_TRAMI - Código de la agencia que debe tramitar el expediente
- COD_MON - Código de la moneda para la reserva, 1 pesos.
- TASA_CAMBIO - Valor de la tasa de cambio para conversión de monedas, 1 para pesos.
- MCA_RECUP - Enviar X cuando el expediente a crear corresponda a recupero, en otro caso NULL
- NRO_EXPED_AFEC - Número de expediente afectado para expedientes de reintegros
- COD_MODI_EXP - Código de la causa de modificación al expediente.
- FEC_MODI_EXP - Fecha de modificación del expediente
- COD_BAJA_EXP - Código de causa de anulación del expediente.
- FEC_BAJA_EXP - Fecha de anulación del expediente
- COD_REAP_EXP - Código de la causa de reapertura del expediente
- FEC_REAP_EXP - Fecha de reapertura del expediente
- SIM_USUARIO - Usuario tronador, sale de la tabla USUARIO campo CODIGO_USUARIO
- MCA_PROCESO - Nulo valor inicial, N no procesado, S procesado correctamente, C procesado correctamente con controles técnicos a autorizar
- FECHA_PROCESO - Fecha en que se procesa la información
- MCA_PROCESO_TER - Marca de procesado por parte de la aplicación del tercero que inicialmente ingresa la información para leer el número de siniestro
- FECHA_PROCESO_TER - Fecha en que procesa la información el tercero
- USUARIO_CREACION - Usuario Oracle que realiza la inserción del registro
- FECHA_CREACION - Fecha en la que se crea el registro
- USUARIO_MODIFICACION - Usuario que realiza la última modificación al registro
- FECHA_MODIFICACION - Fecha de modificación del registro

### **SIM_CARGA_VAR_EXPEDIENTES**

En esta tabla se recibe la información para alimentar la tabla de datos variables de expedientes A7001100, y por esto la información depende de la parametrización del producto.

- SECUENCIA_CAR_EXPE - Secuencia que viene de la tabla SIM_CARGA_EXPEDIENTES, indica cual es el expediente para el que aplica el dato variable.
- CONSECUTIVO - Secuencia manual para indicar la cantidad de datos variables enviados
- PROCESO - Proceso 70 apertura siniestro, 771 creación expedientes, 772 modificación expedientes, 773 anulación de expedientes, 774 reapertura de expedientes, 775 creación de expedientes de Recupero.
- COD_CIA - Código de la compañía
- COD_SECC - Código de la sección
- COD_RAMO - Código del ramo o producto
- TIPO_EXPED - Tipo de expediente a crear o modificar.
- NRO_EXPED - Número de expediente creado, o número de expediente a modificar reserva
- COD_CAMPO - Nombre del campo parametrizado como dato variable
- VALOR_CAMPO - Valor a almacenar para el dato variable
- MCA_PROCESO - Nulo valor inicial, N no procesado, S procesado correctamente, C procesado correctamente con controles técnicos a autorizar
- FECHA_PROCESO - Fecha en que se procesa la información
- MCA_PROCESO_TER - Marca de procesado por parte de la aplicación del tercero que inicialmente ingresa la información para leer el número de siniestro
- FECHA_PROCESO_TER - Fecha en que procesa la información el tercero
- USUARIO_CREACION - Usuario Oracle que realiza la inserción del registro
- FECHA_CREACION - Fecha en la que se crea el registro
- USUARIO_MODIFICACION - Usuario que realiza la última modificación al registro
- FECHA_MODIFICACION - Fecha de modificación del registro

### **SIM_CARGA_RESERVAS**

En esta tabla se recibe la información para alimentar la tabla de datos variables de expedientes A7001100, y por esto la información depende de la parametrización del producto.

- SECUENCIA_CAR_EXPE - Secuencia que viene de la tabla SIM_CARGA_EXPEDIENTES, indica cual es el expediente para el que aplica el dato variable.
- CONSECUTIVO - Secuencia manual para indicar la cantidad de datos variables enviados
- PROCESO - Proceso 70 apertura siniestro, 771 creación expedientes, 772 modificación expedientes, 773 anulación de expedientes, 774 reapertura de expedientes, 775 creación de expedientes de Recupero.
- COD_CIA - Código de la compañía
- COD_SECC - Código de la sección
- COD_RAMO - Código del ramo o producto
- TIPO_EXPED - Tipo de expediente a crear o modificar.
- NRO_EXPED - Número de expediente creado, o número de expediente a modificar reserva
- COD_COB - Código de la cobertura
- COD_CONCEP_RVA - Código del concepto de reserva
- COD_MON - 1 para pesos
- VALOR_MOVIM - Valor para modificar la reserva
- APLICA_DEDUCIBLE - Indicador para aplicar cálculo de deducibles (S para Sí, N o null para no)
- MCA_PROCESO - Nulo valor inicial, N no procesado, S procesado correctamente, C procesado correctamente con controles técnicos a autorizar
- FECHA_PROCESO - Fecha en que se procesa la información
- MCA_PROCESO_TER - Marca de procesado por parte de la aplicación del tercero que inicialmente ingresa la información para leer el número de siniestro
- FECHA_PROCESO_TER - Fecha en que procesa la información el tercero
- USUARIO_CREACION - Usuario Oracle que realiza la inserción del registro
- FECHA_CREACION - Fecha en la que se crea el registro
- USUARIO_MODIFICACION - Usuario que realiza la última modificación al registro
- FECHA_MODIFICACION - Fecha de modificación del registro

### **SIM_CARGA_LIQUIDACIONES**

En esta tabla se recibe la información para genrar las liquidaciones tabla A3001700, alguna información depende de la parametrización del producto, para su correcto funcionamiento.

- SECUENCIA - Secuencia de la tabla que debe ser tomada de SEQ_SIM_CAR_LIQ.
- PROCESO - Proceso 30 liquidación de siniestros, 32 liquidación de reintegros.
- ENT_COLOCADORA - Código de la entidad colocadora. Entidad que envía la información.
- SISTEMA_ORIGEN - Código del sistema origen. Medio por el cual se reporta la información.
- COD_CIA - Código de la compañía
- COD_SECC - Código de la sección
- COD_RAMO - Código del ramo o producto
- NUM_POL1 - Número de póliza.
- NUM_SINI - Número del siniestro a liquidar, nulo si existe valor en el campo SECUENCIA_CAR_SINI
- SECUENCIA_CAR_SINI - Secuencia que viene de la tabla SIM_CARGA_SINIESTROS, se requiere cuando existe un registro en la tabla SIM_CARGA_SINIESTROS con proceso 70.
- TIPO_EXPED - Tipo de expediente a liquidar.
- NRO_EXPED - Número de expediente a liquidar, nulo cuando tenga información en SECUENCIA_CAR_SINI o en SECUENCIA_CAR_EXPE
- SECUENCIA_CAR_EXPE - Secuencia que viene de la tabla SIM_CARGA_EXPEDIENTES, se requiere cuando el proceso corresponde a apertura de siniestro o creación de expediente.
- TIPO_LIQUIDACION - Indica el tipo de liquidación P-Parcial, T-Total, una liquidación total libera la reserva.
- COD_USER - Usuario que realiza la invocación.
- NRO_FACTURA - Número de factura del proveedor.
- FECHA_FACTURA - Fecha de generación de la factura del proveedor.
- FACTURA_EXENTA - Indica si la factura es exenta de ICA, valores S o N.
- LOCALIDAD_FACTURA - Localidad de la factura, código de la ciudad. Sale del codigo_tronador.
- COD_MON - Código de la moneda para el pago, 1 pesos.
- TASA_CAMBIO - Valor de la tasa de cambio para conversión de monedas, 1 para pesos.
- GENERA_ORDEN_PAGO - Indica si debe generar orden de pago (S/N)
- AGENCIA_GIRO - Agencia contable para la liquidación.
- REQUIERE_AUTORIZA - Indica si requiere autorización, S para esperar a que se autorice el pago, N para pagar directamente.
- TDOC_BENEF - Tipo documento del beneficiario de la orden.
- NDOC_BENEF - Número documento del beneficiario de la orden.
- COD_ACT_BENEF - Código de actividad del beneficiario.
- ACTIV_ECONOMICA - Código actividad económica. Tabla C7000002.
- SUBACTIV_ECONOMICA - Código subactividad económina C7000002.
- OBSERVACION - Observación para la liquidación.
- COD_TEXTO - Código de texto. Fines estadísticos.
- SUB_COD_TEXTO - Subcódigo de texto. Fines estadísticos.
- AUTORIZANTE - Usuario tronador del autorizante de la orden de pago. Depende del monto, el concepto de pago y la agencia, tablas A5010020 y A5010010.
- TOTAL_FACTURA - Valor total de la factura no de la liquidación, utilizado para cálculo de retenciones.
- TOTAL_LIQUIDACION - Valor total a liquidar.
- FECHA_PAGO - Fecha estimada de pago.
- MCA_COASEGURO - Indica si se debe liquidar por el total o por la parte del coaseguro de Bolívar. Inicialmente debe ser por el total valor T.
- NUM_LIQUIDACION - Número de la liquidación generada.
- NUM_ORDEN_PAGO - Número de la orden de pago generada.
- COD_CAUSA_ANU - Código causa anulación de la liquidación.
- FECHA_ANULACION - Fecha de anulación de la liquidación.
- SIM_USUARIO - Usuario tronador, sale de la tabla USUARIO campo CODIGO_USUARIO.
- MCA_PROCESO - Nulo valor inicial, N no procesado, S procesado correctamente, C procesado correctamente con controles técnicos a autorizar
- FECHA_PROCESO - Fecha en que se procesa la información
- MCA_PROCESO_TER - Marca de procesado por parte de la aplicación del tercero que inicialmente ingresa la información para leer el número de siniestro
- FECHA_PROCESO_TER - Fecha en que procesa la información el tercero
- USUARIO_CREACION - Usuario Oracle que realiza la inserción del registro
- FECHA_CREACION - Fecha en la que se crea el registro
- USUARIO_MODIFICACION - Usuario que realiza la última modificación al registro
- FECHA_MODIFICACION - Fecha de modificación del registro

### **SIM_CARGA_DET_LIQUIDACIONES**

En esta tabla se recibe la información para alimentar la tabla de datos variables de expedientes A3001800, y por esto la información depende de la parametrización del producto.

- SECUENCIA_CAR_LIQ - Secuencia que viene de la tabla SIM_CARGA_LIQUIDACIONES, indica cual es la liquidación para la que aplica el detalle.
- CONSECUTIVO - Secuencia manual para indicar la cantidad de detalles de la liquidación.
- PROCESO - Proceso 30 liquidación de siniestros, 32 liquidación de recuperos.
- COD_CIA - Código de la compañía.
- COD_SECC - Código de la sección.
- COD_RAMO - Código del ramo o producto.
- COD_COB - Código de la cobertura.
- COD_CONCEP_RVA - Código del concepto de reserva.
- COD_CONCEP_LIQ - Código del concepto de liquidación.
- IMPORTE_LIQ - Valor liquidado para el concepto.
- MCA_PROCESO - Nulo valor inicial, N no procesado, S procesado correctamente, C procesado correctamente con controles técnicos a autorizar
- FECHA_PROCESO - Fecha en que se procesa la información
- MCA_PROCESO_TER - Marca de procesado por parte de la aplicación del tercero que inicialmente ingresa la información para leer el número de siniestro
- FECHA_PROCESO_TER - Fecha en que procesa la información el tercero
- USUARIO_CREACION - Usuario Oracle que realiza la inserción del registro
- FECHA_CREACION - Fecha en la que se crea el registro
- USUARIO_MODIFICACION - Usuario que realiza la última modificación al registro
- FECHA_MODIFICACION - Fecha de modificación del registro

### **SIM_CARGA_VAR_LIQUIDACIONES**

En esta tabla se recibe la información para alimentar la tabla de datos variables de liquidaciones A3001900, y por esto la información depende de la parametrización del producto.

- SECUENCIA_CAR_LIQ - Secuencia que viene de la tabla SIM_CARGA_EXPEDIENTES, indica cual es el expediente para el que aplica el dato variable.
- CONSECUTIVO - Secuencia manual para indicar la cantidad de datos variables enviados
- PROCESO - Proceso 70 apertura siniestro, 771 creación expedientes, 772 modificación expedientes, 773 anulación de expedientes, 774 reapertura de expedientes, 775 creación de expedientes de Recupero.
- COD_CIA - Código de la compañía
- COD_SECC - Código de la sección
- COD_RAMO - Código del ramo o producto
- COD_CAMPO - Nombre del campo parametrizado como dato variable.
- VALOR_CAMPO - Valor a almacenar para el dato variable.
- MCA_PROCESO - Nulo valor inicial, N no procesado, S procesado correctamente, C procesado correctamente con controles técnicos a autorizar
- FECHA_PROCESO - Fecha en que se procesa la información
- MCA_PROCESO_TER - Marca de procesado por parte de la aplicación del tercero que inicialmente ingresa la información para leer el número de siniestro
- FECHA_PROCESO_TER - Fecha en que procesa la información el tercero
- USUARIO_CREACION - Usuario Oracle que realiza la inserción del registro
- FECHA_CREACION - Fecha en la que se crea el registro
- USUARIO_MODIFICACION - Usuario que realiza la última modificación al registro
- FECHA_MODIFICACION - Fecha de modificación del registro

### **SIM_CARGA_ERRORES**

En esta tabla se almacenan los errores retornados en la ejecución del proceso con los datos de cada registro.

- SECUENCIA - Secuencia de la tabla que debe ser tomada de SEQ_SIM_CAR_ERROR.
- ORIGEN_ERROR - Indicador de la tabla donde se origina el error, 1 – Siniestros, 2 – Datos variables de siniestros, 3 – Expedientes, 4 – Datos variables de expedientes, 5 – Reservas, 6 – Liquidaciones, 7 – Detalle de liquidaciones, 8 – Datos variables de liquidación
- SECUENCIA_ORIGEN - Secuencia que viene de la tabla donde se origina el error.
- TIPO_ERROR - Identifica si es un error ‘E’, o es un control técnico a autorizar ´C´
- CODIGO_ERROR - Código del error generado.
- DESC_ERROR - Detalle del error presentado.
- USUARIO_CREACION - Usuario Oracle que realiza la inserción del registro
- FECHA_CREACION - Fecha en la que se crea el registro
- USUARIO_MODIFICACION - Usuario que realiza la última modificación al registro
- FECHA_MODIFICACION - Fecha de modificación del registro

<aside>
⚠️ Las tablas de auditoría con sufijo _JN tienen la misma estructura de la tabla de movimiento, y adicionalmente poseen los siguientes campos

</aside>

- JN_SECUENCIA - Secuencia propia por cada tabla que compone la funcionalidad, el nombre tiene el siguiente patron SEQ_SIM_TABLA_JN (Ejemplo SEQ_SIM_CAR_SINI_JN)
- JN_OPERACION - Indica la operación realizada en la tabla original, INS (Inserción) UPD (Actualización) DEL (Borrado)
- JN_ORACLE_USER - Usuario de base de datos que realiza la operación
- JN_DATETIME - Fecha y hora de la operación en la base de datos

<aside>
⚠️ Las tablas de historia con sufijo _HI, poseen la misma estructura de la tabla de movimiento, y adicionalmente poseen el siguiente campo

</aside>

- HI_REGISTRO - Fecha y hora de ingreso en la tabla de históricos

Cada vez que se modifica la información de las tablas de trabajo, se realiza el paso a las tablas de auditoria, esto mediante triggers en cada una de las tablas, y cuando el registro cumple 2 meses de procesado, se elimina de las tablas de trabajo, y pasa a la tabla de históricos, con esto las tablas de trabajo no poseen un volumen alto de información, lo cual agiliza su manipulación. Esto se reliza desde el paquete que procesa la información.

# 3. Paquete

## **SIM_PCK_CARGA_SINIESTROS**

**En este paquete se tiene la lógica necesaria para la procesar la información de la interfaz,** el llamado puede hacerse de dos maneras, el único procedimiento sobrecargado en la especificación es Proc_ProcesoPrincipal.

### Proc_ProcesoPrincipal - COMPAÑÍA, SECCION Y RAMO

Este es el procedimiento invocado desde la pantalla cobol CB700005, esta pantalla solicita la compañía, sección y ramo, para ejecutar la interfaz, en el desarrollo no se contemplo ejecutarlo a nivel de subproducto. Internamente crea una variable de tipo SIM_TYP_PROCESO y realiza el llamado al otro procedimiento sobrecargado.

### Proc_ProcesoPrincipal - SIM_TYP_PROCESO

Este es el procedimiento encargado de leer las tablas de interfaz y pasar la información al módulo de indemnizaciones, tiene como variable de entrada SIM_TYP_PROCESO, como variable de salida Op_Resultado y Op_ArrErrores, para mantener el estándar de nombramiento de los procedimientos para Simón. Es un procedimiento autónomo, de manera que hace commit por cada registro o elemento que va procesando.

### Secuencia de pasos dentro del procedimiento:

1 - PROC_REGISTRA_PROCESO: Procedimento elaborado para evitar problemas de concurrencia, si llegan a ejecutar la interfaz para el mismo producto desde dos sesiones diferentes.

2 - PROC_CARGA_HISTORICOS: Envía la información procesada desde hace dos meses a las tablas históricas, para dejar menos información en las tablas de proceso.

3 - PROC_PROCESACREASINI: Procesar la creación de siniestros, proceso 70.

4 - PROC_PROCESAMODSINI: Procesar la modificación de siniestros, proceso 75.

5 - PROC_PROCESACAMESTSINI: Procesar cambios de estado de siniestros, proceso 78.

6 - PROC_PROCESACREAEXPED: Procesar la creación de expedientes normales, proceso 771.

7 - PROC_PROCESACREAEXPEDREC: Procesar la creación de expedientes de recupero, proceso 775.

8 - PROC_PROCESAMODIRESER: Procesar la modificación de reserva, proceso 772.

9 - PROC_PROCESALIQUIDACION: Procesar las liquidaciones de expedientes normales, proceso 30.

10 - PROC_PROCESALIQUIDACIONREC: Procesar las liquidaciones de expedientes de recuperos, proceso 32.

11 - PROC_PROCESAANULIQUIDACION: Procesar anulación de liquidaciones, proceso 35.

12 - PROC_TERMINAR_PROCESO: Actualiza tabla de control de procesos, implementada por el proceso 1 para concurrencia.

## Detalle de los procedimientos

### **PROC_REGISTRA_PROCESO**

En una de las primeras ejecuciones de la interfaz, un DBA cancelo el proceso, dado que estaban haciendo seguimiento a algo, y cuando la ejecución nada que terminaba, preguntamos y nos dijeron que habían cancelado sesiones. Esto ocasionó que se contemplaran situaciones como ¿Qué sucede si dos operadores ejecutan la interfaz de forma simultánea con los mismos parámetros. Por eso se implementó el campo SEC_CONTROL en las tablas de trabajo.

Se inserta un registro en la tabla SIM_CARGA_CONTROL_PROCESO, con el número de la secuencia de SEQ_SIM_CAR_CONTROL, luego esta secuencia se guarda igualmente en las tablas de proceso, y en el campo MCA_PROCESO se coloca una P-Pendiente. La interfaz de arrendamiento se ejecuta sin código de proceso, por lo tanto se ejecutan todos los procesos en orden.

### PROC_CARGA_HISTORICOS

Para evitar que las tablas de movimiento poseean mucha información y esto ocasione unas lecturas mas demoradas. La información que ya ha sido procesada al momento de ejecutarse la interfaz desde hace dos meses, se mueven a las respectivas tablas HI, excepto la tabla de errores, esta no se tuvo en cuenta en la construcción del paquete.

### **PROC_PROCESACREASINI**

Recibe como parámetros la variable IP_PROCESO, y la secuencia de proceso generada en el procedimiento PROC_REGISTRA_PROCESO, recorre la tabla SIM_CARGA_SINIESTROS para el proceso 70. Carga la información en una variable de tipo SIM_TYP_DATOS_SINI_WS, igualmente carga los datos variables, y la información de expedientes y reserva. Cuando tiene cargadas todas las variables, realiza el llamado al procedimieto PROC_INVOCA_SERVICIO, con el resultado de la ejecución de ese procedimiento, si es correcta invoca a PROC_CREA_SINI_EXITOSO y si no es exitoso invoca a PROC_CREA_SINI_NO_EXITOSO

### **PROC_PROCESAMODSINI**

Recibe como parámetros la variable IP_PROCESO, y la secuencia de proceso generada en el procedimiento PROC_REGISTRA_PROCESO, recorre la tabla SIM_CARGA_SINIESTROS para el proceso 75. Carga la información en una variable de tipo SIM_TYP_DATOS_SINI_WS, igualmente carga los datos variables. Cuando tiene cargadas las variables, realiza el llamado al procedimieto PROC_INVOCA_SERVICIO, con el resultado de la ejecución de ese procedimiento, si es correcta invoca a PROC_ACT_SINI_EXITOSO y si no es exitoso invoca a PROC_ACT_SINI_NO_EXITOSO

### PROC_PROCESACAMESTSINI

Recibe como parámetros la variable IP_PROCESO, y la secuencia de proceso generada en el procedimiento PROC_REGISTRA_PROCESO, recorre la tabla SIM_CARGA_SINIESTROS para el proceso 78. Carga la información en una variable de tipo SIM_TYP_DATOS_SINI_WS, igualmente carga los datos variables. Cuando tiene cargadas las variables, realiza el llamado al procedimieto PROC_INVOCA_SERVICIO, con el resultado de la ejecución de ese procedimiento, si es correcta invoca a PROC_ACT_SINI_EXITOSO y si no es exitoso invoca a PROC_ACT_SINI_NO_EXITOSO

### PROC_PROCESACREAEXPED

Recibe como parámetros la variable IP_PROCESO, y la secuencia de proceso generada en el procedimiento PROC_REGISTRA_PROCESO, recorre la tabla SIM_CARGA_EXPEDIENTES para el proceso 771. Carga la información en variables de tipo SIM_TYP_EXP_SINI_WS y SIM_TYP_DATOS_SINI_WS, igualmente carga los datos variables del expediente, e información de reservas. Cuando tiene cargadas las variables, realiza el llamado al procedimieto PROC_INVOCA_SERVICIO, con el resultado de la ejecución de ese procedimiento, si es correcta invoca a PROC_CREA_EXPED_EXITOSO y si no es exitoso invoca a PROC_CREA_EXPED_NO_EXITOSO

### PROC_PROCESACREAEXPEDREC

Recibe como parámetros la variable IP_PROCESO, y la secuencia de proceso generada en el procedimiento PROC_REGISTRA_PROCESO, recorre la tabla SIM_CARGA_EXPEDIENTES para el proceso 775. Carga la información en variables de tipo SIM_TYP_EXP_SINI_WS y SIM_TYP_DATOS_SINI_WS, igualmente carga los datos variables del expediente, e información de reservas. Cuando tiene cargadas las variables, realiza el llamado al procedimieto PROC_INVOCA_SERVICIO, con el resultado de la ejecución de ese procedimiento, si es correcta invoca a PROC_CREA_EXPED_EXITOSO y si no es exitoso invoca a PROC_CREA_EXPED_NO_EXITOSO

### PROC_PROCESAMODIRESER

Recibe como parámetros la variable IP_PROCESO, y la secuencia de proceso generada en el procedimiento PROC_REGISTRA_PROCESO, recorre la tabla SIM_CARGA_EXPEDIENTES para el proceso 772. Carga la información en variables de tipo SIM_TYP_EXP_SINI_WS y SIM_TYP_DATOS_SINI_WS, igualmente carga la información de reservas. Cuando tiene cargadas las variables, realiza el llamado al procedimieto PROC_INVOCA_SERVICIO, con el resultado de la ejecución de ese procedimiento, si es correcta invoca a PROC_CREA_EXPED_EXITOSO y si no es exitoso invoca a PROC_CREA_EXPED_NO_EXITOSO

### PROC_PROCESALIQUIDACION

Recibe como parámetros la variable IP_PROCESO, y la secuencia de proceso generada en el procedimiento PROC_REGISTRA_PROCESO, recorre la tabla SIM_CARGA_LIQUIDACIONES para el proceso 30. Carga la información de datos variables de la liquidación en una variable de tipo arreglo PCKG_EXPED_SINIESTROS.r_listasvar, y por cada detalle de liquidación invoca al paquete PROC_GENERA_LIQUIDACION, con el resultado de la ejecución de ese procedimiento, si es correcta invoca a PROC_CREA_LIQ_EXITOSA y si no es exitoso invoca a PROC_CREA_LIQ_NO_EXITOSA

### PROC_PROCESALIQUIDACIONREC

Recibe como parámetros la variable IP_PROCESO, y la secuencia de proceso generada en el procedimiento PROC_REGISTRA_PROCESO, recorre la tabla SIM_CARGA_LIQUIDACIONES para el proceso 32. Carga la información de datos variables de la liquidación en una variable de tipo arreglo PCKG_EXPED_SINIESTROS.r_listasvar, y por cada detalle de liquidación invoca al paquete PROC_GENERA_LIQUIDACION, con el resultado de la ejecución de ese procedimiento, si es correcta invoca a PROC_CREA_LIQ_EXITOSA y si no es exitoso invoca a PROC_CREA_LIQ_NO_EXITOSA

### PROC_PROCESAANULIQUIDACION

Recibe como parámetros la variable IP_PROCESO, y la secuencia de proceso generada en el procedimiento PROC_REGISTRA_PROCESO, recorre la tabla SIM_CARGA_LIQUIDACIONES para el proceso 35. Carga la información en una variable de tipo SIM_TYP_LIQ_SINIESTRO e invoca al paquete SIM_PCK_PROCESO_LIQUIDACION.PROC_GRABA_LIQ_ANUL, con el resultado de la ejecución de ese procedimiento, si es correcta invoca a PROC_CREA_ANULIQ_EXITOSA y si no es exitoso invoca a PROC_ANU_LIQ_NO_EXITOSA

### PROC_TERMINAR_PROCESO

Este procedimiento actualiza la tabla SIM_CARGA_CONTROL_PROCESO, coloca en el campo ESTADO el valor T - Terminado, y en el campo FECHA_FIN, la fecha y hora del sistema, con esto se puede obtener el tiempo de ejecución de la interfaz

### PROC_INVOCA_SERVICIO

Este es un procedimiento autónomo que realiza el llamado al procedimiento PKG_AVISO_SINIESTRO.PRC_SINIESTROS_WS, procedimiento llamado desde el servicio web existente, que utiliza SOAT, Asistencia, y otras interfaces. Este paquete contiene la lógica necesaria para manipular las tablas de indemnizaciones, y llamando a este paquete se evita duplicidad de lógica y problemas con estabilización.

### PROC_GENERA_LIQUIDACION

Con toda la información recibida como parámetros, este procedimiento llama directamente al procedimiento de liquidaciones PKG_LIQUIDA_SINIESTROS.Prc_liquida_inter2

# 4. Ejemplos

## **Creación de siniestros**

### Creación de solo siniestro

Se puede requerir la notificación del siniestro, sin creación de expedientes y reserva, para esto se requiere únicamente información en las tablas SIM_CARGA_SINIESTROS y SIM_CARGA_VAR_SINIESTROS.

Se consulta una póliza y sus fechas de vencimiento para no crear un siniestro fuera de la vigencia de la póliza.

```sql
Declare
  v_siniestro NUMBER(15);
Begin
  v_siniestro := SEQ_SIM_CAR_SINI.nextval;
  INSERT INTO SIM_CARGA_SINIESTROS(SECUENCIA, PROCESO, ENT_COLOCADORA, SISTEMA_ORIGEN, COD_CIA,
    COD_SECC, COD_RAMO, NUM_POL1, FECHA_SINI, HORA_SINI,
    FECHA_DENU_SINI, COD_CAUSA_SINI, TDOC_TERCERO_TOM, NDOC_TERCERO_TOM, TDOC_TERCERO_ASEG,
    NDOC_TERCERO_ASEG, COD_RIES, DESC_SINI, FECHA_FORMALIZAC, TIPO_DEC,
    COD_USER, ESTADO_SINIESTRO, SIM_USUARIO)
  VALUES (v_siniestro, 70, 25, 7, 3,
    37, 486, 5010000835902, TO_DATE('01122021','DDMMYYYY'),'12:00',
    TO_DATE('21122021','DDMMYYYY'), 993, 'CC', 41568082, 'CC',
    41568082, 1, 'MORA ARRENDAMIENTO DICIEMBRE', TO_DATE('21122021','DDMMYYYY'), 'D',
    'PDDASI03', 'AV', '79793163');
  INSERT INTO SIM_CARGA_VAR_SINIESTROS(SECUENCIA_CAR_SINI, CONSECUTIVO, PROCESO, COD_CIA, COD_SECC,
    COD_RAMO, NUM_POL1, COD_NIVEL, COD_GRUPO, COD_CAMPO,
    VALOR_CAMPO)
  VALUES(v_siniestro, 1, 70, 3, 37,
    486, 5010000835902, 1, 1, 'CONS_SAI',
    '2021120001');
  INSERT INTO SIM_CARGA_VAR_SINIESTROS(SECUENCIA_CAR_SINI, CONSECUTIVO, PROCESO, COD_CIA, COD_SECC,
    COD_RAMO, NUM_POL1, COD_NIVEL, COD_GRUPO, COD_CAMPO,
    VALOR_CAMPO)
  VALUES(v_siniestro, 2, 70, 3, 37,
    486, 5010000835902, 1, 1, 'FECHA_PAGO',
    '10-12-2021');
  INSERT INTO SIM_CARGA_VAR_SINIESTROS(SECUENCIA_CAR_SINI, CONSECUTIVO, PROCESO, COD_CIA, COD_SECC,
    COD_RAMO, NUM_POL1, COD_NIVEL, COD_GRUPO, COD_CAMPO,
    VALOR_CAMPO)
  VALUES(v_siniestro, 3, 70, 3, 37,
    486, 5010000835902, 2, 1, 'COD_CONS1',
    '45');
  COMMIT;
End;

```

Con esto se ingresa la información necesaria, para ejecutar la interfaz de forma puntual, se puede consultar el número de secuencia ingresado en la tabla SIM_CARGA_SINIESTROS, y ejecutar el siguiente código.

```sql
DECLARE
  Ip_Proceso sim_typ_proceso;
  Op_Resultado NUMBER(5);
  Op_ArrErrores sim_typ_array_error;
BEGIN
  Ip_Proceso := new sim_typ_proceso();
  Ip_proceso.p_proceso := 70;
  Ip_proceso.p_subproceso := 95728;
  Ip_proceso.p_cod_cia := 3;
  Ip_proceso.p_cod_secc := 37;
  Ip_proceso.p_cod_producto := 486;
  SIM_PCK_CARGA_SINIESTROS.Proc_ProcesoPrincipal(Ip_Proceso, Op_Resultado, Op_ArrErrores);
END;

```

Luego de la ejecución, se puede consultar el número del siniestro creado en el campo NUM_SINI, y en el campo MCA_PROCESO el valor S, si el valor de MCA_PROCESO es N, se debe verificar el error en SIM_CARGA_ERRORES

### Creación de siniestro anulado u objetado

Para crear un siniestro anulado, primero debe crearse el siniestro normal, y posteriormente se anula.

```sql
Declare
  v_siniestro NUMBER(15);
Begin
  v_siniestro := SEQ_SIM_CAR_SINI.nextval;
  INSERT INTO SIM_CARGA_SINIESTROS(SECUENCIA, PROCESO, ENT_COLOCADORA, SISTEMA_ORIGEN, COD_CIA,
    COD_SECC, COD_RAMO, NUM_POL1, FECHA_SINI, HORA_SINI,
    FECHA_DENU_SINI, COD_CAUSA_SINI, TDOC_TERCERO_TOM, NDOC_TERCERO_TOM, TDOC_TERCERO_ASEG,
    NDOC_TERCERO_ASEG, COD_RIES, DESC_SINI, FECHA_FORMALIZAC, TIPO_DEC,
    COD_USER, ESTADO_SINIESTRO, SIM_USUARIO)
  VALUES (v_siniestro, 70, 25, 7, 3,
    37, 486, 5010000835902, TO_DATE('01112021','DDMMYYYY'),'12:00',
    TO_DATE('21122021','DDMMYYYY'), 993, 'CC', 41568082, 'CC',
    41568082, 1, 'MORA ARRENDAMIENTO DICIEMBRE', TO_DATE('21122021','DDMMYYYY'), 'D',
    'PDDASI03', 'AV', '79793163');
  INSERT INTO SIM_CARGA_VAR_SINIESTROS(SECUENCIA_CAR_SINI, CONSECUTIVO, PROCESO, COD_CIA, COD_SECC,
    COD_RAMO, NUM_POL1, COD_NIVEL, COD_GRUPO, COD_CAMPO,
    VALOR_CAMPO)
  VALUES(v_siniestro, 1, 70, 3, 37,
    486, 5010000835902, 1, 1, 'CONS_SAI',
    '2021120001');
  INSERT INTO SIM_CARGA_VAR_SINIESTROS(SECUENCIA_CAR_SINI, CONSECUTIVO, PROCESO, COD_CIA, COD_SECC,
    COD_RAMO, NUM_POL1, COD_NIVEL, COD_GRUPO, COD_CAMPO,
    VALOR_CAMPO)
  VALUES(v_siniestro, 2, 70, 3, 37,
    486, 5010000835902, 1, 1, 'FECHA_PAGO',
    '10-12-2021');
  INSERT INTO SIM_CARGA_VAR_SINIESTROS(SECUENCIA_CAR_SINI, CONSECUTIVO, PROCESO, COD_CIA, COD_SECC,
    COD_RAMO, NUM_POL1, COD_NIVEL, COD_GRUPO, COD_CAMPO,
    VALOR_CAMPO)
  VALUES(v_siniestro, 3, 70, 3, 37,
    486, 5010000835902, 2, 1, 'COD_CONS1',
    '45');
  v_siniestro := SEQ_SIM_CAR_SINI.nextval;
  INSERT INTO SIM_CARGA_SINIESTROS(SECUENCIA, PROCESO, ENT_COLOCADORA, SISTEMA_ORIGEN, COD_CIA,
    COD_SECC, COD_RAMO, NUM_POL1, FECHA_SINI, HORA_SINI,
    COD_CAUSA_BAJA, FECHA_BAJA, COD_USER, ESTADO_SINIESTRO, SIM_USUARIO)
  VALUES (v_siniestro, 78, 25, 7, 3,
    37, 486, 5010000835902, TO_DATE('01112021','DDMMYYYY'),'12:00',
    12, TO_DATE('01112021','DDMMYYYY'), 'PDDASI03', 'AN', '79793163');
  COMMIT;
End;

```

Para procesarlo se debe ejecutar la interfaz completa, no es posible crear dos siniestros para la misma póliza simultáneamente y anular uno. Para esto se debe enviar la creación de los siniestros, y luego en una segunda ejecución enviar el siniestro a anular, con su respectivo número de siniestro.

```sql
DECLARE
  Ip_Proceso sim_typ_proceso;
  Op_Resultado NUMBER(5);
  Op_ArrErrores sim_typ_array_error;
BEGIN
  Ip_Proceso := new sim_typ_proceso();
  Ip_proceso.p_cod_cia := 3;
  Ip_proceso.p_cod_secc := 37;
  Ip_proceso.p_cod_producto := 486;
  SIM_PCK_CARGA_SINIESTROS.Proc_ProcesoPrincipal(Ip_Proceso, Op_Resultado, Op_ArrErrores);
END;

```

### Creación de siniestro con expediente

El proceso es similar a la creación del siniestro, solo que adicionalmente se requiere información en las tablas SIM_CARGA_EXPEDIENTES y SIM_CARGA_RESERVAS.

```sql
Declare
  v_siniestro NUMBER(15);
  v_expediente NUMBER(15);
Begin
  v_siniestro := SEQ_SIM_CAR_SINI.nextval;
  INSERT INTO SIM_CARGA_SINIESTROS(SECUENCIA, PROCESO, ENT_COLOCADORA, SISTEMA_ORIGEN, COD_CIA,
    COD_SECC, COD_RAMO, NUM_POL1, FECHA_SINI, HORA_SINI,
    FECHA_DENU_SINI, COD_CAUSA_SINI, TDOC_TERCERO_TOM, NDOC_TERCERO_TOM, TDOC_TERCERO_ASEG,
    NDOC_TERCERO_ASEG, COD_RIES, DESC_SINI, FECHA_FORMALIZAC, TIPO_DEC,
    COD_USER, ESTADO_SINIESTRO, SIM_USUARIO)
  VALUES (v_siniestro, 70, 25, 7, 3,
    37, 486, 5010000835902, TO_DATE('02122021','DDMMYYYY'),'12:00',
    TO_DATE('21122021','DDMMYYYY'), 993, 'CC', 41568082, 'CC',
    41568082, 1, 'MORA ARRENDAMIENTO DICIEMBRE', TO_DATE('21122021','DDMMYYYY'), 'D',
    'PDDASI03', 'AV', '79793163');
  INSERT INTO SIM_CARGA_VAR_SINIESTROS(SECUENCIA_CAR_SINI, CONSECUTIVO, PROCESO, COD_CIA, COD_SECC,
    COD_RAMO, NUM_POL1, COD_NIVEL, COD_GRUPO, COD_CAMPO,
    VALOR_CAMPO)
  VALUES(v_siniestro, 1, 70, 3, 37,
    486, 5010000835902, 1, 1, 'CONS_SAI',
    '2021120001');
  INSERT INTO SIM_CARGA_VAR_SINIESTROS(SECUENCIA_CAR_SINI, CONSECUTIVO, PROCESO, COD_CIA, COD_SECC,
    COD_RAMO, NUM_POL1, COD_NIVEL, COD_GRUPO, COD_CAMPO,
    VALOR_CAMPO)
  VALUES(v_siniestro, 2, 70, 3, 37,
    486, 5010000835902, 1, 1, 'FECHA_PAGO',
    '10-12-2021');
  INSERT INTO SIM_CARGA_VAR_SINIESTROS(SECUENCIA_CAR_SINI, CONSECUTIVO, PROCESO, COD_CIA, COD_SECC,
    COD_RAMO, NUM_POL1, COD_NIVEL, COD_GRUPO, COD_CAMPO,
    VALOR_CAMPO)
  VALUES(v_siniestro, 3, 70, 3, 37,
    486, 5010000835902, 2, 1, 'COD_CONS1',
    '45');
  v_expediente := SEQ_SIM_CAR_EXPED.nextval;
  INSERT INTO SIM_CARGA_EXPEDIENTES(SECUENCIA, SECUENCIA_CAR_SINI, PROCESO, SISTEMA_ORIGEN, COD_CIA,
    COD_SECC, COD_RAMO, TIPO_EXPED, COD_USER, COD_AGEN_TRAMI,
    COD_MON, TASA_CAMBIO, SIM_USUARIO)
  VALUES(v_expediente, v_siniestro, 70, 25, 3,
    37, 486, 'ARR', 'PDDAS03', 5010,
    1, 1, '79793163');
  INSERT INTO SIM_CARGA_RESERVAS(SECUENCIA_CAR_EXPE, CONSECUTIVO, PROCESO, COD_CIA, COD_SECC,
    COD_RAMO, TIPO_EXPED, COD_COB, COD_CONCEP_RVA, COD_MON,
    VALOR_MOVIM, APLICA_DEDUCIBLE)
  VALUES(v_expediente, 1, 70, 3, 37,
    486, 'ARR', 716, 60, 1,
    500000, 'N');
  COMMIT;
End;

```

Se consulta la información en la tabla de siniestros SIM_CAR_SINIESTROS, y se ejecuta puntualmente la creación de ese siniestro.

```sql
DECLARE
  Ip_Proceso sim_typ_proceso;
  Op_Resultado NUMBER(5);
  Op_ArrErrores sim_typ_array_error;
BEGIN
  Ip_Proceso := new sim_typ_proceso();
  Ip_proceso.p_proceso := 70;
  Ip_proceso.p_subproceso := 95767;
  Ip_proceso.p_cod_cia := 3;
  Ip_proceso.p_cod_secc := 37;
  Ip_proceso.p_cod_producto := 486;
  SIM_PCK_CARGA_SINIESTROS.Proc_ProcesoPrincipal(Ip_Proceso, Op_Resultado, Op_ArrErrores);
END;

```

### Creación de siniestro con expediente y liquidacion

La diferencia con el ejemplo anterior, consiste en adicionar información en las tablas SIM_CARGA_LIQUIDACIONES y SIM_CARGA_DET_LIQUIDACIONES.

```sql
Declare
  v_siniestro   NUMBER(15);
  v_expediente  NUMBER(15);
  v_liquidacion NUMBER(15);
Begin
  v_siniestro := SEQ_SIM_CAR_SINI.nextval;
  INSERT INTO SIM_CARGA_SINIESTROS(SECUENCIA, PROCESO, ENT_COLOCADORA, SISTEMA_ORIGEN, COD_CIA,
    COD_SECC, COD_RAMO, NUM_POL1, FECHA_SINI, HORA_SINI,
    FECHA_DENU_SINI, COD_CAUSA_SINI, TDOC_TERCERO_TOM, NDOC_TERCERO_TOM, TDOC_TERCERO_ASEG,
    NDOC_TERCERO_ASEG, COD_RIES, DESC_SINI, FECHA_FORMALIZAC, TIPO_DEC,
    COD_USER, ESTADO_SINIESTRO, SIM_USUARIO)
  VALUES (v_siniestro, 70, 25, 7, 3,
    37, 486, 5010000835902, TO_DATE('03122021','DDMMYYYY'),'12:00',
    TO_DATE('21122021','DDMMYYYY'), 993, 'CC', 41568082, 'CC',
    41568082, 1, 'MORA ARRENDAMIENTO DICIEMBRE', TO_DATE('21122021','DDMMYYYY'), 'D',
    'PDDASI03', 'AV', '79793163');
  INSERT INTO SIM_CARGA_VAR_SINIESTROS(SECUENCIA_CAR_SINI, CONSECUTIVO, PROCESO, COD_CIA, COD_SECC,
    COD_RAMO, NUM_POL1, COD_NIVEL, COD_GRUPO, COD_CAMPO,
    VALOR_CAMPO)
  VALUES(v_siniestro, 1, 70, 3, 37,
    486, 5010000835902, 1, 1, 'CONS_SAI',
    '2021120001');
  INSERT INTO SIM_CARGA_VAR_SINIESTROS(SECUENCIA_CAR_SINI, CONSECUTIVO, PROCESO, COD_CIA, COD_SECC,
    COD_RAMO, NUM_POL1, COD_NIVEL, COD_GRUPO, COD_CAMPO,
    VALOR_CAMPO)
  VALUES(v_siniestro, 2, 70, 3, 37,
    486, 5010000835902, 1, 1, 'FECHA_PAGO',
    '10-12-2021');
  INSERT INTO SIM_CARGA_VAR_SINIESTROS(SECUENCIA_CAR_SINI, CONSECUTIVO, PROCESO, COD_CIA, COD_SECC,
    COD_RAMO, NUM_POL1, COD_NIVEL, COD_GRUPO, COD_CAMPO,
    VALOR_CAMPO)
  VALUES(v_siniestro, 3, 70, 3, 37,
    486, 5010000835902, 2, 1, 'COD_CONS1',
    '45');
  v_expediente := SEQ_SIM_CAR_EXPED.nextval;
  INSERT INTO SIM_CARGA_EXPEDIENTES(SECUENCIA, SECUENCIA_CAR_SINI, PROCESO, SISTEMA_ORIGEN, COD_CIA,
    COD_SECC, COD_RAMO, TIPO_EXPED, COD_USER, COD_AGEN_TRAMI,
    COD_MON, TASA_CAMBIO, SIM_USUARIO)
  VALUES(v_expediente, v_siniestro, 70, 25, 3,
    37, 486, 'ARR', 'PDDASI03', 5010,
    1, 1, '79793163');
  INSERT INTO SIM_CARGA_RESERVAS(SECUENCIA_CAR_EXPE, CONSECUTIVO, PROCESO, COD_CIA, COD_SECC,
    COD_RAMO, TIPO_EXPED, COD_COB, COD_CONCEP_RVA, COD_MON,
    VALOR_MOVIM, APLICA_DEDUCIBLE)
  VALUES(v_expediente, 1, 70, 3, 37,
    486, 'ARR', 716, 60, 1,
    500000, 'N');
  v_liquidacion := SEQ_SIM_CAR_LIQ.nextval;
  INSERT INTO SIM_CARGA_LIQUIDACIONES(SECUENCIA, PROCESO, ENT_COLOCADORA, SISTEMA_ORIGEN, COD_CIA,
    COD_SECC, COD_RAMO, NUM_POL1, SECUENCIA_CAR_SINI, TIPO_EXPED,
    SECUENCIA_CAR_EXPE, TIPO_LIQUIDACION, COD_USER, NRO_FACTURA, FECHA_FACTURA,
    FACTURA_EXENTA, LOCALIDAD_FACTURA, COD_MON, TASA_CAMBIO, GENERA_ORDEN_PAGO,
    AGENCIA_GIRO, REQUIERE_AUTORIZA, TDOC_BENEF, NDOC_BENEF, COD_ACT_BENEF,
    OBSERVACION, COD_TEXTO, SUB_COD_TEXTO, AUTORIZANTE, TOTAL_FACTURA,
    TOTAL_LIQUIDACION, FECHA_PAGO, MCA_COASEGURO, SIM_USUARIO)
  VALUES(v_liquidacion, 30, 25, 7, 3,
    37, 486, 5010000835902, v_siniestro, 'ARR',
    v_expediente, 'T', 'PDDASI03', '0', TO_DATE('20122021','DDMMYYYY'),
    'S', 5010, 1, 1, 'S',
    5010, 'N', 'CC', 41568082, 1,
    '03-DIC.21', 1, 1, 10232, 500000,
    500000, TO_DATE('23122021','DDMMYYYY'), 'T', '79793163');
  INSERT INTO SIM_CARGA_DET_LIQUIDACIONES(SECUENCIA_CAR_LIQ, CONSECUTIVO, PROCESO, COD_CIA, COD_SECC,
    COD_RAMO, COD_COB, COD_CONCEP_RVA, COD_CONCEP_LIQ, IMPORTE_LIQ)
  VALUES(v_liquidacion, 1, 30, 3, 37,
    486, 716, 60, 329, 500000);
  COMMIT;
End;

```

Luego se debe ejecutar toda la interfaz, o ejecutar la creación del siniestro, y luego la ejecución de la liquidación. Aquí se ejecuta toda la interfaz.

```sql
DECLARE
  Ip_Proceso sim_typ_proceso;
  Op_Resultado NUMBER(5);
  Op_ArrErrores sim_typ_array_error;
BEGIN
  Ip_Proceso := new sim_typ_proceso();
  Ip_proceso.p_cod_cia := 3;
  Ip_proceso.p_cod_secc := 37;
  Ip_proceso.p_cod_producto := 486;
  SIM_PCK_CARGA_SINIESTROS.Proc_ProcesoPrincipal(Ip_Proceso, Op_Resultado, Op_ArrErrores);
END;

```

## **Modificación de siniestros**

Es posible modificar la descripción, causa de siniestro, fecha de siniestro. Pero se debe tener cuidado de no tener expedientes, si ya tiene expedientes, y la modificacíon incluye cambios en las coberturas, se puede recibir un mensaje de error.

```sql
Declare
  v_siniestro   NUMBER(15);
Begin
  v_siniestro := SEQ_SIM_CAR_SINI.nextval;
  INSERT INTO SIM_CARGA_SINIESTROS(SECUENCIA, PROCESO, ENT_COLOCADORA, SISTEMA_ORIGEN, COD_CIA,
    COD_SECC, COD_RAMO, NUM_POL1, COD_USER, DESC_SINI,
    NUM_SINI, COD_CAUSA_MODI, FECHA_MODI, SIM_USUARIO)
  VALUES (v_siniestro, 75, 25, 7, 3,
    37, 486, 5010000835902, 'PDDASI03', 'PRUEBA CAMBIO',
    50100001563, 1, TO_DATE('23122021','DDMMYYYY'), '79793163');
  COMMIT;
End;

```

Se ejecuta mediante

```sql
DECLARE
  Ip_Proceso sim_typ_proceso;
  Op_Resultado NUMBER(5);
  Op_ArrErrores sim_typ_array_error;
BEGIN
  Ip_Proceso := new sim_typ_proceso();
  Ip_proceso.p_proceso := 75;
  Ip_proceso.p_subproceso := 95829;
  Ip_proceso.p_cod_cia := 3;
  Ip_proceso.p_cod_secc := 37;
  Ip_proceso.p_cod_producto := 486;
  SIM_PCK_CARGA_SINIESTROS.Proc_ProcesoPrincipal(Ip_Proceso, Op_Resultado, Op_ArrErrores);
END;

```

### Modificación datos variables

La modificación de siniestros, se envía cuando se requiere realizar un cambio en algún dato variable, en este caso podría ser un cambio en el número de siniestro SAI

```sql
Declare
  v_siniestro   NUMBER(15);
Begin
  v_siniestro := SEQ_SIM_CAR_SINI.nextval;
  INSERT INTO SIM_CARGA_SINIESTROS(SECUENCIA, PROCESO, ENT_COLOCADORA, SISTEMA_ORIGEN, COD_CIA,
    COD_SECC, COD_RAMO, NUM_POL1, COD_USER, NUM_SINI,
    COD_CAUSA_MODI, FECHA_MODI, SIM_USUARIO)
  VALUES (v_siniestro, 75, 25, 7, 3,
    37, 486, 5010000835902, 'PDDASI03', 50100001563,
    1, TO_DATE('23122021','DDMMYYYY'), '79793163');
  INSERT INTO SIM_CARGA_VAR_SINIESTROS(SECUENCIA_CAR_SINI, CONSECUTIVO, PROCESO, COD_CIA, COD_SECC,
    COD_RAMO, NUM_POL1, COD_NIVEL, COD_GRUPO, COD_CAMPO,
    VALOR_CAMPO)
  VALUES(v_siniestro, 1, 75, 3, 37,
    486, 5010000835902, 1, 1, 'CONS_SAI',
    '1010');
  COMMIT;
End;

```

La modificación puede incluir cambio en la descripción y en los datos variables.

La ejecución de la interfaz se realiza mediante.

```sql
DECLARE
  Ip_Proceso sim_typ_proceso;
  Op_Resultado NUMBER(5);
  Op_ArrErrores sim_typ_array_error;
BEGIN
  Ip_Proceso := new sim_typ_proceso();
  Ip_proceso.p_proceso := 75;
  Ip_proceso.p_subproceso := 95828;
  Ip_proceso.p_cod_cia := 3;
  Ip_proceso.p_cod_secc := 37;
  Ip_proceso.p_cod_producto := 486;
  SIM_PCK_CARGA_SINIESTROS.Proc_ProcesoPrincipal(Ip_Proceso, Op_Resultado, Op_ArrErrores);
END;

```

### Cambios de estado

En cambios de estado se contemplan la anulación del siniestro y la objeción.

Para la objeción del siniestro, se debe enviar el estado objetado.

```sql
Declare
  v_siniestro   NUMBER(15);
Begin
  v_siniestro := SEQ_SIM_CAR_SINI.nextval;
  INSERT INTO SIM_CARGA_SINIESTROS(SECUENCIA, PROCESO, ENT_COLOCADORA, SISTEMA_ORIGEN, COD_CIA,
    COD_SECC, COD_RAMO, NUM_POL1, COD_USER, ESTADO_SINIESTRO,
    NUM_SINI, COD_CAUSA_MODI, FECHA_MODI, SIM_USUARIO)
  VALUES (v_siniestro, 78, 25, 7, 3,
    37, 486, 5010000835902, 'PDDASI03', 'OB',
    50100001563, 1, TO_DATE('23122021','DDMMYYYY'), '79793163');
  COMMIT;
End;

```

Y se ejecuta normalmente

```sql
DECLARE
  Ip_Proceso sim_typ_proceso;
  Op_Resultado NUMBER(5);
  Op_ArrErrores sim_typ_array_error;
BEGIN
  Ip_Proceso := new sim_typ_proceso();
  Ip_proceso.p_proceso := 78;
  Ip_proceso.p_subproceso := 95847;
  Ip_proceso.p_cod_cia := 3;
  Ip_proceso.p_cod_secc := 37;
  Ip_proceso.p_cod_producto := 486;
  SIM_PCK_CARGA_SINIESTROS.Proc_ProcesoPrincipal(Ip_Proceso, Op_Resultado, Op_ArrErrores);
END;

```

Para la anulación del siniestro, se debe enviar la causa de baja y la fecha de baja, el estado no es importante, pero mejor enviarlo.

```sql
Declare
  v_siniestro   NUMBER(15);
Begin
  v_siniestro := SEQ_SIM_CAR_SINI.nextval;
  INSERT INTO SIM_CARGA_SINIESTROS(SECUENCIA, PROCESO, ENT_COLOCADORA, SISTEMA_ORIGEN, COD_CIA,
    COD_SECC, COD_RAMO, NUM_POL1, COD_USER, ESTADO_SINIESTRO,
    NUM_SINI, COD_CAUSA_BAJA, FECHA_BAJA, SIM_USUARIO)
  VALUES (v_siniestro, 78, 25, 7, 3,
    37, 486, 5010000835902, 'PDDASI03', 'AN',
    50100001565, 12, TO_DATE('23122021','DDMMYYYY'), '79793163');
  COMMIT;
End;

```

Se ejecuta normalmente

```sql
DECLARE
  Ip_Proceso sim_typ_proceso;
  Op_Resultado NUMBER(5);
  Op_ArrErrores sim_typ_array_error;
BEGIN
  Ip_Proceso := new sim_typ_proceso();
  Ip_proceso.p_proceso := 78;
  Ip_proceso.p_subproceso := 95848;
  Ip_proceso.p_cod_cia := 3;
  Ip_proceso.p_cod_secc := 37;
  Ip_proceso.p_cod_producto := 486;
  SIM_PCK_CARGA_SINIESTROS.Proc_ProcesoPrincipal(Ip_Proceso, Op_Resultado, Op_ArrErrores);
END;

```

## **Creación de expedientes**

### Creación de expedientes normales

Cuando se tiene la creación del siniestro, sin expedientes, se puede crear el expediente de la siguiente manera:

```sql
Declare
  v_expediente   NUMBER(15);
Begin
  v_expediente := SEQ_SIM_CAR_EXPED.nextval;
  INSERT INTO SIM_CARGA_EXPEDIENTES(SECUENCIA, PROCESO, SISTEMA_ORIGEN, COD_CIA, COD_SECC,
    COD_RAMO, NUM_SINI, TIPO_EXPED, FEC_APER_EXP, COD_USER,
    COD_AGEN_TRAMI, COD_MON, TASA_CAMBIO, SIM_USUARIO)
  VALUES (v_expediente, 771, 25, 3, 37,
    486, 50100001569, 'ARR', TO_DATE('23122021','DDMMYYYY'), 'PDDASI03',
    5010, 1, 1, '79793163');
  INSERT INTO SIM_CARGA_RESERVAS(SECUENCIA_CAR_EXPE, CONSECUTIVO, PROCESO, COD_CIA, COD_SECC,
    COD_RAMO, TIPO_EXPED, COD_COB, COD_CONCEP_RVA, COD_MON,
    VALOR_MOVIM, APLICA_DEDUCIBLE)
  VALUES(v_expediente, 1, 771, 3, 37,
    486, 'ARR', 716, 60, 1,
    500000, 'N');
  COMMIT;
End;

```

Y se ejecuta

```sql
DECLARE
  Ip_Proceso sim_typ_proceso;
  Op_Resultado NUMBER(5);
  Op_ArrErrores sim_typ_array_error;
BEGIN
  Ip_Proceso := new sim_typ_proceso();
  Ip_proceso.p_proceso := 771;
  Ip_proceso.p_subproceso := 429533;
  Ip_proceso.p_cod_cia := 3;
  Ip_proceso.p_cod_secc := 37;
  Ip_proceso.p_cod_producto := 486;
  SIM_PCK_CARGA_SINIESTROS.Proc_ProcesoPrincipal(Ip_Proceso, Op_Resultado, Op_ArrErrores);
END;

```

Si ya posee expediente, de ese tipo, debe retornar un error indicando que ya existe un expediente de ese tipo.

Para probarlo, se puede ejecutar nuevamente la creación de expediente de este punto, y consultar SELECT * FROM SIM_CARGA_ERRORES WHERE SECUENCIA_ORIGEN = 429534

El error reportado es Error creacion expediente ARR-TIPO DE EXPEDIENTE INGRESADO ES UNICO Y YA EXISTE UN EXPEDIENTE DE ESTE TIPO

### Creación de expedientes recuperos

## **Modificación de reservas**

Si se va a manejar un solo siniestro en el libertador para la póliza, y con este mismo siniestro se pagan 2 o más incumplimientos, se puede manejar la misma situación en Simón.

Se crea el primer siniestro con su respectiva liquidación, y posteriormente se incrementa la reserva del expediente creado, para realizar la liquidación.

### Aumento de reserva

```sql
Declare
  v_expediente   NUMBER(15);
Begin
  v_expediente := SEQ_SIM_CAR_EXPED.nextval;
  INSERT INTO SIM_CARGA_EXPEDIENTES(SECUENCIA, PROCESO, SISTEMA_ORIGEN, COD_CIA, COD_SECC,
    COD_RAMO, NUM_SINI, TIPO_EXPED, NRO_EXPED, COD_USER,
    COD_AGEN_TRAMI, COD_MON, TASA_CAMBIO, COD_MODI_EXP, FEC_MODI_EXP,
    SIM_USUARIO)
  VALUES (v_expediente, 772, 25, 3, 37,
    486, 50100001568, 'ARR', 1, 'PDDASI03',
    5010, 1, 1, 1, TO_DATE('23122021','DDMMYYYY'),
    '79793163');
  INSERT INTO SIM_CARGA_RESERVAS(SECUENCIA_CAR_EXPE, CONSECUTIVO, PROCESO, COD_CIA, COD_SECC,
    COD_RAMO, TIPO_EXPED, COD_COB, COD_CONCEP_RVA, COD_MON,
    VALOR_MOVIM, APLICA_DEDUCIBLE)
  VALUES(v_expediente, 1, 772, 3, 37,
    486, 'ARR', 716, 60, 1,
    500000, 'N');
  COMMIT;
End;

```

Y se ejecuta

```sql
DECLARE
  Ip_Proceso sim_typ_proceso;
  Op_Resultado NUMBER(5);
  Op_ArrErrores sim_typ_array_error;
BEGIN
  Ip_Proceso := new sim_typ_proceso();
  Ip_proceso.p_proceso := 772;
  Ip_proceso.p_subproceso := 429536;
  Ip_proceso.p_cod_cia := 3;
  Ip_proceso.p_cod_secc := 37;
  Ip_proceso.p_cod_producto := 486;
  SIM_PCK_CARGA_SINIESTROS.Proc_ProcesoPrincipal(Ip_Proceso, Op_Resultado, Op_ArrErrores);
END;

```

### Disminución de reserva

Si se llega a detectar que se envió el aumento de reserva para un expediente equivocado, se puede realizar la modificación de manera similar, pero con un valor de modificación de reserva negativo. Se debe tener cuidado de no intentar disminuir por un malor valor a la reserva disponible.

Si se envía un mayor valor, se recibe un mensaje de error indicando que no se puede disminuir la reserva.

```sql
Declare
  v_expediente   NUMBER(15);
Begin
  v_expediente := SEQ_SIM_CAR_EXPED.nextval;
  INSERT INTO SIM_CARGA_EXPEDIENTES(SECUENCIA, PROCESO, SISTEMA_ORIGEN, COD_CIA, COD_SECC,
    COD_RAMO, NUM_SINI, TIPO_EXPED, NRO_EXPED, COD_USER,
    COD_AGEN_TRAMI, COD_MON, TASA_CAMBIO, COD_MODI_EXP, FEC_MODI_EXP,
    SIM_USUARIO)
  VALUES (v_expediente, 772, 25, 3, 37,
    486, 50100001568, 'ARR', 1, 'PDDASI03',
    5010, 1, 1, 1, TO_DATE('23122021','DDMMYYYY'),
    '79793163');
  INSERT INTO SIM_CARGA_RESERVAS(SECUENCIA_CAR_EXPE, CONSECUTIVO, PROCESO, COD_CIA, COD_SECC,
    COD_RAMO, TIPO_EXPED, COD_COB, COD_CONCEP_RVA, COD_MON,
    VALOR_MOVIM, APLICA_DEDUCIBLE)
  VALUES(v_expediente, 1, 772, 3, 37,
    486, 'ARR', 716, 60, 1,
    -100000, 'N');
  COMMIT;
End;

```

Y se ejecuta

```sql
DECLARE
  Ip_Proceso sim_typ_proceso;
  Op_Resultado NUMBER(5);
  Op_ArrErrores sim_typ_array_error;
BEGIN
  Ip_Proceso := new sim_typ_proceso();
  Ip_proceso.p_proceso := 772;
  Ip_proceso.p_subproceso := 429537;
  Ip_proceso.p_cod_cia := 3;
  Ip_proceso.p_cod_secc := 37;
  Ip_proceso.p_cod_producto := 486;
  SIM_PCK_CARGA_SINIESTROS.Proc_ProcesoPrincipal(Ip_Proceso, Op_Resultado, Op_ArrErrores);
END;

```

## **Liquidaciones**

### Liquidación de expedientes normales

Cuando se tiene un expediente con reserva para realizar la liquidación, se puede invocar la liquidación directamente. Esto va a suceder si se desea manejar un único siniestro por póliza.

```sql
Declare
  v_liquidacion NUMBER(15);
Begin
  v_liquidacion := SEQ_SIM_CAR_LIQ.nextval;
  INSERT INTO SIM_CARGA_LIQUIDACIONES(SECUENCIA, PROCESO, ENT_COLOCADORA, SISTEMA_ORIGEN, COD_CIA,
    COD_SECC, COD_RAMO, NUM_POL1, NUM_SINI, TIPO_EXPED,
    NRO_EXPED, TIPO_LIQUIDACION, COD_USER, NRO_FACTURA, FECHA_FACTURA,
    FACTURA_EXENTA, LOCALIDAD_FACTURA, COD_MON, TASA_CAMBIO, GENERA_ORDEN_PAGO,
    AGENCIA_GIRO, REQUIERE_AUTORIZA, TDOC_BENEF, NDOC_BENEF, COD_ACT_BENEF,
    OBSERVACION, COD_TEXTO, SUB_COD_TEXTO, AUTORIZANTE, TOTAL_FACTURA,
    TOTAL_LIQUIDACION, FECHA_PAGO, MCA_COASEGURO, SIM_USUARIO)
  VALUES(v_liquidacion, 30, 25, 7, 3,
    37, 486, 5010000835902, 50100001568, 'ARR',
    1, 'T', 'PDDASI03', '0', TO_DATE('20122021','DDMMYYYY'),
    'S', 5010, 1, 1, 'S',
    5010, 'N', 'CC', 41568082, 1,
    '03-DIC.21', 1, 1, 10232, 400000,
    400000, TO_DATE('23122021','DDMMYYYY'), 'T', '79793163');
  INSERT INTO SIM_CARGA_DET_LIQUIDACIONES(SECUENCIA_CAR_LIQ, CONSECUTIVO, PROCESO, COD_CIA, COD_SECC,
    COD_RAMO, COD_COB, COD_CONCEP_RVA, COD_CONCEP_LIQ, IMPORTE_LIQ)
  VALUES(v_liquidacion, 1, 30, 3, 37,
    486, 716, 60, 329, 400000);
  COMMIT;
End;

```

Y se ejecuta

```sql
DECLARE
  Ip_Proceso sim_typ_proceso;
  Op_Resultado NUMBER(5);
  Op_ArrErrores sim_typ_array_error;
BEGIN
  Ip_Proceso := new sim_typ_proceso();
  Ip_proceso.p_proceso := 30;
  Ip_proceso.p_subproceso := 815203;
  Ip_proceso.p_cod_cia := 3;
  Ip_proceso.p_cod_secc := 37;
  Ip_proceso.p_cod_producto := 486;
  SIM_PCK_CARGA_SINIESTROS.Proc_ProcesoPrincipal(Ip_Proceso, Op_Resultado, Op_ArrErrores);
END;

```

### Liquidación de expedientes recuperos

## Mejoras

## **Listado de detalles pendientes y mejoras para implementar**

**Como todo programa y desarrollo tiene muchas posibilidades de mejorar,** aqui voy a listar los detalles que he identificado, para ver si en algún momento se pueden implementar.

- Liquidación con mas de un concepto.
- Pantalla de resultados de las ejecuciones.
- Correo informando resultado procesos.
- Permitir continuar con un proceso cuando se pierda la sesión.
- Pasar la información de errores a la carga de históricos.
- No se debería solicitar fecha de denuncia del siniestro, ni fecha de apertura del expediente, estas corresponden a la fecha actual.
- La liquidación llama directamente al paquete de liquidación no al servicio de siniestros.
- La anulación de liquidación llama directamente al paquete de liquidación no al servicio de siniestros.
- Cuando se realiza un cambio en datos variables de siniestro, borra la descripción del siniestro.
- Agregar todos los procesos en la tabla SIM_CARGA_CONTROL_PROCESO, para identificar expedientes de expedientes de reintegros, liquidaciones normales, de liquidaciones de reintegros, y siniestros modificados, de siniestros con cambio de estado.
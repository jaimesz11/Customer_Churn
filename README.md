# Customer_Churn
Predicción de clientes que abandonarían la compañía en una empresa de telecomunicaciones

### Descripción y objetivo
El caso consiste en que una compañía de telecomunicaciones se ha percatado de que entre diciembre del 2019 y enero del 2020 se han producido bastantes bajas de clientes. El objetivo es la creación de un modelo analítico que sea capaz de predecir los próximos clientes que potencialmente pueden marcharse de la operadora para intentar lanzar una campaña e intentar retenerles antes de su portabilidad. Además, se pretende conocer las causas por las cuales los clientes se están fugando. Para construir el modelo se dispone de varios datasets con datos que aportan información de los clientes. La información sobre las tablas se recoge a continuación.


### Información de los datsets
#### Tabla clientes
edad: edad de los clientes.
facturacion: dinero que pagan los clientes al mes.
antiguedad: fecha de alta del cliente.
provincia: lugar de procedencia del cliente.
num_lineas: número de líneas móviles contratadas.
num_dt: número de líneas en impago.
incidencia: es SI,si el cliente ha tenido alguna incidencia/reclamación.

#### Tabla productos
conexión: tipo de conexión de internet del cliente.
vel_conexion: velocidad de conexión de internet.
TV: tipo de paquete de tv contratado por el cliente.

#### Tabla consumos
num_llamad_ent: número de llamadas entrantes de todas sus líneas.
num_llamad_sal: número de llamadas salientes de todas sus líneas.
mb_datos: mb de los datos consumidos en todas sus líneas.
seg_llamad_ent: segundos consumidos en llamadas entrantes.
seg_llamad_sal: segundos consumidos en llamadas salientes.

#### Tabla financiación
financiación: es SI, si el cliente tiene financiado algún terminal.
imp_financ: el dinero mensual que paga por los terminales financiados.
descuentos: es SI, si el cliente tiene activo algún descuento (campaña).

La variable target se debe construir. En este caso esta variable describiría si el cliente en cuestión abandona la compañía o no.

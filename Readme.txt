Funcionalidades por vista:

Empleados:
    - Nombre (texto hasta 50 caracteres)
    - Apellido (texto hasta 50 caracteres)
    - DNI (numero entero)
    - Email (texto con @)
    - Cargo (texto hasta 50 caracteres)
    - Fecha de Nacimiento (formato YY-MM-DD)

Cliente:
    - Nombre (texto hasta 50 caracteres)
    - Direccion (texto hasta 50 caracteres)
    - Pedido (texto hasta 50 caracteres)
    - Estado ((texto hasta 50 caracteres, ej: Activo/Inactivo)

Producto:
    - Codigo (numero entero)
    - Descripcion (texto hasta 50 caracteres)
    - Cantidad (numero entero)

Cuando se finaliza la carga, el programa llama a una pagina con un mensaje indicando la carga correcta.

Busqueda:
	Para el modulo de busqueda, esta definido por el momento solo para "Clientes". Se debe indicar el noombre
	a buscar, y el programa, en caso de encontrarlo, devolvera el nombre y estado. EN caso de no estar cargado 
	en la base de datos, devolvera un mensaje que no fue encontrado.


Base de Datos SQLite
    superuser: admin
    password: admin
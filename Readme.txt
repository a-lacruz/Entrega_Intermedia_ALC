Funcionalidades por vista:

Empleados:
    - Nombre (texto hasta 50 caracteres)
    - Apellido (texto hasta 50 caracteres)
    - DNI (numero entero)
    - Email (texto con @)
    - Cargo (texto hasta 50 caracteres)
    - Fecha de Nacimiento (formato YY-MM-DD)
Permite la carga en la base de datos, para el modelo "Empleados"  

Cliente:
    - Nombre (texto hasta 50 caracteres)
    - Direccion (texto hasta 50 caracteres)
    - Pedido (texto hasta 50 caracteres)
    - Estado ((texto hasta 50 caracteres, ej: Activo/Inactivo
 Permite la carga en la base de datos, para el modelo "Cliente"  
    

Producto:
    - Codigo (numero entero)
    - Descripcion (texto hasta 50 caracteres)
    - Cantidad (numero entero)
Permite la carga en la base de datos, para el modelo "Producto"  

Cuando se finaliza la carga, el programa llama a una pagina con un mensaje indicando la carga correcta.

Busqueda:
	Para el modulo de busqueda, esta definido por el momento solo para "Clientes". Se debe escribir 
	en el formulario el nombre a buscar, y el programa, si existiera el registro, devolvera 
	el nombre y estado. En caso de no estar cargado en la base de datos, devolvera un mensaje que no fue encontrado.

Base de Datos SQLite
    superuser: admin
    password: admin

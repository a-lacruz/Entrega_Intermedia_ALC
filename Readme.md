###Funcionalidades por vista:

Empleados:
Permite la carga en la base de datos, para el modelo "Empleados"

    - Nombre (texto hasta 50 caracteres)
    - Apellido (texto hasta 50 caracteres)
    - DNI (numero entero)
    - Email (texto con @)
    - Cargo (texto hasta 50 caracteres)
    - Fecha de Nacimiento (formato YY-MM-DD)

Cliente:
Permite la carga en la base de datos, para el modelo "Cliente"
    - Nombre (texto hasta 50 caracteres)
    - Direccion (texto hasta 50 caracteres)
    - Pedido (texto hasta 50 caracteres)
    - Estado ((texto hasta 50 caracteres, ej: Activo/Inactivo

Producto:
Permite la carga en la base de datos, para el modelo "Producto"
    - Codigo (numero entero)
    - Descripcion (texto hasta 50 caracteres)
    - Cantidad (numero entero)

Cuando se finaliza la carga en cualquiera de los modelos, el programa llama a una pagina con un mensaje indicando la carga correcta.

Busqueda:

El modulo de busqueda, esta definido por el momento solo para "Clientes". Se debe escribir en el formulario el nombre a buscar, y el programa, si existiera el registro, devolvera el nombre del cliente y su estado. En caso de no estar cargado en la base de datos, devolvera un mensaje que no fue encontrado.

Base de Datos SQLite
    superuser: admin
    password: admin

#### Pasos para clonar el proyecto desde Github

Clona el repositorio en tu máquina local utilizando Git. Abre una terminal y escribe:
`git clone https://github.com/usuario/repositorio.git`

Accede al directorio del repositorio clonado:
`cd repositorio`

Asegúrate de tener instalado Django en tu máquina. Si aún no lo tienes instalado, puedes hacerlo ejecutando:
`pip install django`

Crea un entorno virtual para el proyecto. Esto te permitirá tener un espacio aislado para instalar las dependencias necesarias para el proyecto y evitar conflictos con otras aplicaciones. Para crear un entorno virtual con Python, puedes utilizar el siguiente comando:
`python -m venv nombre_entorno`

Activa el entorno virtual:
##### En Windows
`nombre_entorno\Scripts\activate.bat`
##### En Linux o macOS
`source nombre_entorno/bin/activate`

Crea la base de datos y ejecuta las migraciones necesarias para crear las tablas y relaciones necesarias para el proyecto:
`python manage.py makemigrations`
`python manage.py migrate`

Arranca el servidor de desarrollo con el siguiente comando:
`python manage.py runserver`

Ahora podrás acceder al proyecto Django desde tu navegador web en la dirección `<link>`http://127.0.0.1:8000/.
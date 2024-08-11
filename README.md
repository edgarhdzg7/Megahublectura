# MEGA HUB DE LECTURA

![image](https://github.com/user-attachments/assets/8606a3e7-adbe-4c8a-bc94-38d92843bbe5)

Este es un proyecto de Visual Basic 6 que implementa un HUB DE LECTURA. La aplicación permite a los usuarios gestionar libros, realizar búsquedas, ver detalles y portadas, eliminar libros, y agregar libros a una lista de favoritos. El proyecto está conectado a una base de datos SQL Server llamada Biblioteca, donde se almacenan los datos de los libros.

Tabla de Contenidos

# Características

-Buscar Libro: Permite buscar libros por título o autor.
-Libros Leídos: Muestra una lista de libros que han sido marcados como leídos.
-Eliminar Libro: Permite eliminar un libro seleccionado de la lista.
-Agregar a Favoritos: Añade el libro seleccionado a una lista de favoritos.
-Ver Portada y Detalles: Muestra la portada y los detalles del libro seleccionado.



# Requisitos

-Visual Basic 6.0: Entorno de desarrollo.
-SQL Server: Base de datos utilizada para almacenar la información.
-ADO (ActiveX Data Objects): Para la conexión y manejo de datos desde Visual Basic 6.


# Configuración del Proyecto

Clonar el Repositorio: git clone https://github.com/tu_usuario/hub-de-lectura.git
cd hub-de-lectura

# Configuración en Visual Basic 6:

-Abrir el proyecto en Visual Basic 6.
-Asegurarse de que el componente Microsoft ActiveX Data Objects 2.x Library esté habilitado en Project > References.
-Configuración de la Base de Datos:

-Crear una base de datos en SQL Server con el nombre Biblioteca.
-Ejecutar el script create_tables.sql (incluido en el repositorio) para crear las tablas necesarias.

# Estructura de la Base de Datos

-La base de datos Biblioteca incluye las siguientes tablas:

-Libros: Almacena la información de cada libro (ID, Título, Autor, Género, Detalles, Portada).
-LibrosLeidos: Registra los libros que han sido leídos.
-LibrosFavoritos: Registra los libros marcados como favoritos.
-LibrosEliminados: Almacena los libros que han sido eliminados.

![image](https://github.com/user-attachments/assets/51a0db36-a53c-4e6e-b3c3-9143f7dbcc73)


# Conexión a SQL Server

-El proyecto utiliza una conexión ADO para interactuar con SQL Server. La cadena de conexión está configurada de la siguiente manera:

cn.ConnectionString = "Provider=SQLOLEDB;Data Source=MegaServer;Initial Catalog=Biblioteca;User ID=Edgar;Password=edgar7;"


# Uso

-Buscar Libro: Haz clic en el botón "Buscar Libro" y escribe el título o autor del libro.
-Libros Leídos: Haz clic en "Libros Leídos" para ver la lista de libros leídos.
-Eliminar Libro: Selecciona un libro en la lista y haz clic en "Eliminar Libro" para eliminarlo.
-Agregar a Favoritos: Selecciona un libro y haz clic en "Agregar a Favoritos".
-Ver Portada y Detalles: Selecciona un libro y haz clic en "Ver Portada y Detalles" para ver más información.





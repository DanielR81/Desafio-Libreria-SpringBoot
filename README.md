# Consola de Libros con Spring Boot

Esta aplicación de consola, desarrollada con el framework Spring Boot, interactúa con el API Gutendex, un repositorio de libros. La aplicación permite buscar libros, listar información de autores y libros, y gestionar datos almacenados en una base de datos PostgreSQL.

## Requisitos

### Base de datos PostgreSQL:

1 - La aplicación está configurada para funcionar exclusivamente con PostgreSQL.

* Es necesario crear una base de datos vacía antes de ejecutar la aplicación.

2 - Configuración de variables de entorno:

* La configuración de la base de datos se gestiona mediante variables de entorno.

* El archivo application.properties muestra la estructura de configuración requerida.

3 - Java:

* Versión compatible con Spring Boot (en este caso se utilizo del jdk 17).

## Características

### 1 -Creación automática de tablas:

* Al ejecutar la aplicación por primera vez, las tablas necesarias se crean automáticamente en la base de datos si la configuración es correcta.

## Menú interactivo:

La aplicación presenta un menú con las siguientes opciones:

![Screenshot 2025-01-13 004610](https://github.com/user-attachments/assets/54e0a272-b15b-4b28-895a-cf5ee1f17186)

## Uso

### 1 - Conexión inicial:

* Asegúrese de que la base de datos PostgreSQL esté creada y configurada correctamente.

* Configure las variables de entorno necesarias para conectar la aplicación a la base de datos.

### 2 - Primer uso:

* Se recomienda iniciar con la opción 1) Buscar un libro por título.

* Esto asegura que la base de datos se alimente con información proveniente del API Gutendex, permitiendo que las opciones 2) a 5) muestren resultados.

### 3 - Opciones secundarias:

* Las opciones 2) a 5) dependen de la información almacenada en la base de datos.

* Si intenta usarlas sin realizar previamente una búsqueda de libros, no se mostrará información.

### 4 - Salir:

* Use la opción 6) para finalizar la ejecución de la aplicación.

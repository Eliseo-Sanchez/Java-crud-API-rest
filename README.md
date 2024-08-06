# Proyecto CRUD API REST con Spring Boot

## Descripción

Este es un pequeño proyecto que permite realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) a través de una API REST. Es uno de mis primeros proyectos usando **Spring Boot**, **Hibernate**, y **PostgreSQL**. También utilicé herramientas como **Postman**, **MongoDB**, **TablePlus** y **Docker** para probar y gestionar diferentes aspectos del proyecto.

## Características

-   **Operaciones CRUD**: Puedes crear, leer, actualizar y eliminar elementos.
-   **API REST**: Comunicación sencilla a través de HTTP.
-   **Pruebas y Gestión**: Utilicé Postman para probar la API, Docker para contenedores, y TablePlus para gestionar bases de datos.

## Requisitos

-   **Java**: Java 8 o superior.
-   **Maven**: Para manejar las dependencias del proyecto.

## Cómo Empezar

1.  **Clonar el repositorio**
    
    bash
    
    `git clone https://github.com/Eliseo-Sanchez/Java-crud-API-rest` 
    
2.  **Configurar la base de datos**
    
    Ajusta las configuraciones de la base de datos en el archivo `.env` con tus credenciales.
    
    `spring_datasource_url=jdbc:postgresql://localhost:5432/tu_base_de_datos
    spring_datasource_username=tu_usuario
    spring_datasource_password=tu_contraseña
    spring_datasource_db=nombre_bd` 
    
3.  **Iniciar la aplicación**
    
    bash
    
    `mvn clean install
    mvn spring-boot:run` 
    

## Cómo Usar

La API ofrece varias operaciones. Aquí hay algunos ejemplos:

-   **GET** `/api/recursos`: Ver todos los recursos.
-   **POST** `/api/recursos`: Añadir un nuevo recurso.
-   **GET** `/api/recursos/{id}`: Obtener detalles de un recurso específico.
-   **PUT** `/api/recursos/{id}`: Actualizar un recurso.
-   **DELETE** `/api/recursos/{id}`: Eliminar un recurso.

Puedes usar herramientas como Postman para probar estas rutas.

## Tecnologías Utilizadas

-   **Spring Boot**: Para simplificar el desarrollo de la aplicación.
-   **Hibernate**: Para manejar la base de datos de manera eficiente.
-   **MongoDB**: Utilizado para pruebas adicionales.
-   **Postman**: Para probar las solicitudes de la API.
-   **Docker**: Para crear contenedores.
-   **TablePlus**: Para administrar bases de datos.

## Autor

-   **Cristian Sanchez** - eliseo.rivera044@gmail.com

----------
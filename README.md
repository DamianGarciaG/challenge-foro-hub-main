# Foro Hub 👩‍💻

Foro Hub es una aplicación de foro diseñada para facilitar la comunicación y discusión entre usuarios. Esta aplicación permite a los usuarios crear tópicos, responder a los mismos y participar en discusiones.

<p align="center">
    <img src="https://github.com/Orliluq/ForoHub/assets/122529721/952e8461-2eac-4c28-8fd0-bb676e672528"/>
</p>


## Características ⚙️

- Registro y autenticación de usuarios.
- Creación, edición y eliminación de tópicos.
- Respuesta a tópicos existentes.
- Listado de usuarios y tópicos.
- Autenticación mediante JWT.

## Tecnologías utilizadas ⚒️

- Java
- Spring Boot
- Spring Security
- JWT (JSON Web Tokens)
- JPA (Java Persistence API)
- H2 Database (para desarrollo y pruebas)
- Postman (para pruebas de API)
- Swagger (para documentación de API)

## Estructura del proyecto 🖥️

- **Entities**: Clases de entidad que representan las tablas de la base de datos.
- **Dto**: Clases de Data Transfer Object utilizadas para transferir datos entre el cliente y el servidor.
- **Repository**: Interfaces que extienden JpaRepository para realizar operaciones CRUD en las entidades.
- **Service**: Clases de servicio que contienen la lógica de negocio.
- **Controller**: Clases de controlador que manejan las solicitudes HTTP.
- **Security**: Clases relacionadas con la configuración de seguridad y la autenticación.

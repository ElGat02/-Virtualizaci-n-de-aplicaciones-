Proyecto Virtualizacion de aplicaciones

Esta aplicación incorpora tecnologías modernas como Angular para el frontend y Wildffy para el backend, integradas en una 2 imagenes de Docker asi como el despliegue de 7 contenedores. La finalidad de esta práctica es brindar a los  una experiencia práctica y comprensiva en la gestión de múltiples procesos dentro de un solo contenedor de Docker, lo cual es esencial para la comprensión profunda de la virtualización de aplicaciones.

# Aplicación de Microservicios con Docker, WildFly y Angular

Este repositorio contiene el código fuente de una aplicación de microservicios utilizando Docker Compose para orquestar contenedores que ejecutan WildFly como backend y Angular como frontend.

## Estructura del Proyecto

- **Cliente/**: Contiene el código fuente del frontend desarrollado con Angular.
- **src/**: Contiene el código fuente del backend Java para WildFly.
- **Dockerfile**: Dockerfile para construir la imagen del backend.
- **Dockerfile.swagger**: Dockerfile para construir la imagen de Swagger UI.
- **docker-compose.yml**: Archivo para definir y ejecutar aplicaciones multi-contenedor.
- **openapi.yaml**: Especificaciones de la API utilizando el estándar OpenAPI.
- **pom.xml**: Archivo de configuración Maven para el backend.
- **swagger-initializer.js**: Script de inicialización para configurar Swagger UI.

## Requisitos Previos

Para ejecutar esta aplicación, necesitarás tener instalado Docker y Docker Compose. Visita [Docker](https://www.docker.com/get-started) para obtener las instrucciones de instalación.



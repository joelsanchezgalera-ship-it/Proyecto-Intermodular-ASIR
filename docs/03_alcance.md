# 3. Alcance del proyecto
## 3.1. Alcance funcional

El proyecto tiene como objetivo transformar la página web inicial de TransNova Logistics en una aplicación web funcional conectada a una base de datos.

### Funcionalidades incluidas

- Presentación de la información y servicios de TransNova Logistics.
- Gestión de información relacionada con clientes.
- Gestión de información relacionada con envíos.
- Gestión de información relacionada con los servicios ofrecidos.
- Conexión entre la aplicación web y la base de datos.
- Envío y consulta de información mediante la aplicación web.
- Alojamiento de la aplicación mediante un servidor Apache.
- Aplicación de medidas básicas de seguridad.
- Realización de copias de seguridad de la información.
- Documentación de la configuración y de las pruebas realizadas.

### Funcionalidades excluidas

En esta fase no se contempla el desarrollo de una aplicación móvil, la integración con plataformas externas de transporte o sistemas de pago, ni la creación de una infraestructura empresarial de producción.

Estas funcionalidades podrían plantearse como ampliaciones futuras del proyecto.

## 3.2. Alcance técnico

El proyecto utilizará una arquitectura basada en una aplicación web, un servidor Linux y una base de datos relacional.

Las principales tecnologías previstas son:

- **Sistema operativo:** Ubuntu Server.
- **Servidor web:** Apache.
- **Base de datos:** MySQL/MariaDB.
- **Aplicación web:** HTML, CSS y un lenguaje de programación del lado del servidor.
- **Contenedores:** Docker, para facilitar la instalación y gestión de determinados servicios durante el desarrollo.
- **Red:** configuración de red necesaria para permitir la comunicación entre los diferentes componentes.

La infraestructura se desarrollará inicialmente en un entorno de pruebas y se documentará la configuración realizada. El objetivo es disponer de una plataforma que permita ejecutar la aplicación web y conectarla con la base de datos de forma controlada.

La elección definitiva de la plataforma de virtualización o despliegue se justificará posteriormente entre las alternativas indicadas en la actividad: **GNS3, AWS o Docker**.

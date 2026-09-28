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

## 3.3. Alcance temporal

El proyecto se desarrollará de forma progresiva, organizando el trabajo en diferentes fases para facilitar la planificación, implementación y documentación de la solución.

| Fase | Descripción | Resultado previsto |
|---|---|---|
| Fase 1 | Análisis y planificación | Definición del reto, objetivos, alcance y requisitos. |
| Fase 2 | Diseño de la solución | Diseño de la aplicación, base de datos e infraestructura. |
| Fase 3 | Configuración del entorno | Preparación del sistema operativo, servidor y servicios necesarios. |
| Fase 4 | Desarrollo e integración | Desarrollo de la aplicación y conexión con la base de datos. |
| Fase 5 | Seguridad y copias de seguridad | Aplicación de medidas básicas de seguridad y configuración de copias de seguridad. |
| Fase 6 | Pruebas | Comprobación del funcionamiento de la aplicación y de los servicios. |
| Fase 7 | Documentación y presentación | Documentación del proyecto y preparación de la defensa final. |

Los principales hitos serán la finalización de la fase de análisis, la disponibilidad del entorno de servidor, la integración de la aplicación con la base de datos, la realización de las pruebas y la entrega final del proyecto.

## 3.4. Alcance de recursos

El proyecto será desarrollado utilizando los recursos disponibles para el desarrollo del Proyecto Intermodular de 2.º ASIR.

### Recursos humanos

El desarrollo, configuración, pruebas y documentación del proyecto serán realizados por el alumno, aplicando los conocimientos adquiridos en los diferentes módulos del ciclo.

### Recursos hardware

Se utilizará un equipo informático capaz de ejecutar el entorno de desarrollo y las máquinas o contenedores necesarios para realizar las pruebas del proyecto.

### Recursos software

Se utilizarán principalmente herramientas y tecnologías relacionadas con sistemas Linux, servidores web, bases de datos, redes, seguridad y virtualización o contenedores.

### Recursos económicos

El proyecto se plantea utilizando principalmente software y tecnologías que permitan realizar el desarrollo en un entorno académico sin necesidad de contratar servicios externos. Por este motivo, no se establece inicialmente un presupuesto de infraestructura física o de servicios cloud.

# 4. Requisitos del proyecto
## 4.1. Requisitos funcionales

Los requisitos funcionales describen las funciones que deberá proporcionar la aplicación web de TransNova Logistics.

| ID | Requisito funcional | Prioridad | Estado |
|---|---|---|---|
| RF-001 | El sistema deberá mostrar información sobre los servicios de TransNova Logistics. | Alta | Planificado |
| RF-002 | El sistema deberá permitir gestionar la información de los clientes. | Alta | Planificado |
| RF-003 | El sistema deberá permitir gestionar la información de los envíos. | Alta | Planificado |
| RF-004 | El sistema deberá permitir gestionar la información de los servicios. | Alta | Planificado |
| RF-005 | El sistema deberá permitir introducir información mediante formularios web. | Alta | Planificado |
| RF-006 | El sistema deberá almacenar la información introducida en la base de datos. | Alta | Planificado |
| RF-007 | El sistema deberá permitir consultar información almacenada en la base de datos. | Alta | Planificado |
| RF-008 | La aplicación deberá comunicarse con la base de datos mediante el servidor. | Alta | Planificado |
| RF-009 | El servidor deberá alojar y proporcionar acceso a la aplicación web mediante Apache. | Alta | Planificado |
| RF-010 | El sistema deberá permitir realizar pruebas para comprobar el funcionamiento de la aplicación y sus servicios. | Media | Planificado |
## 4.2. Requisitos no funcionales

Los requisitos no funcionales definen las características de calidad, seguridad, rendimiento y mantenimiento que deberá cumplir la solución.

| ID | Requisito no funcional | Prioridad | Estado |
|---|---|---|---|
| RNF-001 | La aplicación deberá presentar un tiempo de respuesta adecuado durante su utilización. | Alta | Planificado |
| RNF-002 | La aplicación deberá adaptarse correctamente a diferentes tamaños de pantalla. | Media | Planificado |
| RNF-003 | La información almacenada deberá protegerse frente a accesos no autorizados. | Alta | Planificado |
| RNF-004 | El servidor y los servicios utilizados deberán mantenerse actualizados. | Alta | Planificado |
| RNF-005 | Deberán realizarse copias de seguridad de la información importante. | Alta | Planificado |
| RNF-006 | La aplicación deberá estar disponible durante las pruebas y demostraciones previstas. | Media | Planificado |
| RNF-007 | La solución deberá estar documentada para facilitar su mantenimiento y configuración. | Alta | Planificado |
| RNF-008 | Los diferentes componentes deberán estar organizados de forma que faciliten su mantenimiento. | Media | Planificado |

## 4.3. Requisitos de negocio

Los requisitos de negocio describen las necesidades principales que debe cubrir la solución desde el punto de vista de la actividad de TransNova Logistics.

| ID | Requisito de negocio | Prioridad | Estado |
|---|---|---|---|
| RN-001 | La solución deberá facilitar la gestión de la información relacionada con los clientes. | Alta | Planificado |
| RN-002 | La solución deberá facilitar la gestión de los envíos realizados por la empresa. | Alta | Planificado |
| RN-003 | La solución deberá permitir gestionar la información de los servicios ofrecidos. | Alta | Planificado |
| RN-004 | La información de clientes, envíos y servicios deberá mantenerse centralizada. | Alta | Planificado |
| RN-005 | La aplicación deberá facilitar el acceso a la información necesaria para la gestión de la actividad. | Media | Planificado |
| RN-006 | La solución deberá permitir ampliar sus funcionalidades en futuras fases del proyecto. | Media | Planificado |

## 4.4. Requisitos por módulos de ASIR

### 4.4.1. ASGBD

Los requisitos relacionados con el módulo de Administración de Sistemas Gestores de Bases de Datos se centran en la instalación, configuración y gestión de la base de datos utilizada por la aplicación.

| ID | Requisito | Prioridad | Estado |
|---|---|---|---|
| ASGBD-001 | El sistema deberá disponer de un sistema gestor de bases de datos para almacenar la información de la aplicación. | Alta | Planificado |
| ASGBD-002 | La base de datos deberá almacenar información relacionada con clientes, envíos y servicios. | Alta | Planificado |
| ASGBD-003 | El sistema deberá permitir realizar consultas sobre la información almacenada. | Alta | Planificado |
| ASGBD-004 | Se deberán realizar copias de seguridad de la base de datos. | Alta | Planificado |
| ASGBD-005 | El acceso a la base de datos deberá estar protegido mediante usuarios y permisos adecuados. | Alta | Planificado |

### 4.4.2. ASO

Los requisitos relacionados con el módulo de Administración de Sistemas Operativos se centran en la configuración y mantenimiento del servidor Linux que proporcionará los servicios necesarios para la aplicación.

| ID | Requisito | Prioridad | Estado |
|---|---|---|---|
| ASO-001 | El servidor deberá utilizar Ubuntu Server como sistema operativo. | Alta | Planificado |
| ASO-002 | El servidor deberá disponer de Apache para alojar la aplicación web. | Alta | Planificado |
| ASO-003 | El sistema deberá disponer de los servicios necesarios para ejecutar la aplicación web. | Alta | Planificado |
| ASO-004 | El servidor deberá mantenerse actualizado mediante las herramientas de actualización del sistema. | Alta | Planificado |
| ASO-005 | El sistema deberá disponer de una configuración de red adecuada para permitir el funcionamiento de la aplicación. | Alta | Planificado |
| ASO-006 | Se deberán realizar tareas básicas de mantenimiento y comprobación del funcionamiento del servidor. | Media | Planificado |

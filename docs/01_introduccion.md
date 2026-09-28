# 1. Introducción
## 1.1. Título del reto
Desarrollo e implementación de una aplicación web funcional para TransNova Logistics, conectada a una base de datos y desplegada mediante un servidor Apache.

## 1.2. Contexto
El proyecto parte del trabajo realizado durante el primer curso de ASIR sobre TransNova Logistics, una empresa simulada dedicada al transporte y la logística. En ese proyecto se diseñó una página web corporativa, una base de datos para gestionar información de clientes, envíos y servicios, además de una infraestructura básica de servidores y red.

Durante el desarrollo del proyecto anterior, la página web tenía principalmente una función informativa y algunos formularios todavía no eran funcionales. Por este motivo, en segundo curso se plantea continuar el proyecto y convertirlo en una aplicación web más realista y útil.

El objetivo de esta ampliación será conectar la aplicación web con la base de datos, configurar un servidor Apache para alojarla y desarrollar la comunicación entre la web y el servidor. De esta forma, la información introducida desde la aplicación podrá ser gestionada mediante la base de datos en lugar de limitarse a mostrar contenido estático.

Durante este curso se continuará el desarrollo para conseguir una aplicación web más funcional, integrada con la base de datos y desplegada mediante Apache.

## 1.3. Problemática o necesidad
El proyecto inicial de TransNova Logistics dispone de una página web y de una base de datos, pero estos elementos no están integrados de forma funcional. La web tiene principalmente un carácter informativo, por lo que los formularios y la gestión de información no permiten realizar operaciones reales sobre la base de datos.

Esta situación limita la utilidad de la aplicación, ya que la información relacionada con clientes, envíos y servicios no puede gestionarse directamente desde la web. Además, es necesario disponer de un servidor correctamente configurado que permita alojar la aplicación y proporcionar los servicios necesarios para su funcionamiento.

Por ello, surge la necesidad de transformar la web existente en una aplicación funcional que permita gestionar información de forma centralizada y que pueda ejecutarse sobre una infraestructura de servidor configurada específicamente para el proyecto.

## 1.4. Objetivos
Objetivo general

Desarrollar una aplicación web funcional para TransNova Logistics que permita gestionar información de la empresa mediante una base de datos y que esté alojada en un servidor Apache correctamente configurado.

Objetivos específicos
- Adaptar la página web desarrollada en el proyecto anterior para convertirla en una aplicación funcional.
- Conectar la aplicación web con la base de datos de TransNova Logistics.
- Configurar un servidor Linux con Apache para alojar la aplicación web.
- Permitir el envío y consulta de información desde la aplicación web mediante la base de datos.
- Organizar la información relacionada con clientes, envíos y servicios.
- Configurar los servicios necesarios para que la aplicación funcione correctamente en el servidor.
- Aplicar medidas básicas de seguridad y realizar copias de seguridad de la información.
- Documentar la configuración realizada y las pruebas de funcionamiento del proyecto.

## 1.5 Interesados
| Interesado | Relación con el proyecto | Necesidad principal |
|---|---|---|
Clientes|Utilizan la aplicación para consultar y gestionar información relacionada con sus servicios y envíos.|Disponer de una aplicación sencilla para realizar consultas y enviar información.
Personal de TransNova Logistics|Gestiona la información de clientes, envíos y servicios mediante la aplicación.	|Acceder y gestionar la información de forma centralizada.
Administrador del sistema	|Se encarga de mantener el servidor, la aplicación y la base de datos.	|Disponer de una infraestructura estable, segura y correctamente configurada.
Desarrollador del proyecto	|Diseña, configura, implementa y documenta la solución.	|Integrar correctamente la aplicación web, el servidor y la base de datos.

<!-- Introducción del proyecto TransNova Logistics -->
## 1.6. Análisis del contexto

### 1.6.1. Contexto empresarial

TransNova Logistics es una empresa simulada del sector del transporte y la logística, creada como base del proyecto desarrollado durante el primer curso de ASIR. Su actividad está relacionada con la gestión de clientes, envíos y servicios de transporte.

El proyecto inicial planteaba la creación de una página web corporativa para presentar los servicios de la empresa y facilitar la gestión de información relacionada con su actividad. También se diseñó una base de datos relacional para almacenar información de clientes, envíos y servicios.

En esta segunda fase del proyecto se pretende ampliar la solución anterior y convertirla en una aplicación web funcional. De esta forma, TransNova Logistics podrá disponer de una plataforma centralizada desde la que gestionar la información de su actividad y mejorar la integración entre la aplicación web, la base de datos y la infraestructura de servidores.

Al tratarse de una empresa simulada, el proyecto se centra principalmente en diseñar y demostrar una solución tecnológica que pueda representar las necesidades de una empresa real del sector logístico.

### 1.6.2. Contexto tecnológico

El proyecto parte de una infraestructura tecnológica planteada durante el primer curso de ASIR. La solución inicial incluye un servidor basado en Ubuntu Server, una red local y una base de datos relacional destinada a gestionar la información de clientes, envíos y servicios.

La página web desarrollada inicialmente tiene principalmente una función informativa y está formada por diferentes páginas HTML y hojas de estilos CSS. Aunque se diseñaron formularios y una estructura preparada para una futura integración, estos elementos no eran todavía completamente funcionales.

En esta segunda fase se pretende aumentar el nivel de digitalización de la solución mediante la integración de la aplicación web con la base de datos. También se plantea utilizar un servidor Apache para alojar la aplicación y permitir la comunicación entre los diferentes componentes.

La infraestructura tecnológica se irá ampliando durante el desarrollo del proyecto, incorporando los servicios necesarios para que la aplicación pueda funcionar de forma centralizada, segura y estable.

### 1.6.3. Contexto del mercado

TransNova Logistics se sitúa dentro del sector del transporte y la logística, un sector estrechamente relacionado con el crecimiento del comercio electrónico y con la necesidad de gestionar cada vez un mayor volumen de envíos.

En España, la logística vinculada al comercio electrónico generó 4.435 millones de euros en 2025, lo que supone un crecimiento del 6 % respecto al año anterior. Además, los diez principales operadores concentraron el 51 % del mercado, mostrando la existencia de una competencia importante y de empresas de gran tamaño. 

El crecimiento de la paquetería también refleja la evolución del sector. Durante 2025 se enviaron en España 1.335 millones de paquetes, un 10 % más que en 2024. Este crecimiento está relacionado con la expansión del comercio electrónico y con la necesidad de ofrecer servicios de transporte y entrega cada vez más eficientes.

Entre los operadores presentes en el mercado español se encuentran empresas como DHL, FedEx, UPS, Correos Express, GLS, MRW, NACEX, SEUR e InPost, entre otras. Esto hace que las empresas del sector tengan que diferenciarse mediante aspectos como la calidad del servicio, la rapidez, la información proporcionada al cliente y la utilización de tecnologías digitales.

La digitalización es una de las principales tendencias del sector. El seguimiento de envíos en tiempo real, el análisis de datos y el uso de nuevas tecnologías permiten mejorar la planificación de rutas, reducir errores y ofrecer una mayor información al cliente.

Por este motivo, el desarrollo de una aplicación web conectada a una base de datos puede representar una mejora tecnológica para TransNova Logistics, ya que permitiría centralizar la información de clientes, envíos y servicios y facilitar su gestión.

### 1.6.4. Contexto social y geográfico

TransNova Logistics se plantea dentro del entorno de **Crevillent, en la provincia de Alicante**, un municipio con una importante actividad empresarial e industrial. Históricamente, la industria de la alfombra ha tenido un papel destacado en la economía local, mientras que actualmente la actividad económica está más diversificada y tiene un peso importante el sector servicios.

El municipio cuenta además con diferentes áreas industriales y un tejido empresarial formado por empresas de distintos sectores. El Ayuntamiento dispone de un directorio empresarial en el que aparecen actividades relacionadas con el comercio, la industria, los servicios y también el transporte.

La situación de Crevillent dentro del entorno de la provincia de Alicante y su proximidad a ciudades como Elche favorecen la relación con otras zonas empresariales y comerciales. Esta situación resulta relevante para una empresa dedicada al transporte y la logística, ya que sus actividades pueden estar relacionadas con el movimiento de mercancías entre empresas, clientes y diferentes localidades.

Desde el punto de vista social y económico, la digitalización de las empresas puede contribuir a mejorar la gestión de sus actividades. De hecho, el Ayuntamiento ha impulsado durante los últimos años diferentes iniciativas relacionadas con el emprendimiento, la innovación y la modernización de establecimientos y actividades económicas.

Por este motivo, el proyecto de TransNova Logistics pretende representar una solución tecnológica adaptada a las necesidades de una empresa del entorno, utilizando una aplicación web y una infraestructura informática que permitan gestionar la información de forma centralizada.























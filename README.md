# Temario-de-construye-e-implementa-aplicaciones-web
Accede a GitHub y crea un repositorio llamado Temario de Aplicaciones Web con el archivo README en donde investigarás con imágenes los temas propuestos. Al finalizar, compartir el permalink del sitio del temario de App Web en GitHub creado por ti.


Propósito de Aprendizaje 1: Comprender los fundamentos del desarrollo de aplicaciones web.
Introducción al desarrollo web
-------------------------------------------------------------------------------------------
# Historia y evolución del desarrollo web:
La historia y evolución del desarrollo web ha estado marcada por avances tecnológicos y cambios en las necesidades de los usuarios. Todo comenzó en la década de 1990 con la creación de la World Wide Web por Tim Berners-Lee, donde los primeros sitios eran estáticos y escritos en HTML básico. Con el tiempo, surgieron nuevas tecnologías como CSS para el diseño y JavaScript para la interactividad, permitiendo páginas más dinámicas. La aparición de frameworks, gestores de contenido y la popularización de los dispositivos móviles impulsaron la evolución hacia aplicaciones web complejas, responsivas y seguras. Actualmente, el desarrollo web continúa transformándose con tendencias como el desarrollo full-stack, el uso de inteligencia artificial y la integración de tecnologías emergentes como WebAssembly y Progressive Web Apps.

-
Tipos de aplicaciones web (estáticas, dinámicas, SPA, PWA)
-

Aplicaciones web estáticas:
-

Son sencillas, con contenido fijo en HTML y CSS, ideales para información que no cambia frecuentemente, como un portafolio personal o una página de presentación.


Aplicaciones web dinámicas:
-

Utilizan bases de datos para mostrar información que se actualiza constantemente. Un ejemplo son los portales de noticias que muestran contenido reciente cada vez que un usuario accede.


Aplicaciones de una sola página (SPA):
-

Cargan una única página web y la actualizan dinámicamente sin necesidad de recargarla por completo, ofreciendo una experiencia fluida como la de una aplicación nativa como Google Docs.


Aplicaciones web progresivas (PWA):
-
Se pueden descargar en dispositivos y funcionar incluso sin conexión, mejorando la accesibilidad y el rendimiento como Netflix o Spotify. 

.
Arquitectura de aplicaciones web
Cliente-Servidor
----------------------------------------
Es un modelo informático donde un programa cliente solicita servicios o recursos a un programa servidor, que los provee. El cliente interactúa con el usuario, mientras que el servidor gestiona y centraliza los recursos y el procesamiento de datos.

Arquitectura de tres capas (presentación, lógica, datos)
-
# Capa de Presentación (Interfaz de Usuario):
Es la capa que interactúa directamente con el usuario, mostrando la información y recolectando las entradas. Generalmente se implementa en tecnologías web como HTML, CSS o JavaScript, y utiliza interfaces gráficas de usuario

# Capa de Lógica de Aplicación (o de Negocio):
Es el "cerebro" de la aplicación, donde se procesan las reglas de negocio, se gestionan las operaciones y se toman decisiones. Esta capa se comunica con la capa de presentación y la capa de datos, actuando como intermediaria. 

# Capa de Acceso a Datos:
Se encarga del almacenamiento, la gestión y la recuperación de la información de una base de datos. Esta capa garantiza la consistencia, seguridad e integridad de los datos. 

REST y API-first design
-
# REST (Representational State Transfer)
REST es un conjunto de principios de diseño para la arquitectura de servicios web, no un estándar en sí mismo. 
Permite la independencia del cliente y el servidor, lo que mejora la escalabilidad y la flexibilidad del sistema. 
Se basa en métodos estándar de HTTP (GET, POST, PUT, DELETE) para realizar operaciones sobre recursos. 
Cada solicitud del cliente al servidor debe contener toda la información necesaria para ser procesada, sin depender de la sesión o el estado anterior. 
La naturaleza sin estado y la consistencia en las respuestas de las solicitudes GET permiten un almacenamiento en caché eficiente, mejorando el rendimiento. 

Enfoque API-First
-
El diseño de la API (el contrato) se define y se aprueba por todas las partes interesadas (desarrolladores, equipos de producto) antes de escribir cualquier código. 
Las API son tratadas como componentes fundamentales del producto, lo que asegura que se alineen con las necesidades de los consumidores de la API, ya sean desarrolladores internos o externos. 
Se utilizan lenguajes de descripción de API, como la Especificación OpenAPI, para definir un contrato claro y estándar que guíe el desarrollo de los servicios. 
Facilita el desarrollo paralelo de diferentes API y la reutilización de componentes, acelerando el proceso. 
Al anticipar las necesidades de los desarrolladores desde el inicio, se crea una experiencia de uso más intuitiva y se mejora la calidad del producto final. 

.
Lenguajes y tecnologías fundamentales
-
# HTML (HyperText Markup Language) 
Es el lenguaje de marcado estándar utilizado para crear la estructura y el contenido de las páginas web.
Define los elementos de una página, como encabezados, párrafos, imágenes y tablas, indicando al navegador qué es cada parte del contenido.

# CSS (Cascading Style Sheets) 
Es un lenguaje de hoja de estilos que se utiliza para describir la presentación de los elementos HTML.
Controla el aspecto visual de una página web, incluyendo colores, fuentes, diseños y la disposición de los elementos.

# JavaScript
Un lenguaje de programación que añade interactividad y dinamismo a las páginas web. 
Permite crear elementos que responden a las acciones del usuario, como formularios interactivos, animaciones y la actualización del contenido sin recargar la página. 

# PHP (PHP: Hypertext Preprocessor)
Un lenguaje de script del lado del servidor que se ejecuta en el servidor web para generar contenido de forma dinámica. 
Se utiliza para procesar datos de formularios, interactuar con bases de datos y crear contenido personalizado para los usuarios, como en el caso de aplicaciones y sitios web dinámicos. 

# MySQL
Un sistema de gestión de bases de datos relacionales (RDBMS) que utiliza el lenguaje de consulta estructurado (SQL). 
Se encarga de almacenar, organizar y recuperar grandes cantidades de datos de manera eficiente. Es fundamental para sitios web y aplicaciones que necesitan manejar información, como usuarios, productos o publicaciones.

Control de versiones
-
# Git: La Herramienta de Control de Versiones
Git es un software de código abierto que te permite guardar "instantáneas" de tus archivos a lo largo del tiempo, creando un historial del proyecto. 
Te ayuda a rastrear los cambios, volver a versiones anteriores si es necesario, y trabajar en diferentes "ramas" de un proyecto sin afectar el código principal. 

# GitHub: La Plataforma de Colaboración 
GitHub es un sitio web y un servicio en la nube que aloja los repositorios creados con Git. 
Permite que varios desarrolladores trabajen en un mismo proyecto al mismo tiempo, viendo las ediciones de los demás en tiempo real. 

Flujo de trabajo con ramas (branching, merge, pull requests)
-
Un flujo de trabajo con ramas en sistemas como Git es un proceso para organizar el desarrollo colaborativo, donde se crean ramas separadas para nuevas características o correcciones, se trabaja en ellas de forma aislada y luego se usan Pull Requests para solicitar la fusión de esos cambios al proyecto principal (rama main) tras una revisión de código. 

# Branching (Ramificación):

La creación de una línea de desarrollo separada de la rama principal para trabajar en características nuevas o experimentales sin interferir con el código estable. 

# Merge (Fusión):
El proceso de combinar los cambios de una rama en otra, generalmente de una rama de característica a la rama principal. 

# Pull Request (Solicitud de Extracción):
Una solicitud formal para incorporar los cambios de una rama a otra. Permite a otros miembros del equipo revisar el código, discutirlo y aprobar la fusión antes de que se realice. 

.
Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web
Diseño e implementación del frontend
------

# Wireframe (Estructura)
Propósito:
Visualizar la estructura de la interfaz, el flujo del usuario y la disposición de los elementos. 
Características:
Es una representación de baja fidelidad, a menudo en escala de grises, que utiliza formas básicas como cajas y líneas. 
Enfoque:
La funcionalidad, la navegación y la ubicación de los componentes, sin detalles estéticos. 
Uso:
Se crean en las primeras etapas del diseño para establecer la base y la arquitectura del producto. 

# Mockup (Maqueta)
Propósito:
Mostrar cómo se verá la interfaz del producto final, con todos sus detalles visuales y estéticos. 
Características:
Es una representación de alta fidelidad que incluye colores, tipografía, imágenes y otros elementos gráficos. 
Enfoque:
La apariencia visual, la estética y la experiencia de usuario, simulando el diseño final. 
Uso:
Se utilizan en etapas intermedias o avanzadas para refinar el diseño visual y obtener feedback. 

API
-
Es un conjunto de reglas y definiciones que permite que dos aplicaciones de software diferentes se comuniquen entre sí, actuando como un puente para el intercambio de datos y servicios. Permite a las aplicaciones enviar y recibir información de manera estandarizada, facilitando la creación de aplicaciones más complejas al no tener que desarrollar todas sus funcionalidades desde cero.

Diseño e implementación del backend
-
# Servidor
Consiste en crear y mantener la lógica del lado del servidor, bases de datos e infraestructura necesaria para que una aplicación web funcione, procese datos y responda a las solicitudes de los usuarios de manera segura y eficiente

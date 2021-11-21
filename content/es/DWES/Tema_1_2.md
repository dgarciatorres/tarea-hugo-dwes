---
title: "Tema_1_2"
date: 2021-11-10T23:26:33+01:00
draft: false
weight: 2
---

# ARQUITECTURA Y TECNOLOGÍA WEB

## Qué es la arquitectura web
La **arquitectura web** es la jerarquización de la información en un sitio **web**. Así como en la arquitectura tradicional se trabaja la estructura de una construcción , la arquitectura web trabaja la estructura de una página web y las categorías que la conforman para su optimización de cara al posicionamiento en buscadores.

{{% button href="https://www.tokioschool.com/noticias/importancia-arquitectura-web/" %}}Más info{{% /button %}}

## Los componentes de una aplicación web
### 1. Servidor web
Un servidor web es un software (programa) encargado de recibir una solicitud por la red; En una red de tipo tcp/ip que es la que usamos en internet, la solicitud se recibe usando el protocolo http y responder a dicha solicitud.

Responder a dicha solicitud implica verificar permisos, ejecutar script, puede que tenga que hacer solicitudes de información a otros servidores y generar un mensaje de respuesta usando igualmente el protocolo http. Es muy frecuente que la respuesta es una página html.

### 2. Servidor Bases de datos
Un servidor de base de datos es un software (programa) encargado de gestionar una bases de datos.

Dada la importancia de esta sección confidencialidad y posible cuello de botella en una aplicación, el servidor de bases de datos suele estar en un servidor dedicado específicamente a ese cometido

### 3. El módulo de ejecución de código en el servidor
Ante una solicitud del cliente el servidor no solo entrega una página web, antes de ello es muy frecuente que ejecute código del cual el cliente nunca será consciente.

Para ello tenemos que tener un módulo instalado en el servidor para ejectuar ese código.Nosotros usaremos PHP y posteriormente JavaScript en el servidor con NodeJS. Es el aspecto fundamental para este módulo o asignatura


## La arquitectura de la aplicación

Un servidor de aplicaciones web en realidad puede estar formado por varios servidores físicos.

> Cada servidor se puede encargar de ejecutar una parte de la aplicación.


### Arquitectura de 3 capas
1. capa de acceso a datos: que se tendrá que encargar de almacenar la información de la aplicación en una base de datos y recuperarla cuando sea necesario.
2. capa intermedia : donde deberás programar la funcionalidad de tu aplicación.
3. capa cliente: que es donde programarás todo lo relacionado con el interface de usuario, esto es, la parte
visible de la aplicación con la que interactuará el usuario.


{{<youtube _yi3UVcuw_8>}}

***¿Cómo ser BACKEND DEVELOPER? Ruta para APRENDER DESARROLLO WEB en 2021***
*Carlos Azaustre - Aprende JavaScript*


## La arquitecturas de despliegue

### Arquitectura LAMP/WAMP

1. **LAMP**
LAMP es un acrónimo de Linux, Apache, MySQL y PHP. Cada uno de estos componentes es de código abierto y de uso gratuito, lo que ha contribuido a su popularidad.

La pila de lámparas es probablemente la pila más común utilizada para alojar sitios web y aplicaciones web, especialmente sitios de tamaño pequeño a mediano.

2. **WAMP**
La forma completa de WAMP es Windows, Apache, MySQL y PHP. Como puede adivinar, el sistema operativo subrayado es Windows.

La única diferencia entre WAMP y LAMP es el sistema operativo detrás de estas pilas. Entonces, todo lo mencionado anteriormente para LAMP también lo hace WAMP, pero solo en el sistema Windows.

### Arquitectura MEAN
La pila media es una pila de JavaScript de código abierto que puede utilizar para crear aplicaciones web modernas rápidas, robustas y fáciles de mantener listas para producción.

La pila media es MongoDB, Express, Angular y Node.js.

MongoDB es la base de datos NoSQL y Express es el marco web que se ejecuta en el nodo, Angular es la plataforma de desarrollo del lado del cliente y Node.js es el entorno de ejecución. Juntos, pueden usarse para crear aplicaciones web increíbles.


### Arquitectura Java EE
Java™ Platform, Standard Edition (Java SE) y Java Platform, Enterprise Edition (Java EE) son plataformas muy utilizadas para la programación de los servidores de aplicaciones en el lenguaje de programación Java. Puede utilizar sesiones de reglas para llamar a aplicaciones Java SE o Java EE.

{{% button href="https://www.ibm.com/docs/es/odm/8.5.1?topic=application-java-se-java-ee-applications" %}}Más info{{% /button %}}
{{% button href="https://www.oracle.com/es/java/technologies/java-ee-glance.html" %}}Documentación oficial{{% /button %}}


----

{{% button href="http://es.wikipedia.org/wiki/Aplicaci%C3%B3n_web" %}}Qué es una aplicación web en wikipedia{{% /button %}}

{{% button href="http://es.wikipedia.org/wiki/Desarrollo_web" %}}Qué es un desarrollo web{{% /button %}}

{{% button href="http://www.hispamedios.com/articles/id34-url-y-uri" icon-position="right" %}}Ques es una URL vs diferencia con URI {{% /button %}}


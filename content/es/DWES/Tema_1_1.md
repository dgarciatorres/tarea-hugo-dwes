---
title: "Tema_1_1"
date: 2021-11-10T23:26:37+01:00
draft: false

weight: 1
---

# CONCEPTOS GENERALES

## Definición de desarrollo WEB
Término que define el proceso de creación de un sitio web o una intranet.
Para poder llevar a cabo esto se usan tecnologías de software del lado del cliente y del lado del servidor involucrando procesos de bases de datos con el uso del un navegador web para realizar unas tareas o mostrar información.

Para desarrollar una aplicación o programa
1. Hay que entenderlo muy bién lo que queremos hacer
2. Hay que planificarlo
3. Hay que realizar esa planificación y probarla

{{% notice note %}}
![Conexión TCP - negociación en tres pasos](/images/DesarrolloAplicaciones.jpeg)
{{% /notice %}}

## Aplicación Web
En la ingeniería de software se denomina aplicación web a aquellas herramientas que los usuarios pueden utilizar accediendo a un servidor web a través de internet o de una intranet mediante un navegador. En otras palabras, es un programa que se codifica en un lenguaje interpretable por los navegadores web en la que se confía la ejecución al navegador.

*Fuente: Wikipedia*

{{% notice info %}}
An information disclaimer
{{% /notice %}}

## Framework
Un entorno de trabajo​, o marco de trabajo​ es un conjunto estandarizado de conceptos, prácticas y criterios para enfocar un tipo de problemática particular que sirve como referencia, para enfrentar y resolver nuevos problemas de índole similar.

{{% notice info %}}
https://www.bestwebframeworks.com/
{{% /notice %}}

*Fuente: Wikipedia*

{{% button href="/es/tecnologías/" %}}Ver alguna tecnologías{{% /button %}}

# Qué es la ip
- Dentro del nivel de red tenemos el protocolo IP
- Su función principal es localizar la red donde está el equipo destino


# Qué es el puerto
- En el nivel de transporte tenemos los protocolos UDP y TCP
- Su función principal es localizar la aplicación a la cual va a ir destinada la comunicación o datos
- Se hace a través de un número que se conoce como el nombre puerto

{{% notice tip %}}
***ifconfig*** (ipconfig en windows) para saber la ip que tengo asignada

***ping*** para enviar un saludo a algún nodo con el objetivo de saber si está conectado

***route*** para conocer mis rutas y la ip de mi router más próximo (mi gateway que enruta)

***tracert*** para conocer la traza de rutas o ip's que sigue un paquete en una transmisión
{{% /notice %}}

{{% notice warning %}}
A warning disclaimer
{{% /notice %}}


# Servidor web:
Un servidor web es una aplicación que se ejecuta en una máquina como un servicio y se mantiene escuchando por un determinado puerto

Los más populares:
1. Apache HTTP Server
2. Microsoft IIS (Internet Information Services)
3. NGINX
4. Lighttpd
5. Sun Java System Web Server


# El comando curl
- Comando para hacer solicitudes de recursos sin usar un navegador.
- Con este comando podemos establecer comunicación con servidores usando los diferentes protocolos que soporta.
- Usando la sintaxis URL podemos transferir ficheros entre cliente y servidor.


**instalacion**
```
sudo apt-get install curl Ejemplos de uso del comando
```

Ver el **contenido** de una página web

```
 curl url_página_web
```

**Guardar** una página web en un fichero -o 
```
curl -o nombreFichero url_página_web
```

**Ver la cabecera** de una web
```
 curl --head url_pagina_web
```

Si la web nos redirige, hay que especificarlo con -L
```
curl -L url_página_web Para que accedamos a la página que nos redirige url_pagina_web
```

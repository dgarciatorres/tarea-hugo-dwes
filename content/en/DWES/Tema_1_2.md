---
title: "Theme_1_2"
date: 2021-11-10T23:26:33+01:00
draft: false
weight: 2
---

# ARCHITECTURE AND WEB TECHNOLOGY

## What is web architecture
The ** web architecture ** is the hierarchy of information on a ** website **. Just as traditional architecture works on the structure of a construction, web architecture works on the structure of a web page and the categories that make it up for optimization for search engine positioning.

{{% button href="https://www.tokioschool.com/noticias/importancia-arquitectura-web/" %}}Más info{{% /button %}}

## The components of a web application
### 1. Web server
A web server is a software (program) in charge of receiving a request over the network; In a tcp / ip type network that is the one we use on the internet, the request is received using the http protocol and responding to said request.

Responding to this request involves checking permissions, executing a script, you may have to make requests for information to other servers and generate a response message using the http protocol as well. Very often the answer is an html page.

### 2. Database Server
A database server is a software (program) in charge of managing a database.

Given the importance of this section, confidentiality and possible bottleneck in an application, the database server is usually on a server specifically dedicated to that purpose.

### 3. The code execution module on the server
Before a request from the client, the server not only delivers a web page, before that it is very frequent that it executes code of which the client will never be aware.

For this we have to have a module installed on the server to execute that code. We will use PHP and later JavaScript on the server with NodeJS. It is the fundamental aspect for this module or subject


## The architecture of the application

A web application server can actually be made up of multiple physical servers.

> Each server can be in charge of executing a part of the application.


### 3-layer architecture
1. Data access layer: which will have to be in charge of storing the application information in a database and retrieving it when necessary.
2. intermediate layer: where you must program the functionality of your application.
3. client layer: which is where you will program everything related to the user interface, that is, the part
visible of the application with which the user will interact.


{{<youtube _yi3UVcuw_8>}}

*** How to be a BACKEND DEVELOPER? Route to LEARN WEB DEVELOPMENT in 2021 ***
*Carlos Azaustre - Learn JavaScript*


## The deployment architectures

### LAMP / WAMP architecture

1. **LAMP**
LAMP is an acronym for Linux, Apache, MySQL, and PHP. Each of these components is open source and free to use, which has contributed to their popularity.

The lamp stack is probably the most common stack used for hosting websites and web applications, especially small to medium sized sites.

2. **WAMP**
The full form of WAMP is Windows, Apache, MySQL, and PHP. As you can guess, the underlined operating system is Windows.

The only difference between WAMP and LAMP is the operating system behind these stacks. So everything mentioned above for LAMP is also done by WAMP, but only on Windows system.

### MEAN Architecture
The medium stack is an open source JavaScript stack that you can use to build fast, robust, and easy-to-maintain modern production-ready web applications.

The middle stack is MongoDB, Express, Angular, and Node.js.

MongoDB is the NoSQL database and Express is the web framework running on the node, Angular is the client-side development platform, and Node.js is the runtime environment. Together, they can be used to create amazing web applications.


### Java EE architecture
Java ™ Platform, Standard Edition (Java SE) and Java Platform, Enterprise Edition (Java EE) are widely used platforms for programming application servers in the Java programming language. You can use rule sessions to call Java SE or Java EE applications.

{{% button href="https://www.ibm.com/docs/es/odm/8.5.1?topic=application-java-se-java-ee-applications" %}}
More info{{% /button %}}
{{% button href="https://www.oracle.com/es/java/technologies/java-ee-glance.html" %}}Official documentation{{% /button %}}


----

{{% button href="http://es.wikipedia.org/wiki/Aplicaci%C3%B3n_web" %}}
What is a web application on wikipedia{% /button %}}

{{% button href="http://es.wikipedia.org/wiki/Desarrollo_web" %}}What is a web development{{% /button %}}

{{% button href="http://www.hispamedios.com/articles/id34-url-y-uri" icon-position="right" %}}What is a URL vs difference with URI{{% /button %}}


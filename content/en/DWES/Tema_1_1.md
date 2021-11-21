---
title: "Theme_1_1"
date: 2021-11-10T23:26:37+01:00
draft: false

weight: 1
---

# GENERAL CONCEPTS

## Definition of WEB development
Term that defines the process of creating a website or an intranet.

In order to do this, client-side and server-side software technologies are used involving database processes with the use of a web browser to perform tasks or display information.

To develop an application or program
1. You have to understand very well what you want to do
2. You have to plan it
3. You have to do that planning and test it

{{% notice note %}}
![Conexión TCP - negociación en tres pasos](/images/DesarrolloAplicaciones.jpeg)
{{% /notice %}}

## Web Application
In software engineering, a web application is defined as those tools that users can use by accessing a web server through the Internet or an intranet through a browser. In other words, it is a program that is encoded in a language interpretable by web browsers in which the execution is entrusted to the browser.

*Source: Wikipedia*

{{% notice info %}}
An information disclaimer
{{% /notice %}}

## Framework
A work environment, or framework is a standardized set of concepts, practices and criteria to approach a particular type of problem that serves as a reference, to face and solve new problems of a similar nature.

{{% notice info %}}
https://www.bestwebframeworks.com/
{{% /notice %}}

*Source: Wikipedia*

{{% button href="/en/tecnologías/" %}}See some technologies{{% /button %}}

# What is the ip
- Within the network level we have the IP protocol
- Its main function is to locate the network where the target computer is



# What is the port
- At the transport level we have the UDP and TCP protocols
- Its main function is to locate the application to which the communication or data is going to be destined
- It is done through a number known as the port name

{{% notice tip %}}
***ifconfig*** (ipconfig in windows) to know the ip that I have assigned

***ping*** to send a greeting to a node in order to know if it is connected

***route*** to know my routes and the IP of my nearest router (my gateway that routes)

***tracert*** to know the trace of routes or ip's that a packet follows in a transmission

{{% /notice %}}

# Web server:
A web server is an application that runs on a machine as a service and keeps listening on a certain port


The most popular:
1. Apache HTTP Server
2. Microsoft IIS (Internet Information Services)
3. NGINX
4. Lighttpd
5. Sun Java System Web Server

# The curl command
- Command to make resource requests without using a browser.
- With this command we can establish communication with servers using the different protocols that it supports.
- Using the URL syntax we can transfer files between client and server.


**installation**
```
sudo apt-get install curl Command usage examples
```

View the **content** of a web page

```
 curl url_página_web
```

**Save** a web page in a file -o
```
curl -o filename web_page_url
```

**See the header** of a web
```
 curl --head url_pagina_web
```

If the web redirects us, we must specify it with -L
```
curl -L url_page_web So that we access the page that redirects us url_page_web
```

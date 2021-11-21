---
title: "Theme_1_2"
date: 2021-11-10T23:26:33+01:00
draft: false
weight: 2
---

# ARCHITECTURE ET TECHNOLOGIE WEB

## Qu'est-ce que l'architecture Web
L'**architecture web** est la hiérarchie des informations sur un ** site web**. Tout comme l'architecture traditionnelle travaille sur la structure d'une construction, l'architecture Web travaille sur la structure d'une page Web et les catégories qui la composent pour l'optimisation du positionnement dans les moteurs de recherche.

{{% button href="https://www.tokioschool.com/noticias/importancia-arquitectura-web/" %}}Más info{{% /button %}}

## Les composants d'une application web
### 1. Serveur Web
Un serveur web est un logiciel (programme) chargé de recevoir une requête sur le réseau ; Dans un réseau de type tcp/ip que l'on utilise sur internet, la requête est reçue en utilisant le protocole http et répondant à ladite requête.

Répondre à cette demande implique de vérifier les autorisations, d'exécuter un script, vous devrez peut-être faire des demandes d'informations à d'autres serveurs et générer un message de réponse en utilisant également le protocole http. Très souvent, la réponse est une page html.

### 2. Serveur de base de données
Un serveur de base de données est un logiciel (programme) chargé de gérer une base de données.

Compte tenu de l'importance de cette section, de la confidentialité et du goulot d'étranglement éventuel d'une application, le serveur de base de données se trouve généralement sur un serveur spécifiquement dédié à cet effet.

### 3. Le module d'exécution de code sur le serveur
Avant une requête du client, le serveur ne livre pas seulement une page web, avant cela il est très fréquent qu'il exécute du code dont le client n'aura jamais connaissance.

Pour cela, nous devons avoir un module installé sur le serveur pour exécuter ce code. Nous utiliserons PHP et plus tard JavaScript sur le serveur avec NodeJS. C'est l'aspect fondamental de ce module ou sujet


## L'architecture de l'application

Un serveur d'applications Web peut en fait être composé de plusieurs serveurs physiques.

> Chaque serveur peut être en charge d'exécuter une partie de l'application.


### Architecture à 3 couches
1. Couche d'accès aux données : qui devra se charger de stocker les informations de l'application dans une base de données et de les récupérer si nécessaire.
2. couche intermédiaire : où vous devez programmer les fonctionnalités de votre application.
3. couche client : c'est là que vous programmerez tout ce qui concerne l'interface utilisateur, c'est-à-dire la partie
visible de l'application avec laquelle l'utilisateur va interagir.


{{<youtube _yi3UVcuw_8>}}

*** Comment être un DÉVELOPPEUR BACKEND ? Route pour APPRENDRE LE DÉVELOPPEMENT WEB en 2021 ***
*Carlos Azaustre - Apprendre JavaScript*


## Les architectures de déploiement

### Architecture LAMPE / WAMP

1. **LAMPE**
LAMP est un acronyme pour Linux, Apache, MySQL et PHP. Chacun de ces composants est open source et libre d'utilisation, ce qui a contribué à leur popularité.

La pile de lampes est probablement la pile la plus couramment utilisée pour héberger des sites Web et des applications Web, en particulier des sites de petite et moyenne taille.

2. **WAMP**
La forme complète de WAMP est Windows, Apache, MySQL et PHP. Comme vous pouvez le deviner, le système d'exploitation souligné est Windows.

La seule différence entre WAMP et LAMP est le système d'exploitation derrière ces piles. Ainsi, tout ce qui est mentionné ci-dessus pour LAMP est également effectué par WAMP, mais uniquement sur le système Windows.

### MOYENNE Architecture
La pile moyenne est une pile JavaScript open source que vous pouvez utiliser pour créer des applications Web modernes, rapides, robustes et faciles à entretenir.

La pile du milieu est MongoDB, Express, Angular et Node.js.

MongoDB est la base de données NoSQL et Express est le framework Web exécuté sur le nœud, Angular est la plate-forme de développement côté client et Node.js est l'environnement d'exécution. Ensemble, ils peuvent être utilisés pour créer des applications Web étonnantes.


### Architecture Java EE
Java ™ Platform, Standard Edition (Java SE) et Java Platform, Enterprise Edition (Java EE) sont des plates-formes largement utilisées pour la programmation de serveurs d'applications dans le langage de programmation Java. Vous pouvez utiliser des sessions de règles pour appeler des applications Java SE ou Java EE.

{{% button href="https://www.ibm.com/docs/es/odm/8.5.1?topic=application-java-se-java-ee-applications" %}}
More info{{% /button %}}
{{% button href="https://www.oracle.com/es/java/technologies/java-ee-glance.html" %}}Official documentation{{% /button %}}


----

{{% button href="http://es.wikipedia.org/wiki/Aplicaci%C3%B3n_web" %}}
What is a web application on wikipedia{% /button %}}

{{% button href="http://es.wikipedia.org/wiki/Desarrollo_web" %}}What is a web development{{% /button %}}

{{% button href="http://www.hispamedios.com/articles/id34-url-y-uri" icon-position="right" %}}What is a URL vs difference with URI{{% /button %}}


---
title: "Theme_1_1"
date: 2021-11-10T23:26:37+01:00
draft: false

weight: 1
---

# CONCEPTS GÉNÉRAUX

## Définition du développement WEB
Terme qui définit le processus de création d'un site Web ou d'un intranet.

Pour ce faire, des technologies logicielles côté client et côté serveur sont utilisées, impliquant des processus de base de données avec l'utilisation d'un navigateur Web pour effectuer des tâches ou afficher des informations.

Pour développer une application ou un programme
1. Vous devez très bien comprendre ce que vous voulez faire
2. Vous devez le planifier
3. Vous devez faire cette planification et la tester

{{% notice note %}}
![Conexión TCP - negociación en tres pasos](/images/DesarrolloAplicaciones.jpeg)
{{% /notice %}}

## Application Web
En génie logiciel, une application Web est définie comme les outils que les utilisateurs peuvent utiliser en accédant à un serveur Web via Internet ou un intranet via un navigateur. Autrement dit, il s'agit d'un programme codé dans un langage interprétable par les navigateurs web dont l'exécution est confiée au navigateur.

*Source : Wikipédia*


## Framework
Un environnement de travail, ou cadre, est un ensemble standardisé de concepts, de pratiques et de critères pour aborder un type particulier de problème qui sert de référence, pour faire face et résoudre de nouveaux problèmes de nature similaire.

{{% notice info %}}
https://www.bestwebframeworks.com/
{{% /notice %}}

*Source: Wikipedia*

{{% button href="/fr/tecnologías/" %}}Voir quelques technologies{{% /button %}}

# Quelle est l'ip
- Au niveau du réseau, nous avons le protocole IP
- Sa fonction principale est de localiser le réseau où se trouve l'ordinateur cible

# Quel est le port
- Au niveau du transport nous avons les protocoles UDP et TCP
- Sa fonction principale est de localiser l'application à laquelle la communication ou les données vont être destinées
- Elle se fait via un numéro connu sous le nom de port

{{% notice tip %}}
***ifconfig*** (ipconfig dans windows) pour connaitre l'ip que j'ai assigné

***ping*** pour envoyer un message d'accueil à un nœud afin de savoir s'il est connecté

***route*** pour connaître mes routes et l'IP de mon routeur le plus proche (ma passerelle qui route)

***tracert*** pour connaître la trace des routes ou des IP qu'un paquet suit dans une transmission

{{% /notice %}}

# Serveur Web:
Un serveur Web est une application qui s'exécute sur une machine en tant que service et continue d'écouter sur un certain port


Le plus populaire:
1. Serveur HTTP Apache
2. Microsoft IIS (Internet Information Services)
3. NGINX
4. Lighttpd
5. Serveur Web Sun Java System

# La commande curl
- Commande pour faire des demandes de ressources sans utiliser de navigateur.
- Avec cette commande, nous pouvons établir une communication avec les serveurs en utilisant les différents protocoles qu'il prend en charge.
- En utilisant la syntaxe URL, nous pouvons transférer des fichiers entre le client et le serveur.


**installation**
```
sudo apt-get install curl Command usage examples
```

Afficher le **contenu** d'une page Web

```
 curl url_página_web
```

**Enregistrer** une page Web dans un fichier -o
```
curl -o filename web_page_url
```

**Voir l'en-tête** d'un site Web
```
 curl --head url_pagina_web
```

Si le web nous redirige, il faut le spécifier avec -L
```
curl -L url_page_web So that we access the page that redirects us url_page_web
```

---
title: "Theme_3"
date: 2021-11-10T23:26:33+01:00
draft: false
weight: 3
---

# LANGUE PHP

## Qu'est-ce que php (acronyme PHP : Hypertext Preprocessor)

C'est un langage open source.

Très populaire (pourrions-nous penser à une norme ?), Une large communauté de support sur internet qui contribue, collabore et résout les doutes.

Particulièrement adapté au développement Web (il peut être utilisé comme langage de bureau, mais ce n'est pas son objectif principal).

Actuellement, la version 7.4.3 est mise à jour le 23/09/2021, elle est considérée comme la version stable, et la version 8.1 est déjà en test, également publiée à la même date le 23/09/2021.


{{% button href="https://www.php.net/manual/es/migration70.php" %}} Php 7 features {{% /button %}}


{{% notice info %}}
![Proceso PHP](/images/ProcesoPHP.png)
{{% /notice %}}


{{% notice note %}}
Le document PHP, une fois correctement interprété sur le serveur, produit une page HTML qui sera envoyée au client.
{{% /notice %}}

{{% notice note %}}
Le code PHP est embarqué dans des documents HTML, cela permet d'introduire facilement du dynamisme dans un site web.
{{% /notice %}}

{{% notice note %}}
L'interpréteur PHP ignore le texte du fichier HTML
Jusqu'à ce qu'il trouve une balise de début du bloc de code PHP intégré.
{{% /notice %}}


## Comment écrire du PHP

```
<?php
instructions
?>
```

**En PHP, le bloc de début et de fin est spécifié avec les caractères**

```
    {   // début de bloc
    }   // fin de bloc
```

**Par contre, le début du programme est précisé avec les libellés**

```
    <? php // Script start tag
    ?> // End of script tag
```

## Fonctions de sortie

**echo**

```
<?php
    echo "premier argument", "deuxième argument", "troisième argument"
 ?>
```

**print**

This statement is the same in use and functionality as *echo*

Cette déclaration est la même en termes d'utilisation et de fonctionnalité que *echo*

Il a deux différences avec *echo* :
1. Vous ne pouvez accepter qu'un seul argument
2. Renvoie une valeur booléenne qui indique si l'instruction a réussi ou non


**printf**

C'est une fonction qui imprime avec le format (elle est utilisée de la même manière qu'en Java) Les spécificateurs de format sont
1.% s chaîne
2,% caractère c
3.% d (décimal),% u (décimal non signé)% o (octal),% x,% X (hexadécimal),% b (binaire)
4.% f,% F (Float avec décimales),% e,% E (Float avec notation scientifique,
Dans son utilisation on précisera la valeur avec le format que l'on souhaite afficher, dans la chaîne de caractères, puis, séparées par des virgules, les valeurs (ou variables) à afficher. La relation est respective et positionnelle.


## Déclarations
Un type de données est un ensemble de valeurs pour lesquelles une série d'opérations sont définies
1. Des variables
2. Des constantes
3. Des fonctions
4. Des cours
5. D'objets et de ressources (classes déjà créées ou incluses)




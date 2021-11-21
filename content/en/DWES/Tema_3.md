---
title: "Theme_3"
date: 2021-11-10T23:26:33+01:00
draft: false
weight: 3
---

# LANGUAGE PHP

## What is php (PHP acronym: Hypertext Preprocessor)

It is an open source language.

Very popular (could we think of a standard?), A large support community on the internet that contributes, collaborates and solves doubts.

Especially suitable for web development (It can be used as a desktop language, but it is not its main purpose).

Currently version 7.4.3 is updated on 9/23/2021, it is considered the stable version, and version 8.1 is already in testing, also published on the same date 9/23/2021.


{{% button href="https://www.php.net/manual/es/migration70.php" %}} Php 7 features {{% /button %}}


{{% notice info %}}
![Proceso PHP](/images/ProcesoPHP.png)
{{% /notice %}}


{{% notice note %}}
The PHP document, once correctly interpreted on the server, produces an HTML page that will be sent to the client.
{{% /notice %}}

{{% notice note %}}
The PHP code is embedded in HTML documents, This allows to easily introduce dynamism to a website.
{{% /notice %}}

{{% notice note %}}
The PHP interpreter ignores the text of the HTML file
Until it finds a start tag of the embedded PHP code block.
{{% /notice %}}

## How to write PHP

```
<?php
instructions
?>
```

**In PHP the start and end block is specified with the characters**

```
    {// start of block
    } // end of block
```
**On the other hand, the start of the program is specified with the labels**

```
    <? php // Script start tag
    ?> // End of script tag
```

## Output functions

**echo**

```
<?php
echo "first argument", "second argument", "third argument"
 ?>
```

**print**

This statement is the same in use and functionality as *echo*

It has two differences with *echo*:
1. You can only accept one argument
2. Returns a Boolean value that represents whether the statement was successful or not


**printf**

It is a function that prints with format (it is used the same as in java) The format specifiers are
1.% s string
2.% c character
3.% d (decimal),% u (unsigned decimal)% o (octal),% x,% X (hexadecimal),% b (binary)
4.% f,% F (Float with decimals),% e,% E (Float with science notation,
In its use we will specify the value with the format we want to display, in the character string, and then, separated by commas, the values ​​(or variables) to display. The relationship is respective and positional.

## Declerations
A data type is a set of values ​​for which a series of operations are defined
1. Of variables
2. Of constants
3. Of functions
4. Of classes
5. Of objects and resources (classes already created or included)




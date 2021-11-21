---
title: "Tema_3"
date: 2021-11-10T23:26:33+01:00
draft: false
weight: 3
---

# LENGUAJE PHP

## Qué es php (acrónimo de PHP: Hypertext Preprocessor)

Es un lenguaje de código abierto.

Muy popular (Podríamos pensar en un estándar?), una gran comunidad de soporte en internet que aporta, colabora y soluciona dudas.

Especialmente adecuado para desarrollo web (Se puede usar como lenguaje de escritorio, pero no es su principal propósito).

Actualmente está la versión 7.4.3 actualizada el 23/9/2021 es considerada la versión estable , estando ya en testing la versión 8.1, también publicada en la misma fecha 23/9/2021.


{{% button href="https://www.php.net/manual/es/migration70.php" %}} Caracterísitcas de php 7 {{% /button %}}


{{% notice info %}}
![Proceso PHP](/images/ProcesoPHP.png)
{{% /notice %}}


{{% notice note %}}
El documento PHP, una vez interpretado correctamente en el servidor, produce una página HTML que será enviada al cliente.
{{% /notice %}}

{{% notice note %}}
El código PHP está embebido en documentos HTML, Esto permite introducir dinamismo fácilmente a un sitio web.
{{% /notice %}}

{{% notice note %}}
El intérprete PHP ignora el texto del fichero HTML
Hasta que encuentra una etiqueta de inicio del bloque de código PHP embebido.
{{% /notice %}}


## Cómo escribir PHP

```
<?php
instrucciones
?>
```

**En PHP el bloque inicio y fin está especificado con los caracteres**

```
  { //inicio de bloque
  } //fin de bloque
```
**Por otro lado el inicio del programa se especifica con las etiquetas**

```
  <?php //Etiqueta de inicio de script
  ?>    //Etiqueta de fin de script
```

## Funciones de salida

**echo**

```
<?php
 echo “primer argumento”, “segundo argumento”, “tercer argumento”
 ?>
```

**print**

Esta sentencia es igual en uso y funcionalidad que *echo*

Tiene dos diferencias con *echo*:
1. Sólo puede aceptar un argumento
2. Devuelve un valor booleano que representa si la sentencia ha tenido exito o no


**printf**

Es un función que imprime con formato (se usa igual que en java) Los especificadores de formato son
1. %s string
2. %c carácter
3. %d (decimal), %u(decimal sin signo) %o(octal), %x, %X (hexadecimal), %b(binario)
4. %f, %F (Float con decimales), %e, %E (Float con notación ciétífica,
En su uso especificaremos el valor con el formato que queramos visualizar, en la cadena de carácteres, y después, separado por comas, los valores (o variables)a visualizar. La relación es respectiva y posicionaL

## Decleraciones
Un tipo de dato es un conjunto de valores para los cuales hay definidos una serie de operaciones
1. De variables
2. De constantes
3. De funciones
4. De clases
5. De objetos y recursos (clases ya creadas o incluidas)


## Constantes
Las constantes se declaran una vez No se pueden modificar, solo usar

Se definen con la función **define()**

O con la palabra reservada **const**

```
<?php
define("IVA",0.21);
const IVA_BASE = 0.06;
....
$total=$base*(1+IVA);
$total=$base_2*(1+IVA_BASE);
 ?>

```

**Constantes predefinidas**

Como en otros lenguajes, existen una serie de constantes predefinidas

Nos las ofrece el entorno y dependerán de él para su valor {{% button href="http://php.net/manual/es/reserved.constants.php" %}}Ver{{% /button %}}

 

PHP Ofrece un gran número de constantes predefinidas 

En php hay 8 constantes que su valor puede cambiar dependiendo del entorno donde se ejecutan

## Funciones de php

Para declarar funciones usamos la siguiente sintaxis

```php
function nombre_funcion([tipo]$var1[=valor_por_defecto], ...):[tipo_retorno]{ [instrucciones]
[return [expresion]]
}
```

## Estructuras de control 

### Selección if ###
Sentencia que evlúa una expresión booleana y ejecuta o no en función de que dicha expresión sea true o false

```php
  if (condicion){
        Sentencia_1;
        Sentencia_2;
    }
```

```php
if (expresion){
        sentencias;
    }elseif (expresion){
        sentencias;
    }else {
        sentencias;
}
```

**Operadores ternario**

Es una forma más compacta de un if else con una única instrucción.
```php
    Expresión? SentenciaOKExpresion : SentenciaNoOkExpresion
```

### Seleccion switch ###

Este es un selector múltiple.


```php
    switch ($valor){
        case:   "valor1":
                acciones
        break;
        case:   "valor2":
                acciones
        break;
        case:   "valor3":
                acciones
        break;
        default:
                acciones si no hay coincidencia anterior
    }
```

```php
    $nota = rand (0,10);
        switch ($nota){
            case ($nota>=0 and $nota<=3):
                echo "<h1>Nota $nota es deficiente</h1>";
                break;
            case 4:
                echo "<h1>Nota $nota es insuficiente</h1>";
                break;
            case 5:
                echo "<h1>Nota $nota es suficiente</h1>";
                break;
            case 6:
                echo "<h1>Nota $nota es bien</h1>";
                break;
            case ($nota>6 and $nota<9):
                echo "<h1>Nota $nota es notable</h1>";
                break;
            case ($nota>=9):
                echo "<h1>Nota $nota es sobresaliente</h1>";
                break;
    }
?>
```

**Iteración while**

```php
    <?php
        $i = 0;
        while ($i < 100) {
            $suma+=$i;
            $i++;
            echo "iteracción  {$i}ª Suma $suma<br />";
        }
    ?>
```

**Iteración do-while**
```php
    <?php
        $i = 0;
        do  {
            $suma+=$i;
            $i++;
            echo "iteracción  {$i}ª Suma $suma<br />";
        }while ($i < 100)
    ?>
```

**Iteración for**

```php
    <?php
        for ($a=0;$a<10 ;$a++){
            echo "$a*$a=".$a*$a."<br>";
        }
    ?>
```

## Operadores y expresiones 
Son símbolos que realizan acciones sobre operandos y dan como resultado un valor.

Tenemos diferentes tipos de operadores en función del tipo de operandos y del resultado


### Operadores aritméticos (+,-,*,/,%,**, ++, --). ###

Retorna un valor numérico.

El ++, -- son valores de autoincremeto y autodecremento, pueder ser pre o post.

El el caso pre, primero incrementa y luego toma el valor.

El el caso post, primero toma el valor y luego incrementa.

### Operadores comparación (==,<,>,>=,<=,<>,!=,===,!==) ###

> == operador de comparación igual que (mismo valor)

>=== operador de comparación exactamente igual que (mismo valor y tipo)

```php
    $num=1;
    if ($num==true)
        echo '$num es igual a true<br>';
    if ($num===true){
        echo "esto nunca se ejecutará";
    }else
        echo '$num no es exactamente igual a true';
```

### Operadores de concatenacón( .) concatena cadena de caracteres. ###

```php
    $nombre="Maria";
    $apellido = " de la Oh";
    
    $nombreCompleto = $nombre.$apellido;
    echo "el valor de nombre completo es $nombreCompleto ---<br>";
    
    $nombreCompleto = $nombre+$apellido;
    echo "el valor de nombre completo es $nombreCompleto --<br>";
```

### Operadores de asignación (= , =>) ###

```php
    <?php
        $b=1;
        for ($a=0;$a<10;$a++){
            $b*=10;
            echo 'valor de $b ='.$b.'<br>';
        }
    ?>
```

### operadores de ejecución (``) ###

```php
    <?php
        $Discos = `df`;
        echo "<pre>$Discos</pre>";
    ?>
```

### operadores lógicos (and,&&, or, ||, xor !) ###

```php
    <?php

        // --------------------
        // foo() nunca será llamado ya que los operadores están en cortocircuito

        $a = (false && foo());
        $b = (true  || foo());
        $c = (false and foo());
        $d = (true  or  foo());

        // --------------------
        // "||" tiene una precedencia mayor que "or"

        // El resultado de la expresión (false || true) es asignado a $e
        // Actúa como: ($e = (false || true))
        $e = false || true;

        // La constante false es asignada a $f antes de que suceda la operación "or"
        // Actúa como: (($f = false) or true)
        $f = false or true;

        var_dump($e, $f);

        // --------------------
        // "&&" tiene una precedencia mayor que "and"

        // El resultado de la expresión (true && false) es asignado a $g
        // Actúa como: ($g = (true && false))
        $g = true && false;

        // La constante true es asignada a $h antes de que suceda la operación "and"
        // Actúa como: (($h = true) and false)
        $h = true and false;

        var_dump($g, $h);
    ?>
```
## Escribir PHP con directivas de inclusión ##

```php
    include('ruta/nobrefichero');
    require('ruta/nobrefichero');
    include_once('ruta/nombrefichero');
    require_once('ruta/nombrefichero');
```

Ambas incluyen el contenido de un fichero php en esa posición.

{{% notice info %}}
Con include si no se encuentra se continúa ejecutando en esa posición.
{{% /notice %}}

{{% notice info %}}
Con require si no está el fichero se detiene en ese punto la ejecución del script.
{{% /notice %}}


## Funciones propias de PHP  

**time()**

Obtiene una marca de tiempo

```
   time(): int
```

**date()**

La función convierte un timestamp en una fecha como cadena de caracteres con el formato que le especifiquemos

```
   data("formato_fecha", "timestamp")
```

**strtotime**

Convierte un string en fecha

```
  strtotime("fecha_como_string", "timestamp")
```

**strftime()**

Da formato a una fecha según el idioma establecido
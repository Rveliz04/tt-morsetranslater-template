<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

Tiene 4 entradas, aparte del reloj, la primera es "START" que inicia la captura de la información, la segunda es "STOP" dejamos de caoturar datos quedandonos con los que hayamos metido (máximo 4), 3ro está "DOT" que representa un punto en código morse y por último "LINE" que representa una línea. La salida de este sistema son 6: 1ro bit que define si la combinación que entro es correcta o no, 2do y 3ro son los 2 bits que cuentan cuantos datos entraron y posterior del 4to al 7mo la combinación de entrada donde "DOT" es 0 y "LINE" es 1.

## How to test

Ve variando las entradas de acuerdo al código morse.

## External hardware

Demux, Display 7 segmentos

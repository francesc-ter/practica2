# Practica 2. Entorno de desarrollo.

## 1.¿Qué es compilar un programa? ¿Qué es interpretar un programa?.
**Compilar:**

Un compilador es un programa que transforma el código fuente de un programa a su equivalente en otro lenguaje de programación de más bajo nivel (una excepción sería el caso de los transpiladores, recordad la diferencia entre compilador y transpilador)

Un intérprete es un programa que ejecuta directamente las instrucciones escritas en un lenguaje de programación dado
 
## 2.Ventajas de los lenguajes compilados y de los lenguajes interpretados.

+-------------------------------+--------------------------------+
|  Lenguajes compilados         | Lenguajes interpretados        |
+-------------------------------+--------------------------------+
| 1. Preparados para ejecutarse | 1. Son multiplataforma         |
|                               |                                |
| 2. A menudo más rápidos       | 2. Son más sencillos de probar |
|                               |                                |
| 3. El código fuente es        | 3. Los errores se detectan     |
|         inaccesible           |          fácilmente            |
+-------------------------------+--------------------------------+


## 3.Indica dos lenguajes compilados y dos interpretados.

+-------------------------------+--------------------------------+
|  Lenguajes compilados         | Lenguajes interpretados        |
+-------------------------------+--------------------------------+
|         C, C++ y Go           |    JavaScript, Python y Ruby   |
+-------------------------------+--------------------------------+
 
## 4.¿el bytecode que genera Java puede decirse que es código objeto? Explica la respuesta.

El código binario de Java para esta máquina virtual recibe el nombre de Bytecode. Este código binario de Java es transformado a código binario de la máquina real por la máquina virtua a través de su compilador JIT (Just in Time) en el momento de la ejecución. Por tanto, si tenemos un programa Java ya compilado, podrá ser ejecutado en una máquina virtual, con independencia de la máquina real (Hardware + SO) en la que está instalada esa máquina virtual.

Se relega entonces el problema no a disponer de una versión compilada de nuestro programa para cada plataforma destino (como sucede en C o Pascal por ejemplo), sino a tener una sola versión compilada de nuestro programa Java en ByteCode y disponer de una máquina virtual para cada plataforma (principio WORA: Write Once Run Anywhere -escribe una vez, ejecuta en cualquier lugar-). Como podrás suponer las máquina virtuales son creadas por terceros, asi que en realidad nos están quitando trabajo (tedioso) que realizar: no sólo compilar para cada plataforma, sino asegurarnos que nuestro código respeta las peculiaridades de la plataforma destino. Además podemos beneficiarnos de mejoras en las máquinas virtuales fácilmente.

## 5.Pon un ejemplo de lenguaje de los tres tipos:

* Bajo nivel.
* Medio nivel
* Alto nivel.



## 6.  Indica el paradigma de programación que siguen los siguientes lenguajes:

* C
* C++
* SQL
* Java
* Javascript
* Lisp
* Prolog

## 7.Indica qué criterios se pueden seguir a la hora de elegir un lenguaje de programación para el desarrollo software.

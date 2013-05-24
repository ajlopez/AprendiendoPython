# Introducci�n

Python es un lenguaje de uso general, creado por Guido van Rossum a finales de los ochenta. 
Se ejecuta en varias plataformas, lo que nos permite armar programas que ejecutan en varios sistemas operativos. Es un lenguaje din�mico e interpretado, y tiene una amplia colecci�n
de librer�as adicionales, que podemos instalar a pedido. Vamos a explorar en estas p�ginas c�mo
es el lenguaje, c�mo se usa, sus caracter�sticas. Pero �qu� vamos a encontrar al programar en Python? Es temprano
para darnos cuenta de todo lo que es como lenguaje y tecnolog�a, pero avanzo algunas caracter�sticas:

- Es f�cil de programar
- Es flexible
- Es poderoso
- Es extensible
- Posee un activo ecosistema de librer�as y frameworks
- Podemos programar para consola, escritorio o web
- Objetos y clases
- Todo es un objeto

>> Nota: El nombre Python est� inspirado por el grupo de c�micos ingleses "Monty Python", incluso se encuentran
referencias al grupo en c�digo de ejemplo. Es habitual encontrar variables como `egg` y `spam` en
lugar de las cl�sicas `foo` y `bar`, en referencia a uno de los "sketchs" del grupo.s 

## Python como lenguaje de scripting

Muchas veces, se usa Python como lenguaje de scripting. �Para qu� se usa un lenguaje de scripting? Algunos usos:

- **Herramientas de shell** lanzadas desde la l�nea de comandos o desde otros programas. Al ser Python f�cil
de escribir y ejecutar, puede servir para reemplazar otros lenguajes de ejecuci�n de comandos de l�nea.

- **Lenguaje de control** Python puede acceder a otras librer�as, escritas en C. Eso lo habilita para ser
un lenguaje de control, que las invoca de forma f�cil, sin necesidad de programar directamente en lenguaje C.

Y es f�cil de usar (sintaxis y sem�ntica simple, interpretaci�n inmediata). Pero no confundirse: que sea f�cil
no significa que sea limitado. En Python podemos escribir el sistema m�s complejo que podemos crear en otros
lenguajes.

Los lenguajes compilados son, en general, de ejecuci�n m�s r�pida. Como suelen ser tipados, el compilador
puede resolver referencias en tiempo de compilaci�n, sin diferirlas a tiempo de ejecuci�n. Ese diferimiento
a tiempo de ejecuci�n es lo que hace que los lenguajes interpretados sean (de nuevo, en general) m�s lentos
que sus pares compilados. Si bien Python es un lenguaje interpretado, tienen algunos paso de compilaci�n interna. El c�digo Python, como en
Java y .NET, se traduce a un c�digo de una m�quina virtual, en lo que se llaman `bytecodes`. Se generan archivos
`.pyc` o `.pyo` (bytecode optimizado) para ejecutarlos varias veces, si no cambia el c�digo fuente original.

## Instalaci�n

(A completar)

En estas p�ginas, voy a usar Python 3.x, aclarando cuando sea necesario la diferencia con Python 2.x.

## Python interactivo

Una vez instalado Python, agregamos su directorio de instalaci�n a nuestro PATH. En mi m�quina Windows, lo
instal� en `c:\Python32` (vean que se agrega ese directorio directamente al PATH, no tiene un subdirectorio `bin`).
Ahora tenemos disponibles desde la l�nea de comando el programa `python`. Por ejemplo

- Si estamos en **Mac OS X** abrimos `Terminal` e ingresamos `python` y enter
- Si estamos en **Linux** abrimos un shell e ingresamos `python` y enter
- Si estamos en **Windows** abrimos una caja de DOS e ingresamos `python` y enter

En una de mis instalaciones aparece algo como

```
Python 3.2.2 (default, Sep  4 2011, 09:51:08) [MSC v.1500 32 bit (Intel)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

Podemos ingresar comandos desde ese prompt `>>>`. Como:

```
>>> print(1+2)
3
```

Vean que obtenemos el resultado de ejecutar la funci�n ya definida `print`. Pueden salir del
modo interactivo ingresando:

```
>>> exit()
```

(A completar)

## Ejecutando Archivos Python

(A completar)

## Probando Python en L�nea

(A completar)

## Fuente consultadas:

(A completar)

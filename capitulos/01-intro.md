# Introducción

Python es un lenguaje de uso general, creado por Guido van Rossum a finales de los ochenta. 
Se ejecuta en varias plataformas, lo que nos permite armar programas que ejecutan en varios sistemas operativos. Es un lenguaje dinámico e interpretado, y tiene una amplia colección
de librerías adicionales, que podemos instalar a pedido. Vamos a explorar en estas páginas cómo
es el lenguaje, cómo se usa, sus características. Pero ¿qué vamos a encontrar al programar en Python? Es temprano
para darnos cuenta de todo lo que es como lenguaje y tecnología, pero avanzo algunas características:

- Es fácil de programar
- Es flexible
- Es poderoso
- Es extensible
- Posee un activo ecosistema de librerías y frameworks
- Podemos programar para consola, escritorio o web
- Objetos y clases
- Todo es un objeto

>> Nota: El nombre Python está inspirado por el grupo de cómicos ingleses "Monty Python", incluso se encuentran
referencias al grupo en código de ejemplo. Es habitual encontrar variables como `egg` y `spam` en
lugar de las clásicas `foo` y `bar`, en referencia a uno de los "sketchs" del grupo.s 

## Python como lenguaje de scripting

Muchas veces, se usa Python como lenguaje de scripting. ¿Para qué se usa un lenguaje de scripting? Algunos usos:

- **Herramientas de shell** lanzadas desde la línea de comandos o desde otros programas. Al ser Python fácil
de escribir y ejecutar, puede servir para reemplazar otros lenguajes de ejecución de comandos de línea.

- **Lenguaje de control** Python puede acceder a otras librerías, escritas en C. Eso lo habilita para ser
un lenguaje de control, que las invoca de forma fácil, sin necesidad de programar directamente en lenguaje C.

Y es fácil de usar (sintaxis y semántica simple, interpretación inmediata). Pero no confundirse: que sea fácil
no significa que sea limitado. En Python podemos escribir el sistema más complejo que podemos crear en otros
lenguajes.

Los lenguajes compilados son, en general, de ejecución más rápida. Como suelen ser tipados, el compilador
puede resolver referencias en tiempo de compilación, sin diferirlas a tiempo de ejecución. Ese diferimiento
a tiempo de ejecución es lo que hace que los lenguajes interpretados sean (de nuevo, en general) más lentos
que sus pares compilados. Si bien Python es un lenguaje interpretado, tienen algunos paso de compilación interna. El código Python, como en
Java y .NET, se traduce a un código de una máquina virtual, en lo que se llaman `bytecodes`. Se generan archivos
`.pyc` o `.pyo` (bytecode optimizado) para ejecutarlos varias veces, si no cambia el código fuente original.

## Instalación

(A completar)

En estas páginas, voy a usar Python 3.x, aclarando cuando sea necesario la diferencia con Python 2.x.

## Python interactivo

Una vez instalado Python, agregamos su directorio de instalación a nuestro PATH. En mi máquina Windows, lo
instalé en `c:\Python32` (vean que se agrega ese directorio directamente al PATH, no tiene un subdirectorio `bin`).
Ahora tenemos disponibles desde la línea de comando el programa `python`. Por ejemplo

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

Vean que obtenemos el resultado de ejecutar la función ya definida `print`. Pueden salir del
modo interactivo ingresando:

```
>>> exit()
```

(A completar)

## Ejecutando Archivos Python

(A completar)

## Probando Python en Línea

(A completar)

## El Zen de Python

Es el PEP20:

Long time Pythoneer Tim Peters succinctly channels the BDFL's
guiding principles for Python's design into 20 aphorisms, only 19
of which have been written down.


- Beautiful is better than ugly.
- Explicit is better than implicit.
- Simple is better than complex.
- Complex is better than complicated.
- Flat is better than nested.
- Sparse is better than dense.
- Readability counts.
- Special cases aren't special enough to break the rules.
- Although practicality beats purity.
- Errors should never pass silently.
- Unless explicitly silenced.
- In the face of ambiguity, refuse the temptation to guess.
- There should be one-- and preferably only one --obvious way to do it.
- Although that way may not be obvious at first unless you're Dutch.
- Now is better than never.
- Although never is often better than *right* now.
- If the implementation is hard to explain, it's a bad idea.
- If the implementation is easy to explain, it may be a good idea.
- Namespaces are one honking great idea -- let's do more of those!

Traducción que encontré en Python Argentina:

- Bello es mejor que feo
- Explícito es mejor que implícito
- Simple es mejor que complejo
- Complejo es mejor que complicado
- Plano es mejor que anidado
- Disperso es mejor que denso
- La legibilidad importa
- Los casos especiales no son tan especiales como para quebrantar las reglas
- Aunque lo práctico gana a la pureza
- Los errores nunca deberían dejarse pasar silenciosamente
- A menos que hayan sido silenciados explícitamente
- Frente a la ambigüedad, rechaza la tentación de adivinar
- Debería haber una -y preferiblemente sólo una- manera obvia de hacerlo
- Aunque esa manera puede no ser obvia al principio a menos que usted sea holandés
- Ahora es mejor que nunca
- Aunque nunca es a veces mejor que ya mismo
- Si la implementación es difícil de explicar, es una mala idea
- Si la implementación es fácil de explicar, puede que sea una buena idea
- Los espacios de nombres (namespaces) son una gran idea ¡Hagamos más de esas cosas!

## Fuente consultadas:

- [The Zen of Python](http://www.python.org/dev/peps/pep-0020/)
- [Python para Todos](http://mundogeek.net/tutorial-python/)

(A completar)

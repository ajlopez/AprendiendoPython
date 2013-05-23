# Introducción

Python es un lenguaje de uso general. Se ejecuta en varias plataformas, lo que nos permite armar programas
que ejecutan en varios sistemas operativos. Es un lenguaje dinámico e interpretado, y tiene una amplia colección
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

## Python como lenguaje de scripting

Muchas veces, se usa Python como lenguaje de scripting. ¿Para qué se usa un lenguaje de scripting? Algunos usos:

- **Herramientas de shell** lanzadas desde la línea de comandos o desde otros programas. Al ser Python fácil
de escribir y ejecutar, puede servir para reemplazar otros lenguajes de ejecución de comandos de línea.

- **Lenguaje de control** Python puede acceder a otras librerías, escritas en C. Eso lo habilita para ser
un lenguaje de control, que las invoca de forma fácil, sin necesidad de programar directamente en lenguaje C.

Y es fácil de usar (sintaxis y semántica simple, interpretación inmediata). Pero no confundirse: que sea fácil
no significa que sea limitado. En Python podemos escribir el sistema más complejo que podemos crear en otros
lenguajes.

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

## Fuente consultadas:

(A completar)

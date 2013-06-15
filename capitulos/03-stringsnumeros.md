# Strings y N�meros

# Strings

Sin necesidar de usar `print`, podemos ingresar en el int�rprete interactivo:
```
>>> "Hola mundo"
Hola mundo
```

Como vimos en el primer programa, podemos usar comillas simples:
```
>>> 'Hola mundo'
Hola mundo
```

Hasta podemos poner dos strings uno seguiendo al otro:
```
>>> 'Hola ' 'mundo'
Hola mundo
>>> "Hola " "mundo"
Hola mundo
```

Esto sirve para strings literales. No nos sirve para variables:
```
>>> x = 'Hola '
>>> y = 'mundo'
>>> x y
  File "<stdin>", line 1
    x y
      ^
SyntaxError: invalid syntax
```

Pero podemos concatenar valores string con el operador de suma:
```
>>> x + y
Hola mundo
```

(A completar)

## N�meros y Expresiones

Podemos usar el int�rprete interactivo como una calculadora
```
>>> 1 + 2
3
```

Esa fue f�cil. Veamos:
```
>>> 12345 + 67890
80235
```

Bueno, tambi�n fue f�cil. Si ingresamos:
```
>>> 1/2
0.5
```

Si no les da como resultado 0.5, y les da 0, entonces est�n en un Python versi�n anterior a la 3. Pueden 
lanzar nuevamente el int�rprete Python pero agregando `-Qnew`:
```
python -Qnew
```

Otra alternativa: ingresar ya estando en el int�rprete:
```
from __future__ import division
```
El `__future__` es un m�dulo que contiene instrucciones nuevas. Pueden incluir esa l�nea directamente en suys programas.

Si quieren division entera, entonces usar la doble barra:
```
>>> 1//2
0
```

Como en otros lenguajes, tenemos el operador de m�dulo (quedarse con el resto de la divisi�n):
```
>>> 1 % 2
1
>>> 7 % 5
2
>>> -9 % 7
5
```

### Enteros Grandes

(A completar)

## Comentarios

Veamos un tema adicional, colado en este cap�tulo. En Python, el caracter `#` (numeral) tiene un significado
especial. Cuando se lo encuentra, todo texto hasta el fin de la l�nea es un comentario que se ignora. Ejemplos:

```
# Ingrese su nombre
nombre = input('�Cu�l es su nombre?')

print(1+2) # imprime 3
```

En lo posible, tratemos que el c�digo del programa hable por s� mismo, sin necesidad de poner comentarios de l�nea.



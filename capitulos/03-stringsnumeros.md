# Strings y Números

# Strings

Sin necesidar de usar `print`, podemos ingresar en el intérprete interactivo:
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

## Números y Expresiones

Podemos usar el intérprete interactivo como una calculadora
```
>>> 1 + 2
3
```

Esa fue fácil. Veamos:
```
>>> 12345 + 67890
80235
```

Bueno, también fue fácil. Si ingresamos:
```
>>> 1/2
0.5
```

Si no les da como resultado 0.5, y les da 0, entonces están en un Python versión anterior a la 3. Pueden 
lanzar nuevamente el intérprete Python pero agregando `-Qnew`:
```
python -Qnew
```

Otra alternativa: ingresar ya estando en el intérprete:
```
from __future__ import division
```
El `__future__` es un módulo que contiene instrucciones nuevas. Pueden incluir esa línea directamente en suys programas.

Si quieren division entera, entonces usar la doble barra:
```
>>> 1//2
0
```

Como en otros lenguajes, tenemos el operador de módulo (quedarse con el resto de la división):
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

Veamos un tema adicional, colado en este capítulo. En Python, el caracter `#` (numeral) tiene un significado
especial. Cuando se lo encuentra, todo texto hasta el fin de la línea es un comentario que se ignora. Ejemplos:

```
# Ingrese su nombre
nombre = input('¿Cuál es su nombre?')

print(1+2) # imprime 3
```

En lo posible, tratemos que el código del programa hable por sí mismo, sin necesidad de poner comentarios de línea.



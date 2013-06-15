# Strings y Números

# Strings

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





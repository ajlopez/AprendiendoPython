# Strings y N�meros

# Strings

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





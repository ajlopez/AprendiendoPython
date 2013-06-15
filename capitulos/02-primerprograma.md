# Primer Programa

No podemos estudiar un lenguaje sin escribir el clásico de clásicos, un simple `Hola mundo`.

## Imprimiendo el mensaje

En el intérprete interactivo podemos ingresar:
```
>>> print("Hola, mundo")
Hola, mundo
```

No hay mayores sorpresas. Tal vez si venimos de Java o .NET, nos asombre un poco más:
```
>>> print('Hola, mundo')
Hola, mundo
```
Sí, el mensaje puede ir encerrado entre comillas simples.

## Programa en archivo

Podemos crear con un editor de texto el archivo `hola.py` conteniendo:
```python
print('Hola, mundo')
```

¿Cómo lo ejecutamos? Desde la línea de comando, ingresando:
```
python hola.py
```

### En UNIX/Linux

Si estamos en UNIX/Linux, podemos agregar una línea con `shebang`:
```python
#!/usr/bin/python
print('Hola, mundo')
```

Esa nueva línea indica qué programa invocar para ejecutar nuestro archivo. Deberíamos marcarlo como ejecutable:
```
chmod +x hola.py
```

Y ahora podemos ejecutarlo simplemente ingresando:
```
./hola.py
```

Puede que en algunas distribuciones tengamos que cambiar el valor `#!/usr/bin/python`. Se puede usar
el truco de poner:
```python
#!/usr/bin/env python
print('Hola, mundo')
```
El `/user/bin/env` interroga al sistema operativo sobre el lugar donde está `python` y lo ejecuta.

### En Windows

En Windows, si tenemos instaladas las distribuciones de Python comunes, con hacer doble click sobre el archivo éste
se ejecuta automáticamente. El instalador asoció la extensión `.py` con el ejecutor `python`. El programa tiene un 
problema: se ejecuta en una ventana, pero luego al terminar, la ventana se cierra automáticamente. Podemos agregar
una línea más al programa, pidiendo entrada del usuario:
```python
print('Hola, mundo')
input()
```

>> Nota: En Python 2.x podríamos poner el `print` sin usar los paréntesis. Y en lugar de `input` deberíamos
usar `raw_input`. Esas cosas que tiene Python ;-)


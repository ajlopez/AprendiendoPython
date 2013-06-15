# Primer Programa

No podemos estudiar un lenguaje sin escribir el cl�sico de cl�sicos, un simple `Hola mundo`.

## Imprimiendo el mensaje

En el int�rprete interactivo podemos ingresar:
```
>>> print("Hola, mundo")
Hola, mundo
```

No hay mayores sorpresas. Tal vez si venimos de Java o .NET, nos asombre un poco m�s:
```
>>> print('Hola, mundo')
Hola, mundo
```
S�, el mensaje puede ir encerrado entre comillas simples.

## Programa en archivo

Podemos crear con un editor de texto el archivo `hola.py` conteniendo:
```python
print('Hola, mundo')
```

�C�mo lo ejecutamos? Desde la l�nea de comando, ingresando:
```
python hola.py
```

### En UNIX/Linux

Si estamos en UNIX/Linux, podemos agregar una l�nea con `shebang`:
```python
#!/usr/bin/python
print('Hola, mundo')
```

Esa nueva l�nea indica qu� programa invocar para ejecutar nuestro archivo. Deber�amos marcarlo como ejecutable:
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
El `/user/bin/env` interroga al sistema operativo sobre el lugar donde est� `python` y lo ejecuta.

### En Windows

En Windows, si tenemos instaladas las distribuciones de Python comunes, con hacer doble click sobre el archivo �ste
se ejecuta autom�ticamente. El instalador asoci� la extensi�n `.py` con el ejecutor `python`. El programa tiene un 
problema: se ejecuta en una ventana, pero luego al terminar, la ventana se cierra autom�ticamente. Podemos agregar
una l�nea m�s al programa, pidiendo entrada del usuario:
```python
print('Hola, mundo')
input()
```

>> Nota: En Python 2.x podr�amos poner el `print` sin usar los par�ntesis. Y en lugar de `input` deber�amos
usar `raw_input`. Esas cosas que tiene Python ;-)


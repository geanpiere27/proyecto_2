### OPERADORES DE FLUJO

Se utilizan para controlar la ejecucion de instrucciones en funncion de ciertas condiciones.Los pricipales operadoress de flujo en **python** son:

1.- ***if*** : se uiutiliza para ejecutar un bloque de codigo si una condicion es verdadera.
```PYTHON
if condicion:
    # bloque de codigo
```
2.- ***elif*** : se utiliza para evaluar multiples condiciones despues de un `if`. Solo se ejecuta si las condiciones anteriores son falsas y la condiciones anteriores son falsas y la condicion actual es verdadera. 
```PYTHON
if condicion1:
    # bloque de codigo
elif condicion2:
    # bloque de codigo
```
3.- ***else*** : se utiliza para ejecutar un bloque de codigo si ninguna de las condiciones anteriores es verdadera.
```PYTHON
if condicion:
    # bloque de codigo
else:
    # bloque de codigo
```
4.- ***for*** : se utiliza para iterar sobre una secuencia (como una lista,tupla,cadena,etc.) y ejecutar un bloque de codigo para cada elemento.
```PYTHON
for elemento in secuencia:
    # bloque de codigo
```
5.- ***while*** : se utiliza para repetir un bloque de codigo mientras una condicion sea verdadera.
```PYTHON
 while condicion:
 # bloque de codigo
```
6.- ***break*** : se utiliza para salir de un bucle (`for` o `while`) antes de que se complete normalmente.
```PYTHON
for elemento in secuencia:
    if condicion:
        break
```
7.- ***continue*** : se utiliza para saltar el resto del cuerpo de un bucle y continua con la siguiente iteracion.
```PYTHON
for elemento in secuencia:
    if condicion:
        continue
```

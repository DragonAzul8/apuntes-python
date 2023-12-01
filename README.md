# Apuntes-python
Mis apuntes de python

## Print

La función `print()` se encarga de imprimir por pantalla.

Por ejemplo:

```python
print("Hola que tal")
```
Podemos concatenar cadenas de caracteres.
```python
print("Hola", "que tal")
print("Hola" + "Anibal")
```
## Input
La función `input()` nos permite introducir información a través del teclado.
Podemos utilizarlo sin indixar nada entre paréntesis:

```python
print("Introduce tu nombre")
input()
```
Si escribimos dentro de los paréntesis, podemos mostrar información antes de escribir:

```python
input("Introduce tu nombre")
```

## Variables
Las variables nos permiten guardar en ellas información. Hay muchos tipos de variables:

- **Enteros**: 5
- **Cadenas de texto**: "Anibal"
- **Booleanos**: True, False

Las variables tienen un nombre que les identifica. Por ejemplo:

```python
nombre = Anibal
print(nombre)
```
El signo igual (=) asigna una valor a la variable.

Un ejemplo completo:

```python
nombre = input("Dime tu nombre: ")
print(nombre)
```
Si queremos covertir el resultado el resultado de un número utilizamos la función `int()`. Por ejemplo:

```python
edad = int(input("Dime tu edad: "))
print(edad+5)
```

## Condicionales
Para dexcidir ejecutar o no un bloque de código en función de si se cumple o no una condición utilizamos `if`.

```python
edad = 18
if edad >= 18
    print("Mayor de edad")
```
También podemos usra `else`para cuando la condición no se cumpla.

```python
edad = 18
if edad >= 18:
    print("Mayor de edad")
else:
    print("Menor de edad")
```

## Bucles 
Los bucles nos permiten repetir un bloque de código más de una vez.

Un ejemplo es el `for`.

```python
for numero in (0,5):
    print (numero)
```
También podemos recorrer una lista:

```python
alumnos = ["pepe", "manolo", "juan"]
for alumno in alumnos:
    print (alumno)
```

## Funciones 
Las funciones nos permiten guardar un bloque de código con un nombre para llamarlas cuando queramos. Las funciones terminan en paréntesis:
`sumar()`, `jugar()`.

Ejemplo:

```python
def calcular():
```
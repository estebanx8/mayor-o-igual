**Programa para encontrar la persona mayor**

_Este programa permite encontrar la persona mayor entre dos personas._

**Instrucciones:**

1. Ejecuta el programa.
2. Ingresa el nombre de la primera persona.
3. Ingresa la edad de la primera persona.
4. Ingresa el nombre de la segunda persona.
5. Ingresa la edad de la segunda persona.
Resultado:

El programa mostrará un mensaje indicando la persona mayor.

Ejemplo:
```
digite su nombre=Ana
  digite su edad=25
  digite su nombre=Juan
  digite su edad=20
 

> la persona mayor es Ana
```
Explicación del código:

* Las líneas `p1=input("digite su nombre=")` y `p2=input("digite su nombre=")` solicitan el nombre de las dos personas.
+ Las líneas `edad1=int(input("digite su edad="))` y `edad2=int(input("digite su edad="))` solicitan la edad de las dos personas.
- La línea `if (edad1 > edad2):` verifica si la edad de la primera persona es mayor que la edad de la segunda persona.
* Si la edad de la primera persona es mayor, la línea `print("la persona mayor es ", p1)` muestra un mensaje indicando que la persona mayor es la primera persona.
- Si la edad de la segunda persona es mayor o igual que la edad de la primera persona, la línea `print("la persona mayor es ", p2)` muestra un mensaje indicando que la persona mayor es la segunda persona.

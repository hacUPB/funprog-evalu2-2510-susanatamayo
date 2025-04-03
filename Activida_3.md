# Algoritmos 🔶

## Pseudocódigo ⏬
Es una representación en lenguaje natural de los pasos que conforman un algoritmo. Se utiliza para describir de manera estructurada y comprensible las acciones necesarias para resolver un problema antes de implementarlo en un lenguaje de programación.
``` 
Inicio
Leer base, altura
Calcular área = (base * altura) / 2
Mostrar área
Fin
``` 
## Preguntas y repuestas ❓

 ### Parte 1 : Identificar algoritmos. 
 
 #### a) Una página web. 

 ❌ No representa un algoritmo, ya que es una estructura informativa y representativa, pero este no necesariamente sigue un conjunto de pasos secuenciales cuyo objetivo sea especifico.

 #### b) Una receta para hacer un pastel, donde se indican ingredientes y pasos a seguir.

✅ Si representa un algoritmo, la receta genera un secuencia de pasos definidos cuyo objetivo es obtener un resultado final. 


#### c) "Piensa en un número y multiplícalo por otro".

❌ No representa un algoritmo, aunque este sugiere una operación matematica este no especifica instrucciones claras de como se llega a un resualtado.

#### d) Un manual de instrucciones para armar un mueble, con pasos detallados y un orden claro.

✅ Si representa un algoritmo, ya que este proporciona un secuencia ordenada de pasos a seguir con el fin de lograr un objetivo. 

#### e) Una lista de compras organizada en orden alfabético

❌ No representa un algoritmo, la lista es una variedad de datos organizados, pero este no define un procceso o una guia de pasos para alcanzar el objetivo especifico. 

### Parte 2 : Variables y Constantes

#### a) El valor de la gravedad en la Tierra, 9.8 m/s².

🔵 Representa una constante, la aceleración de la gravedad en la tierra tiene un valor fijo, el cual no cambia en condiciones normales. 

#### b) La edad de una persona calculada en base al año actual y su año de nacimiento.

🟡 Representa una variable, La edad de una persona varia con el tiempo, lo cual la hace directamente proporcional al tiempo. 

#### c) La cantidad de dinero en una cuenta bancaria. 

🟣 Representa una variable, El saldo de una çuenta bancaria cambia con cada deposito o retiro. 

#### d) La velocidad de la luz en el vacío, 299,792,458 m/s. 

🟠 Representa una constante,el valor de la velocidad de la luz en el vacio es una valor no cambiante. 

#### e) El radio de un círculo. 

🟢 Representa una variable,el radio de un círculo puede cambiar dependiendo del círculo en cuentión, por lo cual no es un valor fijo. 

### Parte 3 : Características de los algoritmos

#### a)  Para elegir la ruta más corta entre varias ciudades, el algoritmo examina rutas candidatas, deteniéndose cuando los cambios en la distancia parecen lo suficientemente pequeños.

❌ No cumple con las caracteristicas de un algoritmo, aunque describe el proceo para encontrar la ruta más corta, la condición es inexacta lo cual no permite cumplir con la caracteristica principal de un algoritmo. 

``` 
Un algoritmo debe ser preciso y tener un criterio de finalización bien definido.

``` 
#### b) Suma los números ingresados y muestra el resultado.
✅ Sí cumple con las características de un algoritmo,define un procedimiento claro (sumar números), tiene entrada (los números ingresados), salida (la suma) y es finito (termina cuando se obtiene el resultado).

#### c) Un conjunto de pasos para calcular el área de un rectángulo dado su base y altura.

✅  Sí cumple con las características de un algoritmo.Tiene entrada (base y altura), un procedimiento definido (multiplicar base por altura), una salida (el área) y es finito.

#### d) El algoritmo cuenta el número de votos obtenidos por cada uno de los candidatos de una elección para presidente. Empieza solicitando el nombre del candidato y finaliza cuando se ingresa el valor -1.

✅ Sí cumple con las características de un algoritmo.Tiene entrada (los votos y nombres de los candidatos), un proceso definido (contar votos), salida (cantidad de votos por candidato) y es finito (termina cuando se ingresa -1).

### Parte 4 : Comprensión de Herramientas

#### a) El pseudocódigo utiliza símbolos estándar para representar las operaciones lógicas.

❌ FALSO, El pseudocódigo es una descripción textual estructurada de un algoritmo que no sigue un estándar de símbolos como los diagramas de flujo. Se basa en palabras clave y una sintaxis similar a la de los lenguajes de programación, pero no utiliza símbolos gráficos específicos.

#### b) Los diagramas de flujo son una representación gráfica de un algoritmo.

✅ CIERTO, Los diagramas de flujo utilizan símbolos gráficos estándar (óvalos, rectángulos, rombos, etc.) para representar visualmente la secuencia de pasos de un algoritmo.

#### c) El pseudocódigo debe estar escrito en un lenguaje de programación específico.

❌ FALSO, El pseudocódigo no está ligado a un lenguaje de programación específico. Su propósito es describir algoritmos de manera clara e independiente de cualquier lenguaje, permitiendo su fácil traducción a distintos lenguajes de programación.


#### d) Un diagrama de flujo siempre debe tener un inicio y un fin claramente definidos. 

✅ CIERTO, Un diagrama de flujo debe ser finito y representar un proceso con un punto de inicio y un punto de finalización bien definidos. Esto garantiza que el algoritmo sea claro y ejecutable.

### Parte 5 : Estructuras de control.

📌Las estructuras de control son herramientas fundamentales en la programación y en la toma de decisiones en la vida cotidiana. Permiten dirigir el flujo de ejecución de un algoritmo o proceso, dependiendo de condiciones o repeticiones. Se dividen en: 

🔴*Estructuras condicionales (decisión):* Ejecutan diferentes acciones según se cumpla o no una condición (Ejemplo:  ```if-else ```).

🔵Estructuras de repetición (bucles): Permiten ejecutar un bloque de código varias veces (Ejemplo: ```for, while```).


#### 🧠Ejemplos 

1) Decidir si llevar un paraguas antes de salir de casa.
 ```
 Inicio
    Si está lloviendo o hay probabilidad de lluvia Entonces
        Tomar paraguas
    Sino
        No tomar paraguas
    Fin Si
Fin
```
2) Decidir si un estudiante aprueba o reprueba un curso con base en su promedio.

 ```
Inicio
    Escribir "Ingrese la calificación del examen 1: "
    Leer calificacion1
    Escribir "Ingrese la calificación del examen 2: "
    Leer calificacion2
    Escribir "Ingrese la calificación del examen 3: "
    Leer calificacion3

    promedio = (calificacion1 + calificacion2 + calificacion3) / 3

    Si promedio >= 6 Entonces
        Escribir "Felicidades, aprobaste el curso!"
    Sino
        Escribir "Lo siento, debes repetir el curso."
    Fin Si
Fin
 
 ```




















































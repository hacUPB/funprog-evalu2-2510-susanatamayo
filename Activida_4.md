 # Algoritmo a código fuente🔄️

 1)  ### Introducción 
 ❓ ¿Por qué crees que el pseudocódigo es útil antes de escribir un programa en C?

💭 El pseudocódigo es útil antes de programar en C porque ayuda a estructurar la lógica del algoritmo sin preocuparse por la sintaxis. Facilita la detección de errores, optimiza el desarrollo, mejora la comunicación en equipos y ahorra tiempo al escribir código. Además, es ideal para el aprendizaje y la depuración antes de la implementación final

2) ### Estructura básica del paseudocódigo 

🧠 Toma un pseudocódigo de un ejercicio anterior o escribe tu propio pseudocódigo, similar al mostrado en el ejemplo de arriba.
```
Inicio
    Escribir "Ingrese las coordenadas del primer punto (x1, y1):"
    Leer x1, y1
    Escribir "Ingrese las coordenadas del segundo punto (x2, y2):"
    Leer x2, y2
    distancia = sqrt((x2 - x1)^2 + (y2 - y1)^2)
    Escribir "La distancia entre los dos puntos es:", distancia
Fin
```

3) ### Traduciendo el pseudocódigo a c 
❓¿Por qué es importante declarar el tipo de variable (int, float, etc.) antes de usarla en C?

💭 Declarar el tipo de variable en C es clave para gestionar la memoria, evitar errores, mejorar la precisión y optimizar el rendimiento. Ayuda al compilador a reservar espacio, detectar problemas y generar código eficiente. 

4) ### Ejemplos adicionales de pseudocódigo y su traducción 

🧠 Escribe tu propio pseudocódigo para calcular el promedio de una lista de calificaciones y tradúcelo a C.

📌 Pseudocodigo
```
Inicio
    Escribir "Ingrese la cantidad de calificaciones:"
    Leer n
    
    suma ← 0
    
    Para i ← 1 hasta n Hacer
        Escribir "Ingrese la calificación ", i, ":"
        Leer calificacion
        suma ← suma + calificacion
    FinPara
    
    promedio ← suma / n
    
    Escribir "El promedio es: ", promedio
Fin
```
📌 Traducción a C

```
#include <stdio.h>

int main() {
    int n, i;
    float calificacion, suma = 0, promedio;

    printf("Ingrese la cantidad de calificaciones: ");
    scanf("%d", &n);

    for (i = 1; i <= n; i++) {
        printf("Ingrese la calificación %d: ", i);
        scanf("%f", &calificacion);
        suma += calificacion;
    }

    promedio = suma / n;
    printf("El promedio es: %.2f\n", promedio);

    return 0;
}
```

5) ### Buenas prácticas 
🧠 ¿Por qué es importante comentar el código, aunque sea breve y conciso?

💭 Comentar el código mejora la comprensión, facilita la depuración, optimiza la colaboración y ahorra tiempo en mantenimiento. Es clave para un desarrollo claro y eficiente. 

6) ### Reto final

🚀  Toma el pseudocódigo de los 5 primeros ejercicios del Reto y realiza la traducción a C:

### a)
📌Pseudocodigo 
```
Inicio
    Escribir "Ingrese las coordenadas del primer punto (x1, y1):"
    Leer x1, y1
    Escribir "Ingrese las coordenadas del segundo punto (x2, y2):"
    Leer x2, y2
    distancia = sqrt((x2 - x1)^2 + (y2 - y1)^2)
    Escribir "La distancia entre los dos puntos es:", distancia
Fin
```
 📌 Traducción a C
```
 #include <stdio.h>
#include <math.h>

int main() {
    double x1, y1, x2, y2, distancia;

    // Solicitar las coordenadas del primer punto
    printf("Ingrese las coordenadas del primer punto (x1, y1): ");
    scanf("%lf %lf", &x1, &y1);

    // Solicitar las coordenadas del segundo punto
    printf("Ingrese las coordenadas del segundo punto (x2, y2): ");
    scanf("%lf %lf", &x2, &y2);

    // Calcular la distancia usando la fórmula de la distancia euclidiana
    distancia = sqrt(pow(x2 - x1, 2) + pow(y2 - y1, 2));

    // Mostrar el resultado
    printf("La distancia entre los dos puntos es: %.2f\n", distancia);

    return 0;
}
```
### b)

📌 Pseudocodigo 
```
Inicio
    Escribir "Ingrese la cantidad de tela en metros:"
    Leer metros
    pulgadas = metros / 0.0254
    Escribir "La cantidad de tela en pulgadas es:", pulgadas
Fin
```
📌 Traducción a C
```
#include <stdio.h>

int main() {
    double metros, pulgadas;

    // Solicitar la cantidad de tela en metros
    printf("Ingrese la cantidad de tela en metros: ");
    scanf("%lf", &metros);

    // Convertir metros a pulgadas (1 pulgada = 0.0254 metros)
    pulgadas = metros / 0.0254;

    // Mostrar el resultado
    printf("La cantidad de tela en pulgadas es: %.2f\n", pulgadas);

    return 0;
}
```
### c)

📌 Psedocodigo
```
INICIO
    Escribir "Ingrese el valor del cateto A:"
    Leer A
    Escribir "Ingrese el valor del cateto B:"
    Leer B
    C = Raíz Cuadrada(A^2 + B^2)
    Escribir "La hipotenusa es:", C
FIN
```
📌 Traducción a C
```
#include <stdio.h>
#include <math.h>

int main() {
    double A, B, C;

    // Solicitar los valores de los catetos
    printf("Ingrese el valor del cateto A: ");
    scanf("%lf", &A);

    printf("Ingrese el valor del cateto B: ");
    scanf("%lf", &B);

    // Calcular la hipotenusa usando el Teorema de Pitágoras
    C = sqrt(A * A + B * B);

    // Mostrar el resultado
    printf("La hipotenusa es: %.2f\n", C);

    return 0;
}
```
### d)

📌 Pseudocodigo 
```
INICIO
    // Solicitar la fecha de nacimiento
    ESCRIBIR "Ingrese el día de nacimiento:"
    LEER dia_nacimiento
    ESCRIBIR "Ingrese el mes de nacimiento:"
    LEER mes_nacimiento
    ESCRIBIR "Ingrese el año de nacimiento:"
    LEER año_nacimiento


    // Obtener la fecha actual
    OBTENER fecha_actual
    dia_actual ← DIA(fecha_actual)
    mes_actual ← MES(fecha_actual)
    año_actual ← AÑO(fecha_actual)


    // Calcular la edad
    edad ← año_actual - año_nac


    // Verificar si ya cumplió años este año
    SI (mes_actual < mes_nac) O (mes_actual = mes_nac Y dia_actual < dia_nac) ENTONCES
        edad = edad - 1  // Aún no ha cumplido años
        ESCRIBIR "Aún no ha cumplido años este año."
    SINO SI (mes_actual = mes_nac Y dia_actual = dia_nac) ENTONCES
        ESCRIBIR "Feliz Cumpleaños!"
    SINO
        ESCRIBIR "Ya cumplió años este año."
    FIN SI


    // Mostrar la edad
    ESCRIBIR "Edad actual: ", edad
FIN
```
📌 Traducción a C
```
#include <stdio.h>
#include <time.h>

int main() {
    int dia_nac, mes_nac, año_nac;
    int dia_actual, mes_actual, año_actual, edad;

    // Solicitar la fecha de nacimiento
    printf("Ingrese el día de nacimiento: ");
    scanf("%d", &dia_nac);
    
    printf("Ingrese el mes de nacimiento: ");
    scanf("%d", &mes_nac);
    
    printf("Ingrese el año de nacimiento: ");
    scanf("%d", &año_nac);

    // Obtener la fecha actual
    time_t t = time(NULL);
    struct tm tm = *localtime(&t);
    
    dia_actual = tm.tm_mday;
    mes_actual = tm.tm_mon + 1;  // tm_mon es base 0, por eso se suma 1
    año_actual = tm.tm_year + 1900;  // tm_year cuenta desde 1900

    // Calcular la edad
    edad = año_actual - año_nac;

    // Verificar si aún no ha cumplido años en el año actual
    if (mes_actual < mes_nac || (mes_actual == mes_nac && dia_actual < dia_nac)) {
        edad--;  // Aún no ha cumplido años este año
        printf("Aún no ha cumplido años este año.\n");
    } else if (mes_actual == mes_nac && dia_actual == dia_nac) {
        printf("¡Feliz Cumpleaños!\n");
    } else {
        printf("Ya cumplió años este año.\n");
    }

    // Mostrar la edad actual
    printf("Edad actual: %d años\n", edad);

    return 0;
}
```
### e)

📌 Pseudocodigo
```
INICIO
    DEFINIR horas_trabajadas, pago_por_hora, sueldo COMO NUMÉRICO
    ESCRIBIR "Ingrese las horas trabajadas en la semana:"
    LEER horas_trabajadas
    ESCRIBIR "Ingrese el pago por hora:"
    LEER pago_por_hora

    SI horas_trabajadas > 50 ENTONCES
        ESCRIBIR "Error: No se permite trabajar más de 50 horas."
    SINO
        sueldo ← 0
        SI horas_trabajadas <= 40 ENTONCES
            sueldo ← horas_trabajadas * pago_por_hora
        SINO SI horas_trabajadas <= 45 ENTONCES
            sueldo ← (40 * pago_por_hora) + ((horas_trabajadas - 40) * (2 * pago_por_hora))
        SINO SI horas_trabajadas <= 50 ENTONCES
            sueldo ← (40 * pago_por_hora) + (5 * 2 * pago_por_hora) + ((horas_trabajadas - 45) * (3 * pago_por_hora))
        FIN SI
        ESCRIBIR "El sueldo semanal es: ", sueldo
    FIN SI
FIN
```
📌 Traducción a C
```
#include <stdio.h>

int main() {
    float horas_trabajadas, pago_por_hora, sueldo = 0;

    // Solicitar las horas trabajadas y el pago por hora
    printf("Ingrese las horas trabajadas en la semana: ");
    scanf("%f", &horas_trabajadas);

    printf("Ingrese el pago por hora: ");
    scanf("%f", &pago_por_hora);

    // Validar que no se trabajen más de 50 horas
    if (horas_trabajadas > 50) {
        printf("Error: No se permite trabajar más de 50 horas.\n");
    } else {
        // Calcular el sueldo según las horas trabajadas
        if (horas_trabajadas <= 40) {
            sueldo = horas_trabajadas * pago_por_hora;
        } else if (horas_trabajadas <= 45) {
            sueldo = (40 * pago_por_hora) + ((horas_trabajadas - 40) * (2 * pago_por_hora));
        } else { // 45 < horas_trabajadas <= 50
            sueldo = (40 * pago_por_hora) + (5 * 2 * pago_por_hora) + ((horas_trabajadas - 45) * (3 * pago_por_hora));
        }

        // Mostrar el sueldo calculado
        printf("El sueldo semanal es: %.2f\n", sueldo);
    }

    return 0;
}
```

❓Después de este tutorial, ¿qué puntos crees que deberías reforzar para sentirte más seguro al traducir pseudocódigo a C?

💭 Considero que la forma de senrime mas segura a la hora de realizar traducciones seria mediante la practica constante. 

# *Representación de datos digitales.* 🛢️

## Ejercicio 1. 

### 1.  Representación de los datos en una computadora. 🖥️

En una computadora, ls representación de datos se realiza mediante el sistema binarario, constituido por valores 0 y 1, los números , las imagenes o cualquier tipo de información en convertida en una secuencia de BIT, los cuales son procesados por la computadora. 

#### - *Representación de números.* 🔢

Para la representación númerica se usan diferentes codificaciónes, como el sistema binario puro para enteros. 

#### - *Representación de letras y caracteres.* 🔡

Para la representación de letras y caracteres, son representados con estándares como ASCII o Unicode, los cuales asignan un valor númerico a cada símbolo. 

#### - *Representación de imágenes.* 🖼️

Las imagenes se reprsentan como matrices de píxeles, donde cada píxel posee un valor numérico el cual indica su color, usando modelos como RGB.

### 2. ¿Cuántos estados diferentes pueden ser representados por N variables binarias?0️⃣1️⃣

Toda variable binaria puede adquir una de dos valore, 0 o 1. si se tiene N variables binarios, cada una puede estar en dos estados independientes del las demás.

Por lo tanto, el número total de estados diferentes que pueden ser representados por 
𝑁
 variables binarias es:


$2^{N}$

 
Este resultado proviene de la regla de la multiplicación: dado que cada variable tiene 2 opciones y hay 

𝑁
 variables, el total de combinaciones posibles es 

2
×
2
×
.
.
.
×
2
2×2×...×2 (
𝑁
N veces), lo que da 
2
𝑁
2 
N
 .

### 3. Unidades de almacenamiento de datos que se utilizan en computación. ⚙️

|Unidad. | Abreviatura. | Equivalencia en Bytes (Base 10) |Equivalencia en Bytes (Base 2)
|--------|--------------|---------------------------------|-----------------------------|
| Byte | B | 1 Byte | 1 Byte 
| KiloByte | KB|$10^{3}$ = 1.000 Bytes|$2^{10}$ = 1.024 Bytes
| MegaByte | MB | $10^{6}$ = 1.000.000 Bytes | $2^{20}$ = 1.048.576 Bytes
| GigaByte | GB|  $10^{9}$ = 1,000,000,000 Bytes | $2^{30}$ = 1,073,741,824 Bytes
| TeraByte | TB | $10^{12}$ = 1,000,000,000,000 Bytes | $2^{40}$ = 1,099,511,627,776 Bytes
| PetaByte | PB | $10^{15}$ = 1,000,000,000,000,000 Bytes | $2^{50}$ = 1,125,899,906,842,624 Bytes
| ExaByte | EB | $10^{18}$ = 1,000,000,000,000,000,000 Bytes | $2^{60}$ =  1,152,921,504,606,846,976 Byte
| ZettaByte | ZB | $10^{21}$ = 1,000,000,000,000,000,000,000 Bytes | $2^{70}$ = 1,180,591,620,717,411,303,424 Bytes
| YottaByte | YB | $10^{24}$ = 1,000,000,000,000,000,000,000,000 Bytes| $2^{80}$ = 1,208,925,819,614,629,174,706,176 Bytes

### 4. George Bool. 💡

El trabajo de George Boole es fundamental en el ámbito de la computación y el almacenamiento de datos ya que estableció la logica Booleana, lo cual genera la base del funcionamiento de los sistemas digitales y computacionales modernos. 

## Ejercicio 2. 🔢
Convertir los números binarios a números decimales. 

❓¿Por qué crees que en las computadoras se usa una representación binaria en lugar de otro tipo de representación?

💡Las computadoras usan representación binaria porque es más fiable, eficiente y fácil de implementar en hardware. Los transistores funcionan naturalmente con dos estados (0 y 1), lo que reduce errores y facilita el procesamiento. Además, el sistema binario es menos vulnerable al ruido y se integra perfectamente con la lógica booleana. Aunque existen otras opciones, el binario sigue siendo la mejor solución por su simplicidad y eficiencia. 


## Ejercicio 3. 🔎
🌟 Python
- Los tipos de datos integrados son: dict, list, set, frozenset y tuple. 
- La clase str se utiliza para contener cadenas de caracteres Unicode. 
- Las clases bytes y bytearray se utilizan para contener datos binarios. 
- El tipo entero (int) representa números enteros sin decimales. 
- El tipo flotante (float) comprende números con decimales. 
- El tipo largo (long) se utiliza para enteros de longitud ilimitada. 

🌟 C
- Se usa int para representar números enteros en 32 bits. También existen short (16 bits), long (64 bits) y unsigned para valores sin signo.
- Se utilizan float (32 bits) y double (64 bits) para manejar números con punto decimal.
- Se representa con char, que almacena un solo carácter en formato ASCII (8 bits).
- Aunque no existía en la versión original de C, se puede usar _Bool o la biblioteca stdbool.h para definir true y false.
- No hay un tipo específico para cadenas; se manejan como arrays de caracteres (char[]).

🌟 Java 
- Los tipos primitivos son: int, short, long, double, float, boolean, byte, char.
- byte es un entero de 8 bits.
- short es un entero de 16 bits.
- int es un entero de 32 bits.
- long es un entero de 64 bits.
- float es un número en coma flotante de precisión simple de 32 bits.

🌟 C++
- Se usa int para números enteros de 32 bits. También existen short (16 bits), long (64 bits) y long long (mayor precisión). Se pueden declarar como unsigned para valores sin signo.
- Se manejan con float (32 bits) y double (64 bits), con double proporcionando mayor precisión. También existe long double para cálculos más precisos.
- Se usa char para almacenar un solo carácter ASCII (8 bits) y wchar_t para caracteres anchos (Unicode).
- Se usa bool, que solo puede tomar true o false.
- Se pueden manejar como arrays de caracteres (char[]), pero C++ también introduce std::string, que permite manipular texto de forma más sencilla.


## Ejercicio 4. 👩🏻‍💻

| Datos| Python | C | Java | C ++ |
|--------------|--------------| ---- | ---| -
| Void |  | X|X| X|
| Char| |X |X|X|
| Int | X |X|X|X |
| Float | X| X| X | 
| Str | X|
| Bool | X||X|X|
| Long | | |X|X
| Complex |X|
| Double | | X |X|X|
| Caracteristicas generales|Tipado dinámico, sin límites específicos, tipos más flexibles.|Tipado estático, eficiente, bajo nivel.|Tipado estático, más seguro, tipos definidos con compatibilidad Unicode| Similar a C, pero con más capacidad orientada a objetos.

## Ejercicio 5. 🧠













# Guía de Ejercicios Algoritmos y Programacion

**Autores:** Prof. Manuel Gomez, Stefani Perez

# Contenido

- [Guía de Ejercicios Algoritmos y Programacion](#guía-de-ejercicios-algoritmos-y-programacion)
- [Contenido](#contenido)
- [Semana 1](#semana-1)
  - [Terminal](#terminal)
  - [Instalaciones](#instalaciones)
  - [Variables Operadores y Tipos de Datos](#variables-operadores-y-tipos-de-datos)
- [Semana 2](#semana-2)
	- [Estructuras Secuenciales (If-else)](#estructuras-secuenciales-if-else)
	- [Estructuras Repetitivas (While/For Loops)](#estructuras-repetitivas-while/for-loops)
	- [Listas](#listas)
- [Semana 3](#semana-3)
- [Semana 4](#semana-4)
- [Semana 5](#semana-5)
- [Semana 6](#semana-6)
- [Semana 7](#semana-7)
- [Semana 8](#semana-8)
- [Semana 9](#semana-9)
- [Semana 10](#semana-10)
- [Semana 11](#semana-11)
- [Semana 12](#semana-12)


# Semana 1

## Terminal

### Ejercicio 0

En el directorio de tu preferencia (Ej. Documents) crea un nuevo directorio (carpeta) llamada AlgoritmosYProgramacion, y ahí debes crear otro directorio llamado GuiaDeEjercicios. En este último directorio, crea 1 archivo llamado ejercicio_0.py. Alli debes crear un programa que imprima por pantalla:

**Output**
```shell
Hola mundo!
```

## Instalaciones

### Ejercicio 0.5

Lee las guias de instalacion que están en **Notion** para poder configurar tu computadora y que este lista para lo que se dara en el curso.

[Guías de Instalación](https://www.notion.so/algoritmos-y-programacion-unimet/Preparadur-as-Algoritmos-y-Programaci-n-ebc3b9f0602242afa1818402ac091597#08f5e74dfa4345548a35eca9d310d874)

## Variables Operadores y Tipos de Datos

### Ejercicio 1

Escribir un programa que le pida al usuario la siguiente informacion: *nombre*, *apellido*, *edad*, y *nro de trimestre actual* (cada dato debe estar en una variable distinta). Luego, muestre por pantalla:

**Output**
```shell
¡Hola soy (nombre) (apellido)! Tengo (edad) y este es mi trimestre nro (nro de trimestre actual)
```
Cada dato debe ser el que haya sido introducido por el usuario.

### Ejercicio 2

Escribir un programa que le pida al usuario el *número de horas trabajadas*, y el *pago por hora*. Posteriormente, debe mostrar por pantalla la paga que le correspondria si el usuario fuera **100%** efectivo, pero como sabemos que la mitad del tiempo estuvo jugando *League of Legends*, tambien debe indicar cual seria su pago real si solo se le paga un **50%**.

**Output**
```shell
Numero de horas trabajadas: (número de horas trabajadas)
Pago por hora: (pago por hora)
¡Hola trabajador! Tu pago deberia ser $(pago ideal), pero como no cumpliste con nuestras expectativas te daremos $(pago real).
```

### Ejercicio 3

Escribir un programa que pida un numero positivo **n** al usuario, y después muestre por pantalla la *suma de todos los enteros desde 1 hasta **n***. Tenga en cuenta que los numeros decimales deben ser *de alguna forma* transformados a enteros.

**Output**
```shell
Numero: (n)
¡Hola usuario! La suma de todos los enteros desde 1 hasta (n) da como resultado (resultado).
```

### Ejercicio 4

Escribir un programa que pida al usuario su **peso** (en kg) y **estatura** (en metros), y que luego calcule el **índice de masa corporal** del usuario y que muestre por pantalla:

**Output**
```shell
Peso: (peso)kg
Estatura: (estatura)m
Tu índice de masa corporal es (índice de masa corporal).
```
El índice de masa corporal calculado debe ser redondeado a *dos decimales*.

### Ejercicio 5

Escribir un programa que le pida al usuario *dos números* y que imprima por pantalla:

**Output**
```shell
Numero 1: (numero 1)
Numero 2: (numero 2)
(numero1) entre (numero2) da un cociente (cociente) y un resto (resto).
```

### Ejercicio 6

Realizar un programa que le pida al usuario su **nombre** y **año de nacimiento**. Calcule cuanto deberia cumplir el usuario este año. Luego, debe indicar por pantalla:

**Output**
```shell
(nombre) debe cumplir (edad) años este año.
```

**BONUS**
Indique el año actual mediante una libreria de python.

### Ejercicio 7

Cree un programa que pida un **numero a** y un **numero b**. Luego, encuentre el valor de c que satisfaga el **teorema de pitágoras**.

**Output**
```shell
Lado a: (numero a)cm
Lado b: (numero b)cm
De acuerdo al teorema de pitagoras, el lado c mide (resultado)cm.
```
[Teorema de Pitagoras](https://www.todamateria.com/teorema-de-pitagoras/)



# Semana 2

## Estructuras Secuenciales If-else

### Ejercicio 8 

Realizar un programa donde se reciba un **número flotante** por teclado e imprima un mensaje diciendo si el número es *par o impar* y evaluar si es *positivo o negativo*.

**Output**
```shell
El número: X es par/impar y positivo/negativo
```
Donde **X** es el número ingresado por teclado.

### Ejercicio 9

Una famosa cadena de cines en Venezuela te contrató para hacerles un programa de descuento basado en la *edad del cliente*, para ello tendrás que recibir por teclado la *edad* y *nombre* del cliente y verificar los siguientes casos:

    Si su edad es menor o igual a 4 años el precio de su entrada es gratis.
    Si su edad es menor o igual a 18 años el precio de su entrada es de $1.50.
    Si su edad es mayor o igual a los 60 años su entrada tendrá un valor de $1.00.
    La entrada para un adulto promedio es de $2.00.

Deberás imprimir un mensaje dependiendo de la edad del cliente para saber el precio de su entrada.

**Output**
```shell
El cliente: {nombre} tiene: {edad} años y su entrada de cine cuesta: ${precio_entrada}.
```

### Ejercicio 10

Te contrataron para realizar un programa que calcule el **premio** de un juego.

Los premios estan basados en puntos:

|  Puntos |     Premio    |
|:-------:|:-------------:|
| 1-50    | No hay premio |
| 51-150  | Bronce        |
| 151-180 | Plata         |
| 181-200 | Oro           |

Todos los límites inferiores y superiores son *inclusivos*, y los puntos solo pueden tomar *valores enteros positivos hasta 200*.

En su declaración *if*, asigne la variable resultado a una cadena que contenga el mensaje *apropiado* según el valor de los puntos.

Si ganaron un premio, el mensaje debería decir:

**Output**
```shell
 "¡Felicitaciones, ganaste la medalla de {nombre del premio} por haber tenido {puntos} pts!"
```
Si no hay premio, el mensaje debe decir:

**Output**
```
 "Ay, lo sentimos pero no hay premios para {puntos} pts."
```

### Ejercicio 11

Desarrolla en Python el juego de *Piedra, Papel y Tijeras* en donde pediras por teclado la opción del jugador 1, luego la opción del jugador 2, y posteriormente dará el resultado diciendo quien gano.

**Output**
```shell
 "¡Felicitaciones jugador 1/2 ganaste esta partida!"
```

### Ejercicio 12

Realice un programa que pida dos numeros al usuario y que permita realizar las siguientes operaciones matemáticas:

- Suma.
- Resta.
- Multiplicación.
- División.
- Potencia.
- Módulo.
- Comparar (mayor o menor que).
- Valor absoluto (de ambos numeros).

Debe preguntarle al usuario qué operación desea realizar. Finalmente, debe imprimir el resultado.

**Output**
```shell
Numero 1: (numero 1)
Numero 2: (numero 2)
Operacion seleccionada: (operacion)
El resultado obtenido es: (resultado).
```

## Estructuras Repetitivas While/For Loops

### Ejercicio 13

Escribir un programa que pida al usuario una *palabra* y la muestre por pantalla **10 veces**.

### Ejercicio 14

Escribir un programa que pida al usuario un **número entero positivo** y muestre por pantalla *todos los números impares desde 1 hasta ese número separados por comas*.

### Ejercicio 15

Escribir un programa que pida al usuario un número entero positivo y muestre por pantalla la cuenta atrás desde ese número hasta cero separados por comas.

**Nota**: La cuenta atras debe ser impresa en una sola linea.

### Ejercicio 16

Escribir un programa que pida al usuario un **número entero positivo** y muestre por pantalla un triángulo rectángulo (como el que se indica a continuacion), que tenga de **altura** el número ingresado.

```shell
*
**
***
****
*****
```

### Ejercicio 17

Escribir un programa que pida al usuario un **número entero** y que muestre por pantalla si es un **número primo** o no.

**Nota:** Si el numero dado es negativo debe transformarlo en positivo.

### Ejercicio 18

Las palabras o números **palíndromos** son aquellas que *se leen igual de izquierda a derecha*. Por ejemplo: 101 es un número palíndromo, y 236 no lo es. Ana es una palabra palíndroma y pan no lo es.

Sabiendo esto, diseñe un programa que determine si un número o palabra ingresada por el usuario, es palíndroma o no.

### Ejercicio 19

Escribir un programa que le pida al usuario una **frase** y una **letra**. Luego, muestre por pantalla el *número de veces que aparece la letra en la frase*.

## Listas

### Ejercicio 20

Escribir un programa que almacene las **asignaturas** de un curso (por ejemplo Matemáticas, Física, Química, Historia y Lengua) en una **lista** y que la muestre por pantalla.

### Ejercicio 21

Realice un programa que dada una **lista** de nombres, pida al usuario introducir un **nombre** y *verificar si este está o no en la lista*.

### Ejercicio 22

Escribe un programa que mediante un **For Loop** pueda iterar sobre la lista *'estudiantes'* y que cree una lista *'usernames'* para cada nombre de la lista de *'estudiantes'*. Cada **username** creado debe cumplir lo siguiente:

- Colocar todo el nombre en **minúscula**.
- Reemplaza los espacios con guion bajo **"_"**.

**Lista de Estudiantes**
```python
[	"Elijah Evans", 
 	"Charissa Mueller", 
 	"Kirby Park",
 	"Jescie Hill",
 	"Leroy Herring",
 	"Francis Castaneda",
 	"Bree Gregory",
 	"Kermit Stevens",
 	"Jordan Terry",
 	"Paul Trujillo",
 	"Linda Beck",
 	"Dara Mckinney",
 	"Idola Pearson",
 	"Phelan Vazquez",
 	"Cleo Dyer",
 	"Kameko Mccall",
 	"Kitra Tillman",
 	"Oren Miles",
 	"Martin Kerr",
 	"Orlando Noble",
 	"Ferdinand Carr",
 	"Scott Norman",
 	"Autumn Winters",
 	"Phillip Heath",
 	"Ryder Mueller",
 	"Armand Lucas",
 	"Naida Hart",
 	"Deborah Spencer",
 	"Blythe Kidd",
 	"Colleen Keller"]
```

**Pista 1:** Puedes remplazar los espacios con el método **.replace()**, para saber como funciona chequea esta documentación:

[Python String replace() Method](https://www.w3schools.com/python/ref_string_replace.asp)

**Pista 2:** Puedes hacer que un string solo contenga minusculas con el metodo **.lower()**
[Python String lower() Method](https://www.w3schools.com/python/ref_string_lower.asp)

### Ejercicio 23

Elabore un algoritmo que le pida al usuario un **número de partida** y un **número final**, para luego imprimir por pantalla los números de la **sucesión de Fibonacci** contenidos dentro de ese rango de números. Los numeros de la sucesion deben guardarse en una lista, y los numeros dentro del rango deben guardarse en otra lista. Luego, debe indicar por pantalla esta ultima lista de los numeros dentro del rango.

### Ejercicio 24

Escribir un programa que almacene los vectores *(1,2,3)* y *(-1,0,2)* en dos listas y muestre por pantalla su **producto escalar**.

### Ejercicio 25

Realizar un algoritmo que dado un número **N** cualquiera, busque todos los **numeros primos** menores a **N** y que los guarde en una **lista**. Luego, debe buscar en la lista *dos numeros primos cuya multiplicación de como resultado N*, en caso de no existir se le debe mostrar al usuario un mensaje de error.

### Ejercicio 26

Realice un algoritmo que realice las operaciones de **suma** y **resta** entre las siguientes **matrices**:

|   | Matriz | A |
|---|--------|---|
| 1 |   4    | 6 |
| 4 |   2    | 5 |
| 6 |   5    | 3 |

|     | Matriz |  B  |
|-----|--------|-----|
| 1.3 |   20   | 12  |
| 1.8 |   28   | 15  |
| 2.5 |   40   | 18  |

El programa debera imprimir *dos matrices resultantes*, una correspondiente a cada operación.

**Pista**: Una matriz puede ser modelada como una *lista de listas*. 

### Ejercicio 27

Realice un algoritmo que dado un **número** ingresado por el usuario realice la operación de *multiplicación por la matriz A* del ejercicio anterior. El programa deberá
mostrar como respuesta la *matriz resultante* de la misma.




# Semana 3

## Diccionarios, Tuplas y Sets

# Semana 4

## Estructuras de Datos Combinadas

# Semana 5

## Modularidad, funciones e importaciones

# Semana 6

## POO: Clases y Objetos 

# Semana 7

## POO: Herencia, Composicion y Polimorfismo

# Semana 8

## Uso de UML, diagramacion de clases

# Semana 9 

## Manejo de Archivos

## Manejo de APIs

## Recursividad

# Semana 10

## Ordenamiento de Listas

## Algoritmos de Busqueda

## Notacion Big O

# Semana 11

## Interfaces Graficas en Python (Extra!)

# Semana 12

## Extras Parte II
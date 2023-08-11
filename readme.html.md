# JavaScript 1

Date Created: 27 de julio de 2023 15:33
Status: Doing

# Ejecutar JavaScript

Se ejecuta por medio de VSC. Se debe crear un archivo index.html y en las líneas de código, poner <script>. Esto le da a entender al editor que estamos trabajando en Java

![Untitled](img/Untitled.png)

Consola: Es donde se ve el resultado del código JS

Para verlo, abrimo el archivo index.html y se abrirá en Chrome. Ahora se usa Ctrl+shift+j para ver la consola

# Comentarios

Son textos que se incluyen pero que no hacen parte del código como tal. Son usados como guía

Se hacen con dos

//

![Untitled](img/Untitled%201.png)

![Untitled](img/Untitled%202.png)

# Variables

Tipos de datos: Undefined (no existe valor asignado), null (nulo), boolean (booleano), string (cadena de caracteres), symbol, number (numero) & object

Variable: Crea un espacio en el dispositivo y guarda un valor en ese lugar de memoria

![Untitled](img/Untitled%203.png)

# Operador de Asignación

Si se definen variables pero no su valor, en la consola se verá reflejado como valor indefinido

![Untitled](img/Untitled%204.png)

![Untitled](img/Untitled%205.png)

Podemos darle un valor a la variable despues de creada

![Untitled](img/Untitled%206.png)

# Asignar el valor de una variable a otra variable

![Untitled](img/Untitled%207.png)

![Untitled](img/Untitled%208.png)

# Variables no Inicializadas

Son aquellas variables a las que no se les ha asignado un valor

![Untitled](img/Untitled%209.png)

# Mayúsculas y Minúculas

En JS es importante que las variables sean escritas como se declararon, respetando mayúsculas y minúsculas

![Untitled](img/Untitled%2010.png)

# Operaciones Aritméticas

![Untitled](img/Untitled%2011.png)

![Untitled](img/Untitled%2012.png)

![Untitled](img/Untitled%2013.png)

![Untitled](img/Untitled%2014.png)

# Números Decimales

![Untitled](img/Untitled%2015.png)

Aplican la misma manera de las operaciones artiméticas

# Residuo de una división.

Esta operación da el valor del residuo de una división, es decir si divido 17/3 nos da 5,6. Pero el residuo es aquello que no se puede dividir de manera entera es decir que daría 5 y residuo 2. Se hace con%

![Untitled](img/Untitled%2016.png)

# Incrementar el valor de una variable

![Untitled](img/Untitled%2017.png)

![Untitled](img/Untitled%2018.png)

![Untitled](img/Untitled%2019.png)

![Untitled](img/Untitled%2020.png)

# Reducción del valor de una variable

![Untitled](img/Untitled%2021.png)

![Untitled](img/Untitled%2022.png)

# Asignación de Suma

Cuando se desea sumar una variable a un numero, se puede hacer de forma abreviada

![Untitled](img/Untitled%2023.png)

Otro Ejemplo

![Untitled](img/Untitled%2024.png)

# Asignación de Resta

![Untitled](img/Untitled%2025.png)

# Asignación de la Multiplicación

![Untitled](img/Untitled%2026.png)

# Asignación de División

![Untitled](img/Untitled%2027.png)

# Variable con Cadenas de Caracteres

![Untitled](img/Untitled%2028.png)

# Escapar Comillas en Cadenas de Caracteres

Si se desea declarar una variable de caracteres que incluyan comillas, debe hacerse de la siguiente manera \”texto”

![Untitled](img/Untitled%2029.png)

# Escape de Caracteres con Comillas Simples

![Untitled](img/Untitled%2030.png)

![Untitled](img/Untitled%2031.png)

Se puede hacer también intercalando comillas simples y comillas dobles como se muestra en los ejemplo

# Secuencias de Escape

Son combinaciones de caracteres que no se representan a sí mismos como caracteres como tal

![Untitled](img/Untitled%2032.png)

# Concatenar Cadenas de Caracteres

![Untitled](img/Untitled%2033.png)

# Construir Cadenas con Variables

![Untitled](img/Untitled%2034.png)

# Agregar Variables a Cadenas de Caracteres

![Untitled](img/Untitled%2035.png)

# Longitud de una cadena de caracteres

Para conocer la cantidad de caracteres de una variable, al momento de imprimir se agrega .lenght, es decir console.log(variable.length)

![Untitled](img/Untitled%2036.png)

# Notación de Corchetes: Primer Caracter

Nos permite acceder a un caracter especial de una cadena

![Untitled](img/Untitled%2037.png)

# Inmutabilidad de Cadena de Caracteres

Una vez definida una cadena de caracteres, no es posible cambiar algún elemento de ella.

![Untitled](img/Untitled%2038.png)

# Notación de Corchetes: Enésimo Caracter

![Untitled](img/Untitled%2039.png)

![Untitled](img/Untitled%2040.png)

# Notación de Corchetes: Último Caracter

![Untitled](img/Untitled%2041.png)

![Untitled](img/Untitled%2042.png)

# Notación de Corchetes: De Derecha a Izquierda

![Untitled](img/Untitled%2043.png)

y Así sucesivamente

# Palabras en Blanco

Vamos a hacer que un texto se imprima en la consola declarando varibales de las palabras 

![Untitled](img/Untitled%2044.png)

# Arreglos (Arrays)

Son estructuras que permiten almacenar múltiples valores  en una misma estructura. Son como vectores.

![Untitled](img/Untitled%2045.png)

# Arreglos Anidados

Se pueden crear arreglos en los que los elementos del mismo, sean arreglos. A esto se le llaman arreglos anidados

![Untitled](img/Untitled%2046.png)

# Identificación de un elemento de un arreglo

Se puede ubicar un elemento de un arreglo mendiante su posición

![Untitled](img/Untitled%2047.png)

# 

# Modificar los datos de un arreglo

Se pueden hacer modificaciones a los datos de un arreglo mediante la declaración de su valor

![Untitled](img/Untitled%2048.png)

# Acceder a Arreglos Multidimensionales

Se hace mediante definicions de subindices

![Untitled](img/Untitled%2049.png)

# .push()

Este método agrega a un arreglo un valor al final de este

![Untitled](img/Untitled%2050.png)

# .pop()

Este método elimina el último  elemento del arreglo, pero adicional nos permite guardarlo en una nueva variable

![Untitled](img/Untitled%2051.png)

# .shift()

Elimina el primer elemento de un arreglo

![Untitled](img/Untitled%2052.png)

# .unshift()

Agrega un elemento al principio de un arreglo. Dentro del paréntesis se define el valor que debe tomar ese elemento que vamos a agregar

![Untitled](img/Untitled%2053.png)

# Lista de Compras

Se pueden imprimier mensajes en la consola usandop las ubicaiones de los arreglos

![Untitled](img/Untitled%2054.png)

# Funciones

Se pueden escribir código que se puede reutilizar

![Untitled](img/Untitled%2055.png)

![Untitled](img/Untitled%2056.png)
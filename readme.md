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

# Argumentos

Las variables de la función se dfinen como parámetros

![Untitled](img/Untitled%2057.png)

para este caso, los parámetros son a y  b

dentro de esa función SUMAR se define que hará esta función

![Untitled](img/Untitled%2058.png)

Para este caso, hará la suma de a+b y muestra en la consola la suma de estos

Ahora, con la función definida, podemos llamarla con los valores que queramos darle a a y b

![Untitled](img/Untitled%2059.png)

Y así se muestra en la consola

![Untitled](img/Untitled%2060.png)

Los argumentos, son los VALORES QUE SE LE ASIGNAN A LOS PARÁMETROS. Es decir, un argumento es un parámetro con valor

Los parámetros también pueden ser definidos mediante variables de la siguiente manera

![Untitled](img/Untitled%2061.png)

# Ámbito Globales

Es una variable que se puede usar en cualquier parte del programa, ya que está definida en el programa principal (no dentro de una función)

# Ámbito Local

Son variables definidas dentro de una función, y solo se pueden usar dentro de esa función

# Diferencias entre Global y Local

Si tengo dos variables con el mismo nombre, una local y otra global estas tienen diferentes jerarquías según en donde se usen. Si se usan dentro de una función, va a tener mayor jerarquía la variablo local. Si se hace fuera de la función, tendrá jerarquía la global (ya que las locales no pueden usarse fuera de la función)

![Untitled](img/Untitled%2062.png)

[https://www.notion.so](https://www.notion.so)

# Retornar un Valor

Tenemos la funcion sumar, dentro de la funcion no siempre es necesario imprimir en la consola el resultado. Podemos calcularlo y guardar el valor sin necesidad de imprimir. Para es usamos la palabra reservada return. Asi queda el valor guardado y posteriormente podemos usarlo bien sea para imprimirlo, o para otros calculos

![Untitled](img/Untitled%2063.png)

![Untitled](img/Untitled%2064.png)

# Undefined

Si se define la función sumar y dentro de la función no retornamos la suma, el valor mostrado deberá ser UNDEFINED. Es decir, siempre debemos retornar el valor

![Untitled](img/Untitled%2065.png)

# Asignar un valor retornado

Se puede asignar una variable al retorno de una función. Se define la función y su variable, dentro de la función se define que es lo que vamos a retoirnar. En este caso es un mensaje. Despues de esto, fuera de la funcion definimos una valiable que será igual a la funcion creada definida en la una variable especifica, ene ste casi “JavaScript”

![Untitled](img/Untitled%2066.png)

![Untitled](img/Untitled%2067.png)

# Permanece en Línea (queue)

En informática, una cola o queue, es una estructura de datos abstracta en la cual los elemntos se mantienen en orden. Los nuevos elementos se pueden añadir al final de la cola y los elementos previos se retiran del principio de la cola

![Untitled](img/Untitled%2068.png)

![Untitled](img/Untitled%2069.png)

# Valores Booleanos

Son valores que pueden tomar valores de verdadero o falso. True or False. Deben escribirse en minuscula siempre (true & false).

# Operador de Igualdad ==

Es un opoerador que compara la igualdad de dos términos. Su resultado será un opoerador booleano-

![Untitled](img/Untitled%2070.png)

![Untitled](img/Untitled%2071.png)

NO DEBERIAN USARSE PARA COMPARAR ARREGLOS

# Operador de Igualdad Estricta ===

Nos permite comparar si los datos son iguales y son del mismo tipo

![Untitled](img/Untitled%2072.png)

# Práctica de como comparar valores

![Untitled](img/Untitled%2073.png)

![Untitled](img/Untitled%2074.png)

# Operadores de Desigualdad ! =

Es un operador que compara la igualdad de dos valores. Su respuesta será true si son distintos y false si son iguales. Es lo opuesto a los operadores de igualdad

![Untitled](img/Untitled%2075.png)

TAMPOCO DEBE USARSE PARA COMPARAR ARREGLOS

# Operador de Desigualdad Estricta ! = =

Funciona igual que el operadod de igual estricta, compara el valor y el tipo de datos. Si son iguales retornará false, si son diferentes retornara true

![Untitled](img/Untitled%2076.png)

# Operador Mayor Que

Compara el valor absoluto de un valor con respecto a otro. Si se da la condición será true, si no false.

Para cadenas de caracteres, se dará por orden alfabético donde a es el menor valor y z el mayor

![Untitled](img/Untitled%2077.png)

También será usado en variables

![Untitled](img/Untitled%2078.png)

# Operador Mayor o Igual que ≥

Adiciona la condición de mayoría e igualdad

# Operador Menor que < y menor o igual que ≤

Funcionan de manera similar que los dos operadores anteriores

![Untitled](img/Untitled%2079.png)

![Untitled](img/Untitled%2080.png)

# Operador Lógico AND &&

Nos permiten combinar expresiones para elaborar condiciones mas elaboradas

Los operadores lógicos tiene tablas de verdad que determinan sus valores de salida

![Untitled](img/Untitled%2081.png)

![Untitled](img/Untitled%2082.png)

# Operador Lógico OR ||

![Untitled](img/Untitled%2083.png)

![Untitled](img/Untitled%2084.png)

![Untitled](img/Untitled%2085.png)

# Operador Lógico NOT !

![Untitled](img/Untitled%2086.png)

Se usa para negar un valor de salida

![Untitled](img/Untitled%2087.png)

![Untitled](img/Untitled%2088.png)

# Sentencias Condicionales IF

Nos permiten elegir si un bloque de código se ejecuta o no

![Untitled](img/Untitled%2089.png)

![Untitled](img/Untitled%2090.png)

# Cláusula ELSE

![Untitled](img/Untitled%2091.png)

![Untitled](img/Untitled%2092.png)

![Untitled](img/Untitled%2093.png)

# Cláusula ELSE IF

Es para anidar IF y ELSE conjuntamente

![Untitled](img/Untitled%2094.png)

![Untitled](img/Untitled%2095.png)

# Encadenar if….else

Ejercicio Práctico

![Untitled](img/Untitled%2096.png)

# Código de Golf

Ejercicio Práctico

![Untitled](img/Untitled%2097.png)

![Untitled](img/Untitled%2098.png)

![Untitled](img/Untitled%2099.png)
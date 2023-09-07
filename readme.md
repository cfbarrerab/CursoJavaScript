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

# Sentencias Switch

La declaración o sentencia Switch evalúa una expresión, comparando el valor de esa expresión con una instancia CASE y ejecuta declaraciones asociadas a ese CASE, así como las declaraciones en los CASE que siguen

![Untitled](img/Untitled%20100.png)

![Untitled](img/Untitled%20101.png)

# Switch: Opción predeterminada

Esta opción se ejecutará si ninguno de los valores es el es valor de la variable o de la expresión. Se hace con DEFAULT

![Untitled](img/Untitled%20102.png)

![Untitled](img/Untitled%20103.png)

# Switch: Múltiples Casos

Se puede ejecutar un código especifico para varios valores.

![Untitled](img/Untitled%20104.png)

![Untitled](img/Untitled%20105.png)

# If…Else por Switch

Vamos a hacer un cógiso donde se obtengan los mismos resultados mediante IF-ELSE y con SWITCH

![Untitled](img/Untitled%20106.png)

![Untitled](img/Untitled%20107.png)

Ahora con SWITCH

![Untitled](img/Untitled%20108.png)

![Untitled](img/Untitled%20109.png)

# Retornar Valores Booleanos

Hay maneras mas resumidas de retornar valores booleanos. La manera como hemos visto hasta ahora con condicionales es:

![Untitled](img/Untitled%20110.png)

![Untitled](img/Untitled%20111.png)

Pero podemos retornar el valor directamente de la comparación

![Untitled](img/Untitled%20112.png)

![Untitled](img/Untitled%20113.png)

# Patrón de Retorno Anticipado

Cuando se retorna un valor de una función, esta se detiene inmediatamente.

![Untitled](img/Untitled%20114.png)

Para este caso, la línea 4 no se ejecutará pues está después de la línea 3 que ejectuta un retorno

![Untitled](img/Untitled%20115.png)

Para este caso, si el número es mayor que cero el programa calculará su raíz cuadrada. Si el número es menor que cero, el valor retornado será UNDEFINED. El patrón de retorno anticipado nos sirve para descartar de entrada aquellos valores que no son aplicables a nuestro código, como es el caso de los números negativos para el ejemplo. 

# Proyecto Conteo de Cartas

Descripción: En el juego de casino de BlackJack el jugador puede sacarle ventaja a la casa llevando un registro del número relativo de cartas altas y bajas que quedan en la baraja. A esto le llaman CONTEO DE CARTAS. Tener más cartas altas en la baraja es una ventaja para el jugador. Se le asigna un valor a cada carta de acuerdo a la siguiente tabla. Si el conteo es positivo, el jugador debería apostar alto, si el conteo es negativo o cero, el jugador debería apostar bajo.

![Untitled](img/Untitled%20116.png)

Nuestra meta es desarrollar una función para contar cartas.

La función debe tomar un parámetro CARTA que puede ser un número o una cadena de caracteres y luego aumentar o reducir el valor de la variable global CONTEO de acuerdo al valor de la carta.

La función debe retornar una cadena de caracteres con el conteo actual y las cadenas: "Apostar" (si el conteo es positivo) o "Esperar" si el conteo es cero o negativo.

El conteo actual y la decisión del jugador (Apostar o Esperar) deben estar separados por un espacio

SOLUCIÓN

![Untitled](img/Untitled%20117.png)

![Untitled](img/Untitled%20118.png)

![Untitled](img/Untitled%20119.png)

# Crear Objetos

Nos permiten guardar una secuencia o un conjunto de propiedades que están relacionadas con sus correspondientes valores. Se definene en JS de la siguiente manera

![Untitled](img/Untitled%20120.png)

# Acceder a Propiedades: Notación de Punto

Para acceder al valor de alguna propiedad de un objeto, se hace mediante la notación de punto. De la siguiente manera

![Untitled](img/Untitled%20121.png)

# Acceder a Propiedades: Notación de corchetes

También se pueden acceder a las distintas propiedades con esta notación que es equivalente

![Untitled](img/Untitled%20122.png)

# Acceder a propiedades: Variables

Podemos definir una variable que sea equivalente a alguna propiedad del objeto. Y posterior, usar la notación de corchetes para llamarlo. Como se muestra a continuación. Esto solo puede hacerse con esta notación, con la notación de punto no es posible

![Untitled](img/Untitled%20123.png)

# Actualizar Propiedades

Definimos un objeto llamada MOCHILA con las propiedades mostradas. La propiedad CONTENIDO tiene más de un elemento, y lo escribimos mediante un arreglo como se muestra a continuación. Una 

![Untitled](img/Untitled%20124.png)

Una vez definida las propiedades, accedemos a la propiedad del color (línea 7) y podemos cambiarla como se muestra en la línea 8. En la línea 9 se muestra que la propiedad ya quedó actualizada.

Para añadir elementos a la propiedad que se defina como un arreglo, para este caso CONTENIDO, usamos el método .PUSH como se muestra a continuación

![Untitled](img/Untitled%20125.png)

O sencillamente definimos nuevamente el contenido de la propiedad con lo que se requeira

![Untitled](img/Untitled%20126.png)

# Agregar Propiedades

Para agregar una propiedad a un objeto, se puede hacer de la siguiente manera con notación de punto y notación de corchetes

![Untitled](img/Untitled%20127.png)

![Untitled](img/Untitled%20128.png)

# Eliminar Propiedades

Para eliminar alguna propiedad podemos hacerlo de la siguiente manera

![Untitled](img/Untitled%20129.png)

# Objetos para Búsquedas

Por medio de OBjetos, podemos simplificar códigos realizados por medio de SWITCH. Un ejemplo claro es el siguiente código

![Untitled](img/Untitled%20130.png)

![Untitled](img/Untitled%20131.png)

![Untitled](img/Untitled%20132.png)

Ahora si lo definimos como un objeto

![Untitled](img/Untitled%20133.png)

![Untitled](img/Untitled%20134.png)

# Verificar Propiedades

Se define un objeto con sus propiedades y se valida si existe con hasOwnProperty(). El retorno será booleano

![Untitled](img/Untitled%20135.png)

![Untitled](img/Untitled%20136.png)

Desarrollemos una función que determine si un objeto tiene una propiedad

![Untitled](img/Untitled%20137.png)

![Untitled](img/Untitled%20138.png)

# Objetos Complejos

Los objetos puede definirse mediante arreglos anidados de manera compleja como se muestra a continuación

![Untitled](img/Untitled%20139.png)

Veamos como podemos acceder a alguna de sus propiedades

![Untitled](img/Untitled%20140.png)

![Untitled](img/Untitled%20141.png)

![Untitled](img/Untitled%20142.png)

![Untitled](img/Untitled%20143.png)

# Objetos Anidados

También se pueden definir Objetos dentro de otros Objetos, de manera similar a a los arreglos anidados. Para acceder a alguna propiedad, podemos usar la notación que se muestra a continuación

![Untitled](img/Untitled%20144.png)

![Untitled](img/Untitled%20145.png)

# Arreglos Anidados

Cuando un objeto esta definido en arreglo, como en el siguiente ejemplo, se debe usar notación de punto para acceder a alguno de sus elementos. Como se muestra a a continuación

![Untitled](img/Untitled%20146.png)

![Untitled](img/Untitled%20147.png)

![Untitled](img/Untitled%20148.png)

# Proyecto: Colección de Discos

Tenemos un objeto que representa parte de una colección de álbumes musicales. Cada álbum tiene un único ID asociado a otras propiedades.

No todos los álbumes tienen la información completa

![Untitled](img/Untitled%20149.png)

# Ciclo While

Se usan cuando no se tiene un número específico de iteraciones, pero si se conoce lo que tiene que ser cierto para detener el proceso.

Dentro del paréntesis de while, irá la condicion del ciclo

![Untitled](img/Untitled%20150.png)

![Untitled](img/Untitled%20151.png)

Otro ejemplo

![Untitled](img/Untitled%20152.png)

![Untitled](img/Untitled%20153.png)

# Ciclo For

Lo usamos cuando sabemos cuantas iteraciones necesitamos. Dentro del par+entesis del for, ira el valor inicial; la condición final; y como queremos que se actualice la variable

![Untitled](img/Untitled%20154.png)

![Untitled](img/Untitled%20155.png)

# Ciclos For: Números Impares

Vamos a crear un arreglo con los números impares entre 0 y 19, incluyendolo

![Untitled](img/Untitled%20156.png)

![Untitled](img/Untitled%20157.png)

Otro Ejemplo. Hagamos un arreglo que contenga todos los número pares desde 2 hasta 26, incluyendolo

![Untitled](img/Untitled%20158.png)

![Untitled](img/Untitled%20159.png)

# Ciclos For: Contar hacia atrás

Hagamos un contador desde 20 hasta 11 con el ciclo for, de uno en uno

![Untitled](img/Untitled%20160.png)

![Untitled](img/Untitled%20161.png)

El mismo ejemplo con arreglo

![Untitled](img/Untitled%20162.png)

![Untitled](img/Untitled%20163.png)

# Iterar Sobre un Arreglo con ciclo For

Vamos  a crear un programa que sume los elementos de un arreglo

![Untitled](img/Untitled%20164.png)

![Untitled](img/Untitled%20165.png)

Otro Ejemplo con cadenas de caracteres, vamos a convertir las cadenas de caracteres a mayúculas con toUpperCase

![Untitled](img/Untitled%20166.png)

![Untitled](img/Untitled%20167.png)

Otro Ejemplo, hagamos un programa que cuente los números pares de un arreglo

![Untitled](img/Untitled%20168.png)

![Untitled](img/Untitled%20169.png)

# Ciclos For Anidados

Vamos usas ciclos for anidados para mostrar elementos de arreglos anidados

![Untitled](img/Untitled%20170.png)

![Untitled](img/Untitled%20171.png)

# Ciclos Do While

Es un ciclo muy similar a While, la diferencia es que se va a ejecutar mínimo una vez el código así no se cumpla la condición. Eso es útil cuando hay que pedir que un usuario ingrese un valor y así podemos compararlo.

Para este código, x = 5. El ciclo dice que independiente de el valor de x, al  menos una vez se ejecutará la impresión. 

![Untitled](img/Untitled%20172.png)

Como el condicional del ciclo es que x sea menor que 10, y x lo es, se seguirá ejecutando el código. Entonces este imprimirá en consola los número del 5 al 9.

![Untitled](img/Untitled%20173.png)

Ahora si x =15, no cumple con el condicional. Sin embargo imprimirá una vez el valor de x por que así es la naturaleza del ciclo

![Untitled](img/Untitled%20174.png)

![Untitled](img/Untitled%20175.png)

# Proyecto: Buscar Contactos

Vamos a hacer un proyecto con todo lo aprendido que nos permita buscar un contacto en una lista de contacto

![Untitled](img/Untitled%20176.png)

![Untitled](img/Untitled%20177.png)

![Untitled](img/Untitled%20178.png)

# Números aleatorio entre 0 y 1

Para poder generar números aleatorios entre [0 y 1), podemos usar la siguiente función matemática

![Untitled](img/Untitled%20179.png)

![Untitled](img/Untitled%20180.png)

![Untitled](img/Untitled%20181.png)

![Untitled](img/Untitled%20182.png)

# Números Aleatorios Enteros

Vamos a combinar dos métodos establecidos en JS

Usaremos la función floor que retorna el valor entero menor o igual de un número. A este lo vamos a multiplicar por la función random y así obtendremos número enteros aleatorios entre un rango

![Untitled](img/Untitled%20183.png)

![Untitled](img/Untitled%20184.png)

![Untitled](img/Untitled%20185.png)

![Untitled](img/Untitled%20186.png)

Y así podemos crear una función predeterminada que podremos usar posteriormente luego

![Untitled](img/Untitled%20187.png)

Ahora, si queremos generar un número definido de números aleatorios, podemos hacerlo mediante un ciclo de la siguiente manera

![Untitled](img/Untitled%20188.png)

![Untitled](img/Untitled%20189.png)

![Untitled](img/Untitled%20190.png)

# Números Aleatorios en un Rango

Si ahora queremos que el rango no empiece siempre desde cero, podemos establecer una operación matemática con la función declarada anteriormente

![Untitled](img/Untitled%20191.png)

![Untitled](img/Untitled%20192.png)

![Untitled](img/Untitled%20193.png)

# Función praseInt()

Esta función convierte una cadena de caracteres a un entero.  Para el caso de decimales, elimina la parte decimal. 

![Untitled](img/Untitled%20194.png)

A continuación veremos un ejemplo de su aplicación

![Untitled](img/Untitled%20195.png)

# Función parseInt() con una Base

Esta función también nos permite pasar un número determinado a un sistema numérico en otra base. En este ejmpo, vamos a poner el número 110111 y definimos que está en base 2. El retorno será su equivalencia en base 10

![Untitled](img/Untitled%20196.png)

Ahora otro ejemplo en sistema hexadecimal

![Untitled](img/Untitled%20197.png)

# Operador Condicional Ternario

Este operador nos permite compactar un condicional en una sola línea

Para mostrarlo vamos a comparar un condicional sencillo 

![Untitled](img/Untitled%20198.png)

Esto es equivalente a 

![Untitled](img/Untitled%20199.png)

Esto lo podemos interpretar así: evalue si x < y. Si esta condicion es verdadera retorne x, si no retorne y

También podemos usarlo para operar matemáticamente así

![Untitled](img/Untitled%20200.png)

# Múltiples operadores condicionales
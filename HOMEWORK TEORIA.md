Home Works teoría.

Lección 2: Javascript I.
En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

* Variables
Las variables son espacios en memoria, que yo voy a reservar, para guardar algún dato y luego utilizarlo. A las variables les tenemos que poner nombres, con esto se hace más fácil acceder a ellas. Para declarar una variable debemos usar la palabra reservada var seguida del nombre de la variable. Para guarda un valor en ella usamos el signo de asignación “=”.Por ejemplo var alumno = “Sebastián”.

* Strings
Es un tipo de dato. En las variables de este tipo puedo guardar cadenas de caracteres, es decir, texto. 

* Funciones (argumentos, `return`)
Con las funciones puedo agrupar código para luego reutilizar. Con ellas evito escribir el mismo código repetidas veces. Básicamente las funciones nos ayudan a que nuestros programas hagan algo.
A través del argumento las funciones pueden recibir uno o más datos del exterior para poder trabajar con ellos dentro de la misma.
Las funciones pueden también devolver algún valor o resultado a través de la palabra reservada 'return'.

* Declaraciones `if`
El 'if' se utiliza como control de flujo de datos. Es una estructura condicional muy útil para la verificación o validación de algo. En esta estructura se evalúa que se cumpla determinada condición, si dicha condición se cumple se ejecuta un cierto código.
* Valores booleanos (`true`, `false`)
El tipo de datos Booleano solo admite dos posibilidades, true o false. Cuando se verifica que una expresión es verdadera entonces js entiende que es true y por el contrario cuando es falsa, false. Por ejemplo: 1 === 1   //true – verdadero.
                                                                3 === 5  //false – falso.

Lección 3: Javascript II.

* for
Estructura que repite en forma de bucle un código de programación hasta que devuelve lo que estamos buscando o se detiene después de cierto tiempo (cuando no se cumple determinada condición).

* &&, ||, !
Operadores lógicos que utilizamos para combinar más de una expresión de igualdad para la verificación o validación. Estos operadores funcionan con una lógica booleana.
Todas las expresiones de igualdad que combina && (and) tienen que ser true para que la validación sea true. En cambio en || (or) con que solo se cumpla una sola igualdad la validación es verdadera. El operador !  es de negación, es decir invierte todo lo que precede. 
Por Ejemplo: !true = false. 



Lección 4: Javascript III.

* Arrays
Los arrays son contenedores de almacenamiento para colección de datos. Mientras que en una variable puedo almacenar un solo dato en los arreglos puedo guardar un conjunto de estos datos.

Lección 5: Javascript IV.

* Objetos
Los objetos son contenedores de datos y contiene mucha información sobre una sola cosa. Básicamente los objetos son una colección de propiedades.

* Propiedades
Una propiedad es una asociación clave y valor. Por ejemplo, tenemos el objeto alumno que tiene la propiedad nombre : “Juan” en donde nombre es la clave y juan es el valor asociado a dicha clave.

* Métodos
En JavaScript un método es una propiedad de un objeto que permite ejecutar algún código. Es decir, los métodos son las funciones. Por ejemplo: objeto.saludar(); //Hola

* Bucle for…in
Estructura repetitiva similar a la que usamos para recorrer arrays pero con sintaxis ligeramente diferente.  Este for in recorre cada clave de un determinado objeto hasta cuando haya iterado todas ellas.

* Notación de puntos vs notación de corchetes
La notación de puntos (Dot Notation) es más rápida y más simple, para acceder a una variable tenemos que escribir el objeto seguido de un punto y el nombre de la propiedad (o clave). Ejemplo: 
objeto.propiedad1;
objeto.propiedad2[2];
En la notación de corchetes (Bracket Notation) tenemos que poner el nombre del objeto seguido de corchetes y entre ellos en nombre de la propiedad (o clave) entre comillas. O también podemos poner dentro de los corchetes una variable que contenga el nombre de la propiedad, lo que representa una gran ventaja cuando se utiliza en métodos ya que puedo pasar dicha variable dentro del argumento del mismo. Ejemplo:
usuario[‘email’];
var pass = ‘miPass123’;
usuario[pass]; 


Lección 6: Javascript V.

* prototype
Las clases tienen una forma única de establecer un método una sola vez y dar acceso a cada  objeto de esa clase a esos métodos.
prototype es una propiedad que tiene los objetos en JavaScript que me permite compartir métodos entre los objetos de una misma clase (o constructor). 

* Constructors (de Clases)
Un constructor es una función que me va a permitir construir objetos. A esta función le puedo pasar parámetros como argumentos los cuáles serán las propiedades del mismo.


Lección 7: Javascript VI.

* Funciones Callback
En JS las funciones don tratadas como “First Class”, es decir que son iguales que cualquier otro elemento del lenguaje (como los objetos, arrays, etc.). De esta manera las funciones se pueden pasar como parámetros en el argumento de otra función, ser retornadas como resultado o guardadas en otras estructuras de datos (objetos, arrays, etc.).
Recibe el nombre de callback la función que se pasa como parámetro en el argumento de otra función.

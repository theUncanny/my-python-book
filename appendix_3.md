# Apendice 3: Glosario Extra

## 1-9
---

## A
---
### ACID
En bases de datos se denomina ACID a las características de los parámetros que permiten clasificar las transacciones de los sistemas de gestión de bases de datos. Cuando se dice que es ACID compliant se indica -en diversos grados- que éste permite realizar transacciones.

En concreto **ACID** es un acrónimo de **A**tomicity, **C**onsistency, **I**solation and **D**urability, esto es, *Atomicidad*, *Consistencia*, *Aislamiento* y *Durabilidad*.

[TODO]

https://es.wikipedia.org/wiki/ACID

### Array asociativo

En el ámbito de las ciencias de la computación, un *array asociativo* es un *tipo de dato abstracto* (en: **A**bstract **D**ata **T**ype, **TDA**) compuesto de una colección de parejas *llaves/claves* (en: key) *valor* (en: value). Mientras que, en una colección, los valores pueden repetirse, las llaves/claves deben ser únicas.

El concepto abstracto de array asociativo está presente e implementado en diferentes lenguajes de programación y se les da diferentes nombres, mapa (en: map), tabla de símbolos (en: symbol table), diccionario (en: dict), hashes.

[TODO]

Referencias:

https://en.wikipedia.org/wiki/Associative_array
https://es.wikipedia.org/wiki/Vector_asociativo

### Assessor
[TODO]

## B
## C
## D
---
### Dirty object
---
Ver definición en **Objeto sucio**.

## E
---
### Estructura de control
Bloque de código que, como su nombre sugiere, permite controlar el flujo del programa, es decir, que debe hacer el programa en cada parte del mismo, pues permite implementar respuestas a cuestiones del tipo "que, como, cuando, donde y porque" (propias del paradigma imperativo) para gestionar las diferentes tareas que el programa debe realizar según que condiciones se den (*if-elif-else*) o repeticiones se quieran (*for*, *while*), a fin de poder obtener la solución del algoritmo implementado.

[TODO]

### Estructura de datos
https://en.wikipedia.org/wiki/Data_structure
https://en.wikipedia.org/wiki/List_of_data_structures
https://en.wikipedia.org/wiki/List_of_terms_relating_to_algorithms_and_data_structures


## F
---
### Fixture

Un ***fixture*** es un concepto usado a menudo en el contexto de las pruebas de software como una analogía a la palabra y concepto usado durante los procesos de fabricación industrial de utensilios, herramientas y maquinaria, consistiendo un *fixture* en una herramienta (p.e: un tornillo o torno de banco) que permite mantener fijo (en: *fixed*) un objeto físico (un tornillo, una tuerca, una tubería, otra herramienta, etc.) sujetándolo con firmeza a fin de poder realizar algún trabajo (aserrar, perforar, fresas, limar, marcar, etc.) sobre el mismo .

En el ámbito de la ingeniería del software un *fixture* suele representar un ***elemento o estado fijo*** al que se puede establecer una parte o incluso toda la aplicación (por ejemplo, mediante ciertos valores de entrada), considerándose muy útiles por su reusabilidad para realizar varias pruebas (ya que el coste de tiempo en diseñar pruebas suele ser alto si no se dispone de estos), volviendo a los estados originales de la aplicación una vez que las pruebas se completan. En BB.DD. relacionales o de tipo NoSQL (p.e: MongoDB) un *fixture* describe el estado inicial en el que se encuentra la base de datos (en: *database*) cuando se ejecuta una prueba (en: *test*).

## G
---
### Getter
[TODO]

## H
---

### HTTP Router

Se conoce como *HTTP router* o *HTTP request router*, cuya traducción más fiel seria *enrutador* o *encaminador de peticiones HTTP*, es un concepto que se asemeja, de forma análoga, al dispositivo de hardware de red conocido como *router* y, al igual que este se encarga interconectar subredes enviando o "encaminando" paquetes de datos transmitidos entre las máquinas conectadas a estas subredes, un *HTTP request router* se encarga de procesar las peticiones que llegan vía protocolo HTTP, desde una URL, con una URI, para traducirlas de tal forma que *encamina* o dirige la petición hacia el recurso exacto que se está solicitando y realizar la solicitud (*request*) sobre dicho recurso con el *método HTTP* concreto con el que se se haya solicitado tal recurso (GET, POST, HEAD, DELETE, etc.) al servidor HTTP.

[TODO]

http://trevinca.ei.uvigo.es/~txapi/espanol/proyecto/superior/memoria/node44.html
https://es.wikipedia.org/wiki/Router
https://www.playframework.com/documentation/2.1.1/ScalaRouting
http://php.net/manual/es/class.yaf-router.php
http://symfony.com/doc/current/book/routing.html
https://librosweb.es/libro/symfony_2_x/capitulo_6/creando_rutas.html
http://gitnacho.github.io/symfony-docs-es/book/routing.html
http://symfony.com/doc/current/components/http_foundation/introduction.html
http://www.nodebeginner.org/index-es.html
https://elithrar.github.io/article/map-string-interface/
http://www.gorillatoolkit.org/pkg/context
https://blog.golang.org/context



## I
---
### Inyección de dependencias
https://es.wikipedia.org/wiki/Inyecci%C3%B3n_de_dependencias

### Iterador (en: Iterator)
https://en.wikipedia.org/wiki/Iterator

## J
## K
## L
---
### Lectura sucia (en: Dirty read)
[TODO]

https://es.wikipedia.org/wiki/Aislamiento_(ACID)

## M
## N
## O
---
### Objeto sucio (en: Dirty object)

Un *"objeto sucio"* (*dirty object*), entendido, de forma abstracta, como un contenedor de datos, cuyo contenido original ha sido modificado en algún momento durante el tiempo de ejecución, pero que se da la circunstancia de que el nuevo contenido aun no ha sido sincronizado y almacenado de forma permanente en disco (p.e: en un fichero, en un esquema de BB.DD., etc), es decir, por el momento, el nuevo contenido solo está en la memoria principal del sistema (p.e: la memoria RAM, memoria caché, etc.), lo que implica que este nuevo contenido aun es potencialmente "volatil" y, por tanto, los cambios en el contenido original de dicho objeto pueden perderse si dichos cambios no se sincronizan correctamente y a tiempo.

> **EJEMPLO**: Una situación bastante típica para la existencia de los llamados *objetos sucios* se dan en la constante desincronizacion que existe una caché de datos y el almacenamiento final (ficheros, BB.DD, etc.), esto hace que, si por algún motivo (p.e: un corte de electricidad, fallo en la red, caida puntual de un servicio, etc.) no se sincroniza el contenido de la caché con el almacenamiento final, todos los cambios realizados se pueden perder.

**REFERENCIAS**:

* http://stackoverflow.com/questions/1745888/what-is-meant-by-the-term-dirty-object
* http://www.dagolden.com/index.php/2633/no-more-dirty-reads-with-mongodb/

## P
---
### Patrón de diseño de software
[TODO]
https://en.wikipedia.org/wiki/Software_design_pattern

## Q
## R

## S
---
### Scaffolding

La palabra *scaffold*, de origen inglés, significa en español *andamio* como sustantivo y *andamiar* como verbo. En el contexto del desarrollo de software el *scaffolding*, o *andamiaje*, es una técnica que permite construir aplicaciones que hagan uso de bases de datos y suele ser usada y soportada de serie por algunos *frameworks* basados en el patrón **Modelo-Vista-Controlador** (en: _**M**odel-**V**iew-**C**ontroller_, **MVC**), mediante la cuál el programador puede escribir una especificación en la que describa cómo debe ser usada la base de datos. Posteriormente el compilador o interprete (dependerá del lenguaje de programación en el que se basa el *framework* MVC en cuestión) hará uso de esa especificación para generar el código necesario que la aplicación usará para realizar las operaciones que se consideran básicas a la hora de gestionar una base de datos, esto es "*Crear*-*Leer*-*Actualizar*-*Eliminar*" (en: "_**C**reate_-_**R**ead_-_**U**pdate_-_**D**elete_", **CRUD**).

El *scaffolding* fue popularizado por el *framework* _**Ruby on Rails**_ para el lenguaje Ruby y actualmente es una técnica común implementada en otros *frameworks*, especialmente basados en el lenguaje PHP, cómo CakePHP, Symfony.

Scaffolding is a technique supported by some model–view–controller frameworks, in which the programmer can specify how the application database may be used. The compiler or framework uses this specification, together with pre-defined code templates, to generate the final code that the application can use to create, read, update and delete database entries, effectively treating the templates as a "scaffold" on which to build a more powerful application.

Scaffolding is an evolution of database code generators from earlier development environments, such as Oracle's CASE Generator, and many other 4GL client-server software development products.

[TODO]

http://techtastico.com/post/que-es-el-scaffolding-o-scaffold/
https://en.wikipedia.org/wiki/Scaffold_(programming)
http://book.cakephp.org/1.3/es/The-Manual/Developing-with-CakePHP/Scaffolding.html
http://www.frangarcia.net/articles/324/scaffolding-en-grails

## T
---
### Tipo de datos abstracto
[TODO]

## V
## W
## X
## Z


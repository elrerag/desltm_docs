# Lectura

___
# Nombre de la unidad: 
UML

# Descripción unidad
En el capítulo de UML se conocerá el lenguaje de modelamiento unificado (UML), con el cual se aprenderá a crear casos de usos, diagramas de secuencias y diagramas de clases, para agilizar la creación de piezas de software.

# Requerimientos
Se espera que el alumno posea un conocimiento previo del paradigma de programación orientado a objetos, además de tener instalada la herramienta StarUml.

# Referencias  

* UML distilled - Martin Fowler.

### Glosario
* __Notación__: Es la acción y efecto de notar, hace referencia al sistema de signos convencionales que se adopta, para expresar algún concepto.

* __Metodología__: Grupo de mecanismos o procedimientos racionales, empleados para el logro de un objetivo.

* __Paradigma__: Teoría o conjunto de teorías, cuyo núcleo central se acepta sin cuestionar y que suministra la base y modelo para resolver problemas y avanzar en el conocimiento

* __Software__: Conjunto de programas, instrucciones y reglas informáticas que permiten ejecutar distintas tareas en una computadora.

* __Programación Imperativa__: En este paradigma de la programación, que, como su nombre lo indica, __imperan las instrucciones, condiciones o pasos__ indicamos exactamente, lo que el programa debe hacer. Típicamente nos encontraremos con estructuras cíclicas tales como: while, for. También condicionales if o switch. Lo que no quiere decir que si un programa posee estas instrucciones es puramente imperativo. Podemos reconocer este tipo de programación cuando leemos el código y su traza es una interpretación de lectura secuencial de lo que está escrito.

* __Programación procedural__: Se trata de un estilo de programación; basado en estructurar el código de un programa en componentes, que reciben el nombre de procedimientos, subrutinas o funciones.

* __Programación Orientada a Objetos  (POO)__: Este paradigma, es un tipo de programación imperativa, que mediante algunas técnicas (por ejemplo la herencia), resuelve algunas falencias que existían en la programación procedural (por ejemplo la reutilización de código), utilizando objetos, cada uno de ellos, compuestos por un estado (datos) y un comportamiento.

* __Programación declarativa__: Es un paradigma de la programación, en la que los programas se describen en términos de proposiciones y afirmaciones, que son __declaradas__, en donde los pasos para resolverlo, no impera. En este tipo de programación, nos encontraremos mucha recursividad.

* __Programación Funcional__: Es un paradigma que pertenece a la programación declarativa, basado en el trabajo de Alonzo Church y Stephen Kleene en la década de 1930, llamado: El Cálculo Lambda; este paradigma se compone de funciones que deben cumplir ciertas reglas (por ejemplo, que sean funciones puras). en donde encontraremos formas recursivas de por ejemplo trabajar con arreglos como lo son: `map`, `reduce` o `filter`. La principal diferencia con la programación orientada a objetos, es que la programación funcional, no posee estados.

* __Cliente__: El ente que paga por el producto.

* __Usuario__: Es quien usa el producto.

* __Stakeholder__: Es quien sostiene la estaca, todo aquél se se ve afectado por el producto y/o proyecto.

* __Framework__: Un marco de trabajo, o framework, es una estructura real o conceptual destinada a servir de soporte o guía para la construcción de algo que expande la estructura en algo útil. Para nuestro caso, es mejor que lo veamos como un software pre construido, al que le podemos ir adicionando piezas según sus reglas, con la finalidad obtener un producto personalizado a nuestras necesidades.

* __Patrón__: Hechos o cosas recurrentes. Estos se repiten con previsibilidad, por lo tanto, pueden funcionar como modelo para producir determinada cosa a partir de ellos.

* __Patrón de diseño de modelo-vista-controlador (MVC)__: Especifica que una aplicación consta de tres capas: La primera es el modelo de datos, que es la capa con la responsabilidad de la gestión de los datos, luego tenemos la capa de presentación, es lo que el usuario ve, es decir, la vista. La forma en que la información sea presentada al usuario, son responsabilidad de esta capa, por último, tenemos la capa del controlador, que es la capa encargada de orquestar o controlar, la interacción de las dos capas anteriormente mencionadas.

* __Agilidad__: Se refiere a la flexibilidad que posee un proyecto, es decir, que pueda cambiar y que esto no produzca un alto impacto en el esfuerzo.

## Capítulo 1: Introducción.

## Competencias esperadas.
* Conocer el lenguaje de modelado unificado (UML).
* Conocer los distintos tipos de diagramas.
* Reconocer el paradigma de la programación en el que está basado UML.


### ¿Qué es UML?
UML (Unified Modeling language), es un **lenguaje** de modelado unificado, que surge a finales de la década de los 80 y principios de los 90. Entre los años 94 y 96, Grady y Jim e Ivar, conocidos como; "los tres amigos", crearon finalmente UML. Resultado de un trabajo iterativo y gradual, que pone a nuestra disposición, una norma construida sobre muchas ideas y contribuciones realizadas (unificadas), por numerosos individuos y compañías de la comunidad de la orientación a objetos.  
**UML es un lenguaje y no una metodología**, esto suele causar confusiones. Las _metodologías_ poseen un lenguaje y un proceso para modelar. En este caso; el lenguaje de modelado es la notación (gráfica), de la que se valen las metodologías para expresar los diseños.

### Breve historia.
En el año 1980, el paradigma de la orientación a objetos; ya no era parte solamente del contexto científico, en vez de ello, se encontraba ya en uso "cotidiano" en lenguajes que comenzaron a ser ampliamente utilizados como `Smalltalk`, dando paso a la creación de nuevos lenguajes basados en en la _POO_., como es el caso de `C++`. Antes de que todo esto ocurriera, ya existían diferentes tipos de metodologías para representar el diseño de un _software_ utilizando la _programación procedural_; pero ahora había que lograr el mismo éxito en la POO. Entre los años 90 y el 98, muchas fueron las organizaciones que intentaron llegar a un estándar unificado; pero finalmente "los tres amigos", y, su versión 1.1 de UML fueron los ganadores. Tal fue su éxito, que hasta el día de hoy seguimos usando UML como el lenguaje, para representar el diseño de artefactos de nuestras aplicaciones.

### ¿Qué tan rigurosos debemos ser, a la hora de implementar este lenguaje?  
El propósito de UML es ser una herramienta, y, como tal, se debe tener en cuenta que su estricta utilización, irá directamente relacionada con el contexto en el que se esté trabajando, por ejemplo, si estamos trabajando en una herramienta, que a partir de los modelos que se creen con UML, se genere código de forma automatizada. Es en este caso, donde usaremos UML de forma rigurosa, para que el código generado sea el que se necesita.  
En el caso que se desee utilizar UML en el contexto de una reunión en la que se desee entender un problema y donde los modelos diseñados no sean documentados formalmente (por ejemplo en una pizarra en una reunión con el cliente), podemos entonces usar UML con mayor libertad, sin dar tanta importancia a los detalles, sino que basta con que expliquen el problema de una forma global. En este tipo de casos debemos usar lo mínimo que nos aporte una mejor interpretación del problema que se desea resolver. Existen ocasiones en que la notación oficial puede llegar a estorbar, en estos casos no hay que dudar en adaptar el lenguaje a las necesidades personales. Quizás puede ser mal visto el que no estemos usando UML con todas sus sutilezas; pero en este caso ganamos flexibilidad y mientras la comunicación no se vea afectada, no existe mayor problema en alterar un poco este lenguaje. Hay que tener cuidado al momento de adaptarlo, no nos podemos exceder, ya que el diferir mucho la estructura oficial, puede resultar en que no se comprenda lo que se desee expresar.

### ¿Qué debemos preguntarnos antes de usar UML?
Ya se ha mencionado que UML lo usamos como una herramienta, y para que lo sea, tenemos que asegurarnos, que la utilización de este lenguaje **sea útil**. Después de todo, los diagramas que realizamos pueden ser visualmente atractivos; pero ningún cliente va a agradecer la belleza de los diseños que hemos generados con UML; lo que los clientes, usuarios, stakeholders, etc. quieren son aplicaciones que funcionan. Es por todo esto, que al momento de utilizar UML, debemos hacernos la siguiente pregunta: ¿Cuál será el beneficio de utilizarlo? y ¿Cómo su uso ayudará al momento de implementar el código?. Si estas preguntas no tienen una respuesta clara. Entonces, quizás el uso de modelos construidos con UML, no generan un real aporte, que justifiquen su utilización.

### UML y los paradigmas de programación.
 El reconocido empresario de las tecnologías de la información `Tom Hadfield`, quien a la edad de doce años, creó junto a su padre `socckernet (1994)`, sitio que fue vendido a ESPN en 40 millones de dólares dice:

> los lenguajes de objetos, permiten ventajas pero no las proporcionan. Para aprovechar estas ventajas hay que realizar el infame cambio de paradigma. (¡Sólo asegúrese de estar sentado al momento de hacerlo!)  

La mayoría de las personas que podían reconocer la programación en esos años e incluso en ahora, la asocia al paradigma de la programación imperativa. Antes de que el mundo comenzara a utilizar la POO de forma natural, se utilizaba la programación procedural, y esto era lo usual, lo que sabíamos, por tanto, un cambio en el paradigma suponía un esfuerzo que queda reflejado en la frase de Hadfield. Entonces estamos ante una herramienta que nos permite modelar,  y por ejemplo, por medio de un _framework_ llevaríamos rápidamente a código los diagramas que hemos diseñado, si están correctamente diseñados por supuesto. Todo esto gracias a que UML fue concebido para la POO. Entonces, ¿en qué situación nos encontramos ahora?. Se podría afirmar que un "nuevo" paradigma emerge, el paradigma de la programación declarativa, todo esto debido a que lenguajes como `javascript`, que toma fuerza en la cantidad de aplicaciones que existentes o que se estén desarrollando; pero hay que mencionar que este lenguaje, es un lenguaje funcional (hija del paradigma declarativo), y, además es un lenguaje imperativo. Entonces nos encontramos ante una mezcla de lo que es programación funcional y programación orientada a objetos. Quizás debamos comenzar a comprender que esta mezcla de paradigmas puede coexistir y debemos acostumbrarnos a ello, verlo como una nueva forma de construir, y, no verlo como un dolor de cabeza, hasta que nos acostumbremos a su uso. UML nos seguirá sirviendo para representar gráficamente problemas; pero quizás el enfoque cambie un poco, hacia la utilización de nuevas herramientas que mezcle lo funcional con lo orientado a objetos. Verán que en librerías como _React js_ ya utiliza esta mezcla de paradigmas y que cada nueva versión de Java, incluye muchas herramientas que permiten usar la programación funcional. Como sea que termine esta história, UML aún nos entrega una interfaz entre lo que es abstracto y lo que podríamos llamar tangible.

## El proceso de desarrollo de software.

UML, es un lenguaje para modelar, por eso no asume la noción de un proceso; pero para poder realizar un buen desarrollo, hay que analizar el propio proceso de desarrollar aplicaciones.  

Una visión del desarrollo en su nivel más alto sería como la que muestra la figura 1.1.

<center>![Proceso de desarrollo de software](img/procesoDesarrollo.png)</center>
<center>Figura 1.1: Proceso de desarrollo de software.</center>

Durante la concepción, se establece la razón de ser del proyecto, además del alcance del mismo. Es en esta etapa en donde se define si el proyecto se realiza o no.

En la elaboración, se detallan más profundamente los requerimientos, para así llegar a confeccionar una arquitectura base. Los diseños utilizados han de ser de alto nivel, es decir, sin gran nivel de detalle, destacando solamente lo principal. Dependiendo del nivel de _agilidad_ del proyecto, esta etapa puede ser desde una reunión de un par de horas, hasta una entrega de documentos formales, con iteraciones. Al finalizar esta etapa, las preguntas: ¿Qué es lo que va a construir en realidad?, ¿Cómo lo va a construir?, ¿Qué tecnología empleará?, deben ser contestadas.

En la construcción, como se indica en la figura 1.1, la iteración es clave. No quiere decir que el las otras etapas no se pueda iterar; pero en esta etapa, cada iteración es un mini proyecto. Terminando con una demostración funcional al stakeholder. Con ello reducimos el riesgo, ya que si algo no ha salido como se quería, solamente está en juego la iteración y no el proyecto completo. La funcionalidad será incremental y la construcción de código será iterativa. 
¿Cuándo se debe usar el desarrollo iterativo?  
> El desarrollo iterativo únicamente se debe utilizar en aquellos proyectos que se quiere que tengan éxito.

Todas las técnicas de UML son útiles durante esta etapa; pero hay que ser cuidadosos, de no excedernos, como dice la siguiente cita:

> Los memorandos cuidadosamente escritos y seleccionados, pueden sustituir con toda facilidad a la tradicional documentación detallada del diseño. Esta última es sobresaliente en pocas ocasiones, excepto en algunos puntos aislados. Destaque estos puntos... y olvídese del resto.. "Ward Cunningham (1996)"

Durante la transición, no se hacen desarrollos para añadir funciones nuevas (a menos que sean pequeñas y absolutamente indispensables). Ciertamente, sí hay desarrollo para depuración. Un buen ejemplo de una fase de transición es el tiempo entre la liberación beta y ]a liberación definitiva del producto.

## Notaciónes UML.

UML como se ha indicado, es un lenguaje; pero debemos saber como dicho lenguaje, nos ayuda para representar los conceptos del paradigma de la orientación a objetos. A continuación veremos algunos diagramas que utilizan este lenguaje.






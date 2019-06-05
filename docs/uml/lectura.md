### **Nombre de la unidad**
* UML

### **Descripción unidad**
* En el capítulo de UML se conocerá el lenguaje de modelamiento unificado (UML), con el cual se aprenderá a crear casos de usos, diagramas de secuencias y diagramas de clases, para agilizar la creación de piezas de software.

### **Requerimientos**
* Conocimiento previo del paradigma de programación orientado a objetos.
* Tener una herramienta de modelado como [StarUml](http://staruml.io/download).

### **Referencias**

* UML distilled - Martin Fowler.
* El Lenguaje Unificado de Modelado - J. Rumbaugh, I. Jacobson, G. Booch.
* [https://www.smartdraw.com/uml-diagram/](https://www.smartdraw.com/uml-diagram/)
* [https://ingenieriadesoftware.es/opiniones-lenguaje-uml-20-anos/](https://ingenieriadesoftware.es/opiniones-lenguaje-uml-20-anos/)
* [https://www.uml.org](https://www.uml.org)


### **Glosario**  

* __Aplicación__: Es un tipo de software que permite al usuario realizar uno o más tipos de trabajo.

* __Notación__: Es la acción y efecto de notar, hace referencia al sistema de signos convencionales que se adopta, para expresar algún concepto.

* __Metodología__: Grupo de mecanismos o procedimientos racionales, empleados para el logro de un objetivo.

* __Paradigma__: Teoría o conjunto de teorías, cuyo núcleo central se acepta sin cuestionar y que suministra la base y modelo para resolver problemas y avanzar en el conocimiento.

* __Software__: Conjunto de programas, instrucciones y reglas informáticas que permiten ejecutar distintas tareas en una computadora.

* __Programación Imperativa__: En este paradigma de la programación, que, como su nombre lo indica, __imperan las instrucciones, condiciones o pasos__ indicamos exactamente, lo que el programa debe hacer. Típicamente nos encontraremos con estructuras cíclicas tales como: while, for. También condicionales if o switch. Lo que no quiere decir que si un programa posee estas instrucciones es puramente imperativo. Podemos reconocer este tipo de programación cuando leemos el código y su traza es una interpretación de lectura secuencial de lo que está escrito.

* __Programación procedural__: Se trata de un estilo de programación; basado en estructurar el código de un programa en componentes, que reciben el nombre de procedimientos, subrutinas o funciones.

* __Programación Orientada a Objetos  (POO)__: Este paradigma, es un tipo de programación imperativa, que mediante algunas técnicas (por ejemplo la herencia), resuelve algunas falencias que existían en la programación procedural (por ejemplo la reutilización de código), utilizando objetos, cada uno de ellos, compuestos por un estado (datos) y un comportamiento.

* __Programación declarativa__: Es un paradigma de la programación, en la que los programas se describen en términos de proposiciones y afirmaciones, que son __declaradas__, en donde los pasos para resolverlo, no impera. En este tipo de programación, nos encontraremos mucha recursividad.

* __Programación Funcional__: Es un paradigma que pertenece a la programación declarativa, basado en el trabajo de Alonzo Church y Stephen Kleene en la década de 1930, llamado: El Cálculo Lambda; este paradigma se compone de funciones que deben cumplir ciertas reglas (por ejemplo, que sean funciones puras). en donde encontraremos formas recursivas de por ejemplo trabajar con arreglos como lo son: `map`, `reduce` o `filter`. La principal diferencia con la programación orientada a objetos, es que la programación funcional, no posee estados.

* __Cliente__: En el contexto de la toma de requerimientos, es el ente que paga por el producto.

* __Usuario__: Es quien usa el producto.

* __Stakeholder__: Es quien sostiene la estaca, todo aquél se se ve afectado por el producto y/o proyecto.

* __Framework__: Un marco de trabajo, o framework, es una estructura real o conceptual destinada a servir de soporte o guía para la construcción de algo que expande la estructura en algo útil. Para nuestro caso, es mejor que lo veamos como un software pre construido, al que le podemos ir adicionando piezas según sus reglas, con la finalidad obtener un producto personalizado a nuestras necesidades.

* __Patrón__: Hechos o cosas recurrentes. Estos se repiten con previsibilidad, por lo tanto, pueden funcionar como modelo para producir determinada cosa a partir de ellos.

* __Patrón de diseño de modelo-vista-controlador (MVC)__: Especifica que una aplicación consta de tres capas: La primera es el modelo de datos, que es la capa con la responsabilidad de la gestión de los datos, luego tenemos la capa de presentación, es lo que el usuario ve, es decir, la vista. La forma en que la información sea presentada al usuario, son responsabilidad de esta capa, por último, tenemos la capa del controlador, que es la capa encargada de orquestar o controlar, la interacción de las dos capas anteriormente mencionadas.

* __Agilidad__: Se refiere a la flexibilidad que posee un proyecto, es decir, que pueda cambiar y que esto no produzca un alto impacto en el esfuerzo.

---
## **Capítulo 1: Introducción a UML.**
---

#### **Competencias esperadas.**
* Conocer el lenguaje de modelado unificado (UML).
* Conocer los distintos tipos de diagramas.
* Reconocer el paradigma de la programación en el que está basado UML.
* Entender el concepto del proceso de creación de software.

#### **¿Qué es un modelo?**
<p style="text-align: justify;">
Un modelo, es una representación de algo, en cierto medio (Papel, pantallas, maquetas, etc.), que capta los aspectos principales, ignorando los menos importantes o que no aporten información relevante. Un modelo en un sistema de software está expresado mediante UML.
</p>

#### **¿Qué es UML?**
<p style="text-align: justify;">
UML (Unified Modeling language), es un **lenguaje** de modelado unificado, que surge a finales de la década de los 80 y principios de los 90. Entre los años 94 y 96, Grady y Jim e Ivar, conocidos como; "los tres amigos", crearon finalmente UML. Resultado de un trabajo iterativo y gradual, que pone a nuestra disposición, una norma construida sobre muchas ideas y contribuciones realizadas (unificadas), por numerosos individuos y compañías de la comunidad de la orientación a objetos.  
**UML es un lenguaje y no una metodología**, esto suele causar confusiones. Las _metodologías_ poseen un lenguaje y un proceso para modelar. En este caso; el lenguaje de modelado es la notación (gráfica), de la que se valen las metodologías para expresar los diseños.
<p>

#### **Breve historia.**  
<p style="text-align: justify;">
En el año 1980, el paradigma de la orientación a objetos; ya no era parte solamente del contexto científico, en vez de ello, se encontraba ya en uso "cotidiano" en lenguajes que comenzaron a ser ampliamente utilizados como `Smalltalk`, dando paso a la creación de nuevos lenguajes basados en en la _POO_., como es el caso de `C++`. Antes de que todo esto ocurriera, ya existían diferentes tipos de metodologías para representar el diseño de un _software_ utilizando la _programación procedural_; pero ahora había que lograr el mismo éxito en la POO. Entre los años 90 y el 98, muchas fueron las organizaciones que intentaron llegar a un estándar unificado; pero finalmente "los tres amigos", y, su versión 1.1 de UML fueron los ganadores. Tal fue su éxito, que hasta el día de hoy seguimos usando UML como el lenguaje, para representar el diseño de artefactos de nuestras aplicaciones.
</p>

#### **¿Qué tan rigurosos debemos ser, a la hora de implementar este lenguaje?**  
<p style="text-align: justify;">
El propósito de UML es ser una herramienta, y, como tal, se debe tener en cuenta que su estricta utilización, irá directamente relacionada con el contexto en el que se esté trabajando, por ejemplo, si estamos trabajando en una herramienta, que a partir de los modelos que se creen con UML, se genere código de forma automatizada. Es en este caso, donde usaremos UML de forma rigurosa, para que el código generado sea el que se necesita.  
En el caso que se desee utilizar UML en el contexto de una reunión en la que se desee entender un problema y donde los modelos diseñados no sean documentados formalmente (por ejemplo en una pizarra en una reunión con el cliente), podemos entonces usar UML con mayor libertad, sin dar tanta importancia a los detalles, sino que basta con que expliquen el problema de una forma global. En este tipo de casos debemos usar lo mínimo que nos aporte una mejor interpretación del problema que se desea resolver. Existen ocasiones en que la notación oficial puede llegar a estorbar, en estos casos no hay que dudar en adaptar el lenguaje a las necesidades personales. Quizás puede ser mal visto el que no estemos usando UML con todas sus sutilezas; pero en este caso ganamos flexibilidad y mientras la comunicación no se vea afectada, no existe mayor problema en alterar un poco este lenguaje. Hay que tener cuidado al momento de adaptarlo, no nos podemos exceder, ya que el diferir mucho la estructura oficial, puede resultar en que no se comprenda lo que se desee expresar.
</p>

#### **¿Qué debemos preguntarnos antes de usar UML?**  
<p style="text-align: justify;">
Ya se ha mencionado que UML lo usamos como una herramienta, y para que lo sea, tenemos que asegurarnos, que la utilización de este lenguaje **sea útil**. Después de todo, los diagramas que realizamos pueden ser visualmente atractivos; pero ningún cliente va a agradecer la belleza de los diseños que hemos generados con UML; lo que los clientes, usuarios, stakeholders, etc. quieren son aplicaciones que funcionan. Es por todo esto, que al momento de utilizar UML, debemos hacernos la siguiente pregunta: ¿Cuál será el beneficio de utilizarlo? y ¿Cómo su uso ayudará al momento de implementar el código?. Si estas preguntas no tienen una respuesta clara. Entonces, quizás el uso de modelos construidos con UML, no generan un real aporte, que justifiquen su utilización.
</p>

#### **UML y los paradigmas de programación.**
<p style="text-align: justify;">
 El reconocido empresario de las tecnologías de la información `Tom Hadfield`, quien a la edad de doce años, creó junto a su padre `socckernet (1994)`, sitio que fue vendido a ESPN en 40 millones de dólares dice:
</p>

> los lenguajes de objetos, permiten ventajas pero no las proporcionan. Para aprovechar estas ventajas hay que realizar el infame cambio de paradigma. (¡Sólo asegúrese de estar sentado al momento de hacerlo!)  

<p style="text-align: justify;">
La mayoría de las personas que podían reconocer la programación en esos años e incluso en ahora, la asocia al paradigma de la programación imperativa. Antes de que el mundo comenzara a utilizar la POO de forma natural, se utilizaba la programación procedural, y esto era lo usual, lo que sabíamos, por tanto, un cambio en el paradigma suponía un esfuerzo que queda reflejado en la frase de Hadfield. Entonces estamos ante una herramienta que nos permite modelar,  y por ejemplo, por medio de un <code>framework</code> llevaríamos rápidamente a código los diagramas que hemos diseñado, si están correctamente diseñados por supuesto. Todo esto gracias a que UML fue concebido para la POO. Entonces, ¿en qué situación nos encontramos ahora?. Se podría afirmar que un "nuevo" paradigma emerge, el paradigma de la programación declarativa, todo esto debido a que lenguajes como <code>javascript</code>, que toma fuerza en la cantidad de aplicaciones que existentes o que se estén desarrollando; pero hay que mencionar que este lenguaje, es un lenguaje funcional (hija del paradigma declarativo), y, además es un lenguaje imperativo. Entonces nos encontramos ante una mezcla de lo que es programación funcional y programación orientada a objetos. Quizás debamos comenzar a comprender que esta mezcla de paradigmas puede coexistir y debemos acostumbrarnos a ello, verlo como una nueva forma de construir, y, no verlo como un dolor de cabeza, hasta que nos acostumbremos a su uso. UML nos seguirá sirviendo para representar gráficamente problemas; pero quizás el enfoque cambie un poco, hacia la utilización de nuevas herramientas que mezcle lo funcional con lo orientado a objetos. Verán que en librerías como _React js_ ya utiliza esta mezcla de paradigmas y que cada nueva versión de Java, incluye muchas herramientas que permiten usar la programación funcional. Como sea que termine esta história, UML aún nos entrega una interfaz entre lo que es abstracto y lo que podríamos llamar tangible.
</p>

#### **El proceso de desarrollo de software.**

<p style="text-align: justify;">
UML, es un lenguaje para modelar, por eso no asume la noción de un proceso; pero para poder realizar un buen desarrollo, hay que analizar el propio proceso de desarrollar aplicaciones.  
</p>

Una visión del desarrollo en su nivel más alto sería como la que muestra la figura 1.1.

<center>![Proceso de desarrollo de software](img/procesoDesarrollo.png)</center>
<center>Figura 1.1: Proceso de desarrollo de software.</center>
<p style="text-align: justify;">
Durante la concepción, se establece la razón de ser del proyecto, además del alcance del mismo. Es en esta etapa en donde se define si el proyecto se realiza o no.
</p>

<p style="text-align: justify;">
En la elaboración, se detallan más profundamente los requerimientos, para así llegar a confeccionar una arquitectura base. Los diseños utilizados han de ser de alto nivel, es decir, sin gran nivel de detalle, destacando solamente lo principal. Dependiendo del nivel de <code>agilidad</code> del proyecto, esta etapa puede ser desde una reunión de un par de horas, hasta una entrega de documentos formales, con iteraciones. Al finalizar esta etapa, las preguntas: ¿Qué es lo que va a construir en realidad?, ¿Cómo lo va a construir?, ¿Qué tecnología empleará?, deben ser contestadas.
</p>

<p style="text-align: justify;">
En la construcción, como se indica en la figura 1.1, la iteración es clave. No quiere decir que el las otras etapas no se pueda iterar; pero en esta etapa, cada iteración es un mini proyecto. Terminando con una demostración funcional al stakeholder. Con ello reducimos el riesgo, ya que si algo no ha salido como se quería, solamente está en juego la iteración y no el proyecto completo. La funcionalidad será incremental y la construcción de código será iterativa. 
¿Cuándo se debe usar el desarrollo iterativo?  
</p>

> El desarrollo iterativo únicamente se debe utilizar en aquellos proyectos que se quiere que tengan éxito.

<p style="text-align: justify;">
Todas las técnicas de UML son útiles durante esta etapa; pero hay que ser cuidadosos, de no excedernos, como dice la siguiente cita:
</p>

> Los memorandos cuidadosamente escritos y seleccionados, pueden sustituir con toda facilidad a la tradicional documentación detallada del diseño. Esta última es sobresaliente en pocas ocasiones, excepto en algunos puntos aislados. Destaque estos puntos... y olvídese del resto.. "Ward Cunningham (1996)"

<p style="text-align: justify;">
Durante la transición, no se hacen desarrollos para añadir funciones nuevas (a menos que sean pequeñas y absolutamente indispensables). Ciertamente, sí hay desarrollo para depuración. Un buen ejemplo de una fase de transición es el tiempo entre la liberación beta y ]a liberación definitiva del producto.
</p>

#### **Tipos de diagramas en UML.**  

<p style="text-align: justify;">
No existe una línea que divida claramente UML; pero podemos reconocer los diferentes tipos de diagramas, para poder apreciar el aspecto del sistema que se intenta representar.  
</p>

Tipos Estructurales  

* **Diagrama de clases.**
* Diagrama de paquetes.
* Diagrama de objetos.
* Diagrama de componentes.
* Diagrama de estructura compuesta.
* Diagrama de despliegue.

Tipos comportamiento.  

* Diagrama de actividad.
* **Diagrama de secuencia.**
* **Diagrama de casos de uso.**
* Diagrama de estado.
* Diagrama de comunicación.
* Diagrama de interacción.
* Diagrama de sincronización.

<p style="text-align: justify;">
Los diagramas que están destacados, se detallarán en los capítulos posteriores. Esto no se debe a que los demás no sirvan o sean menos importantes, más bien, se trata de poder utilizar lo mejor de UML, para resolver la mayoría de los problemas de diseño de software.  
</p>

> *"De verdad, sólo necesitas un 20% del UML, para modelar el 80% del diseño que necesitarás en un proyecto – ágil o no".* - *Grady Booch.*

---
## **Capítulo 2: Los casos de uso.**
---
### **2.1 Competencias esperadas.**
* Comprender el concepto de casos de uso.
* Construir caso de uso.
* Identificar los casos de uso, para una problemática y representarla con la notación UML.

### **2.2 Introducción.**
<p style="text-align: justify;">
Durante mucho tiempo, cuando era utilizado el paradigma procedural de forma popular, incluso cuando la POO comenzaba a ser muy conocida y utilizada. Los escenarios eran representados de forma muy rústica. las personas se auxiliaban de escenarios típicos que les ayudaban a comprender los requerimientos. Muchas veces se construían; pero no se documentaban, Ivar Jacobson, uno de los tres creadores de UML, elevó la visibilidad del caso de uso (su nombre para un escenario) a tal punto, que lo convirtió en un elemento primario de la planificación y el desarrollo de proyectos de software.
</p>

### **2.3 Diagramas de casos de uso.**
<p style="text-align: justify;">
En el año 1994, Jacobson no solo logró introducir los casos de uso como un concepto para ayudar en los primeros pasos del desarrollo de aplicaciones, además, desarrollo una representación gráfica de este hecho y lo llamó El <strong>Diagrama de Casos de Uso</strong>, y este diagrama ahora forma parte de UML.
</p>

Una representación de un diagrama de casos de uso sería el siguiente:  


<center>![Proceso de desarrollo de software](img/cuBasic.png)</center>
<center><small>Figura 2.1: Diagrama de casos de uso básico.</small></center>  

#### **2.3.1 Casos de uso (CU)**
<p style="text-align: justify;">
Un caso de uso es, en esencia, una <strong>interacción típica entre un usuario y un sistema de software</strong>. considere la aplicación con la que se escriben estas líneas que usted lee. Dos casos de uso típicos serían "poner una parte del texto en negritas" y "Borrar el texto seleccionado". Por medio de estos ejemplos, se puede uno dar una idea de ciertas propiedades de los casos de uso.  
</p>

<center>![Proceso de desarrollo de software](img/CU.png)</center>
<center><small>Figura 2.2: Notación de un caso de uso.</small></center>



* Capta alguna función visible para el usuario.
* Puede ser pequeño o grande.
* Logra un objetivo discreto para el usuario.

<p style="text-align: justify;">
Usualmente, el caso de uso se extrae de las interacciones, que los potenciales usuarios del sistema tengan con la aplicación que se desee construir. Cada una de estas, se debe abordar de forma discreta, darle un nombre y escribir una breve descripción. No hay que detallar tan profundamente esta interacción, todo esto dependiendo de la cantidad de ramificaciones, de las que esté compuesto el caso de uso, se podrá más adelante obtener mayores detalles que pueden resultar en nuevos casos de uso.
</p>

**Objetivos del usuario vs interacciones con el sistema:**
<p style="text-align: justify;">
Cuando se están tomando los requerimientos, a veces es fácil confundirse entre los objetivos que el usuario tiene y las <strong>interacciones que hará con el sistema</strong>. Supongamos el desarrollo de un sistema de ventas. Surgirán interacciones como: "Ingresar un producto", "actualizar precio". etc. Esto difiere de los objetivos que pueda tener el usuario como, "mantener la información de los precios actualizada", "Garantizar que esté disponible la información de los productos". En ambos casos tenemos requerimientos del usuario, pero la granularidad es diferente, ya que las interacciones son más sencillas de implementar que los objetivos. Cuando estamos reuniendo los casos de uso del sistema, debemos mantener una granularidad más o menos similar, es decir, el nivel de detalle y complejidad de cada caso de uso, debe ser similar. Finalmente como lo definimos, mantendremos el foco de la captura de los casos de uso, centradas en las interacciones, sin perder de vista los objetivos, en el caso que sólo tengamos los objetivos del usuario, debemos granular esta información, en interacciones necesarias para que se cumplan los objetivos.
Como recomendación, es bueno tener varios casos de uso por objetivo, al menos los objetivos principales, ya que en las iteraciones que vayamos haciendo, se recibe mucho mejor que el usuario vea como se van cumpliendo sus objetivos (aunque lo más probable es que estos objetivos vayan evolucionando a medida que el sistema avanza).
</p>

#### **2.3.2 Actores**
<p style="text-align: justify;">
Empleamos el término actor para llamar así al usuario, cuando desempeña ese papel con respecto al sistema. Los actores llevan a cabo casos de uso. Un mismo actor puede realizar muchos casos de uso; a la inversa, un caso de uso puede ser realizado por varios actores. <strong>No es necesario que los actores sean seres humanos</strong>, a pesar de que los actores estén representados por figuras humanas. El actor puede ser también un sistema externo que necesite cierta información del sistema actual
</p>

<center>![Proceso de desarrollo de software](img/actor.png)</center>
<center><small>Figura 2.3: Notación de un actor.</small></center>

#### **2.3.3 Relaciones**
 UML define cuatro tipos de relaciones en los diagramas de casos de uso:

**Comunicación**

Esta relación es la que más veremos en los CU, como estereotipo se representa por <code> <<communicate>> </code>; pero generalmente este estereotipo no va escrito. Es una relación de asociación que nos muestra la interacción entre un actor y el caso de uso.

<center>![Proceso de desarrollo de software](img/CUASS001.png)</center>
<center><small>Figura 2.4: Relación de comunicación de asociación.</small></center>













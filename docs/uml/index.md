# UML

# Lectura

### ¿Qué es UML?
UML (Unified Modeling language), es un **lenguaje** de modelado unificado, que surge a finales de la década de los 80 y principios de los 90. Entre los años 94 y 96, Grady y Jim e Ivar, conocidos como; "los tres amigos", crearon finalmente UML. Resultado de un trabajo iterativo y gradual, que pone a nuestra disposición, una norma construida sobre muchas ideas y contribuciones realizadas (unificadas), por numerosos individuos y compañías de la comunidad de la orientación a objetos.  
**UML es un lenguaje y no una metodología**, esto suele causar confusiones. Las metodologías poseen un lenguaje y un proceso para modelar. En este caso; el lenguaje de modelado es la notación (gráfica), de la que se valen las metodologías para expresar los diseños.

### Breve história.
En el año 1980, el paradigma de la orientación a objetos; ya no era parte solamente del contexto científico, en vez de ello, se encontraba ya en uso "cotidiano" en lenguajes que comenzaron a ser ampliamente utilizados como `Smalltalk`, dando paso a la creación de nuevos lenguajes basados en en la POO., como es el caso de `C++`. Antes de que todo esto ocurriera, ya existían diferentes tipos de metodologías para representar el diseño de un software escrito proceduralmente; pero ahora había que lograr el mismo éxito en los lenguajes orientados a objetos. Esto motivó al desarrollo de un lenguaje que sea capaz de representar los diseños de las soluciones basadas en la POO. Entre los años 90 y el 98, muchas fueron las organizaciones que intentaron llegar a un estándar unificado; pero finalmente "los tres amigos", y, su versión 1.1 de UML fueron los ganadores. Tal fue su éxito, que hasta el día de hoy seguimos usando UML como el lenguaje, para representar el diseño de artefactos de nuestras aplicaciones.

### ¿Qué tan rigurosos debemos ser, a la hora de implementar este lenguaje?  
El propósito de UML es ser una herramienta, y, como tal, se debe tener en cuenta; que su estricta utilización irá directamente relacionada con el contexto en el que se esté trabajando, por ejemplo, si estamos trabajando en una herramienta, que a partir de los modelos que se creen con UML, se genere código de forma automatizada. Es en este caso, donde usaremos UML de forma rigurosa, para que el código generado sea el que se necesita.  
En el caso que se desee utilizar UML en el contexto de una reunión en la que se desee entender un problema y donde los modelos diseñados no sean documentados formalmente (por ejemplo en una pizarra en una reunión con el cliente), podemos entonces usar UML con mayor libertad, sin dar tanta importancia a los detalles, sino que basta con que expliquen el problema de una forma global. En este tipo de casos debemos usar lo mínimo que nos aporte una mejor interpretación del problema que se desea resolver. Existen ocasiones en que la notación oficial puede llegar a estorbar, en estos casos no hay que dudar en adaptar el lenguaje a las necesidades personales. Quizás puede ser mal visto el que no estemos usando UML con todas sus sutilezas; pero en este caso ganamos flexibilidad y mientras la comunicación no se vea afectada, no existe mayor problema en alterar un poco este lenguaje. Hay que tener cuidado al momento de adaptarlo, no podemos excedernos, ya que el diferir mucho la estructura oficial, puede resultar en que no se comprenda lo que se desee expresar.

### ¿Qué debemos preguntarnos antes de usar UML?
Ya se ha mencionado que UML lo usamos como una herramienta, y para que lo sea: debemos asegurarnos que la utilización de este lenguaje sea útil. Después de todo, los diagramas que realizamos pueden ser visualmente atractivos; pero ningún cliente va a agradecer la belleza de los diseños que hemos generados con UML; lo que los clientes, usuarios, stakeholders, etc. quieren son aplicaciones que funcionan. Es por todo esto que a la hora de utilizar UML debemos preguntarnos: ¿Cuál será el beneficio de utilizarlo? y ¿Cómo su uso ayudará al momento de implementar el código?. Si estas preguntas no tienen una respuesta clara. Entonces, quizás el uso de modelos construidos con UML, no generan un real aporte, que justifiquen su utilización.

### UML y el paradigma de la orientación a objetos.
Un paradigma según la rae es lo siguiente: 
> "Teoría o conjunto de teorías cuyo núcleo central se acepta sin cuestionar y que suministra la base y modelo para resolver problemas y avanzar en el conocimiento"  

Es decir, si el problema es desarrollar, tratando de reutilizar el máximo de código posible y la orientación a objetos resuelve dicho problema, hablamos entonces del paradigma de orientación a objetos.  
El reconocido empresario de las tecnologías de la información `Tom Hadfield`, quien a la edad de doce años, creó junto a su padre `socckernet`, sitio que fue vendido a ESPN en 40 millones de dólares dice:

> los lenguajes de objetos permiten ventajas pero no las proporcionan. Para aprovechar estas ventajas hay que realizar el infame cambio de paradigma. (¡Sólo asegúrese de estar sentado al momento de hacerlo!)  








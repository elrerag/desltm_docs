
---
# LECTURA
---

## Componentes de la unidad
---

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
* Ingeniería del software: un enfoque práctico séptima edición- Pressman · MC Graw-Hill
* [https://www.smartdraw.com/uml-diagram/](https://www.smartdraw.com/uml-diagram/)
* [https://ingenieriadesoftware.es/opiniones-lenguaje-uml-20-anos/](https://ingenieriadesoftware.es/opiniones-lenguaje-uml-20-anos/)
* [https://www.uml.org](https://www.uml.org)


### **Glosario**  

* __Agilidad__  
<p style="text-align: justify">
  Se refiere a la __flexibilidad__ que posee un proyecto, es decir, que pueda cambiar y que esto no produzca un alto impacto en el esfuerzo.
</p>

* __Aplicación__  
<p style="text-align: justify">
  Es un tipo de software que permite al usuario realizar uno o más tipos de trabajo.
<p>

* __Cliente__  
<p style="text-align: justify">
  En el contexto de la toma de requerimientos, es el ente que paga por el producto.
</p>

* __Framework__  
<p style="text-align: justify">
  Un marco de trabajo, o framework, es una estructura real o conceptual destinada a servir de soporte o guía para la construcción de algo que expande la estructura en algo útil. Para nuestro caso, es mejor que lo veamos como un software pre construido, al que le podemos ir adicionando piezas según sus reglas, con la finalidad obtener un producto personalizado a nuestras necesidades.
</p>

* __Granularidad__
<p style="text-align: justify;">
  Representa el nivel de detalle con el que se desea modelar la información sobre el negocio que se esté analizando.
</p>

* __Metodología__  
<p style="text-align: justify">
  Grupo de mecanismos o procedimientos racionales, empleados para el logro de un objetivo.
</p>

* __Notación__  
<p style="text-align: justify">
  Es la acción y efecto de notar, hace referencia al sistema de signos convencionales que se adopta, para expresar algún concepto.
</p>

* __Paradigma__  
<p style="text-align: justify">
  Teoría o conjunto de teorías, cuyo núcleo central se acepta sin cuestionar y que suministra la base y modelo   para resolver problemas y avanzar en el conocimiento.
</p>

* __Patrón__  
<p style="text-align: justify">
  Hechos o cosas recurrentes. Estos se repiten con previsibilidad, por lo tanto, pueden funcionar como modelo para producir determinada cosa a partir de ellos.
</p>

* __Patrón de diseño de modelo-vista-controlador (MVC)__  
<p style="text-align: justify">
  Especifica que una aplicación consta de tres capas: La primera es el modelo de datos, que es la capa con la responsabilidad de la gestión de los datos, luego tenemos la capa de presentación, es lo que el usuario ve, es decir, la vista. La forma en que la información sea presentada al usuario, son responsabilidad de esta capa, por último, tenemos la capa del controlador, que es la capa encargada de orquestar o controlar, la interacción de las dos capas anteriormente mencionadas.
</p>

* __Programación declarativa__  
<p style="text-align: justify">
  Es un paradigma de la programación, en la que los programas se describen en términos de proposiciones y afirmaciones, que son __declaradas__, en donde los pasos para resolverlo, no impera. En este tipo de programación, nos encontraremos mucha recursividad.
</p>

* __Programación Funcional__  
<p style="text-align: justify">
  Es un paradigma que pertenece a la programación declarativa, basado en el trabajo de Alonzo Church y Stephen Kleene en la década de 1930, llamado: El Cálculo Lambda; este paradigma se compone de funciones que deben cumplir ciertas reglas (por ejemplo, que sean funciones puras). en donde encontraremos formas recursivas de por ejemplo, trabajar con arreglos como lo son: `map`, `reduce` o `filter`. La principal diferencia con la programación orientada a objetos, es que la programación funcional, no posee estados.
</p>

* __Programación Imperativa__:  
<p style="text-align: justify">
  En este paradigma de la programación, que, como su nombre lo indica, __imperan las instrucciones, condiciones o pasos__ indicamos exactamente, lo que el programa debe hacer. Típicamente nos encontraremos con estructuras cíclicas tales como: while, for. También condicionales if o switch. Lo que no quiere decir que si un programa posee estas instrucciones es puramente imperativo. Podemos reconocer este tipo de programación cuando leemos el código y su traza es una interpretación de lectura secuencial de lo que está escrito.
</p>

* __Programación Orientada a Objetos (POO)__  
<p style="text-align: justify">
  Este paradigma, es un tipo de programación imperativa, que mediante algunas técnicas (por ejemplo la herencia), resuelve algunas falencias que existían en la __programación procedural__ (por ejemplo la reutilización de código), utilizando objetos, cada uno de ellos, compuestos por un estado (datos) y un comportamiento.
</p>

* __Programación procedural__  
<p style="text-align: justify">
  Se trata de un estilo de programación imperativa, basado en estructurar el código de un programa en componentes, que reciben el nombre de procedimientos, subrutinas o funciones.
</p>

* __Software__  
<p style="text-align: justify">
  Conjunto de programas, instrucciones y reglas informáticas que permiten ejecutar distintas tareas en una  computadora.
</p>

* __Stakeholder__  
<p style="text-align: justify">
  Es quien sostiene la estaca, todo aquél se se ve afectado por el producto y/o proyecto.
</p>

* __Usuario__  
<p style="text-align: justify">
  Es quien usa el producto.
</p>

---
## **Capítulo 1 - Introducción a UML.**
---

### **1.1 - Competencias esperadas.**
* Conocer el lenguaje de modelado unificado (UML).
* Conocer los distintos tipos de diagramas.
* Reconocer el paradigma de la programación en el que está basado UML.
* Entender el concepto del proceso de creación de software.

### __1.2 - Introducción__  

<p style="text-align: justify">
Los tres amigos. Quizás esta poca ortodoxa forma de llamar a los creadores de una de las mayores innovaciones conceptuales de los últimos tiempos, nos parezca algo alejado a lo que estamos acostumbrados; pero la misión de la creación de tecnología tiene ese propósito. Estos "amigos" quizás no pensaron que basándose en el trabajo que realizaron mientras el último respiro del pasado siglo los acompañaba; se han creado estándares que ya son oficiales. Quizás hemos sido testigos de la aplicación de UML en varios "bocetos" abandonados en pizarras llenas de sueños, que, tal vez llegaron a ser realidad. Puede que hasta lo hayamos utilizado sin darnos cuenta, o para aquellos con más experiencia; puede que lo sigan utilizando de forma profesional. UML no solo nos crea una interfaz entre lo que se piensa y lo que se hace, si no que además, ayuda no solo a la industria de software, sino, en general, de cualquier industria que utilice modelos. Cualquiera que sea el uso que se le esté dando a UML, deben saber estos, amigos; que su trabajo sigue estando vigente, tal vez no completamente en la forma que pensaron en un principio; pero nos sigue ayudando a enfocarnos en construir en lugar de reconstruir.
</p>

&nbsp;
<center>![requerimientos](img/introimg1.png)</center>
<center><small>Figura 1.1 - Comprensión de lo que de requiere desarrollar.</small></center>  
&nbsp;

### __1.3 - Algunas definiciones__  

* __1.3.1 ¿Qué es un modelo?__  
<p style="text-align: justify">
  Un modelo, es una representación de algo, en cierto medio (Papel, pantallas, maquetas, etc.), que capta los aspectos principales, ignorando los menos importantes o que no aporten información relevante. Un modelo en un sistema de software está expresado mediante UML.
</p>

&nbsp;
<center>![](img/img002.png)</center>
<center><small>Figura 1.2 - Representación de un modelo.</small></center>  
&nbsp;

* __1.3.2 - ¿Qué es UML?__  
<p style="text-align: justify;">
  UML (Unified Modeling language), es un **lenguaje** de modelado unificado, que surge a finales de la década de los 80 y principios de los 90. Entre los años 94 y 96, Grady y Jim e Ivar, conocidos como; "los tres amigos", crearon finalmente UML. Resultado de un trabajo iterativo y gradual, que pone a nuestra disposición, una norma construida sobre muchas ideas y contribuciones realizadas (unificadas), por numerosos individuos y compañías de la comunidad de la orientación a objetos.  
</p>
<p style="text-align: justify;">
  __UML es un lenguaje y no una metodología__, esto suele causar confusiones. Las _metodologías_ poseen un lenguaje y un proceso para modelar. En este caso; el lenguaje de modelado es la notación (gráfica), de la que se valen las metodologías para expresar los diseños.
</p>

### __1.3 - Un poco de historia.__  
<p style="text-align: justify;">
En el año 1980, el paradigma de la orientación a objetos; ya no era parte solamente del contexto científico, en vez de ello, se encontraba ya en uso "cotidiano" en lenguajes que comenzaron a ser ampliamente utilizados como `Smalltalk`, dando paso a la creación de nuevos lenguajes basados en en la _POO_., como es el caso de `C++` y `Java`. Antes de que todo esto ocurriera, ya existían diferentes tipos de metodologías para representar el diseño de un _software_ utilizando la _programación procedural_; pero ahora había que lograr el mismo éxito en la POO. Entre los años 90 y el 98, muchas fueron las organizaciones que intentaron llegar a un estándar unificado; pero finalmente "los tres amigos", y, su versión 1.1 de UML fueron los ganadores. Tal fue su éxito, que hasta el día de hoy seguimos usando UML como el lenguaje, para representar el diseño de artefactos de nuestras aplicaciones.
</p>

### **1.4 - A la hora de implementar este lenguaje, ¿Qué tan rigurosos debemos ser?**  
<p style="text-align: justify;">
El propósito de UML es ser una herramienta y como tal, se debe tener en cuenta que su estricta utilización, irá directamente relacionada con el contexto en el que se esté trabajando, por ejemplo, si estamos trabajando en una herramienta, que a partir de los modelos que se creen con UML, se genere código de forma automatizada. Es en este caso, donde usaremos UML de forma rigurosa, para que el código generado sea el que se necesita.  
En el caso que se desee utilizar UML en el contexto de una reunión en la que se desee entender un problema y donde los modelos diseñados no sean documentados formalmente (por ejemplo en una pizarra en una reunión con el cliente), podemos entonces usar UML con mayor libertad, sin dar tanta importancia a los detalles, sino que basta con que expliquen el problema de una forma global. En este tipo de casos debemos usar lo mínimo que nos aporte una mejor interpretación del problema que se desea resolver. Existen ocasiones en que la notación oficial puede llegar a estorbar, en estos casos no hay que dudar en adaptar el lenguaje a las necesidades personales. Quizás puede ser mal visto el que no estemos usando UML con todas sus sutilezas; pero en este caso ganamos flexibilidad y mientras la comunicación no se vea afectada, no existe mayor problema en alterar un poco este lenguaje. Hay que tener cuidado al momento de adaptarlo, no nos podemos exceder, ya que el diferir mucho la estructura oficial, puede resultar en que no se comprenda lo que se desee expresar.
</p>

### **1.5 - Antes de usar UML, ¿Qué nos debemos preguntar?**  
<p style="text-align: justify;">
Ya se ha mencionado que UML lo usamos como una herramienta, y para que lo sea, tenemos que asegurarnos, que la utilización de este lenguaje **sea útil**. Después de todo, los diagramas que realizamos pueden ser visualmente atractivos; pero ningún cliente va a agradecer la belleza de los diseños que hemos generados con UML; lo que los clientes, usuarios, stakeholders, etc. quieren son aplicaciones que funcionan. Es por todo esto, que al momento de utilizar UML, debemos hacernos la siguiente pregunta: ¿Cuál será el beneficio de utilizarlo? y ¿Cómo su uso ayudará al momento de implementar el código?. Si estas preguntas no tienen una respuesta clara. Entonces, quizás el uso de modelos construidos con UML, no generan un real aporte, que justifiquen su utilización.
</p>

### **1.6 - UML y los paradigmas de programación.**
<p style="text-align: justify;">
 El reconocido empresario de las tecnologías de la información `Tom Hadfield`, quien a la edad de doce años, creó junto a su padre `socckernet (1994)`, sitio que fue vendido a ESPN en 40 millones de dólares dijo:
</p>  
&nbsp;

> <p style="text-align: justify;">"Los lenguajes de objetos, permiten ventajas pero no las proporcionan. Para aprovechar estas ventajas hay que realizar el infame cambio de paradigma. (¡Sólo asegúrese de estar sentado al momento de hacerlo!)"</p>  

&nbsp;
<p style="text-align: justify;">
La mayoría de las personas que podían reconocer la programación en esos años e incluso ahora, la asocia al paradigma de la programación imperativa. Antes de que el mundo comenzara a utilizar la POO de forma natural, se utilizaba la programación procedural, y esto era lo usual, lo que sabíamos. por esta razón un cambio en el paradigma suponía un esfuerzo que queda reflejado en la frase de Hadfield. Entonces estamos ante una herramienta que nos permite modelar,  y por ejemplo, por medio de un <code>framework</code> llevaríamos rápidamente a código los diagramas que hemos diseñado, si están correctamente diseñados por supuesto. Todo esto gracias a que UML fue concebido para la POO. Entonces, ¿en qué situación nos encontramos ahora?. Se podría afirmar que un "nuevo" paradigma emerge, el paradigma de la programación declarativa, todo esto debido a que lenguajes como <code>javascript</code>, que toma fuerza en la cantidad de aplicaciones que existentes o que se estén desarrollando; pero hay que mencionar que este lenguaje, es un lenguaje funcional (hija del paradigma declarativo), y, además es un lenguaje imperativo. Entonces nos encontramos ante una mezcla de lo que es programación funcional y programación orientada a objetos. Quizás debamos comenzar a comprender que esta mezcla de paradigmas puede coexistir y debemos acostumbrarnos a ello, verlo como una nueva forma de construir, y, no verlo como un dolor de cabeza, hasta que nos acostumbremos a su uso. UML nos seguirá sirviendo para representar gráficamente problemas; pero quizás el enfoque cambie un poco, hacia la utilización de nuevas herramientas que mezcle lo funcional con lo orientado a objetos. Verán que en librerías como _React js_ ya utiliza esta mezcla de paradigmas y que cada nueva versión de Java, incluye muchas herramientas que permiten usar la programación funcional. Como sea que termine esta história, UML aún nos entrega una interfaz entre lo que es abstracto y lo que podríamos llamar tangible.
</p>

&nbsp;
<p style="text-align: justify;">
  En el siguiente ejemplo, se puede ver el uso de estructuras funcionales, dentro del lenguaje Java. En ambos casos el resultado será 3 y 4.
</p>
&nbsp;

```Java
package cl.desafiolatam.ejemplos.padigmas;

import java.util.ArrayList;
import java.util.stream.Collectors;

public class Principal {
	
	public static void main(String[] args) {
        ArrayList<Integer> numeros = new ArrayList<>();
        numeros.add(1);
        numeros.add(2);
        numeros.add(3);
        numeros.add(4);
        
        System.out.println("Resultado imperativo");
        imperativo(numeros);
        
        System.out.println("Resultado funcional");
        funcional(numeros);
		    
	}

	public static void imperativo(ArrayList<Integer> numeros) {
        for(Integer numero: numeros) {
        	if(numero > 2) {
        		System.out.println(numero);
        	}
        }

	}

	public static void funcional(ArrayList<Integer> numeros) {
        numeros.stream().filter(x -> x > 2).collect(Collectors.toList()).forEach(System.out::println); 
	}

}

```

### **1.7 - El proceso de desarrollo de software.**

<p style="text-align: justify;">
UML, es un lenguaje para modelar, por eso no asume la noción de un proceso; pero para poder realizar un buen desarrollo, hay que analizar el propio proceso de desarrollar aplicaciones.  
</p>

Una visión del desarrollo en su nivel más alto sería como la que muestra la figura 1.3.

&nbsp;
<center>![Proceso de desarrollo de software](img/procesoDesarrollo.png)</center>
<center>Figura 1.3 - proceso de desarrollo de software.</center>
&nbsp;

<p style="text-align: justify;">
Durante la <strong>concepción</strong>, se establece la razón de ser del proyecto, además del alcance del mismo. Es en esta etapa en donde se define si el proyecto se realiza o no.
</p>

<p style="text-align: justify;">
En la <strong>elaboración</strong>, se detallan más profundamente los requerimientos, para así llegar a confeccionar una arquitectura base. Los diseños utilizados han de ser de alto nivel, es decir, sin gran nivel de detalle, destacando solamente lo principal. Dependiendo del nivel de <code>agilidad</code> del proyecto, esta etapa puede ser desde una reunión de un par de horas, hasta una entrega de documentos formales, con iteraciones. Al finalizar esta etapa, las preguntas: ¿Qué es lo que va a construir en realidad?, ¿Cómo lo va a construir?, ¿Qué tecnología empleará?, deben ser contestadas.
</p>

<p style="text-align: justify;">
En la <strong>construcción</strong>, como se indica en la figura 1.3, la iteración es clave. No quiere decir que el las otras etapas no se pueda iterar; pero en esta etapa, cada iteración es un mini proyecto. Terminando con una demostración funcional al stakeholder. Con ello reducimos el riesgo, ya que si algo no ha salido como se quería, solamente está en juego la iteración y no el proyecto completo. La funcionalidad será incremental y la construcción de código será iterativa. <strong>¿Cuándo se debe usar el desarrollo iterativo?, El desarrollo iterativo únicamente se debe utilizar en aquellos proyectos que se quiere que tengan éxito.</strong>
</p>

<p style="text-align: justify;">
Todas las técnicas de UML son útiles durante esta etapa; pero hay que ser cuidadosos, de no excedernos, como dice la siguiente cita:
</p>

&nbsp;
> Los memorandos cuidadosamente escritos y seleccionados, pueden sustituir con toda facilidad a la tradicional documentación detallada del diseño. Esta última es sobresaliente en pocas ocasiones, excepto en algunos puntos aislados. Destaque estos puntos... y olvídese del resto.. "Ward Cunningham (1996)"
&nbsp;

<p style="text-align: justify;">
Durante la <strong>transición</strong>, no se hacen desarrollos para añadir funciones nuevas (a menos que sean pequeñas y absolutamente indispensables). Ciertamente, sí hay desarrollo para depuración. Un buen ejemplo de una fase de transición es el tiempo entre la liberación beta y ]a liberación definitiva del producto.
</p>

### **1.8 - La práctica de la ingeniería de software.**

<p style="text-align: justify;">
  Al describir el proceso de desarrollo de software, logramos poder ver las actividades estructurales generales, que son el esqueleto de la arquitectura para el trabajo de ingeniería de software. Con la finalidad de poder tener una mayor comprensión de esta práctica citemos un libro clásico <i>"How to solve it"</i>, escrito antes que existieran las computadoras modernas. Acá <i>George Polya</i>, escribió, sin saberlo, la esencia de la práctica de la ingeniería de software:
</p>

+ Entender el problema (Comunicación y análisis).
+ __Planear la solución (Modelado y diseño del software).__
+ Ejecutar el plan (generación del código).
+ Examinar la exactitud del resultado (probar y asegurar la calidad).

<p style="text-align: justify;">
  Centremos la atención en la planificación de la solución. Luego de entender el problema (o al menos creer que lo entendemos) y no puede contener las ganas de comenzar a desarrollar la solución; debemos realizarnos las siguientes preguntas:
</p>

+ ¿Ha visto antes, problemas similares?
+ ¿Hay patrones reconocibles en una solución potencial?
+ ¿Hay algún software existente que implemente los datos, funciones y características que se requieren?
+ ¿Ha resuelto un problema similar? Si es así, ¿Son reutilizables los elementos de la solución?
+ ¿El problema, se puede dividir en problemas más pequeños? Si es así ¿Hay soluciones evidentes para estos?

<p style="text-align: justify;">
  Por eso, antes de comenzar a implementar la solución o generar modelos usando UML, nos ahorraremos una buena cantidad de tiempo, si tomamos un poco de aire y nos detenemos a respondernos las preguntas ya expuestas.
</p>


### **1.9 - Un poco acerca de requerimientos.**  

<p style="text-align: justify;">
  Los requerimientos son una especificación de lo que debe ser implementado. Estos son descripciones de cómo el sistema se debe comportar, de las propiedades y atributos del mismo. Deben ser una restricción del proceso de desarrollo del sistema. Existen dos clases de requerimientos, los requerimientos funcionales y los no funcionales.
</p>

#### **1.9.1 - Requerimientos funcionales (qué hacer).**

<p style="text-align: justify;">
  Son las descripciones explícitas del comportamiento que debe tener el sistema y qué información debe manejar. Nos muestran las capacidades o cualidades que debe tener el sistema. Se enfoca en cuál debe ser el comportamiento de la solución y qué información debe manejar. Ejemplos de este tipo de requerimientos pueden ser los siguientes:
</p>
+ El sistema deberá ser capaz de generar el reporte anual.
+ Debe ser capaz de ejecutar procesos nocturnos de reportería.
+ Mantendrá los datos de ventas actualizados.
+ Debe disponer de la información detallada de los proveedores.
+ Etc.

__De este tipo de requerimientos, se extraen los casos de uso (Capítulo 2).__
#### **1.9.2 - Requerimientos no funcionales (cómo hacerlo).**

<p style="text-align: justify;">
  Describen eficiencia, seguridad lógica y de datos, usabilidad o cualquier tipo de requerimiento que no se refiera a las funcionalidades del qué se debe hacer. Son aquellos que nos define el como debe efectuar la tarea, en este tipo de descripción entran detalles como el rendimiento de los recursos: 
</p>
+ Los permisos de acceso al sistema podrán ser cambiados solamente por el administrador.
+ El sistema debe ser capaz de operar adecuadamente, con hasta 100.000.000 usuarios con sesiones concurrentes.
+ El tiempo de aprendizaje del sistema por usuario; deberá ser menor a 4 horas.
+ Etc.

### **1.10 - Tipos de diagramas en UML.**  

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

&nbsp;
> <p style="text-align: justify;">"De verdad, sólo requieres un 20% de UML, para modelar el 80%, del diseño que necesitarás en un proyecto – ágil o no". - Grady Booch (2018).</p >
&nbsp;

---
## **Capítulo 2 - Los casos de uso.**
---

### **2.1 - Competencias esperadas.**
* Entender los tipos de requerimientos.
* Comprender el concepto de casos de uso.
* Construir caso de uso.
* Identificar los casos de uso, para una problemática y representarla con la notación UML.

### **2.2 - Introducción.**
<p style="text-align: justify;">
Durante mucho tiempo, cuando era utilizado el paradigma procedural de forma popular, incluso cuando la POO comenzaba a ser muy conocida y utilizada. Los escenarios eran representados de forma muy rústica. las personas se auxiliaban de escenarios típicos que les ayudaban a comprender los requerimientos. Muchas veces se construían; pero no se documentaban, Ivar Jacobson, uno de los tres creadores de UML, elevó la visibilidad del caso de uso (su nombre para un escenario) a tal punto, que lo convirtió en un elemento primario de la planificación y el desarrollo de proyectos de software.
</p>

#### **2.2.1 - Uso de la herramienta StarUml.**
<p style="text-align: justify;">
  Esta herramienta nos permite realizar todos los tipos de diagramas que se explicarán en esta unidad, su uso es libre aunque si lo pagamos tendremos acceso a más opciones, para los que deseen ahondar en el diseño con esta herramienta existen planes mensuales y anuales. Para efectos de uso en la unidad, la versión libre nos será suficiente.
</p>

Para instalar la herramienta, debemos ir a la siguiente URL: [http://staruml.io/download](http://staruml.io/download)

&nbsp;
<center>![diagrama](img/star001.png)</center>
&nbsp;

Descargamos la versión de nuestro sistema operativo e instalamos como cualquier otro programa. 

Una vez instalado podemos entonces comenzar a utilizarlo.

### **2.3 - Diagramas de casos de uso (Cuentan una historia).**
<p style="text-align: justify;">
En el año 1994, Jacobson no solo logró introducir los casos de uso como un concepto para ayudar en los primeros pasos del desarrollo de aplicaciones, además, desarrollo una representación gráfica de este hecho y lo llamó El <strong>Diagrama de Casos de Uso</strong>, y este diagrama ahora forma parte de UML.
</p>

### En la herramienta, nos vamos a model -> add diagram -> Use Case Diagram.

&nbsp;
<center>![casosUso](img/custar.png)</center>
&nbsp;

Una representación de un diagrama de casos de uso sería el siguiente:  

&nbsp;
<center>![diagrama de casos de uso básico.](img/cuBasic.png)</center>
<center><small>Figura 2.1 - diagrama de casos de uso básico.</small></center>  
&nbsp;

#### **2.3.1 - Casos de uso (CU).**
<p style="text-align: justify;">
Un caso de uso es, en esencia, una <strong>interacción típica entre un usuario y un sistema de software</strong>. considere la aplicación con la que se escriben estas líneas que usted lee. Dos casos de uso típicos serían "poner una parte del texto en negritas" y "Borrar el texto seleccionado". Por medio de estos ejemplos, se puede uno dar una idea de ciertas propiedades de los casos de uso.  
</p>

<center>![Notación de un caso de uso.](img/CU.png)</center>
<center><small>Figura 2.2 - notación de un caso de uso.</small></center>



* Capta alguna función visible para el usuario.
* Puede ser pequeño o grande.
* Logra un objetivo discreto para el usuario.

<p style="text-align: justify;">
Usualmente, el caso de uso se extrae de las interacciones, que los potenciales usuarios del sistema tengan con la aplicación que se desee construir. Cada una de estas, se debe abordar de forma discreta, darle un nombre y escribir una breve descripción. No hay que detallar tan profundamente esta interacción, todo esto dependiendo de la cantidad de ramificaciones, de las que esté compuesto el caso de uso, se podrá más adelante, obtener mayores detalles que pueden resultar en nuevos casos de uso.
</p>

* __Objetivos del usuario vs interacciones con el sistema.__
<p style="text-align: justify;">
Cuando se están tomando los requerimientos, a veces es fácil confundirse entre los objetivos que el usuario tiene y las <strong>interacciones que hará con el sistema</strong>. Supongamos el desarrollo de un sistema de ventas. Surgirán interacciones como: "Ingresar un producto", "actualizar precio". etc. Esto difiere de los objetivos que pueda tener el usuario como, "mantener la información de los precios actualizada", "Garantizar que esté disponible la información de los productos". En ambos casos tenemos requerimientos del usuario, pero la granularidad es diferente, ya que las interacciones son más sencillas de implementar que los objetivos. Cuando estamos reuniendo los casos de uso del sistema, debemos mantener una granularidad más o menos similar, es decir, el nivel de detalle y complejidad de cada caso de uso, debe ser similar. Finalmente como lo definimos, mantendremos el foco de la captura de los casos de uso, centradas en las interacciones, sin perder de vista los objetivos, en el caso que sólo tengamos los objetivos del usuario, debemos granular esta información, en interacciones necesarias para que se cumplan los objetivos.
Como recomendación, es bueno tener varios casos de uso por objetivo, al menos los objetivos principales, ya que en las iteraciones que vayamos haciendo, se recibe mucho mejor que el usuario vea como se van cumpliendo sus objetivos (aunque lo más probable es que estos objetivos vayan evolucionando a medida que el sistema avanza).
</p>

#### **2.3.2 - Actores**
<p style="text-align: justify;">
Empleamos el término actor para llamar así al usuario, cuando desempeña ese papel con respecto al sistema. Los actores llevan a cabo casos de uso. Un mismo actor puede realizar muchos casos de uso; a la inversa, un caso de uso puede ser realizado por varios actores. <strong>No es necesario que los actores sean seres humanos</strong>, a pesar de que los actores estén representados por figuras humanas. El actor puede ser también un sistema externo que necesite cierta información del sistema actual. Todos los casos de uso tratan sobre funcionalidad requerida externamente. Si el sistema de contabilidad necesita un archivo, entonces ése es un requerimiento que debe satisfacerse, en donde el actor sería el sistema de contabilidad.
</p>

<center>![Proceso de desarrollo de software](img/actor.png)</center>
<center><small>Figura 2.3 - notación de un actor.</small></center>

#### **2.3.3 - Relaciones**
 UML, define relaciones de estereotipos y generalización. Con estas relaciones, podemos ver gráficamente el como interactúan los casos de uso y los actores, para una mejor comprensión del escenario. A continuación definiremos cada una de ellas.

* __Estereotipo:__ `<<comunicate>>`  
<p style="text-align: justify;">
  Esta relación es la que más veremos en los CU, como estereotipo se representa por <code>&#60;&#60;communicate&#62;&#62;</code>; pero generalmente este estereotipo no va escrito. Es una relación de asociación que nos muestra la interacción entre un actor y el caso de uso.
</p>

<center>![relación de comunicación de asociación](img/CUASS001.png)</center>
<center><small>Figura 2.4 - relación de comunicación de asociación.</small></center>

* __Estereotipo:__ `<<include>>`
<p style="text-align: justify;">
  En términos muy simples, cuando relacionamos dos casos de uso con un “include”, estamos diciendo que el primero (el caso de uso base) incluye al segundo (el caso de uso incluido). Es decir, el segundo es parte esencial del primero. Sin el segundo, el primero no podría funcionar bien; pues no podría cumplir su objetivo.
</p>

&nbsp;
<center>![relación de inclusión](img/CUinclude.png)</center>
<center><small>Figura 2.5 - relación de inclusión.</small></center>
&nbsp;

* __Estereotipo:__ `<<extend>>`
<p style="text-align: justify;">
  Un caso de uso puede tener una extensión que no sea indispensable, pero sería bueno para la comprensión de lo que se desea desarrollar, que esta extensión sea expresada en el diagrama, es en este caso (no abusar), en donde haremos esta relación. Es decir, <strong>el caso de uso base, puede funcionar perfectamente, si no se realiza el caso de uso del cual extiende.</strong>  
  Notamos en la figura 2.6, que la dirección de la flecha es en otro sentido, esto se debe a que así es la notación de la relación de extensión, el sentido va desde el caso de uso que se extiende, hasta el caso de uso que la consume.  
</p>
<p style="text-align: justify;">
  Debemos tener muy claro que esta extensión, no tiene que ver con la técnica de herencia en el paradigma de orientación a objetos, la relación de extensión y la herencia, son dos cosas completamente distintas, ya que se encuentran en contextos diferentes a pesar de su similitud en sus denominaciones.
</p>

&nbsp;
<center>![relación de extensión](img/CUextend.png)</center>
<center><small>Figura 2.6 - relación de extensión.</small></center>  
&nbsp;

* __Generalización__  
<p style="text-align: justify;">
  Cuando hablamos de generalización, esta vez sí que nos estamos refiriendo, a algo muy parecido de lo que hace la herencia en la orientación a objetos, pero esta vez en el contexto de comprender el escenario. Cuando creamos a un actor y un caso de uso, si este caso de uso es una abstracción de otros casos de uso o el actor también podría ser una abstracción de muchos otros actores, podemos aplicar la generalización (otra vez, sin abusar). Así, si el "padre" contiene muchas cosas que un "hijo" que hace lo mismo pero más especializada, esta relación nos sería útil.
</p>

&nbsp;
<center>![Uso de la generalización](img/CUGeneraliza.png)</center>
<center><small>Figura 2.7 - uso de la generalización.</small></center>  
&nbsp;

* __Evitar abusos en la granularidad.__
<p style="text-align: justify;">
  Se debe tener presente que no hay que abusar del uso de estas relaciones, ya que se suele pensar que si el caso de uso se compone de varias piezas, estas deben ser expresadas en el diagrama. Hay que recordar que UML, es un lenguaje que lo utilizamos como herramienta, para lograr una mejor comprensión de lo que se debe desarrollar, complicarlo con complejos diagramas no es el objetivo. Es por eso que no haremos cosas como lo que se representa en la figura 2.8, y, nos enfocaremos siempre en lo suficientemente importante para la comprensión del escenario al que estamos representando, se podría tomar como referencia y sobre todo en un contexto ágil, que el diseño del escenario del caso de uso, cuando se implemente, no debería superar las tres semanas de desarrollo y que se trate solamente de aquellos detalles importantes para lograr que se cumplan estos plazos mentales.
</p>

&nbsp;
<center>![abuso de granularidad](img/CUAbuso.png)</center>
<center><small>Figura 2.8 - abuso de granularidad.</small></center>  
&nbsp;

### **2.4 Ejemplos.**

<p style="text-align: justify;">
A continuación, veremos direferentes ejemplos de diagramas de casos de uso, estos diagramas, pueden ser representados de diferentes maneras, siempre y cuando, se pueda comprender el escenario que se desea representar. Es por eso que las respuestas a estas preguntas no son únicas. Se recomienda diseñar los diagrámas de la forma más sencilla posible.
</p>

#### **Ejemplo 1.**

<p style="text-align: justify;">
Diseñar un diagrama de casos de uso, que exprese el escenario de una máquina expendedora de bebidas.
</p>

Solución:  

Lo primero que podemos identificar son los actores que interactúan en este escenario:

* Usuario
* Proveedor

El usuario puede comprar el producto y el proveedor se encarga de retirar el dinero además de mantener la máquina con suficientes productos. Concluimos entonces que el escenario posee los siguientes Casos de Uso.

* Comprar producto.
* Recolectar dinero.
* Reponer productos.

Luego el Diagrama de Casos de Uso, sería el siguiente:  

&nbsp;
<center>![casos de uso include](img/EJERCU001.png)</center>
&nbsp;

#### **Ejemplo 2.**

Diseñar un diagrama de casos de uso, que exprese el escenario que responde a los siguientes requerimientos:

* Un juego de teléfono móvil donde participan dos jugadores cada uno con su propia terminal.

* Cuando dos jugadores desean jugar, uno de ellos crea una nueva partida y el otro se conecta.

* El objetivo del juego es manejar una nave y disparar al contrario. Si uno de los dos jugadores acierta, la partida termina.

* Si uno de los dos jugadores deja la partida (o se pierde la conexión) la partida termina.


Solución:  

Al igual que en el ejemplo anterior, debemos reconocer a los actores involucrados. Estos serían los siguientes:

* Terminal servidor, este se encarga de crear la partida.
* Terminal cliente, encargado de unirse a la partida que se ha creado

Podemos ver que ambos pueden dar término a la partida por tanto se concluyen los siguientes Casos de Uso.

* Crear partida.
* Unirse a la partida, necesita que la partida esté creada.
* Terminar partida, necesita que la partida esté creada.

Resultando en el siguiente Diagrama de Casos de Uso:

&nbsp;
<center>![casos de uso include](img/EJERCU002.png)</center>
&nbsp;

#### **Ejemplo 3.**

Diseñar un diagrama de casos de uso, que exprese el escenario que responde a un sistema de ventas de entradas online.


Solución:  

En este caso no disponemos de mucha información acerca de lo que se tiene que diseñar, excepto que es un sistema de ventas. Así que debemos usar la imaginación de un escenario típico.

Este tipo de sistema debería tener un usuario, este, tendría la opción de comprar una entrada. Quizás podría registrarse como socio. Como un actor no humano, tendríamos el sistema de pago, que usualmente debería ser un servicio aparte del sistema, ya que no es nuestra responsabilidad cumplir con el nivel que necesita una transacción monetaria. Finalmente necesitamos a alguien que revise las ventas realizadas. De esto podemos obtener los siguientes, Casos de Uso.

* Comprar entrada. (necesita cobrar).
* Cobrar.
* Registrarse como socio, opcional.
* Revisar ventas.

Como resultado de lo anterior, se obtiene el siguiente Diagrama de Casos de Uso:

&nbsp;
<center>![casos de uso include](img/EJERCU003.png)</center>
&nbsp;


---
## **Capítulo 3 - Diagramas de secuencia.**
---

### **3.1 - Competencias esperadas.**
* Tener nociones de la vista de interacción.
* Conocer el concepto de los diagramas de secuencia.
* Conocer el papel de los roles y los mensajes.
* Construir diagrama de secuencia.
* Eficiencia en la construcción de los diagramas de secuencia.

### **3.2 - Introducción.**
<p style="text-align: justify;">
  Extraer los casos de uso de una aplicación por medio de los requerimientos funcionales de un usuario, parece ahora una tarea simple. Pero ¿qué pasa con su comportamiento?. Tenemos las interacciones que asumimos que tienen los actores con el sistema; pero es posible analizar esas interacciones con un poco más de detalle para poder interpretar si el comportamiento que se pensó o se piensa, sea el correcto.
</p>

#### __3.3 - Diagrama de secuencia.__

<p style="text-align: justify;">
En UML, existe la llamada "Vista de interacción", describe secuencias de intercambios de mensajes entre los <code>roles</code> que implementan el comportamiento del sistema. Esta visión proporciona una vista integral del comportamiento del sistema, es decir, muestra el flujo de control  a través de muchos objetos, este tipo de vista se expresa en dos diagramas, el diagrama de colaboración y el diagrama que veremos a continuación: El diagrama de secuencia.
</p>

<p style="text-align: justify;">
Un diagrama de secuencia, muestra un conjunto de mensajes, dispuestos en una secuencia temporal. Cada rol en la secuencia se muestra como una línea de vida, una línea vertical. A diferencia de otros diagramas, el diagrama de de secuencia al mostrarnos interacciones entre los roles, está dentro de los diagramas dinámicos. <strong>Puede usarse un diagrama de secuencia, para mostrar las interacciones en un caso de uso o en un escenario de un sistema de software.</strong>
</p>

### En la herramienta, nos vamos a model -> add diagram -> Sequence Diagram.

&nbsp;
<center>![casosUso](img/custar2.png)</center>
&nbsp;

* __Rol__  
<p style="text-align: justify">
  Es la descripción de un objeto, que desempeña un determinado papel dentro de una interacción.
</p>

* __Mensaje__  
<p style="text-align: justify">
  Es la funcionalidad que permite la comunicación entre los roles. De acá, ya tendremos una idea de lo que serán los métodos y sus interacciones.
</p>

&nbsp;
<center>![Diagrama de secuencia](img/SECUENCIA000.png)</center>
<center><small>Figura 3.1 - Diagrama de secuencia.</small></center>  
&nbsp;  


<p style="text-align: justify;">
Como vimos en un ejemplo anterior, en donde usamos los casos de uso para modelar el escenario de la compra de entradas online. Veamos ahora como poder llevar ese caso de uso a un diagrama de secuencia. De un diagrama de casos de uso, pueden salir muchos diagrámas de secuencia, por ejemplo, está la secuencia en el caso que, el usuario acepte o rechace la inscripción como socio, además de la interacción del administrador con el sistema. Es por eso, que se muestra un flujo normal y los demás se descartan. Hay que recordar que debemos usar solamente lo necesario para que la idea sea captada.
</p>

&nbsp;
<center>![Compra de entradas online, flujo normal.](img/SECUENCIA001.png)</center>
<center><small>Figura 3.2 - Compra de entradas online, flujo normal.</small></center>  
&nbsp;

Hagamos el flujo normal del administrador consultando las ventas.

&nbsp;
<center>![casos de uso include](img/SECUENCIA002.png)</center>
<center><small>Figura 3.3 - Flujo normal, administrador consulta las ventas</small></center>  
&nbsp;

<p style="text-align: justify;">
Se puede ver que algunos mensajes poseen argumentos y otros no. Notamos una similitud a la programación de métodos; pero hay que tener cuidado al pensar que deben estár la totalidad de los métodos que contendrán nuestras clases, ya que esto sería una complicación innecesaria en la etapa de toma de requerimientos. Lo que haya faltado por diseñar, se puede agregar en la siguiente iteración, a menos que se tenga el suficiente tiempo, además de la absoluta claridad en lo que se quiere desarrollar.  
</p>

<p style="text-align: justify;">
Podemos además como se ha mencionado, diseñar flujos alternativos. Un flujo alternativo, es aquél que no forma parte del problema principal, pero amerita que sea expuesto, por ejemplo, si es que pasa algún error en el flujo y saber como abordarlo.
</p>

&nbsp;
<center>![Flujo alternativo, cuenta no posee saldo](img/SECUENCIA003.png)</center>
<center><small>Figura 3.4 - Flujo alternativo, cuenta no posee saldo.</small></center>  
&nbsp;

> "El código surge con naturalidad del diagrama de secuencia. En la práctica, generalmente me sirvo de un diagrama de secuencia para bosquejar la interacción y después hago algunos cambios a medida que lo codifico. Si la interacción es importante, entonces actualizo la gráfica de secuencia como parte de mi documentación. Si considero que tal gráfica no añadirá mucha claridad al código, archivo el borrador de la gráfica de secuencia en el archivero circular", - << Martin Fowler >>  

<p style="text-align: justify;">
Ya podemos entonces identificar las interacciones entre los roles. Tenemos a un usuario que requiere la compra de una entrada, entonces podemos imaginar que necesitamos un tipo de dato llamado entrada, quizás en este punto se nos ocurre la idea que puedan existir varios tipos de entradas y le preguntemos al especialista del negocio, aquellas dudas que surgen en este punto, antes que sea demasiado tarde y tengamos desarrollado algo erróneo. Analizaremos estas afirmaciones en el siguiente capítulo.
</p>

---
## **Capítulo 4 - Diagrama de Clases.**
---
### **4.1 - Competencias esperadas.**
* Relacionar el diagrama con la POO.
* Reconocer las notaciones como cajas y generalizaciones.
* Construir diagrama de clases.
* Llevar los diagramas de clase a código en Java.

### **4.2 - Introducción.**

<p style="text-align: justify;">
  Para modelar las clases e interfaces, incluidos sus atributos, operaciones, relaciones y asociaciones con otras clases, el UML proporciona el diagrama de clases, que aporta una visión estática o de estructura de un sistema, sin mostrar la naturaleza dinámica de las comunicaciones entre los objetos de las clases.
  El diagrama de clase, además de ser de uso extendido, también está sujeto a la más amplia gama de conceptos de modelado. Aunque los elementos básicos son necesarios para todos, los conceptos avanzados se usan con mucha menor frecuencia. Es por eso que se toman los temas más importantes y suficiente para lograr los objetivos propuestos.
</p>

### En la herramienta, nos vamos a model -> add diagram -> Class Diagram.

&nbsp;
<center>![casosUso](img/custar3.png)</center>
&nbsp;

### **4.3 - Componentes de un diagrama de clases.**

####__4.3.1 - Atributos de una clase.__
<p style="text-align: justify;">
  Un atributo es algo que un objeto de dicha clase conoce o puede proporcionar todo el tiempo. Por lo general, los atributos se implementan como campos (variables de instancia) de una clase, pero no necesitan serlo. Podrían ser valores que la clase puede calcular a partir de sus variables o valores de instancia y que puede obtener de otros objetos de los cuales está compuesto. Por ejemplo, un objeto puede conocer siempre la hora actual y regresarla siempre que se solicite. Por tanto sería adecuado mencionar la hora actual como un atributo de dicha clase de objetos. Sin embargo, el objeto muy probablemente no tendría dicha hora almacenada en una de sus variables de instancia, por que necesitaría actualizar de manera continua ese campo. En vez de ello, el objeto probablemente calcularía la hora actual (por ejemplo, a través de consulta con objetos de otras clases) en el momento en el que se le solicite la hora.
</P>

####__4.3.2 - Operaciones.__

<p style="text-align: justify;">
  Una operación, es lo que pueden hacer los objetos de la clase. por lo general, se implementa como un método de la clase.
</p>

####__4.3.3 - Cajas.__

<p style="text-align: justify;">
  Elementos principales de un diagrama de clase, son los íconos utilizados para representar clases e interfaces. Cada caja se divide en partes horizontales. La parte superior contiene el nombre de la clase. La sección media menciona sus atributos. La tercera sección del diagrama de clase, contiene las operaciones o comportamientos de la clase.
</p>

&nbsp;
<center>![Ejemplo de una claja](img/CLASES001.png)</center>
<center><small>Figura 4.1 - Ejemplo de una caja. La representación gráfica de una clase..</small></center>  
&nbsp;

La figura 4.1, presenta un ejemplo simple de una clase `PuraSangre`, esta modela caballos de pura sangre y osee tres atributos:

+ `padre`.
+ `madre`.
+ `anioNacimiento`.

Además de tres operaciones:

+ `obtenerPadre()`.
+ `obtenerMadre()`.
+ `obtenerEdadActual()`.

<p style="text-align: justify;">
 <strong>Puede haber otros atributos que no se muestren en el diagrama.</strong> Cada atributo, puede tener un nombre, un tipo y un nivel de visibilidad. El tipo y la visibilidad son opcionales. El tipo sigue al nombre y se separa de él mediante dos puntos. La visibilidad se indica, anteponiendo cualquiera de los siguientes símbolos: 
</p>

+ <code>-</code> Visibilidad privada.
+ <code>#</code> Visibilidad protegida.
+ <code>~</code> Paquete.
+ <code>+</code> Visibilidad privada.

También es posible, especificar si un atributo es del tipo static subrayándolo.

Para los atributos especificamos el nombre y el tipo de retorno de la siguiente forma:

+ <code>nombre</code>:<code>tipoDeRetorno</code>

En el caso de las operaciones, tenemos estas más opciones:

+ <code>nombreOperacion(nombreParametro:tipo, ...)</code>
+ <code>nombreOperacion():tipoRetorno</code>
+ <code>nombreOperacion(nombreParametro:tipo, ...):tipoRetorno</code>

__La implementación de la caja de ejemplo en Java sería la siguiente:__

``` java
package cl.desafiolatam.uml.diagramaclase;

import java.util.Date;

public class PuraSangre {
  private PuraSangre padre;
  private PuraSangre madre;
  private int anioNacimiento;

  public PuraSangre obtenerPadre() {
    // TODO implementar acá
    return null;
  }

  public PuraSangre obtenerMadre() {
    // TODO implementar acá
    return null;
  }

  public int obtenerEdadActual(Date anioActual) {
    // TODO implementar acá
    return 0;
  }

}

```  

<p style="text-align: justify;">
Vemos que ya podemos comenzar a preparar el código base de nuestra aplicación, incluso la herramienta <code>starUml</code> posee una opción de llevar nuestro modelo a código.
</p>

__Paso 1: Debemos tener nuestro diagrama de clases, en un modelo como indica la siguiente imágen:__

&nbsp;
<center>![ejemplogeneracion](img/CLASES002.png)</center>
&nbsp;

__Paso 2: Seleccionamos `tools -> Java -> generate code`.__

&nbsp;
<center>![ejemplogeneracion](img/CLASES003.png)</center>
&nbsp;


__Paso 3: Seleccionamos la el modelo y la ubicación en donde lo queremos dejar. Esto genera una carpeta con el nombre del modelo y si revisamos su interior, encontraremos los archivos generados, en este caso es solo uno.__

&nbsp;
<center>![ejemplogeneracion](img/CLASES004.png)</center>
&nbsp;

__Podemos entonces revisar su contenido:__

```Java


import java.util.*;

/**
 * 
 */
public class PuraSangre {

    /**
     * Default constructor
     */
    public PuraSangre() {
    }

    /**
     * 
     */
    private PuraSangre padre;

    /**
     * 
     */
    private PuraSangre madre;

    /**
     * 
     */
    private int anioNacimiento;

    /**
     * @return
     */
    public PuraSangre obtenerPadre() {
        // TODO implement here
        return null;
    }

    /**
     * @return
     */
    public PuraSangre obtenerMadre() {
        // TODO implement here
        return null;
    }

    /**
     * @param anioActual 
     * @return
     */
    public int obtenerEdadActual(Date anioActual) {
        // TODO implement here
        return 0;
    }

}

```


####__4.3.4 - Generalización (Herencia).__

<p style="text-align: justify;">
  Los diagramas de clase, también pueden mostrar relaciones entre las clases, una clase que sea una subclase de otra clase se conecta con ella mediante una flecha con una línea sólida y con una punta triangular hueca. La flecha apunta de la subclase a la superclase. Podemos relacionar esto con la relación de herencia en la POO.
</p>

&nbsp;
<center>![Ejemplo de generalización01](img/CLASES005.png)</center>
<center><small>Figura 4.2 - Ejemplo de generalización - (Herencia).</small></center>  
&nbsp;

#####__Clase `Caballo`:__

```Java
package cl.desafiolatam.uml.diagramaclase;

import java.util.Date;

public class Caballo {
    private String nombre;
    private int anioNacimiento;

    public Caballo(String nombre, int anioNacimiento) {
      this.nombre = nombre;
      this.anioNacimiento = anioNacimiento;
    }

    public String obtenerNombre() {
        // TODO implementar aquí.
        return "";
    }

    public int obtenerEdadActual(Date anioActual) {
        // TODO implementar aquí.
        return 0;
    }

}

```

#####__Clase `PuraSangre`:__

```Java
package cl.desafiolatam.uml.diagramaclase;

import java.util.Date;

public class PuraSangre extends Caballo {
    private PuraSangre padre;
    private PuraSangre madre;

    public PuraSangre(PuraSangre padre, PuraSangre madre, String nombre, int anioNacimiento) {
      super(String nombre, int anioNacimiento);
      this.padre = padre;
      this.madre = madre;
    }

   public PuraSangre obtenerPadre() {
      // TODO implementar acá
      return null;
   }

    public PuraSangre obtenerMadre() {
      // TODO implementar acá
      return null;
    }

}

```


##### __Clase `CuartoDeMilla`:__


```Java
package cl.desafiolatam.uml.diagramaclase;

import java.util.Date;

public class CuartoDeMilla extends Caballo {
    public CuartoDeMilla padre;
    public CuartoDeMilla madre;

    public CuartoDeMilla(PuraSangre padre, PuraSangre madre, String nombre, int anioNacimiento) {
      super(String nombre, int anioNacimiento);
      this.padre = padre;
      this.madre = madre;
    }

    public CuartoDeMilla obtenerPadre() {
        // TODO implementar aquí.
        return null;
    }

    public CuartoDeMilla obtenerMadre() {
        // TODO implementar aquí.
        return null;
    }

}

```

####__4.3.5 - Implementación de Interfaces en UML.__

<p style="text-align: justify;">
Podemos expresar además, la relación de implementación de interfaces. Esto nos ayuda a poder diseñar un bosquejo de lo que se pretende construir, de esta forma, podemos hacer un mapa completo de la estructura que tendrán nuestras clases e interfaces además de poder generar el código desde la misma herramienta
</p>

&nbsp;
<center>![Ejemplo de interfaces](img/CLASES006.png)</center>
<center><small>Figura 4.3 - Ejemplo de interfaces.</small></center>  
&nbsp;

__Clase: Equino__

``` Java
package cl.desafiolatam.uml.interfaces

public interface Equino {

    public abstract void Hablar();

}

```

&nbsp;

__Clase: Caballo__

``` Java
package cl.desafiolatam.uml.interfaces

public class Caballo implements Equino {

    public void Hablar() {
        // TODO implementar aquí.
    }

}

```

&nbsp;

__Clase: Cebra__

``` Java
package cl.desafiolatam.uml.interfaces


public class Cebra implements Equino {

    public Cebra() {}
    @Override
    public void Hablar() {
        // TODO implementar aquí.
    }

}

```
&nbsp;

__Clase: Mula__

``` Java
package cl.desafiolatam.uml.interfaces


public class Mula implements Equino {

    @Override
    public void Hablar() {
        // TODO implementar aquí.
    }

}

```
<p style="text-align: justify;">
 Podemos generar un código muy similar desde la herramienta, y ver que se auto-generan los métodos que se implementan desde la interfaz. De esta forma, podemos ver que si utilizamos el paradigma de programación orientado a objetos, este diagrama nos proporciona no solamente una idea de como debemos implementar el código, sino que además nos proporciona parte de dicho código.
</p>


<p style="text-align: justify;">
  Los sistemas de software son una de las tecnologías más importantes en todo el mundo. En los últimos 60 años, el software ha pasado a ser la solución de un problema especializado y herramienta de análisis de la información a una industria en sí misma. No obstante, aún hay problemas para desarrollar software de alta calidad a tiempo y dentro del presupuesto asignado.
  "Una imagen vale más que mil palabras", pero antes de esto, debemos saber de qué imagen se trata y cuáles son esas mil palabras. Si no logramos generar diagramas que logren comunicar una correcta solución, surge una imagen errónea, que conduce al software erróneo.
</p>

__Como consejo final de la unidad, se listan los principios del modelado, a lo que debemos apegarnos con la mayor fuerza posible, para que lo aprendido de UML, sea un real aporte al desarrollo de software.__

+ El equipo de software, tiene como objetivo principal, elaborar software y no modelos.
+ Viajar ligero, no crear más modelos de los necesarios.
+ Tratar de producir el modelo más sencillo que describa al problema o al software.
+ Construir modelos susceptibles al cambio.
+ Ser capaz de enunciar un propósito explícito para cada modelo que se cree.
+ Adaptar los modelos que se desarrollan al sistema en cuestión.
+ Tratar de construir modelos útiles, pero olvidarse de construir modelos perfectos.
+ No ser dogmáticos respecto a la sintaxis del modelo. Si se tiene éxito para comunicar contenido, la representación es secundaria.
+ Si su instinto dice que un modelo no es correcto a pesar de que se vea bien en el papel, hay razones para estar preocupados.
+ Obtener retroalimentación tan pronto como sea posible.

Si se siguen estos principios, nuestros modelos tendrán un mejor aporte y no significaran una pérdida de tiempo, si no que todo lo contrario, por que hay que recordar que _meses de programación, nos ahorran unas horas de planificación_.

---


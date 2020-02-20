================================================
 Fase 2 - Definición del Contexto de un Sistema
================================================

Introducción
==============

El *contexto de un sistema software* es el entorno donde se enmarca dicho sistema software. Sin una consideración adecuada del contexto resulta imposible desarrollar de forma correcta un sistema software, ya que dicho contexto influye directamente sobre dicho sistema. Es decir, no se puede considerar un sistema de forma aislada a su contexto.

Por ejemplo, una empresa que desarrolle un sistema informático para una administración pública podría decidir qué es interesante que se puedan exportar informes de resultados como documentos Excel, conocida hoja de cálculo muy utilizada por los equipos directivos para innumerables tareas. No obstante, dicha administración pública podría haber decretado que todo el software utilizado dentro de dicha administración debe ser, en la medida de lo posible, software libre. Ejemplos de dichas administraciones podrían ser la Junta de Extremadura o la Junta de Andalucía.

En estas circunstancias, la funcionalidad del sistema relativa a la posibilidad de exportar informes a documentos Excel debe ser revisada. El programa Excel no es en absoluto software libre, por lo que entraría en conflicto con las normas reguladoras del contexto donde se enmarca dicho sistema. Por tanto, algo que se añade como una funcionalidad extra para beneficio del usuario, puede acabar siendo fuente de innumerables problemas por una inadecuada consideración del contexto.

El objetivo general de esta práctica es que el alumno se familiarice con el concepto de contexto de un sistema software, aprendiendo a definirlo de manera correcta. A continuación, describimos los objetivos, actividades y criterios de evaluación que conforman esta segunda fase del proyecto.

Objetivos
===========

Los objetivos de esta práctica son:
  #. Ser capaz de elaborar y ejecutar planes para la definición del contexto de un sistema sw.
  #. Ser capaz de identificar los elementos que pertenecen a cada una de las vistas del contexto de un sistema sw.
  #. Ser capaz de definir los elementos estructurales que conforman la vista de dominio del contexto de un sistema sw, así como sus relaciones y restricciones.
  #. Ser capaz de definir las leyes y normativas que podrían influir en el desarrollo y funcionamiento de un sistema sw, sabiendo, además, identificar la vista concreta a la cual pertenecen dichas leyes, normativas o regulaciones.
  #. Ser capaz de identificar los actores que forman parte del contexto de un sistema software.
  #. Ser capaz de elaborar perfiles de actores que formen parte del contexto de un sistema software.
  #. Ser capaz de describir la infrestructura tecnológica existente en el entorno donde se desplegará un sistema software.
  #. Ser capaz de describir todos los elementos existentes en el entorno donde se desplegará un sistema software que podrían condicionar los procesos y técnicas a utilizar para el desarrollo de dicho sistema software.
  #. Ser capaz a definir la frontera de un sistema sw, el contexto de un sistema software y la frontera del contexto de un sistema sw.
  #. Ser capaz de definir un glosario que permita entender la terminología propia del contexto donde se desplegará un determinado sistema software.

Actividades
============

Para definir el contexto de un sistema sw, cada grupo deberá realizar las siguientes actividades:
  #. Planificar una serie de actividades cuyo objetivo final sea la definición del contexto del sistema. Para ello, se aconseja considerar cada vista del sistema de manera individual y realizar, al menos, una dinámica de grupo por cada vista del contexto a definir.
  #. Ejecutar las actividades definidas anteriormente con objeto de definir cada una de las cuatro vistas propuestas para la definición del contexto: dominio, utilización, tecnología y desarrollo.
  #. Documentar los resultados obtenidos utilizando para ello la plantilla proporcionada más abajo.
  #. Generar un glosario de términos relacionados con el contexto del sistema.

Para definir la *vista de dominio* del sistema se deberá crear algún tipo de diagrama o modelo que recoga las entidades existentes en el contexto del sistema, así como las relaciones y restricciones existentes entre dichas entidades. Para ello aconseja crear un mapa mental, pero representaciones alternativas como un diagrama entidad-relación o una ontología también serían aceptables. La vista de dominio debe recoger, además, las normativas, regulaciones y leyes que puedan tener algún tipo de relación con las entidades identificadas. Finalmente, para completar la vista de dominio, se deberán crear listas dentro/fuera que determinen qué elementos se estima que pertenecerán al sistema, cuáles al contexto, cuáles son simplemente irrelevantes y cuáles están en las fronteras entre sistema y contexto o entre contexto y la irrelevancia.

Para definir la *vista de utilización* se deberá, en primer lugar, identificar tantos actores existentes en el contexto del sistema como sea posible. A continuación, se deberá priorizar y ordenar los actores identificados según su relevancia o importancia con respecto al sistema a desarrollar. Dicha lista de actores, ordenada de mayor a menor relevancia, debe incluirse en el documento que defina el contexto del sistema. A continuación, se especificarán sólo los perfiles de los actores de mayor relevancia. Se especificarán tantos perfiles de actores como miembros tenga cada grupo, de manera que exista una especificación del perfil de un actor por alumno. La especificación del perfil de cada actor se realizará de manera individual por un único alumno.

Para definir la *vista de tecnología* se deberá identificar la infraestructura tecnológica, si la hubiere, del entorno donde se desplegará el sistema. Dicha infraestructura deberá describirme por medio del algún diagrama o modelo, como por ejemplo, un diagrama de despliegue o un esquema de topología de red. Dicho diagrama deberá contener todos los detalles del contexto que se consideren relevantes para el sistema y puede complementarse con todo el texto escrito que se considere necesario.

Para definir la *vista de desarrollo* se describirá mediante texto simple todas aquellos elementos y cuestiones existente en el contexto del sistema que se considere que puedan tener influencia en las métodos de trabajo, técnicas y herramientas utilizados para el desarrollo del sistema.

Para la elaboración del glosario deberán incluirse en el mismo dos definiciones por alumno.

Para elaborar el contexto del sistema sw se proporciona:

  #. :download:`La plantilla para la definición del contexto <src/contexto/plantillaContexto.docx>`
  #. :download:`La plantilla para la definición del glosario <src/contexto/plantillaGlosario.docx>`
  #. :download:`Ejemplo de Definición del Contexto un Sistema Sw <src/contexto/ejemploContexto.pdf>`

Elementos a Entregar y Aclaraciones
=======================================

Criterios de Evaluación
=========================

Los criterios de evaluación para la planificación de actividades y la elaboración de actas se proporcionan en las secciones que describen estos elementos transversales.

Para la evaluación de la visión, se analizarán los siguientes elementos:

  #. Definición de la Visión del Sistema (6 puntos).
  #. Viabilidad Económica (1 punto).
  #. Pruebas de Aceptación (2 puntos).
  #. Ortografía, Gramática y Maquetación (1 punto).

La calificación de cada uno de estos apartados será común a todo el grupo.
Para *Ortografía, Gramática y Maquetación*, los criterios de evaluación aparecen descritos en la sección de elementos transversales. El resto de apartados se evaluará conforme a los criterios descritos a continuación.

Definición de la Visión del Sistema
------------------------------------

Para evaluar y calificar la definición de un sistema se atenderá al grado de satisfacción de los elementos abajo descritos.

**Características imprescindibles**

    #. La visión define en un su primera fase el objetivo último del sistema.
    #. La visión establece claramente qué beneficio obtienen sus usuario mediante la utilización del sistema.
    #. La visión da una idea general de qué mecanismos concretos se utilizarán para alcanzar los objetivos descritos.

**Características recomendables**

    #. La visión no incluye detalles o formas de realizar el sistema que no sean absolutamente imprescindibles o restrinjan el sistema innecesariamente.
    #. Todos los elementos mencionados han sido elevados a su máximo nivel de abstracción posible.
    #. La visión carece de sentencias excesivamente largas, confusas o imprecisas.
    #. La visión carece de listas cerradas, salvo en los casos en los cuales la intención sea limitar el ámbito del sistema a esa lista concreta.

Para poder obtener una calificación de 5 o más en este apartado es necesario que la definición de la visión satisfaga absolutamente todas las características imprescindibles, así como que satisfaga en gran medida las recomendables.

Viabilidad Económica
---------------------

Para evaluar y calificar la viabilidad económica de un sistema se atenderá al grado de satisfacción de los elementos abajo descritos.

  #. Las fuentes de financiación o ingresos están claramente identificadas.
  #. El mecanismo por el cual dichas fuentes producen los ingresos esperados está justificado de forma clara, precisa y concisa, y no es fácilmente cuestionable.

La satisfacción del primer elemento es absolutamente imprescindible para poder obtener una calificación de 5 en este apartado.

Pruebas de Aceptación
----------------------

  #. El criterio de aceptación sirve para medir la utilidad del sistema con respecto al objetivo último de sus usuarios finales.
  #. El criterio de aceptación está define de forma clara y precisa, de manera que se pueda ejecutar sin ambigüedades ni malinterpretaciones.
  #. El criterio de aceptación es ejecutable con unos costes razonables.

La satisfacción del primer elemento es absolutamente imprescindible para poder obtener una calificación de 5 en este apartado.

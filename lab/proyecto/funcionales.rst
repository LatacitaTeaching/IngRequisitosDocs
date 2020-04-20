==================================================
Fase 7 - Especificación de Requisitos Funcionales
==================================================

Introducción
=============

Durante de un proceso de Ingeniería de Requisitos, los conceptos de *esencia* y *encarnación* aparecen recurrentemente a lo largo del mismo para, en primer lugar, definir qué debe hacer el sistema (esencia), y, a continuación, especificar *cómo* debe hacerlo (encarnación). Es decir, un Proceso de Ingeniería completo consiste en determinar cómo hacer lo que se debe hacer.

Por ejemplo, para un sistema software para la gestión de una biblioteca, un Ingeniero de Requisitos puede determinar que el sistema debe permitir la incorporación de nuevos libros al catálogo de la biblioteca. Esto especifica el qué se quiere hacer. No obstante, hay diversas formas de hacerlo. La más sencilla es crear un formulario que permita la incorporación de los nuevas adquisiciones de manera manual. Esta forma sería un posible *cómo*, pero no es el único *cómo*, o manera de materializar el sistema. Por ejemplo, podría considerarse como alternativa la posibilidad de importar automáticamente los datos de los nuevos libros a añadir desde algún catálogo de libros públicamente accesible en línea. Esta nueva alternativa es más cómoda para el usuario, que únicamente necesitaría especificar algún dato del libro, como su ISBN, quedando el resto de sus datos automáticamente incorporados al catálogo de la biblioteca. Por otro lado, esta nueva alternativa podría más compleja de implementar, y por tanto más cara de desarrollar, que la opción inicial de crear un formulario para la incorporación manual de los datos.

En la fase anterior del Proceso de Ingeniería de Requisitos, vimos cómo se pueden utilizar modelos de objetivos para especificar las intenciones y deseos de los diversos *stakeholders* con respecto a un sistema sw. Es decir, para especificar el *qué* debe hacer el sistema. Tras esta especificación del *qué*, o de la esencia del sistema, para completar una *Especificación de Requisitos*, los ingenieros de requisitos deberán desarrollar escenarios que especifiquen maneras concretas de satisfacer los objetivos identificados. Es decir, los ingenieros de requisitos deberán especificar con detalle *cómo* el sistema va a hacer lo que tiene que hacer.

El objetivo último de esta práctica es que el alumno adquiera las habilidades necesarias para especificar escenarios satisfactoriamente. La siguiente sección detalla los subobjetivos que  deberán satisfacerse para poder alcanzar dicho objetivo general.

Objetivos
==========

Los objetivos concretos de esta práctica son:

  #. Ser capaz de especificar tareas de un modelo de objetivos mediante *casos de uso*.
  #. Ser capaz de especificar escenarios alterativos y excepcionales mediante la especificación de extensiones de un caso de uso.
  #. Ser capaz de especificar tareas de un modelo de objetivos mediante *historias de usuario*.

La siguiente sección describe las actividades que se deberán realizar para la consecución de estos objetivos.

Actividades
============

Para aprender a especificar escenarios que indiquen maneras concretas de satisfacer un requisito funcional, cada alumno, de manera individual, deberá:

  #. Especificar de manera completa, como *caso de uso*, una tarea, u objetivo de nivel mar, contenido en el modelo de objetivos elaborado en la práctica anterior. Para especificar este caso de uso, se deberá utilizar la plantilla estandarizada disponible al final de esta sección. Además, el alumno deberá crear *mock-ups* de las diferentes interfaces de usuario a utilizar durante la ejecución del caso de uso.
  #. Especificar de manera completa, como *historia de usuario*, una tarea, u objetivo de nivel mar, contenido en el modelo de objetivos elaborado en la práctica anterior. Para especificar esta historia de usuario, se deberá utilizar la plantilla estandarizada disponible al final de esta sección. Además, el alumno deberá crear *mock-ups* de las diferentes interfaces de usuario a utilizar durante la ejecución de la historia de usuario.

Las tareas, u objetivos de nivel mar, escogidos por cada alumno para la especificación del caso de uso y de la historia de usuario deberán ser distintos entre sí; y a su vez, distintos de cualquier tarea, u objetivo de nivel mar, seleccionado por el resto de sus compañeros de grupo para la especificación de sus casos de uso e historias de usuario. En caso de no haber tareas suficientes en el modelo de objetivos para todos los miembros de un grupo, se deberá contactar con el profesor, quien generará nuevas tareas para que haya al menos dos tareas por cada miembro del grupo.

Para la realización de los *mock-ups*, se recomienda la utilización de la herramienta `NinjaMock <https://ninjamock.com/>`_. En cualquier caso, se aconseja que los prototipos realizados no sean muy realistas y tengan la apariencia de bocetos a mano alzada, aún cuando hayan sido realizados mediante herramientas informáticas.

.. note::
   Dadas las circunstancias excepcionales que estamos viviendo durante el curso 2019-2020 debido a la crisis sanitaria generada por el Covid-19, se permitirá a los alumnos de dicho curso  utilizar una misma tarea, u objetivo de nivel mar, para especificar su caso de uso y su historia de usuario. De esta forma, se espera rebajar el trabajo del alumno, que simplemente deberá especificar un caso de uso y, a continuación, llevar a cabo las modificaciones que sean oportunas para especificar el mismo escenario como historia de usuario. Si lo desease, también podría realizarlo al revés, primero especificar el escenario como historia de usuario y luego transformarlo a caso de uso. No obstante, esta facilidad posee como problema de que los errores cometidos en la especificación del escenario aparecerían duplicados en ambas especificaciones, por lo que podrían penalizar doble.

Para la *especificación de casos de uso* e *historias de usuario* se proporciona:

  #. :download:`Una plantilla para la especificación de casos de uso <src/funcionales/plantillaCasosDeUso.docx>`
  #. :download:`Una plantilla para la especificación de historias de usuario <src/funcionales/plantillaHistoriasDeUsuario.docx>`
  #. :download:`Ejemplo de especificación de un caso de uso <src/funcionales/ejemploCasoDeUso.pdf>`
  #. :download:`Ejemplo de especificación de una historia de usuario <src/funcionales/ejemploHistoriaDeUsuario.pdf>`

Elementos a Entregar y Aclaraciones
=======================================

Se deberán entregar para su evaluación los siguientes elementos:

  #. Una plantilla con la especificación completa del caso de uso seleccionado por el alumno.
  #. Una plantilla con la especificación completa de la historia de usuario seleccionada por el alumno.
  #. Una serie de *mock-ups* que especifiquen, a modo de prototipo, las interfaces de usuario que sería necesario implementar para dar soporte al caso de uso e historias de usuario especificadas.

El conjunto de ficheros resultantes se entregará dentro de las fechas establecidas a través de la plataforma *Moodle* siguiendo las instrucciones en ella proporcionadas. Las entregas fuera de las fechas establecidas o con un formato diferente al solicitado tendrán una calificación de cero. Cada documento se evaluará y calificará conforme a los criterios especificados en la siguiente sección.

Criterios de Evaluación
=========================

La calificación de la fase de modelado y especificación de objetivos vendrá determinada por la ponderación de las calificaciones de los siguientes apartados:

  #.
  #. Ortografía, Gramática y Maquetación (1 punto).

Cada uno de estos apartados se calificará mediante el procedimiento y los criterios a continuación proporcionados, excepto *Ortografía, Gramática y Maquetación*, que se evaluará conforme a los criterios establecidos para ello en el correspondiente apartado de la sección de elementos transversales.

Completitud
------------

Para evaluar la completitud del modelo de objetivos se verificará que estén recogidos en dicho modelo todos los objetivos del stakeholder  entrevistado en la fase anterior del proyecto.

Para poder obtener una calificación de aprobado en este apartado, todos aquellos objetivos que puedan ser considerados como de alta importancia para el stakeholder entrevistado deberán estar contenidos en el modelo creado.

Modelado de Objetivos
----------------------

Para calificar la corrección del modelo de objetivos creado, se verificará el grado de satisfacción de los siguientes elementos:

  #. Cada elemento del modelo es sintácticamente correcto.
  #. No se utilizan elementos de modelado sin razón aparente y de manera inconsistente. Por ejemplo, aparecen de repente recursos asociados a ciertos objetivos, sin razón aparente.
  #. Para cada relación AND, la no satisfacción del padre debida a la no satisfacción de cualquiera de sus hijos es obvia y no es fácilmente refutable.
  #. Para cada relación OR, la satisfacción inmediata del padre debida a la satisfacción de cualquiera de sus hijos es obvia y no es fácilmente refutable.
  #. Por casa descomposición basada en una serie de contribuciones, la sustitución de dicha serie de contribuciones por una descomposición AND u OR no es obvia y fácilmente argumentable.
  #. Los hijos de un padre sirven para responder a la pregunta de cómo se alcanza el objetivo especificado por el padre.
  #. El padre un hijo sirve para responder, en parte, a la pregunta de por qué se desea satisfacer un objetivo hijo.
  #. El signo de cada contribución es correcto.
  #. El peso de cada contribución es adecuado dentro del contexto del modelo de objetivos.
  #. Todas las relaciones entre objetivos están debidamente identificadas.
  #. Las tareas se utilizan correctamente para modelar la existencia de escenarios que dan lugar a la satisfacción de uno o más objetivos.

Especificación de Objetivos de Nivel Cielo, Cometa y Mar
---------------------------------------------------------

Para calificar la corrección de las especificaciones de objetivos creadas, se verificará el grado de satisfacción de los siguientes elementos:

  #. Cada objetivo está correctamente identificado.
  #. El nombre de cada objetivo proporciona una idea clara del propósito de dicho objetivo. Para ello, se recomienda que el objetivo comience por verbo que indique la acción a realizar. En el caso de los objetivos blandos, se recomienda añadir algún adverbio o adjetivo al nombre del objetivo, de manera que quede más claro cómo se puede graduar el objetivo.
  #. Cada objetivo está correctamente identificado como duro o blando.
  #. Si el objetivo es blando, dicho objetivo tiene definido un criterio de verificación que permite medir con claridad el grado de satisfacción del objetivo.
  #. El nivel del objetivo es correcto y no es fácilmente rebatible.
  #. El valor de Kano asignado al objetivo es correcto y no es fácilmente rebatible.
  #. La lista de actores involucrados o afectados por el objetivo es correcta, conteniendo todos actores relevantes para el objetivo y no conteniendo actores que se puedan considerar como irrelevantes.
  #. La descripción del objetivo expresa un deseo o intención de un determinado actor o conjunto de actores.
  #. La descripción del objetivo da una idea clara y precisa del beneficio que espera obtener el actor mediante la satisfacción de dicho objetivo.
  #. El apartado de contribuciones describe como el objetivo especificado contribuye a satisfacer uno o más objetivos padre.
  #. Por cada contribución descrita, el peso de dicha contribución está debidamente justificado.
  #. La justificación del peso de cada contribución no es una simple réplica de la descripción asociada a su valor cualitativo. Por ejemplo, para una contribución de tipo *make*, la justificación de que la satisfacción del hijo es suficiente para la satisfacción del padre no sería una justificación aceptable. En este caso, habría que explicar por qué la satisfacción del objetivo, por si sola, es suficiente para alcanzar la satisfacción del padre, no siendo necesaria la satisfacción de ningún otro objetivo hijo.
  #. Toda contribución que aparece en el modelo de objetivos está descrita en el correspondiente apartado de contribuciones, y viceversa.
  #. Todo objetivo referenciado en la especificación del objetivo está también contenido en el modelo de objetivos.

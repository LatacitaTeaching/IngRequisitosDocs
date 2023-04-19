================================================
Fase 6 - Modelado y Especificación de Objetivos
================================================

Introducción
=============

Todo sistema (software) se desarrolla con la intención de satisfacer un conjunto de necesidades de una serie de usuarios finales. Si el sistema fallase a la hora de satisfacer dichas necesidades, tal sistema resultaría inútil a sus usuarios finales, por lo que carecería de valor alguno.

Por tanto, a nivel de Ingeniería del Requisitos, es de crucial importancia saber identificar y especificar de forma adecuada cuáles son las diferentes necesidades de los distintos usuarios que interactuarán de una manera u otra con el sistema. Dichas necesidades representan los *objetivos* que deberá satisfacer el sistema. La satisfacción de dichos objetivos deberá guiar en todo momento el proceso de diseño del sistema, ya que de esta satisfacción dependerá el éxito o el fracaso del sistema.

Los objetivos que debe satisfacer determinado sistema no suelen estar todos aislados entre sí, sino que suelen conformar una compleja e intrincada red de relaciones. Estas relaciones indican, entre otras cuestiones, cómo los objetivos de alto nivel se descomponen en una serie de objetivos de bajo nivel, o cómo un determinado objetivo influye o afecta a otros objetivos del sistema.

El objetivo general de la presente práctica es aprender a identificar, modelar y especificar los objetivos que debe satisfacer un sistema software, así como las relaciones existentes entre dichos objetivos. Para alcanzar dicha meta, se deberán satisfacer los objetivos que se describen en la siguiente sección.

Objetivos
==========

Los objetivos concretos de esta práctica son:

  #. Ser capaz de identificar objetivos mediante el examen del material obtenido en una actividad de captura de requisitos.
  #. Ser capaz de modelar objetivos utilizando una notación concreta, más específicamente, la notación GRL.
  #. Ser capaz de utilizar la herramienta `jUCMNav <http://jucmnav.softwareengineering.ca/foswiki/ProjetSEG>`_ para la creación de modelos de objetivos.

..  #. Ser capaz de especificar objetivos en lenguaje natural mediante plantillas estandarizadas.
  
La siguiente sección describe las actividades que se deberán realizar para la consecución de estos objetivos.

Actividades
============

Para modelar y especificar los objetivos del sistema a desarrollar cada grupo deberá llevar a cabo las siguientes actividades:

  #. Identificar los objetivos que deberá satisfacer el sistema a partir de la información obtenida en las entrevistas realizadas en la fase anterior del proyecto. En el caso de que, tras examinar el material recopilado, se advierta que este material es insuficiente o incompleto, se recomienda contactar con el profesor para repetir la entre
  #. Crear un modelo GRL inicial que contenga tanto los objetivos identificados como las relaciones entre dichos objetivos.
  #. Refinar el modelo de objetivos hasta alcanzar su completitud.

..  #. Especificar un objetivo del nivel cielo utilizando para ello las plantillas proporcionadas.
..  #. Por último, cada miembro del grupo deberá especificar, de manera individual, utilizando la correspondiente plantilla, un objetivo cometa o del nivel de mar.

.. Para la especificación de objetivos se proporciona:

..  #. :download:`Una plantilla para la especificación detallada de objetivos <src/objetivos/plantillaObjetivos.docx>`
..  #. :download:`Ejemplos de especificación de objetivos <src/objetivos/ejemploObjetivos.pdf>`

..   Para la especificación de valores de Kano de cada objetivo identificado se utilizará la clasificación y conjunto de valores proporcionados por la herramienta Scrumdesk, que es la herramienta que se utilizará en cuarto curso para la realización del proyecto integrado. Dicho clasificación está disponible en este `enlace <https://www.scrumdesk.com/how-to-kano-model-helps-in-agile-product-backlog-prioritization/>`_.


Elementos a Entregar y Aclaraciones
=======================================

Se deberán entregar para su evaluación los siguientes elementos:

  #. *Modelo de objetivos*: Se deberán entregar uno o más archivos de imagen en formato .png o .jpg, con los diagramas correspondientes al modelo de objetivos creado. Se recomienda además incorporar un fichero de texto con la descripción del modelo de objetivos, de manera que se pueda entender mejor la lógica existente tras su diseño. 

..  #. *Plantillas de especificación de objetivos*: Las plantillas de especificación de objetivos se entregarán en un único documento en formato .pdf. Dicho documento deberá contener la especificación de un objetivo del nivel cielo, y tantos objetivo del nivel cometa o mar como alumnos tenga el grupo. Además, la autoría de cada objetivo del nivel cometa o mar debe estar claramente identificada.

El conjunto de ficheros resultantes se entregará a través de la plataforma *Moodle* siguiendo las instrucciones en ella proporcionadas y dentro de las fechas establecidas. Las entregas fuera de dichas fechas o con un formato diferente al solicitado tendrán una calificación de cero. Cada documento se evaluará y calificará conforme a los criterios especificados en la siguiente sección.

Criterios de Evaluación
=========================

La calificación de la fase de modelado y especificación de objetivos vendrá determinada por la ponderación de las calificaciones de los siguientes apartados:

  #. Completitud (3 puntos).
  #. Modelado de Objetivos (6 puntos).
  #. Ortografía, Gramática y Maquetación (1 punto).

..  #. Especificación de Objetivos de Nivel Cielo (1 punto)
..  #. Especificación de Objetivos de Nivel Cometa o Mar (1.5 puntos)

Todos los apartados tendrán una calificación común a todo el grupo. Cada uno de estos apartados se calificará mediante el procedimiento y los criterios a continuación proporcionados.

*Ortografía, Gramática y Maquetación* se evaluará conforme a los criterios establecidos para ello en el correspondiente apartado de la sección de elementos transversales. El resto de elementos se calificará mediante el procedimiento y los criterios a continuación proporcionados.

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

.. Especificación de Objetivos de Nivel Cielo, Cometa y Mar
.. ---------------------------------------------------------

.. Para calificar la corrección de las especificaciones de objetivos creadas, se verificará el grado de satisfacción de los siguientes elementos:

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

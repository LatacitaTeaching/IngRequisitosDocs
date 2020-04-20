=====================================================
Fase 7 - Especificación de Requisitos No Funcionales
=====================================================

Introducción
=============


Objetivos
==========

Los objetivos concretos de esta práctica son:

  #.

La siguiente sección describe las actividades que se deberán realizar para la consecución de estos objetivos.

Actividades
============

Para aprender a especificar los requisitos funcionales del sistema a desarrollar cada alumnos, de manera individual, deberá llevar a cabo las siguientes actividades:

  #.

Para la especificación de objetivos se proporciona:

  #. :download:`Una plantilla para la especificación de casos de uso <src/funcionales/plantillaObjetivos.docx>`
  #. :download:`Una plantilla para la especificación de historias de usuario <src/funcionales/plantillaHistoriasUsuario.docx>`
  #. :download:`Ejemplo de especificación de un caso de uso <src/funcionales/ejemploCasoDeUso.pdf>`
  #. :download:`Ejemplo de especificación de una historia de usuario <src/funcionales/ejemploHistoriaDeUsuario.pdf>`

Elementos a Entregar y Aclaraciones
=======================================

Se deberán entregar para su evaluación los siguientes elementos:

  #.

El conjunto de ficheros resultantes se entregará a través de la plataforma *Moodle* siguiendo las instrucciones en ella proporcionadas y dentro de las fechas establecidas. Las entregas fuera de dichas fechas o con un formato diferente al solicitado tendrán una calificación de cero. Cada documento se evaluará y calificará conforme a los criterios especificados en la siguiente sección.

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

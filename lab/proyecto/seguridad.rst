===========================================================
Fase 8 - Análisis y Especificación de Requisitos Seguridad
===========================================================

Introducción
=============

Afortundamente, la mayoría de las personas tienen una actitud positiva que les hace pensar que otras personas no cometerán errores y que no existen personas deshonestas o malintencionadas. Por desgracia, la realidad es bien distinta. Todas las personas somos falibles y, por tanto, podemos equivocarnos en algún momento de nuestras vidas. Consecuentemente, todo proceso que dependa de personas es falible, y podría fallar debido a errores humanos. De igual forma, el hardware también falla, haciendo que los sistemas software que corren sobre dicho hardware fallen. Finalmente, hay que tener en cuenta que aunque todos los que estamos leyendo este documento somos personas honestas, es bien sabido por todos que, desafortunadamente, hay personas deshonestas que pueden utilizar un sistema malintencionadamente, tanto por buscar un beneficio propio como por el placer de generar el caos.

Por tanto, cuando desarrollamos un sistema software, si queremos que dicho sistema software sea *confiable*, tendremos que proteger al sistema de todos estos posibles elementos que podrían causarle daños. La *seguridad software* estudia precisamente cómo proteger un sistema software de acciones externas, conocidas como *ataques*, que podrían dañar el sistema, generando un perjuicio a los stakeholders que lo utilizan. Esta protección es de vital importancia en los *sistemas sociotécnicos*, es decir, en sistemas que dan soporte a los procesos de negocio de diferentes organizaciones.

El objetivo de esta práctica es aprender a ejecutar procesos de análisis y especificación de requisitos de seguridad. Para ello, deberán satisfacerse los objetivos que se detallan en la siguiente subsección.

Objetivos
==========

Los objetivos concretos de esta práctica son:

  #. Ser capaz de identificar activos de un sistema sw.
  #. Ser capaz de identificar y analizar amenazas que podrían afectar a un activo software.
  #. Ser capaz de identificar diferentes ataques que podrían materializar las amenazas identificadas.
  #. Ser capaz de diseñar y analizar diferentes tipos de medidas de seguridad que permitan evitar, neutralizar o mitigar los diferentes ataques que podría sufrir un sistema software.
  #. Ser capaz de analizar la efectividad de las medidas de seguridad de un sistema mediante el análisis de sus premisas de confianza y contrargumentos.
  #. Ser capaz de balancear seguridad frente a otros requisitos no funcionales del sistema, como coste o usabilidad.

La siguiente sección describe las actividades que se deberán realizar para la consecución de estos objetivos.

Actividades
============

Para aprender a especificar requisitos de seguridad, cada alumno deberá, de manera individual:

  #. Partiendo de los modelos de objetivos y escenarios creados en las etapas anteriores del proyecto, identificar un activo que forme parte de dicho sistema software. Cada alumno deberá escoger un activo distinto al de sus compañeros.
  #. Para el activo identificado, identificar todas las potenciales amenazas que podrían afectar a dicho activo.
  #. Para las dos amenazas que se consideren más relevantes, analizar su exposición.
  #. Para la amenaza que se considere más importante tratar de las dos anteriormente analizadas, identificar todos los posibles ataques que podrían materializar dicha amenaza. Especificar cómo se llevaría a cabo el ataque de manera detallada.
  #. Para todos los ataques identificados en el punto anterior, diseñar medidas de control que permitan evitar, neutralizar o mitigar dichos ataques.
  #. Para una de las medidas de control especificadas en el punto anterior, especificar cuáles serían sus premisas de confianza.
  #. Para cada premisa de confianza identificada en el punto anterior, identificar sus contrargumentos, si los hubiere.
  #. Si hubiese algún contrargumento que mereciese la pena seguir tratando, diseñar una medida de control. Para dicha medida de control no es necesario identificar nuevas premisas de confianza y contrargumentos, por lo que el análisis de la seguridad deberá parar en este nivel.

.. note:: Para el curso 2020-2021, dado lo apretado del calendario, no es necesario especificar permisas de confianza y contrargumentos. Es decir, si alguien ha realizado un análisis de seguridad perfecto pero ha dejado de especificar las premisas de confianza y los contrargumentos, su calificación será de 10. No obstante, aquellos alumnos que lo deseen, podrán especificar premisas de confianza y contrargumentos que, en caso de estar bien especificados, serán recompensados con hasta dos puntos extra en la práctica.

Para la *especificación de requisitos de seguridad* se proporciona:

  #. :download:`Una plantilla para la especificación de requisitos de seguridad <src/seguridad/plantillaSeguridad.docx>`
  #. :download:`Ejemplo de análisis y especificación de requisitos de seguridad <src/seguridad/ejemploAnalisisSeguridadAsignacion.pdf>`

Estas actividades se evaluarán conforme al procedimiento descrito en la siguiente sección.

Elementos a Entregar y Aclaraciones
=======================================

Para la evaluación de esta práctica se deberán entregar un documento, conforme a una plantilla proporcionada, conteniendo los resultados de la ejecución del proceso de ingeniería de requisitos para el activo seleccionado.

Dicho documento se entregará dentro de las fechas establecidas a través de la plataforma *Moodle* siguiendo las instrucciones en ella proporcionadas. Las entregas fuera de las fechas establecidas o con un formato diferente al solicitado tendrán una calificación de cero. Cada documento se evaluará y calificará conforme a los criterios especificados en la siguiente sección.

Criterios de Evaluación
=========================

La calificación de la fase de análisis y especificación de requisitos de seguridad vendrá determinada por la ponderación de las calificaciones de los siguientes apartados:

  #. Completitud del Análisis (2.5 puntos).
  #. Corrección del Análisis (4 puntos).
  #. Eficacia de las Medidas de Control (2.5 puntos).
  #. Ortografía, Gramática y Maquetación (1 punto).

Cada uno de estos apartados se calificará mediante el procedimiento y los criterios a continuación proporcionados, excepto *Ortografía, Gramática y Maquetación*, que se evaluará conforme a los criterios establecidos para ello en el correspondiente apartado de la sección de elementos transversales. Además, en el caso concreto de esta práctica, a dichos criterios sobre *Ortografía, Gramática y Maquetación* se suma la necesidad de que la relación entre amenaza, exposición, ataque, medida de control, premisa de confianza y contrargumento quede lo más clara posible.

Completitud del Análisis
-------------------------

Para evaluar la completitud del análisis realizado, se verificará que:

  #. No existen amenazas por identificar, en especial, amenazas que puedan considerarse obvias.
  #. No existen ataques por identificar, en especial, ataques accidentales provenientes del propio usuario, para la amenaza analizada.
  #. Por cada ataque, existe al menos una medida de control que lo evita, mitiga o neutraliza.
  #. No existen premisas de confianza por identificar, en especial, premisas que puedan considerarse obvias, para la medida de control seleccionada para ser analizada en mayor profundidad.
  #. No existen contrargumentos por identificar, en especial, contrargumentos que puedan considerarse obvios, para las premisas de confianza identificadas.
  #. Para todo contrargumento identificado que necesite ser tratado, existe una medida de control que lo evita, mitiga o neutraliza.

Corrección del Análisis
------------------------

Para evaluar la corrección del análisis realizado, se verificará que:

  #. El activo seleccionado es un elemento físico o lógico del sistema en construcción.
  #. El nombre dado a cada amenaza es claro y no genera confusión.
  #. La exposición a cada amenaza establece claramente y de manera razonada cuáles serían los daños y pérdidas ocasionadas en caso de que se materialice alguna amenaza.
  #. La exposición a cada amenaza establece claramente y de manera razonada cuál es la probabilidad de que se produzca.
  #. La exposición a cada amenaza está valorada cualitativamente de manera razonada en base tanto a su posible impacto como a la probabilidad de que se produzca.
  #. Cada ataque expresa, de forma clara y concisa, algún mecanismo mediante el cual llevar a cabo una amenaza, o indica con claridad que el ataque se contempla no para erradicarlo, sino para neutralizarlo una vez que se produzca.
  #. Cada ataque afecta al activo analizado, y no a otros activos del sistema.
  #. Cada medida de control evita, mitiga o neutraliza uno o más ataques o contrargumentos identificados.
  #. La descripción de cada medida de control es clara y no existen dudas obvias de cómo se podría proceder a su implantación.
  #. Cada premisa de confianza representa un predicado lógico que ha de ser verdad para que la medida de control sea efectiva.
  #. Cada contrargumento representa un hecho o fenómeno concreto y detallado que invalidaría la premisa de confianza a la que se asocia.


.. danger::
  El campo *Radioisótopos Afectados* no tiene ningún sentido y hay que dejarlo en blanco. Se ha introducido en la plantilla de especificación de requisitos de seguridad simplemente para verificar qué alumnos prestan atención a clase o, al menos, leen las normas de evaluación. Todo aquél que indique algún radioisótopo en esta casilla tendrá automáticamente una calificación de cero en esta fase del proyecto. Por tanto, esta casilla debe considerarse como una simple `cláusula Van Halen <https://twitter.com/eladdio/status/1313612563284926466>`_.


Eficacia de las Medidas de Control
-----------------------------------

Para evaluar la eficacia de las medidas de control propuestas, se verificará que:

  #. No existan objeciones obvias a la capacidad de una medida de control para evitar, mitigar o neutralizar un ataque, o cuando dichas objeciones existan, éstas están identificadas como contrargumentos.
  #. Cada medida de control no afecta a la facilidad de utilización del sistema de manera claramente desproporcionada.
  #. La implantación de cada medida de control es factible.
  #. La implantación de cada medida de control tiene un coste razonable con relación al daño que intenta evitar.

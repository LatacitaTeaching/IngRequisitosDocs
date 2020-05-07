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
  #. Para la amenaza que se considere más importante tratar, de las dos anteriormente analizadas, identificar todos los posibles ataques que podrían materializar dicha amenaza. Especificar cómo se llevaría a cabo el ataque de manera detallada.
  #. Para todos los ataques identificados en el punto anterior, diseñar medidas de control que permitan evitar, neutralizar o mitigar dichos ataques.
  #. Para una de las medidas de control especificadas en el punto anterior, especificar cuáles serían sus premisas de confianza.
  #. Para cada premisa de confianza identificada en el punto anterior, identificar sus contrargumentos, si los hubiere.
  #. Si hubiese algún contrargumento que mereciese la pena seguir tratando, diseñar una medida de control. Para dicha medida de control no es necesario identificar nuevas premisas de confianza y contrargumentos, por lo que el análisis de la seguridad deberá parar en este nivel.

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

  #. ( punto)

Cada uno de estos apartados se calificará mediante el procedimiento y los criterios a continuación proporcionados, excepto *Ortografía, Gramática y Maquetación*, que se evaluará conforme a los criterios establecidos para ello en el correspondiente apartado de la sección de elementos transversales.

Completitud de ...
---------------------------------------------------

La relación entre amenaza, exposición, ataque, medida de control, premisa de confianza y contrargumento debe quedar lo más clara posible.

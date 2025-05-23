==================================================
Fase 6 - Especificación de Requisitos Funcionales
==================================================

Introducción
=============

Durante un proceso de Ingeniería de Requisitos, los conceptos de *esencia* y *encarnación* aparecen recurrentemente a lo largo del mismo para, en primer lugar, definir qué debe hacer el sistema (esencia), y, a continuación, especificar *cómo* debe hacerlo (encarnación). Es decir, un Proceso de Ingeniería de Requisitos completo consiste en determinar cómo hacer lo que se debe hacer.

Por ejemplo, para un sistema software para la gestión de una biblioteca, un Ingeniero de Requisitos puede determinar que el sistema debe permitir la incorporación de nuevos libros al catálogo de la biblioteca. Esto especifica el qué se quiere hacer. No obstante, hay diversas formas de hacerlo. La más sencilla es crear un formulario que permita la incorporación de las nuevas adquisiciones de manera manual. Esta forma sería un posible *cómo*, pero no es el único *cómo*, o manera de materializar el sistema. Por ejemplo, podría considerarse como alternativa la posibilidad de importar automáticamente los datos de los nuevos libros a añadir desde algún catálogo de libros accesible públicamente en línea. Esta nueva alternativa es más cómoda para el usuario, que únicamente necesitaría especificar algún dato del libro, como su ISBN, quedando el resto de sus datos automáticamente incorporados al catálogo de la biblioteca. Por otro lado, esta nueva alternativa podría ser más compleja de implementar y, por tanto, más cara.

En la fase anterior del Proceso de Ingeniería de Requisitos, vimos cómo se pueden utilizar modelos de objetivos para especificar las intenciones y deseos de los diversos *stakeholders* con respecto a un sistema sw. Es decir, para especificar *qué* debe hacer el sistema. Tras esta especificación del *qué*, o de la esencia del sistema, para completar una *Especificación de Requisitos*, los ingenieros software deberán desarrollar escenarios que especifiquen maneras concretas de satisfacer los objetivos identificados. Es decir, se deberá especificar con detalle *cómo* el sistema va a hacer lo que tiene que hacer.

El objetivo último de esta fase del proyecto de Ingeniería de Requisitos es que el estudiante adquiera las habilidades necesarias para especificar escenarios satisfactoriamente. La siguiente sección detalla los subobjetivos que deberán satisfacerse para poder alcanzar este objetivo general.

Objetivos
==========

Los objetivos concretos de esta práctica son:

  #. Ser capaz de especificar tareas de un modelo de objetivos mediante *casos de uso*.
  #. Ser capaz de especificar escenarios alternativos y excepcionales mediante la especificación de extensiones de un caso de uso.
  #. Ser capaz de especificar tareas de un modelo de objetivos mediante *historias de usuario*.
  #. Construir el *Product Backlog* que se utilizará durante el curso que viene para el desarrollo del proyecto integrado.

La siguiente sección describe las actividades que se deberán realizar para la consecución de estos objetivos.

Actividades
============

Para aprender a especificar escenarios que indiquen maneras concretas de satisfacer un requisito funcional, cada alumno, de manera individual, deberá:

  #. Especificar de manera completa, como *caso de uso*, una tarea, u objetivo de nivel mar, contenido en el modelo de objetivos elaborado en la práctica anterior. Para especificar este caso de uso, se deberá utilizar la plantilla estandarizada disponible al final de esta sección. Además, el alumno deberá crear *mock-ups* de las diferentes interfaces de usuario a utilizar durante la ejecución del caso de uso.
  #. Especificar de manera inicial en *Scrumdesk*, es decir, incluyendo sólo título y descripción, todas las tareas identificadas en el modelo de objetivos creado en la fase anterior del proyecto. Por cada historia de usuario, identificar con claridad su autor.
  #. Especificar de manera completa, como *historia de usuario*, una tarea de las anteriormente introducidas en *Scrumdesk*, incluyendo en tal especificación todas las pruebas de aceptación que sean pertinentes y adjuntando todos los *mockups* que sean necesarios para la comprensión de la historia de usuario.

.. Para la especificación del caso de uso y las historia de usuario completa, un alumno podrá utilizar una misma tarea del modelo de objetivos. 
.. De esta forma, el alumno podría rebajar su carga de trabajo, ya que simplemente deberá especificar uno de los dos elementos y, a continuación, transformar dicho elemento al otro formato. No obstante, esta facilidad posee como problema que los errores cometidos en la especificación del escenario aparecerían duplicados en ambas especificaciones, por lo que podrían penalizar doble. Además, en caso de que el caso de uso y la historia de usuario no fuesen consistentes, es decir, hubiese elementos en una representación que no tuviesen su análogo en la otra representación, la calificación global de esta práctica sería de suspenso. 

Las tareas escogidas por cada alumno para la especificación del caso de uso y de la historia de usuario deberán ser distintas entre sí y distintas de las tareas seleccionadas por el resto de sus compañeros de equipo para la especificación de sus casos de uso e historias de usuario. En caso de no haber tareas suficientes en el modelo de objetivos para todos los miembros del equipo de trabajo, se deberá contactar con el profesor, quien generará nuevas tareas para que haya al menos dos tareas diferentes por cada miembro del grupo.

Para la realización de los *mock-ups* se podrá hacer uso de cualquier herramienta e incluso podrán estar hechos a mano alzada. En cualquier caso, se aconseja que los prototipos realizados no sean muy realistas y tengan la apariencia de bocetos a mano alzada, aún cuando hayan sido realizados mediante herramientas informáticas.

Para la *especificación de casos de uso* e *historias de usuario* se proporciona:

  #. :download:`Una plantilla para la especificación de casos de uso <src/funcionales/plantillaCasosDeUso.docx>`
  #. :download:`Ejemplo de especificación de un caso de uso <src/funcionales/ejemploCasoDeUso.pdf>`
  #. :download:`Ejemplo de especificación de una historia de usuario <src/funcionales/ejemploHistoriaDeUsuario.pdf>`

Elementos a Entregar y Aclaraciones
=======================================

Se deberán entregar para su evaluación los siguientes elementos:

  #. Una plantilla con la especificación completa del caso de uso seleccionado por cada alumno del equipo.
  #. Un *Product Backlog* completo en *Scrumdesk*, con la especificación inicial como historias de usuario de todas las tareas identificadas en el diagrama de objetivos creado en la fase anterior del proyecto de Ingeniería de Requisitos.
  #. La especificación completa, incluyendo la definición de las pruebas de aceptación, de una historia de usuario por cada alumno del equipo.
  #. Una serie de *mock-ups* que especifiquen, a modo de prototipo, las interfaces de usuario que sería necesario implementar para dar soporte al caso de uso especificado por cada alumno.

El conjunto de ficheros resultantes se entregará dentro de las fechas establecidas a través de la plataforma *Moodle* siguiendo las instrucciones en ella proporcionadas. Las entregas fuera de las fechas establecidas o con un formato diferente al solicitado tendrán una calificación de cero. Cada documento se evaluará y calificará conforme a los criterios especificados en la siguiente sección.

Criterios de Evaluación
=========================

La calificación de la fase de modelado y especificación de objetivos vendrá determinada por la ponderación de las calificaciones de los siguientes apartados:

  #. Completitud del Caso de Uso (1 punto).
  #. Corrección de la Especificación del Caso de Uso (2 puntos).
  #. Completitud de la Historia de Usuario (1 punto).
  #. Corrección de las Tarjetas de la Historia de Usuario (2 puntos).
  #. Corrección de la Confirmación de la Historia de Usuario (1 puntos).
  #. Identificación de Escenarios Alternativos y Excepcionales (2 puntos).
  #. Ortografía, Gramática y Maquetación (1 punto).

Cada uno de estos apartados se calificará mediante el procedimiento y los criterios a continuación proporcionados, excepto *Ortografía, Gramática y Maquetación*, que se evaluará conforme a los criterios establecidos para ello en el correspondiente apartado de la sección de elementos transversales.

Completitud del Caso de Uso e Historia de Usuario
---------------------------------------------------

Para evaluar la completitud del caso de uso, y de la historia de usuario, se verificará que el escenario especificado permita satisfacer de manera satisfactoria el objetivo, u objetivos, para el cual fue creado. Para poder obtener una calificación de aprobado en este apartado, no deberá haber más de una objeción razonable al funcionamiento del caso de uso o historia de usuario. En los casos en los que dicha objeción sea muy evidente, aún cuando sea sólo una, el alumno tampoco podrá obtener una calificación de aprobado o superior en el correspondiente apartado.

Se verificará también que todo caso de uso termine informando al usuario de algún modo acerca del éxito o fracaso de la ejecución del escenario que representa.

Corrección de la Especificación del Caso de Uso
------------------------------------------------

Para calificar la corrección de la especificación del caso de uso creado por el alumnos, se verificará el grado de satisfacción de los siguientes elementos:

  #. El caso de uso tiene un identificador asignado.
  #. El nombre del caso de uso comienza con un verbo.
  #. El nombre del caso de uso es significativo de la acción que realiza.
  #. El actor principal es la persona que inicia, físicamente o a petición suya, la ejecución del caso de uso.
  #. En aquellos casos en los que el actor principal no sea el que físicamente inicie el caso de uso, el actor primario último está correctamente identificado y especificado.
  #. Todos los actores secundarios que intervienen en el caso de uso están correctamente identificados y especificados.
  #. Todos los actores secundarios especificados intervienen explícitamente en el caso de uso.
  #. La descripción del caso de uso no dice nada que pueda ser fácilmente rebatible.
  #. La descripción del caso de uso permite comprender de manera resumida qué hace el caso de uso y cómo lo hace.
  #. La descripción del caso de uso es breve, no siendo superior a 5 líneas, salvo casos muy justificados.
  #. El evento de activación está correctamente identificado.
  #. El evento de activación no contiene referencias a elementos concretos de una interfaz gráfica.
  #. El evento de activación no forma parte del escenario principal.
  #. La precondición especifica un predicado sobre el estado del sistema que ha de ser verdad antes de la ejecución del caso de uso para que éste pueda alcanzar el éxito.
  #. La precondición chequea sólo condiciones que se puedan verificar antes de la ejecución del caso de uso.
  #. La precondición se refiere sólo el estado inicial del sistema y no hace referencia a elementos obvios que puedan ser perfectamente asumibles de manera implícita.
  #. La precondición no chequea condiciones que pudiesen variar espontáneamente durante la ejecución del caso de uso.
  #. Las garantías de éxito establecen claramente cómo se modifica el estado del sistema en caso de que el escenario pueda ejecutarse con éxito.
  #. Las garantías de éxito están especificadas de manera que se facilite la creación de un caso de prueba que verifique su satisfacción.
  #. Las garantías mínimas establecen las condiciones necesarias para asegurar que, en caso de que el escenario no pueda ejecutarse de forma satisfactoria, ningún actor del sistema, ni el propio sistema, resulten perjudicados.
  #. El escenario principal especifica el escenario de éxito habitual que se espera de la ejecución del caso de uso.
  #. Tanto el escenario principal como los escenarios de las extensiones son secuencias lineales de pasos que no contienen bifurcaciones.
  #. El escenario principal no contiene errores ni situaciones excepcionales.
  #. Cada paso del escenario principal, o de una extensión, está adecuadamente numerado.
  #. Cada paso de una extensión está adecuadamente tabulado.
  #. Cada paso del escenario principal está escrito desde una perspectiva de éxito.
  #. Cada paso del escenario principal, o de una extensión, es una interacción usuario-sistema, sistema-usuario, sistema-sistema, una verificación del sistema o una computación.
  #. Cada paso es realizable desde un punto de vista computacional.
  #. Cada paso del escenario principal, o de una extensión, contiene una única acción y no puede ser fácilmente descompuesto en dos pasos.
  #. Cada paso del escenario principal, o de una extensión, tiene claramente identificado el sujeto que realiza la acción.
  #. Cada paso del escenario principal, o de una extensión, que sea una interacción entre el sistema y un actor, tiene claramente identificado tanto el destinatario de la acción como lo que se transfiere entre el sistema y el actor.
  #. Cada paso del escenario principal, o de una extensión, es consistente con el paso anterior. Por ejemplo, si un paso ``X`` se transfiere el control del sistema al usuario, en el paso ``X+1``, el sistema no puede seguir realizando acciones.
  #. Cada paso del escenario principal, o de una extensión, no hace referencia a elementos gráficos concretos, como *botón* o *lista desplegable*, estando estos *widgets* gráficos convenientemente abstraídos.
  #. Cada paso del escenario principal, o de una extensión, que se refiere a un formulario, identifica dicho formulario de manera unívoca.
  #. Cada extensión tiene una condición de extensión claramente especificada.
  #. Cada condición de extensión especifica un evento detectable por el sistema.
  #. Cada extensión referencia al paso del escenario principal, o de otra extensión, donde podría producirse el evento que da lugar a la ejecución de dicha extensión.
  #. El paso inicial de una extensión no vuelve a chequear la condición de extensión.
  #. El paso final de una extensión indica a donde se redirige el flujo de la extensión.
  #. Siempre que el sistema muestre información a un actor, el sistema espera a que el usuario haya leído la información mostrada.

Corrección de las Tarjetas de las Historias de Usuario
--------------------------------------------------------

De todas las historias de usuario especificadas por un alumno, se calificarán las tarjetas de las tres que este alumno decida. Entre esas tres debe estar la historia de usuario que el alumno haya especificado de manera completa. Los nombres de estas tres historias de usuario se indicarán al final de documento que contenga el caso de uso especificado por el alumno.

Para calificar la corrección de la tarjeta inicial asociada a una historia de usuario  se verificará el grado de satisfacción de los siguientes elementos:

  #. La historia de usuario tiene un identificador asignado.
  #. El nombre de la La historia de usuario comienza con un verbo.
  #. El nombre de la La historia de usuario es significativo de la acción que realiza.
  #. La descripción de la historia de usuario sigue el formato ``Yo, como <rol>, quiero <acción> de manera que <objetivo>``.
  #. El rol especificado es correcto.
  #. El rol no es simplemente ``usuario`` en sistemas donde existan usuarios con diferentes tipos de roles.
  #. La acción a ejecutar es clara y consistente con el nombre de la historia de usuario.
  #. El objetivo especificado no es una simple consecuencia de la acción.
  #. El objetivo especificado indica el beneficio real que el actor espera conseguir con la ejecución de la acción.

Corrección de la Confirmación de la Historia de Usuario
--------------------------------------------------------

Para calificar la corrección de la tarjeta inicial asociada a una historia de usuario  se verificará el grado de satisfacción de los siguientes elementos:

  #. Cada prueba de confirmación tiene un título que resume brevemente el propósito de la prueba.
  #. Cada prueba de confirmación está compuesta por un conjunto de pasos de preparación más una serie de verificaciones.
  #. Cada prueba de confirmación está escrita de manera que sea fácilmente implementable como un test automatizado.
  #. Cada paso de una prueba de confirmación es una interacción usuario-sistema, sistema-usuario, sistema-sistema, una verificación del sistema o una computación.
  #. Cada paso de una prueba de confirmación contiene una única acción y no puede ser fácilmente descompuesto en dos pasos.
  #. Cada paso de una prueba de confirmación tiene claramente identificado el sujeto que realiza la acción.
  #. Cada paso de una prueba de confirmación que se refiere a un formulario, identifica dicho formulario de manera unívoca.
  #. Cada verificación expresa una condición que sea computable.

Identificación de Escenarios Alternativos y Excepcionales
----------------------------------------------------------

Para evaluar la completitud de los escenarios alternativos y excepcionales identificados se verificará que existan tanto extensiones como criterios de confirmación para un amplio abanico de situaciones, entre las cuáles se recomienda considerar al menos:

  #. Entrada de datos erróneos por parte del actor primario.
  #. Inactividad del actor primario cuando esta inactividad pueda dejar el escenario en un estado intermedio peligroso para el sistema.
  #. Fallos al acceder a elementos hardware como ficheros alojados en discos duros.
  #. Fallos al acceder a bases de datos.
  #. Fallos al comunicarse con sistemas externos.
  #. Denegación de peticiones realizadas a sistemas externos.
  #. Fallos por falta de recursos para computaciones pesadas.
  #. Fallos al realizar verificaciones internas de condiciones (e.g. disponibilidad de saldo).

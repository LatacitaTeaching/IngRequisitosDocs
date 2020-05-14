==============================================================
 Práctica Opcional - Modelado de Procesos de Negocio con BPMN
==============================================================

Introducción
=============

Toda empresa u organización lleva a cabo una serie de procesos o actividades más o menos predefinidas para la realización de sus actividades ordinarias. Por ejemplo, cuando vamos a una tienda, el dependiente nos atiende conforme a un protocolo que es más o menos similar para todos los clientes. De igual forma, cuando acudimos a una oficina bancaria para solicitar una hipoteca, el empleado que corresponda sigue una serie de pasos predefinidos en los cuales se nos va solicitando una información muy específica. La especificación de estos procedimientos como una secuencia ordenada de pasos con posibles flujos de ejecución alternativos, destacando además los diferentes actores que intervienen y cómo se intercambian mensajes, es lo que se conoce como *proceso de negocio*.

La formalización o definición rigurosa de un proceso de negocio conlleva una serie de ventajas. En primer lugar, permite hacer el proceso explícito y repetible. Cuando un trabajador se jubile, cambie de puesto o trabajo, dicho trabajador será más fácilmente reemplazable por otro, ya que las acciones que el nuevo trabajador debe realizar están claramente especificadas y definidas. Si el proceso no estuviese formalizado, el nuevo trabajador podría realizar  acciones diferentes y cometer errores también cometidos inicialmente por su predecesor en el puesto. El nuevo trabajador irá subsanando dichos errores, hasta converger a un proceso de trabajo depurado, similar al de su predecesor. Este tiempo de depuración por ensayo y error puede fácilmente evitarse haciendo los procesos de negocio explícitos y transferibles entre empleados.

En segundo lugar, la formalización de los procesos de negocio facilita su análisis y mejora. Una vez definido claramente el proceso, podremos diseñar diferentes métricas que permitan analizar su eficiencia. A partir de los resultados de estas métricas se podrían proponer acciones de mejora, introducirlas en los procesos y observar si con dichas acciones conseguimos mejorar los resultados previamente obtenidos.

Dentro del ámbito del desarrollo software, la especificación de procesos de negocio es importante para saber cómo tienen que comportarse los sistemas software que dan soporte a dichos procesos de negocio. Mediante la definición de un proceso de negocio, sabremos qué acciones concretas deberán llevar a cabo los sistemas software ante determinados eventos, qué información necesitan y cómo han de comunicarse con otros sistemas. Dicho de otro modo, un proceso de negocio establece un conjunto de requisitos acerca de cómo ha de comportarse un sistema software. Consecuentemente, todo buen Ingeniero de Requisitos debe saber como especificar y modelar de manera rigurosa procesos de negocio. Por tanto, el objetivo general de esta práctica es que el alumno  se entrene en la especificación de procesos de negocio sencillos utilizando para ello la notación BPMN 2.0, como punto de partida para un posterior aprendizaje más completo del modelado y especificación de procesos de negocio.

Objetivos
==========

Los objetivos concretos de esta práctica son:

  #. Comprender el concepto de proceso de negocio.
  #. Entender la relación entre la definición de procesos de negocio y la captura de requisitos.
  #. Aprender a modelar procesos de negocio sencillos utilizando BPMN 2.0.

La siguiente sección describe las actividades que se deberán realizar para la consecución de estos objetivos concretos.

Actividades
============

Para alcanzar los objetivos descritos en la sección anterior, el alumno deberá crear, utilizando la herramienta Eclipse BPMN2 Modeler, un modelo BPMN 2.0 que especifique el proceso de negocio que se describe a continuación.

Tramites para el Depósito de un TFG
------------------------------------

Una vez que un alumno considere como terminado su Trabajo Fin de Grado, éste deberá iniciar los trámites para su presentación y pública defensa. El primer paso para proceder a dicha presentación será solicitar el visto bueno de su director de Trabajo Fin de Grado.

El director, ante tal petición de visto bueno, revisará el correspondiente Trabajo Fin de Grado e informará al alumno de si se le concede o no dicho visto bueno. Si se lo concede, tras comunicárselo al alumno, el director deberá enviar un correo electrónico al Presidente de la Comisión de Evaluación de Trabajos de Fin de Grado para informarle de que hay un alumno listo para defender públicamente su Trabajo Fin de Grado, facilitando así que se puedan empezar a realizar los trámites oportunos por parte de esta
comisión. Por el contrario, si el director le denegase el visto bueno, éste no deberá hacer nada más y terminará su participación en proceso.

Si el alumno no obtiene el visto bueno de su director de Trabajo de Fin de Grado, deberá revisar su trabajo. Cuando haya realizado las modificaciones oportunas, el alumno podrá solicitar de nuevo el visto bueno de su director; visto bueno que podrá nuevamente ser denegado o concedido.

Una vez que el alumno haya obtenido el visto bueno de su director, éste deberá cumplimentar el impreso para la solicitud de depósito de su Trabajo Fin de Grado, y enviarlo por correo electrónico tanto a su director de Trabajo Fin de Grado como a la Secretaría de la Facultad. A continuación, deberá subir el documento pdf con su memoria de Trabajo Fin de Grado a la plataforma Moodle, dentro del curso y la tarea creados para ello. Tras estos trámites, el alumno deberá esperar a que se le notifique o bien la fecha y hora para la defensa pública de su Trabajo Fin de Grado, o bien la denegación de la solicitud de depósito por incumplir alguno de los requisitos necesarios para poder proceder a dicha defensa pública.

Respecto al director del del Trabajo Fin de Grado, éste, al recibir el correo del alumno con el impreso de solicitud, deberá confirmar a la Secretaría de la Facultad que el alumno tiene autorización para proceder a dicho depósito.
Además, una vez enviada la confirmación de la autorización para el depósito a la Secretaría de la Facultad, el director del Trabajo de Fin de Grado deberá enviar un informe confidencial sobre la calidad del Trabajo de Fin de Grado realizado por el alumno al Presidente de la Comisión de Evaluación de Trabajos de Fin de Grado. Tras este envío, su participacón en este proceso se dará por concluida.

Si el director del Trabajo Fin de Grado indicase a la  la Secretaría de la Facultad que el alumno no tiene autorización para realizar el depósito, ésta  denegará de inmediato al alumno el depósito de su Trabajo Fin de Grado. Por otro lado, si la Secretaría de la Facultad no recibe confirmación de la autorización de depósito por parte director del Trabajo Fin de Grado en el plazo de 5 días tras la recepción por correo electrónico de la solicitud de depósito del alumno, se entenderá dicha solicitud de depósito como no autorizada y se procederá a su inmediata denegación.

En relación a la Secretaría de la Facultad, una vez ésta reciba la confirmación del director del Trabajo Fin de Grado de la autorización para el depósito, comprobará si el alumno cumple o no con los requisitos necesarios para proceder a la defensa pública de su Trabajo Fin de Grado. Si el alumno no cumple dichos requisitos, se procederá a denegar su solicitud de depósito. Si el alumno cumple con los requisitos para el depósito, la Secretaría de la Facultad informará al Presidente de la Comisión para la Evaluación de los Trabajos de Fin de Grado para que asigne fecha, lugar y hora para la celebración de la defensa pública de dicho trabajo. Tras esta notificación, concluye la participación de la Secretaría de la Facultad en este proceso administrativo.

El Presidente de la Comisión para la Evaluación de los Trabajos de Fin de Grado, una vez recibida la notificación de la Secretaría confirmando el depósito de un nuevo Trabajo Fin de Grado formará un tribunal adecuado para la evaluación de dicho trabajo, fijará día, hora y lugar para su lectura y pública defensa, e informará de todos estos datos al alumno, tras lo cual terminará su participación en este proceso.

Elementos a Entregar y Aclaraciones
====================================

Para la evaluación de esta práctica se deberá entregar únicamente uno o más diagramas BPMN 2.0, realizados con la herramienta Eclipse BPMN2 Modeler, que contengan la especificación del proceso de negocio descrito en el punto anterior. Los diagramas deberán entregarse en formato ``png``, no aceptándose otros formatos de imagen.

Dichos diagramas se entregarán a través de la plataforma Moodle siguiendo las instrucciones en ella proporcionadas y dentro de las fechas establecidas. Las entregas fuera de fecha tendrán una calificación de cero.

Las entregas se evaluarán conforme a los criterios de evaluación descritos en la siguiente sección.

Criterios de Evaluación
=========================

La calificación del modelado del proceso de negocio propuesto vendrá determinida por la ponderación de las calificaciones de los siguientes elementos:

  #. Identificación de Participantes (1 punto).
  #. Corrección Sintáctica (1 punto).
  #. Correcta Utilización de las Tareas y Eventos (1 punto).
  #. Correcta Utilización de los Gateways (1 punto).
  #. Corrección Semántica (5 puntos).
  #. Ortografía, Gramática y Maquetación (1 punto).

La calificación de esta práctica será individual y se evaluará conforme a los criterios descritos a continuación.

Identificación de Participantes
---------------------------------

En este apartado se valorará que se hayan identificado correctamente todos los actores que intervienen en el proceso de negocio, y que éstos estén correctamente representados como *participantes (pools)* o *subparticipantes (lanes)*.

Dada la sencillez de este apartado, un único error puede hacer perder la totalidad de sus puntos.

Corrección Sintáctica
-----------------------

En este apartado se valorará que el diagrama BPMN 2.0 creado sea sintácticamente correcto, es decir, que se hayan respetado las reglas del lenguaje. A este respecto, cabe señalar que la herramienta *Eclipse BPMN2 Modeler* es capaz de verificar la corrección sintáctica de los diagramas, señalando con una aspa roja aquellos elementos que puedan considerarse como sintácticamente incorrectos.

Dada la sencillez de este apartado, un único error puede hacer perder la totalidad de sus puntos.

Correcta Utilización de las Tareas y Eventos
---------------------------------------------

Para calificar la correcta utilización de las tareas y eventos, se verificará el grado de satisfacción de los siguientes elementos:

  #. Cada tarea constituye una actividad atómica que no es fácilmente descomponible en dos o más pasos.
  #. Las tareas cuyo resultado sea una comunicación entre participantes generan un mensaje, que es recogido de manera adecuada por el correspondiente participante.
  #. Cada participante tiene correctamente identificado un evento de inicio.
  #. El tipo de evento para iniciar el flujo de actividades de cada participante es adecuado.
  #. El flujo de actividades de cada participante llega un evento de terminación.
  #. Cada nodo de terminación está correctamente identificado como terminación simple o terminación abrupta.
  #. Cada evento de temporización tiene indicado o bien el tiempo que ha de transcurrir desde que se activa hasta que genere un *token* de salida, o bien la hora concreta a la que generará un *token* de salida.
  #. Los eventos basados en la recepción de un mensaje indican el asunto del mesaje cuando éste sea relevante.
  #. Los eventos basados en condición identifican con claridad la condición que ha de cumplirse para que generen un token de salida.

Correcta Utilización de los Gateways
-------------------------------------

En este apartado se valorará que los *gateways* seleccionados para crear bifurcaciones sean correctos con respecto a su propósito, así como que las condiciones de sus flujos condicionales, cuando proceda, estén correctamente identificadas.

Más concretamente, se analizará el grado de satisfacción de los siguientes elementos:

  #. Las bifurcaciones basadas en eventos tienen identificadas al menos dos eventos.
  #. Las bifurcaciones exclusivas tienen un conjunto de condiciones mutuamente excluyentes.
  #. Las bifurcaciones exclusivas o inclusivas poseen flujos condicionales suficientes para cubrir todas las situaciones posibles que fuese necesario tratar.
  #. Las bifurcaciones paralelas convergentes se utilizan para sincronizar flujos de ejecución que deban sincronizarse en un punto determinado.
  #. Las bifurcaciones inclusivas convergentes se utilizan para unir flujos de ejecución alternativos donde uno solo de ellos podría estar activo en un momento dado.
  #. Se diferencia correctamente entre bifurcación divergente exclusiva e inclusiva.

Corrección Semántica
---------------------

En este apartado se valorará que todo lo indicado en la descripción textual del proceso de negocio quede reflejado en algún apartado del diagrama BPMN 2.0 que lo modela, y que todo lo que aparece en el diagrama del proceso de negocio sea conforme a la descripción textual del proceso de negocio. Se verificará también que cada tarea esté correctamente asignada al participante que deba realizarla.

Ortografía, Gramática y Maquetación
-------------------------------------

Para calificar la ortografía, gramática y maquetación, se verificará el grado de satisfacción de los siguientes elementos:

  #. Los textos que aparecen en el diagrama están libres de errores tipográficos u ortográficos.
  #. Los textos que aparecen en el diagrama están libres de errores gramaticales.
  #. Los elementos del diagrama están, en general, bien alineados.
  #. Los elementos del diagrama no están solapados.
  #. El diagrama es, con carácter general, compacto, sin existir un espaciado excesivo entre sus elementos.
  #. El diagrama se lee bien de izquierda a derecha.
  #. Las líneas entre elementos son, con carácter general, líneas rectas.
  #. Los cruces de líneas se evitan, en la medida de lo posible.
  #. El diagrama, con carácter general, se percibe como ordenado y limpio.

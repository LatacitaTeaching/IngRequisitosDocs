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
  #. Entender la relación entre la definición de un proceso de negocio y la captura de requisitos.
  #. Aprender a modelar procesos de negocio sencillos utilizando BPMN 2.0.

La siguiente sección describe las actividades que se deberán realizar para la consecución de estos objetivos concretos.

Actividades
============

Para alcanzar los objetivos descritos en la sección anterior, el alumno deberá crear, utilizando la herramienta Eclipse BPMN2 Modeler, un modelo BPMN 2.0 que especifique el proceso de negocio que se describe a continuación.

Presentación de un TFG
-----------------------

Una vez que un alumno considere como terminado su Trabajo Fin de Grado, éste deberá iniciar los trámites para su presentación y pública defensa. El primer paso para proceder a dicha presentación será solicitar el visto bueno de su director de Trabajo Fin de Grado. El director, ante tal petición de visto bueno, revisará el Trabajo Fin de Grado e informará al alumno de si le concede o no dicho visto bueno. Si se lo concede, el director deberá enviar un correo electrónico al Presidente de la Comisión de Evaluación de Trabajos de Fin de Grado para informarle que hay un alumno listo para defender públicamente su Trabajo Fin de Grado, facilitando así que dicho Presidente pueda empezar a realizar los arreglos que estime oportunos. Si no le concede el visto bueno, el director no deberá hacer nada más y terminará su proceso, espera de que el alumno modique su trabajo y vuelva a solicitar un nuevo visto bueno.

Si el alumno no obtiene el visto bueno de su director de Trabajo de Fin de Grado, éste deberá revisar su trabajo. Cuando haya realizado las modificaciones solicitadas, el alumno podrá solicitar de nuevo el visto bueno de su director; visto bueno que podrá nuevamente ser denegado o concedido.

Si el alumno obtiene el visto bueno, el alumno deberá cumplimentar el impreso para la solicitud de depósito de su Trabajo Fin de Grado, y enviarlo por correo electrónico tanto a su director de Trabajo Fin de Grado como a la Secretaría de la Facultad. A continuación, deberá subir el documento pdf con su memoria de Trabajo Fin de Grado a la plataforma Moodle, dentro del curso y la tarea creada para ello. Tras estos trámites, el alumno deberá esperar a que se le notifique la fecha y hora para la defensa pública de su Trabajo Fin de Grado, o la denegación de la solicitud de depósito por incumplir alguno de los requisitos necesarios para poder proceder a dicha defensa pública.

El director del Trabajo Fin de Grado, al recibir el correo del alumno con el impreso de solicitud, deberá confirmar a la Secretaría de la Facultad que el alumno tiene autorización para proceder al depósito. Si el director del Trabajo Fin de Grado indicase que el alumno no tiene autorización para realizar el depósito, la Secretaría de la Facultad cancelará de inmediato todos los trámites para el depósito del Trabajo Fin de Grado del Alumno. Si la Secretaría de la Facultad no recibe confirmación del director del Trabajo Fin de Grado en el plazo de 5 días, procederá inmediatamente a la cancelación de todos los trámites para el depósito.

Por otra parte, una vez enviada la confirmación de la autorización para el depósito a la Secretaría de la Facultad, el director del Trabajo de Fin de Grado deberá enviar un informe confidencial sobre la calidad del Trabajo de Fin de Grado realizado por el alumno al Presidente de la Comisión de Evaluación de Trabajos de Fin de Grado. Tras este envío, su participacón en este proceso se dará por concluida.

La Secretaría de la Facultad, una vez recibida la confirmación del director del Trabajo Fin de Grado, comprobará si el alumno cumple o no con los requisitos necesarios para proceder a la defensa pública de su trabajo. Si no los cumple, se cancelarán inmediatamente todos los trámites. Si los cumple, informará al Presidente de la Comisión de Evaluación de Trabajos de Fin de Grado para que asigne fecha, lugar y hora para la celebración de la defensa pública del trabajo. Tras esta notificación, concluye la participación de la Secretaría de la Facultad en este proceso administrativo.

Por otro lado, una vez recibida la notificación de la Secretaría, el Presidente de la Comisión de Evaluación de Trabajos de Fin de Grado notificará al alumno la fecha, lugar y hora para la defensa pública de su Trabajo Fin de Grado.

Tras recibir el alumno esta notificación, se da por concluido el proceso administratibo de depósito de un Trabajo Fin de Grado.

Elementos a Entregar y Aclaraciones
====================================

Para la evaluación de esta práctica se deberá entregar únicamente uno o más diagramas BPMN 2.0, realizados con la herramienta Eclipse BPMN2 Modeler, que contengan la especificación del proceso de negocio descrito en el punto anterior. Los diagramas deberán entregarse en formato ``png``, no aceptándose otros formatos de imagen.

Dichos diagramas se entregarán a través de la plataforma Moodle siguiendo las instrucciones en ella proporcionadas y dentro de las fechas establecidas. Las entregas fuera de fecha tendrán una calificación de cero.

Las entregas se evaluarán conforme a los criterios de evaluación descritos en la siguiente sección.

Criterios de Evaluación
=========================

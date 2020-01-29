===================================
 Gestor de Planes de Convalidación
===================================

Este caso de estudio está basado en el Proyecto Fin de Carrera de *D. Antonio Cuenca González*, presentado y defendido con éxito en Marzo de 2003, y accesible a través de este `enlace <https://repositorio.unican.es/xmlui/handle/10902/1932>`_.

El objetivo de dicho proyecto era desarrollar un sistema de información para la gestión de los expedientes alumnos de intercambio (Erasmus o Séneca) dentro de la Escuela Universitaria de Enfermería de la Universidad de Cantabria. Por cada alumno de intercambio, hay que generar un plan de convalidaciones que detalle las asignaturas a cursar en la universidad de destino y, en caso de superarlas, las convalidaciones de asignaturas que se obtendrán en la universidad de origen. Este plan de convalidaciones deben ser conformes a una serie de normas impuestas tanto por la universidad de origen como por la universidad de destino. El enlace disponible más abajo proporciona un ejemplo de plan de convalicación.

:download:`Ejemplo de Plan de Convalidación <src/planConvalidacion.pdf>`

Los administrativos de la Escuela de Enfermería habían estado realizando estos planes de convalidación de manera completamente manual, a partir de una plantilla Word que completaban, imprimían, almacenaban y gestionaban en papel.
Esto tiene asociado una serie de problemas de sobra conocidos:

  #. Al gestionarse los expedientes manualmente, no es descartable la existencia de errores humanos que transpapelen o pierdan ciertos expedientes.
  #. Las búsquedas de expedientes concretos son más lentas, pues han de realizarse manualmente. Este tiempo puede verse incrementado notablemente si, por algún tipo de error, algún papel estuviese mal clasificado.
  #. Los expedientes físicos podrían dañarse o perderse por diversos motivos, como un incendio o inundación que afectase a la Secretaría de la Escuela. De manera más mundana, un simple café que se vuelque sobre un expediente podría compromoter seriamente su integridad.
  #. Los expedientes físicos pueden ocupar un cierto volumen que podría reducirse drásticamente si se gestionasen de manera digital.
  #. Los archivos digitales son más fácilmente duplicables que los archivos físicos, por lo que es más sencillo obtener copias de respaldo de dichos archivos.
  #. Al chequearse todas las normas que deben aplicarse a un plan de convalidacionesde manera manual no es descartable la presencia de errores humanos que den lugar a planes de convalidaciones que incumplan la normativa vigente.
  #. La comprobación manual de que cada expediente es conforme a la normativa actual de cada universidad requiere actualmente un considerable esfuerzo, esfuerzo que podría ahorrarse si estas comprobaciones pudiesen automatizarse de alguna forma.

Por todas estas razones, y dado el creciente número de alumnos de intercambio la Secretaría de la Escuela Universitaria de Enfermería de la Universidad de Cantabria decidió llevar a cabo la informatización este proceso administrativo y encargar a D. Antonio Cuenca el desarrollo de una aplicación software con las siguientes características generales.

La aplicación debía ser capaz de gestionar información asociada a las diversas universidades que participen en programas de intercambio con la Universidad de Cantabria. Por ejemplo, si se estableciese un acuerdo de intercambio de estudiantes entre la Universidad de Cantabria y la Universidad de York, el sistema debería permitir añadir información sobre esta universidad al sistema. Esta información costaría de diversos elementos, como datos de contacto, persona responsable de los programas de intercambio en dicha universidad, o asignaturas existentes en su plan de estudios, entre otros elementos.

La aplicación debe también incorporar y gestionar los datos de los alumnos que participen en estos programas de intercambios. Para los alumnos que pertenezcan a la Universidad de Cantabria, se desea poder importar estos datos automáticamente desde el propio campus virtual de la Universidad.

La aplicación también debe guiar y asesorar al personal de la Escuela de Enfermería a la hora de proponer convalidaciones de asignaturas. Para ello, por cada asignatura a convalidar, el sistema deberá mostrar las asignaturas de la universidad de origen o destino que podrían participar en dicha convalidación. Para ello, el sistema tendrá que tener en cuenta la normativa existente en cada universidad. Por ejemplo, la normativa actual de la Universidad de Cantabria impide que se puedan convalidar asignaturas cursadas durante un Erasmus por asignaturas ya cursadas y que se encuentren suspensas.

Dado que el sistema maneja información personal de los alumnos, deberá ser conforme a todas las leyes de privacidad y protección de datos que sean aplicables a dicha información personal. Además, el sistema, en la medida de lo posible, deberá integrarse en las aplicaciones existentes dentro del campus virtual de la Universidad de Cantabria o, al menos, interoperar de manera transparente con él.

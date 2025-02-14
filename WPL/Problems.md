# &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;Problemas - WPL
# &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; NexOng - Grupo 5

***MIEMBROS***:

<table>
  <tr>
    <td>AURORA NAVAS JIMÉNEZ</td>
    <td>MARÍA NÚÑEZ REYES</td>
    <td>CLAUDIA GILABERT PRIETO</td>
  </tr>
  <tr>
    <td>MARTA INÉS GONZÁLEZ DIÁNEZ</td>
    <td>FÉLIX ÁNGEL GUDIEL GÜEMES</td>
    <td>MIGUEL ANGEL ROMALDE DORADO</td>
  </tr>
  <tr>
    <td>FRANCISCO DE ASÍS ROSSO RAMÍREZ</td>
    <td>PABLO PERIÁÑEZ CABRERO</td>
    <td>FRANCISCO JAVIER CALDERÓN RODRÍGUEZ</td>
  </tr>
  <tr>
    <td>PEDRO LOPEZ RUZ</td>
    <td>IVÁN RAMÍREZ LARA</td>
    <td>SAMUEL LUIS RODRÍGUEZ MANESS</td>
  </tr>
  <tr>
    <td>MANUEL ORTIZ BLANCO</td>
    <td>SERGIO AGUAYO OROZCO</td>
    <td>JUAN LUIS RUANO MURIEDAS</td>
  </tr>
  <tr>
    <td>MANUEL FRANCISCO BARCIA JIMENEZ</td>
    <td></td>
    <td></td>
  </tr>
</table>

<a name="br2"></a> 

## Índice
1. Registro de cambios
2. Introducción
3. Registro
4. Soluciones

## Registro de cambios
**Versión** | **Fecha** | **Descripción**| **Redacción** | **Revisión**
--- | --- | --- | --- | --- 
1.0.0 | 7/3/2024 | Semana 6 | SAMUEL LUIS RODRÍGUEZ MANESS | MARÍA NÚÑEZ REYES
2.0.0 | 16/3/2024 | Semana 7 | MARÍA NÚÑEZ REYES | CLAUDIA GILABERT PRIETO
3.0.0 | 30/3/2024 | Semana 8 | PEDRO LÓPEZ RUZ | SAMUEL LUIS RODRÍGUEZ MANESS
4.0.0 | 7/4/2024 | Semana 9 | PEDRO LÓPEZ RUZ Y SAMUEL LUIS RODRÍGUEZ MANESS | MARÍA NÚÑEZ REYES
5.0.0 | 19/4/2024 | Semana 10 | PEDRO LÓPEZ RUZ| MARÍA NÚÑEZ REYES
6.0.0 | 27/4/2024 | Semana 11 | PEDRO LÓPEZ RUZ| MARÍA NÚÑEZ REYES
7.0.0 | 04/5/2024 | Semana 12 | PEDRO LÓPEZ RUZ| SAMUEL LUIS RODRÍGUEZ MANESS
8.0.0 | 10/5/2024 | Semana 13 | FRANCISCO DE ASÍS ROSSO RAMÍREZ | JUAN LUIS RUANO MURIEDAS



## Introducción
Este documento recopila los problemas encontrados a lo largo de todo el proceso de desarrollo del proyecto. Por cada problema se especifica el conflicto en sí, cuando se dio, cómo (y cuándo) se resolvió y el impacto que tuvo sobre el proyecto.

Este historial no debe sólo informar sobre el historial del desarrollo de la aplicación, sino también servir como referencia para futuros problemas y poder actuar en concordancia a ellos.

## Registro
### Desacuerdos y falta de confianza entre miembros del equipo
Algunos miembros del equipo han mostrado su frustración en la reunión del día 5 de marzo ante la actitud que se ha presentado a la hora de comunicarse con sus líderes o con otros compañeros. Se han detectado faltas de respeto y de orden por lo que se ha hecho uso de una mediadora para resolver este problema.

### Disconformidad general con las medidas de auto-evaluación del equipo y falta de transparencia
La mayoría del equipo ha sentido que las medidas de evaluación que se realizan sobre otros miembros no han sido correctas. Por una parte, es complicado ofrecer una valoración realista a las personas con las que menos contacto se ha tenido, además no se ha considerado algunas valoraciones justas cuando algunas encuestas son de carácter objetivo. Luego, se desea buscar un nivel más alto de transparencia a la hora de realizar la rúbrica del rendimiento de cada persona, para poder presentar dudas y tener los motivos de nuestra nota visibles.
En la reunión del pasado martes 12 de marzo, se ha seguido mostrando disconformidad con las notas anteriores. Parte del equipo ha sentido que las medidas de evaluación que se realizan sobre otros miembros no han sido correctas ni justas. Por una parte, es complicado ofrecer una valoración realista a las personas con las que menos contacto se ha tenido, además no se ha considerado algunas valoraciones justas, cuando algunas encuestas son de carácter objetivo. Luego, se desea buscar un nivel más alto de transparencia a la hora de realizar la rúbrica del rendimiento de cada persona, para poder presentar dudas y tener los motivos de nuestra nota visibles.

### Problemas con las políticas de ramas y commits
Las políticas de ramas y de commits buscan asegurar el cumplimiento uniforme y correcto al trabajar con git flow, pero se ha comprobado que también puede causar problemas. Algunos conflictos de una rama por las medidas del conventional commits acabaron afectando a varios miembros de modo que no podían hacer sus Pull Requests.

### Miembros desconocen el estado general del proyecto
Algunos miembros del equipo no realizan sus tareas de forma correcta y hay pérdidas de tiempo al no leer todos los requisitos del cliente y no dedicar un repaso al estado del progreso del proyecto, y lo que están haciendo otros miembros. Esto también provoca tener que empezar algunas tareas desde el principio.

### Poca atención a la descripción de las issues por parte de algunos miembros
Algunos miembros del equipo han sufrido retrasos en sus tareas por no comprender los requerimientos de algunas issues, por no leer detenidamente la descripción de éstas.

### Discordancia entre backend y frontend
La coordinación entre backend y frontend no ha sido muy acertada estas primeras semanas. Debido a la incompatibilidad de los atributos necesitados en frontend y los implementados en backend, el equipo de frontend ha tenido que aplazar alguna issue y adelantar contenido del sprint 3 para tener suficiente trabajo que implementar esta semana. Esto puede haberse debido a la disparidad en la planificación inicial, errores de concepción de algunos requisitos y falta de seguimiento del *mockup*.

### Merge Problemático

Un miembro del equipo al integrar una funcionalidad realizó por error un pull de una rama que no debería haber hecho provocando fallas en las siguientes implementaciones a partir de esa.

### Incumplimiento Commitment Agreement por los usuarios pilotos

El grupo de la tarde y el nuestro firmamos un commitment agreement en el cual nos comprometiamos a desplegar la aplicación el lunes 25 de marzo  y tener para testear ese mismo lunes hasta el miércoles 27 de marzo. Llegado ese lunes, nuestro grupo ya tenía desplegado la aplicación como habíamos firmado, pero el otro grupo no estaba en la misma situación alegando a una miembro de nuestro equipo que habían tenido problemas y que si podíamos cambiar el commitment agreement a más tarde, a lo que nosotros respondimos con una negativa, debido a que ya estaba firmado y cambiarlo supondría el incumplimiento total del mismo.

### Problemas con los permisos de algunas funcionalidades

Durante la realización de los test en el backend, varios compañeros se dieron cuenta de que faltaban permisos para una serie de funcionalidades como por ejemplo la creación de familias. Tras investigar la causa se comprobó que provenía de una implentación, la cual, trataba de adjuntar los permisos admin de las aplicaciones, pero durante el desarrollo de la misma omitió algunos permisos provocando errores. Debido a esto el frontend no pudo trabajar de manera fluida debido que se les impedían realizar varias funciones para probar sus métodos implementados.

Haciendo enfoque en la parte del frontend, por errores similares al mencionado anteriormente algunos miembros han tenido que empezar sus tareas más tarde de lo habitual y han sido acabadas mucho más cerca de la deadline, mientras que otras no han sido terminadas.

### Incumplimiento de Commitment Agreement por los usuarios pilotos de nuevo

Como comentamos en anteriores apartados, el grupo de tarde y el nuestro firmamos un acuerdo por el que nos comprometíamos a ejercer de usuarios pilotos en unas fechas establecidas. El anterior acuerdo fue roto por el grupo de tarde, ya que les tomaron más tiempo ofrecernos su aplicación desplegada y cuando la recibimos era muy básica con poco que testerar. Recordando esto, nos comprometimos en el Commitment Agreement que el día lunes 15 de abril ambos grupos deberíamos de tener la aplicación desplegada, para poder testear hasta el día jueves de 18 de abril. Llegado ese lunes nuestro grupo desplegó la aplicación y avisó al grupo de tarde de que ya podían testear. Posteriormente, el grupo de tarde, demorándose un poco más, entregó un link con la supuesta aplicación desplegada y con el formulario para realizar el testeo a través de Discord, sin proporcionarnos ningún tipo de landing page. Tras esto, una compañera de nuestro grupo, encargada de comunicarse con el grupo de tarde, entró a testear la aplicación encontrando, para su sorpresa, una aplicación sin terminar en donde había errores, enlaces que no te redirigían a ningún sitio y en resumen, era prácticamente el enlace que nos habían entregado en el testeo del S2. Tras comprobar el contenido nuestra compañera se puso en contacto con uno de los miembros del otro grupo, alegando una explicación a lo que respondió textualmente que nos habían querido engañar, ya que no tenían la aplicación para nada terminada y que no iban a poder terminarla, por lo que nos dijeron que como muy pronto sería el mismo día de la entrega del S3.

 ### Horas de Trabajo establecidas

En primeras semanas de trabajo de curso, establecimos una serie de horas de trabajo para realizar el trabajo para la ONG. Llegada a la última semana del Sprint 3 nos dimos cuenta que ya se había sobrepasado ese límite y que estábamos jugando con el 10% de contingencia de horas que establecimos como posible riesgo de que algo así se diese.

## Soluciones
Las soluciones que se pondrán o ya se han puesto en marcha para resolver los problemas anteriores son los siguientes:
- Mediante un mediador, se ha recordado a las personas involucradas en el conflicto personal lo importante que es el respeto entre los miembros de un equipo y se ha llegado a un compromiso mediante el diálogo para continuar el proyecto lo mejor posible.
- Se ha creado un nuevo sistema de evaluación entre los miembros del equipo que ha sido votado por los miembros. Queda por aprobarse para que se convierta en el modelo de evaluación oficial. Algunas de estos cambios son:
   - Baja el porcentaje a 10%
   - Se simplifica la rúbrica, eliminando algunos apartados objetivos
   - Se incluye el poker planning como medida objetiva para el rendimiento
   - Los miembros del equipo miden el rendimiento del PM y los Team Leader.
Tras el avance de las semanas se realizó algunos cambios en la forma de evaluación, en concreto en el formulario de evaluación, donde se ha incluido un campo de texto obligatorio en el cual se debe de expresar el motivo de dicha puntuación además de puntos de mejora y flaqueza.
- Se han relajado las restricciones a la hora de hacer commits para evitar posibles desastres por bloqueos. Sin embargo, el incumplimiento continuo de las conventional commits se penalizará tras varios avisos.
- Se recordará a los miembros del equipo la importancia de hacer una revisión general al proyecto, de informarse sobre los requerimientos de su tarea y de leer bien las descripciones de las issues. También hay que esforzarse por escribir descripciones lo más claras y detalladas posibles, así como dejar un buen comentario de revisión.
- Buscar una mayor alineación entre los requerimientos solicitados por las páginas y la base de datos del backend a través del diálogo entre ambos equipos.
- Una vez se localizó el problema del merge se creo un rama Hotfix para intentar mitigar los daños causados 
- Tras trasladar nuestro pensamiento de no cambiar el commitment agreement, los usuarios piloto del grupo de tarde aceptaron las condiciones muy a su pesar y enviaron una versión desplegada de la aplicación ese mismo día.
- Tras localizar los errores se lanzó una rama hotfix que corregía dichos permisos y se lanzó una pull request para comprobar que verdaderamente se había realizado el cambio.
- Se notificó a los miembros de frontend del arreglo y se consiguió trabajar en condiciones finalmente.
- Una vez recibida tal respuesta del grupo de tarde, la compañera expresó su decepción, alegando que no estaba bien lo que habían hecho y que por lo tanto, aunque nosotros no pudiésemos testear, ellos deberían de realizar el testeo en la fecha acordada de nuestra aplicación.
- Tras visualizar el problema de las horas, decidimos establecer todas esas tareas extraoficiales (Trabajo desarrollado durante la Semana de Santa y Feria) a trabajo de voluntariado ya que la ONG nos pedía cada vez nuevas cosas y no éramos capaces de decirles que no. Además, establecimos un límite de horas por miembro en el cual toda tarea que sobrepasase ese límite (siempre y cuando no sea obligatorio reflejarlo) se consideraría como trabajo de voluntariado.

## Resultados

Los resultados tras la aplicación de las soluciones:

- Tras la mediación se ha obtenido un ambiente de trabajo más calmado, en donde se realizan comentarios por cada discrepancia que vaya apareciendo para llegar a un consenso entre todos los miembros del grupo. Tras el avance de las semanas la figura del mediador se ha convertido en una pieza importante debido a que muchas discrepancias eran fundadas por las evaluaciones, por ello el tener un mediador para posicionarse de manera neutral en este tipo de caso tan peliagudos han ayudado tanto a los Team Leaders a reducir carga de trabajo, como a controlar desacuerdos antes de llegar a situaciones más tensas. Ya en esta semana final, la figura del mediador ha tenido un papel mucho menor casi inexistente ya que no hemos coordinado a la perfección y sin crearnos problemas entre unos y otros.
  
- Respecto al sistema de evaluación, estos cambios han generado multitud de opiniones tanto a favor como en contra, es decir, hay miembros cuyo nota sobrepasa el 10 apareciendo calificaciones de 11 u 12 y otros con una calificación más baja y para ellos injusta. Con el nuevo formulario, se ha conseguido paliar las confrontaciones debido a que al ser público las evaluaciones y también quién es la persona evaluante y juzgada, se ha conseguido que haya una revisión tras la publicación de las notas para hablar con los damnificados y llegar a un acuerdo siempre y cuando sea fundamentado. Además, se ha propuesto que las personas cuyas notas sean superiores a la nota máxima puedan escalar sus notas en calificaciones de otros Sprints suyos y por otro lado si se observa que un miembro del grupo trabaja bien y se ha notado una mejoría tras el paso de las semanas se consideraría asignar la nota máxima en los Sprints.
  
- Tras relajar las restricciones a la hora de realizar los commits y pull request ha fluido un poco mejor el trabajo pero todavía a final de semana seguían habiendo pull requests por aprobar y por ello se ha sugerido que todos los miembros del equipo activen las notificaciones por email para mitigar la ralentización. Ya pasadas unas semanas, el limitar las políticas de ramas ha sido un acierto, ya que se ha agilizado mucho más el cierre de las pull request sobre todo en soluciones de bugs, donde es necesario un rápido cierre para que puedan trabajar el equipo de frontend. Además, los miembros han seguido a rajatabla la política de ramas y no ha habido ningún incumplimiento.
  
- Una vez dejado clara la importancia de realizar una buena lectura de las issues y esforzarse por escribir descripciones lo más claras y detalladas posibles, así como dejar un buen comentario de revisión, han aparecido nuevos comentarios en las reviews mucho más ricas tanto por parte de quien ha implementado la issue incorporando formas de cómo acceder a la tarea realizada y cómo probarla, como por parte de los revisores. Esto con el avance de las semanas ha ayudado mucho, debido a que se ha agilizado el trabajo y los miembros del equipo, han preguntado más dudas a sus respectivos Team Leaders, para no realizar ningún tipo de trabajo en vano.
  
- Acerca de la comunicación entre backend y frontend, se ha incrementado la participación de los miembros de frontend preguntando dudas al equipo de backend, aunque todavía hay discrepancias lingüísticas entre miembros, es por ello que varias personas en la retrospectiva han propuesto realizar una reunión en próximas semana entre ambos equipos. Además, se propuso que los Team Leaders de ambos subgrupos realizasen reuniones de forma semanal para coordinar ambos grupos y que no dependiese tanto el frontend del trabajo realizado del backend sino que el frontend tuviera margen de trabajo mientras que el backend iba adelantando tareas. Ya en estas semanas finales, se le ha preguntado a ambos TL sobre esta medida y cómo se ha llevado a cabo por parte de ambos. En primer lugar, la TL de Frontend ha expresado que con la reuniones, el trabajo se ha realizado de forma más controlada, aunque en un principio el equipo de frontend adoptó las medidas más lentamente, en esta últimas semanas se ha notado una gran mejoría. Por parte del TL de backend, ha expresado la gran mejoría desde que se interpuso la norma, aunque recalca que la coordinación no ha sido perfecta al 100% debido a que lo que él expresaba por su parte a la TL de fronted algunas veces no se llevaba a cabo, como se había acordado en la reunión.
  
- Tras revertir los cambios, el miembro del equipo en cuestión pidió perdón y revirtió el merge en su rama haciendo que se solucionase el problema. Además, al integrarse la rama hotfix en develop, los demás miembros al hacer pull de la misma en sus ramas, solucionaron los errores causados.
  
- Cuando los usuarios pilotos de nuestro grupo accedieron a la versión desplegada del grupo de tarde, rápidamente se dieron cuenta de que era una versión bastante básica sin apenas funcionalidades, por lo que no pudieron testear demasiado.
  
- Una vez aceptada la pull request e integrada en la rama develop, el equipo frontend pudo trabajar sin ningún tipo de problema.

- Finalmente, llegados el jueves 19 de abril, el grupo de tarde realizó el formulario por lo que no llegaron a incumplir totalmente el acuerdo. Una semana después, concretamente el miércoles 24 de abril el grupo de tarde nos pasó el enlace de su despliegue y pudimos ejercer de usuarios piloto. El ejercer de usuarios pilotos no ha sido una tarea fácil, ya que la aplicación poseía muchos problemas tanto de carga, como funcionales y muchos miembros del equipo no entendían si eran problemas nuestros o por parte de ellos.
  
- Tras adoptar esta medida de límite de horas se ha reducido el riesgo y de esta manera se ha adoptado una nueva planificación compatible con las horas restantes.

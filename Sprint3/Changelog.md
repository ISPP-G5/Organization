# Changelog - Sprint 3
# NexOng - Grupo 5


## Índice

1. Introducción

2. Sprint 1

    2.1. Incrementos Sprint 1
   
    2.2. Mejoras Sprint 1

    2.3. Arreglos Sprint 1
   
3. Sprint 2

    3.1. Incrementos Sprint 2
   
    3.2. Mejoras Sprint 2

    3.3. Arreglos Sprint 2
   
4. Sprint 3

    4.1. Incrementos Sprint 3
   
    4.2. Mejoras Sprint 3

    4.3. Arreglos Sprint 3
   

## Registro de cambios


<table>
  <tr>
   <td><strong>Versión</strong>
   </td>
   <td><strong>Fecha</strong>
   </td>
   <td><strong>Descripción</strong>
   </td>
   <td><strong>Redacción</strong>
   </td>
   <td><strong>Revisión</strong>
   </td>
  </tr>
  <tr>
   <td>1.0.0</td>
   <td>21/4/2024</td>
   <td>Primera versión</td>
   <td>FRANCISCO DE ASÍS ROSSO RAMÍREZ</td>
   <td>
     <ul>
     <li>CLAUDIA GILABERT PRIETO</li>
     <li>PABLO PERIÁÑEZ CABRERO</li>
     </ul>
    </td>
  </tr>
</table>



<br/>

# 

<br/>



#  1. Introducción

En este documento se recogen los avances realizados en el proyecto durante el desarrollo del proyecto
en cada Sprint, divididos en: incrementos o *features* (nuevas características del proyecto), mejoras o *improvements* (continuación del desarrollo de partes de código ya hechas anteriormente para actualizarlas o proporcionarles una mejor utilidad) y arreglos o *fixes* (reparación de partes del código que nofuncionaban correctamente o se han quedado obsoletas). Cada apartado se desglosa en las partes
*backend* y *frontend*.



# 2. Sprint 1


## 2.1. Incrementos Sprint 1

### Backend

- **[Dummy data (#3)](https://github.com/ISPP-G5/NexONG_Backend/issues/3)**.
    - Añadidos datos de prueba para frontend.

- **[DB schema implementation (#5)](https://github.com/ISPP-G5/NexONG_Backend/issues/5)**.
    - Implementado el esquema de la base de datos.
 
- **[Users CRUD (#9)](https://github.com/ISPP-G5/NexONG_Backend/issues/9)**.
    - Implementadas las operaciones CRUD para usuarios.
 
- **[Creación api rest (#14)](https://github.com/ISPP-G5/NexONG_Backend/issues/14)**.
    - Creada API REST.
 
- **[Add corsheader and readme update (#17)](https://github.com/ISPP-G5/NexONG_Backend/issues/17)**.
    - Añadido corsheader.
    - Actualizado README.md.
 
- **[Upload documents to the DB (#18)](https://github.com/ISPP-G5/NexONG_Backend/issues/18)**.
    - Añadida la posibilidad de subir documentos a la base de datos.
 
- **[Meeting CRUD (#19)](https://github.com/ISPP-G5/NexONG_Backend/issues/19)**.
    - Implementadas las operaciones CRUD para reuniones.
 
- **[Event CRUD (#20)](https://github.com/ISPP-G5/NexONG_Backend/issues/20)**.
    - Implementadas las operaciones CRUD para eventos.
 
- **[Student and CentreExit CRUD (#21)](https://github.com/ISPP-G5/NexONG_Backend/issues/21)**.
    - Implementadas las operaciones CRUD para alumnos.
    - Implementadas las operaciones CRUD para salidas.
 
- **[Lesson CRUD (#24)](https://github.com/ISPP-G5/NexONG_Backend/issues/24)**.
    - Implementadas las operaciones CRUD para clases.
 
- **[Evaluation CRUD (#25)](https://github.com/ISPP-G5/NexONG_Backend/issues/25)**.
    - Implementadas las operaciones CRUD para evaluaciones.
 
- **[User, Educator, Partner, Volunteer y Family CRUD (#48)](https://github.com/ISPP-G5/NexONG_Backend/issues/48)**.
    - Implementadas las operaciones CRUD para educadores.
    - Implementadas las operaciones CRUD para voluntarios.
    - Implementadas las operaciones CRUD para familias.
 
- **[Donation CRUD (#55)](https://github.com/ISPP-G5/NexONG_Backend/issues/55)**.
    - Implementadas las operaciones CRUD para donaciones.


### Frontend

- **[Home page (#1)](https://github.com/ISPP-G5/NexONG_Frontend/issues/1)**.
    - Implementada la página de inicio de la aplicación.
 
- **[Screen for the creation of the form (#2)](https://github.com/ISPP-G5/NexONG_Frontend/issues/2)**.
    - Añadida una pantalla con el formulario de voluntarios.
 
- **[Navbar-Activities (#3)](https://github.com/ISPP-G5/NexONG_Frontend/issues/3)**.
    - Añadidas las pantallas de actividades a la página principal.
 
- **[Admin-Families (#9)](https://github.com/ISPP-G5/NexONG_Frontend/issues/9)**.
    - Añadida sección "Familias" a la pantalla de administradores.
 
- **[Admin screen-Account configuration (#10)](https://github.com/ISPP-G5/NexONG_Frontend/issues/10)**.
    - Añadida pantalla de configuración para administradores.
 
- **[Feature/11-Admin screen- Lessons, events, projects (#11)](https://github.com/ISPP-G5/NexONG_Frontend/issues/11)**.
    - Añadidas a la pantalla de administradores las secciones "Clases", "Eventos" y "Proyectos".
 
- **[App styles (#12)](https://github.com/ISPP-G5/NexONG_Frontend/issues/12)**.
    - Definidos estilos para la aplicación.
 
- **[Feature/40-Connection with the backend (#40)](https://github.com/ISPP-G5/NexONG_Frontend/issues/40)**.
    - Implementada la conexión entre backend y frontend mediante un entorno para desarrollo y otro para despliegue.
 
- **[Feature/50-Agenda2030 (#50)](https://github.com/ISPP-G5/NexONG_Frontend/issues/50)**.
    - Añadida una pantalla de la agenda 2030 a la barra de navegación.
 
- **[Feature/51-Volunteers (#51)](https://github.com/ISPP-G5/NexONG_Frontend/issues/51)**.
    - Creada la pantalla de voluntarios.
 
- **[Feature/52-AssociationDropdown-1 (#52)](https://github.com/ISPP-G5/NexONG_Frontend/issues/52)**.
    - Creado el dropdown de "Asociación" con las pantallas:
        - "Nosotros".
        - "Historia".
        - "Misión, Visión y Valores".
     
- **[Feature/53-AssociationTransparency (#53)](https://github.com/ISPP-G5/NexONG_Frontend/issues/53)**.
    - Añadida pantalla "Transparencia".
 
- **[Feature/54-AssociationDropdown2 (#54)](https://github.com/ISPP-G5/NexONG_Frontend/issues/54)**.
    - Añadidas al dropdown de "Asociación" las pantallas:
        - "Dónde estamos".
        - "Entidades Colaboradoras".
     
- **[Agenda 2030 (#60)](https://github.com/ISPP-G5/NexONG_Frontend/issues/60)**.
    - Creada la pantalla "Agenda 2030".


## 2.2. Mejoras Sprint 1

### Backend

- **[Change the DB to PostgreSQL (#16)](https://github.com/ISPP-G5/NexONG_Backend/issues/16)**.
    - Cambiada la configuración por defecto de SQLite a PostgreSQL.
 
- **[Populate (#52)](https://github.com/ISPP-G5/NexONG_Backend/issues/52)**.
    - Creada una versión extendida del populate para la base de datos.
 
- **[Revisit Event and LessonEvent CRUD (#57)](https://github.com/ISPP-G5/NexONG_Backend/issues/57)**.
    - Implementadas más restricciones en CRUD de eventos.
 
- **[Models changes in the app (#61)](https://github.com/ISPP-G5/NexONG_Backend/issues/61)**.
    - Implementados en modelo los cambios surgidos tras la reunión con el cliente.

### Frontend

- **[Fix/39-styles (#39)](https://github.com/ISPP-G5/NexONG_Frontend/issues/39)**.
    - Arreglados los estilos para ajustarse a distintos tamaños de pantalla.
 
- **[Fix/44-Home page (#44)](https://github.com/ISPP-G5/NexONG_Frontend/issues/44)**.
    - Ahora el pie de página no ocupa tanta proporción de la pantalla.
    - Añadida información faltante en la página de inicio.
 
- **[Fix/47-Admin view for families (#47)](https://github.com/ISPP-G5/NexONG_Frontend/issues/47)**.
    - Mejorada la pantalla de familias para administradores y su funcionalidad.
 
- **[Fix styles for admin (#56)](https://github.com/ISPP-G5/NexONG_Frontend/issues/56)**.
    - Mejorados los estilos para las vistas de administradores.
     
- **[Fix/62-Activities screens (#67)](https://github.com/ISPP-G5/NexONG_Frontend/issues/67)**.
    - Cambiado el formato de las pantallas del desplegable de actividades al nuevo estilo.


## 2.3. Arreglos Sprint 1

### Backend

No aplica.

### Frontend
 
- **[Navbar-Register (#4)](https://github.com/ISPP-G5/NexONG_Frontend/issues/4)**.
    - Cambiada la estructura del formulario de registro.
 
- **[Feature/5-Navbar-Log-in (#5)](https://github.com/ISPP-G5/NexONG_Frontend/issues/5)**.
    - Cambiada la estructura del formulario de inicio de sesión.
 
- **[Fix/42-register (#42)](https://github.com/ISPP-G5/NexONG_Frontend/issues/42)**.
    - Arreglado botón de inicio de sesión con Google.
    - Traducido el formulario de registro a español.
    - Ahora la página "Registrarse" es más *responsive*.



# 3. Sprint 2


## 3.1. Incrementos Sprint 2

### Backend

- **[Admin authorisation (#73)](https://github.com/ISPP-G5/NexONG_Backend/issues/73)**.
    - Los administradores pueden realizar POST, PUT y DELETE sobre todos los eventos.
    - Los administradores pueden realizar POST, PUT y DELETE sobre todas las clases.
    - Solo los usuarios autenticados pueden realizar GET de clases y eventos
    - Los administradores pueden realizar POST de educadores y de usuarios con rol de educador.
    - Los administradores no pueden realizar POST de alumnos o de usuarios con rol distinto a educador.
    - Los administradores no pueden realizar POST de donaciones.
    - Los administradores no pueden realizar POST de calificaciones de cuatrimestre.
 
- **[Student and Family Authorisation (#74)](https://github.com/ISPP-G5/NexONG_Backend/issues/74)**.
    - Las familias pueden realizar las operaciones CRUD de alumnos.
    - Las familias pueden realizar las operaciones CRUD de evaluaciones.
    - Las familias pueden realizar las operaciones CRUD de salidas.
    - Las familias pueden realizar GET de calificaciones. 
    - Las familias pueden realizar GET de clases.
    - Las familias pueden modificar el campo de asistentes a eventos.
    - Las familias pueden modificar el campo de asistentes a actividades.
 
- **[Educator authorisation (#75)](https://github.com/ISPP-G5/NexONG_Backend/issues/75)**.
    - Los educadores pueden realizar las operaciones CRUD de evaluaciones.
    - Los educadores pueden realizar las operaciones CRUD de tipos de evaluación.
    - Los educadores pueden realizar GET de asistencia a clases.
    - Los educadores pueden realizar GET de actividades.
    - Los educadores pueden realizar GET de alumnos.
    - Los educadores pueden realizar GET de autorizaciones.
    - Los educadores pueden realizar GET de evaluaciones.
    - Los educadores pueden realizar GET de clases.
    - Los educadores pueden realizar PUT en el campo de educadores de una actividad.
    - Los educadores pueden realizar PUT en el campo de asistentes de una actividad.
    - Los educadores pueden modificar solo las clases en las que son educadores.
    - Los educadores no pueden modificar el campo de educadores de las clases.
 
- **[Partner Authorisation (#76)](https://github.com/ISPP-G5/NexONG_Backend/issues/76)**.
    - Los socios pueden realizar GET de eventos.
    - Los socios pueden realizar GET de actividades.
    - Los socios pueden realizar GET de reuniones.
    - Los socios pueden realizar GET de donaciones.
    - Los socios pueden realizar GET de donaciones puntuales.
    - Los socios pueden realizar POST de donaciones.
    - Los socios pueden realizar POST de donaciones puntuales.
    - Los socios pueden realizar PUT del campo de asistentes en las reuniones.
 
- **[Volunteer Authorisation (#77)](https://github.com/ISPP-G5/NexONG_Backend/issues/77)**.
    - Los voluntarios pueden realizar las operaciones CRU de asistencia a clases.
    - Los voluntarios pueden realizar GET de eventos.
    - Los voluntarios pueden realizar GET de actividades.
    - Los voluntarios pueden modificar el campo de voluntarios de eventos.
    - Los voluntarios pueden modificar el campo de voluntarios de actividades.
 
- **[Punctual donations & Home documents models and CRUD (#93)](https://github.com/ISPP-G5/NexONG_Backend/issues/93)**.
    - Creado modelo de donaciones puntuales.
    - Añadido CRUD de donaciones puntuales
    - Creado modelo de documentos de la página de inicio.
    - Añadido CRUD de documentos de la página de inicio.
 
- **[Email validation (#110)](https://github.com/ISPP-G5/NexONG_Backend/issues/110)**.
    - Implementada verificación de cuenta por email.
 
- **[Educative centre Authorisation (#128)](https://github.com/ISPP-G5/NexONG_Backend/issues/128)**.
    - Los centros educativos pueden realizar las operaciones CRUD de alumnos.
    - Los centros educativos realizar las operaciones CRUD de evaluaciones.
    - Los centros educativos realizar las operaciones CRUD de salidas.
    - Los centros educativos realizar GET de calificaciones. 
    - Los centros educativos realizar GET de clases.
    - Los centros educativos modificar el campo de asistentes a eventos.
    - Los centros educativos modificar el campo de asistentes a actividades.

### Frontend

- **[Feature/7-Admin screen- volunteers and educators (#7)](https://github.com/ISPP-G5/NexONG_Frontend/issues/7)**.
    - Los administradores pueden ver los educadores.
    - Los administradores pueden ver los voluntarios.
    - Los administradores pueden aceptar las solicitudes de educadores.
    - Los administradores pueden aceptar las solicitudes de voluntarios.
 
- **[Feature/8-AdminScreen Partners(#8)](https://github.com/ISPP-G5/NexONG_Frontend/issues/8)**.
    - Los administradores pueden ver los socios.
 
- **[Feature/80-Navbar:Donations (#80)](https://github.com/ISPP-G5/NexONG_Frontend/issues/80)**.
    - Creada la pantalla de "Donaciones".
 
- **[Feature/81-Navbar suggestions (#81)](https://github.com/ISPP-G5/NexONG_Frontend/issues/81)**.
    - Creada la pantalla "Sugerencias".
 
- **[Feature/85-LogIn (#85)](https://github.com/ISPP-G5/NexONG_Frontend/issues/85)**.
    - Creada una pantalla de inicio de sesión para distintos tipos de usuario.
 
- **[Feature/86-Navbar suggestions (#86)](https://github.com/ISPP-G5/NexONG_Frontend/issues/86)**.
    - Ahora los voluntarios pueden ver y editar su perfil.
 
- **[Feature/90-VolunteersAgenda (#90)](https://github.com/ISPP-G5/NexONG_Frontend/issues/90)**.
    - Los voluntarios pueden ver la agenda de eventos.
    - Los voluntarios pueden apuntarse a eventos desde la agenda.
 
- **[Feature/91-VolunteersAttendance (#91)](https://github.com/ISPP-G5/NexONG_Frontend/issues/91)**.
    - Los voluntarios ahora pueden ver el nombre y fecha de los eventos a los que están apuntados.
 
- **[Feature/94-Creation volunteers component (#94)](https://github.com/ISPP-G5/NexONG_Frontend/issues/94)**.
    - Añadida barra lateral a la pantalla para voluntarios.
    - Añadida cabecera a la pantalla para voluntarios.
 
- **[Feature/97-Educators component (#97)](https://github.com/ISPP-G5/NexONG_Frontend/issues/94)**.
    - Añadida barra lateral a la pantalla para educadores.
    - Añadida la cabecera a la pantalla para educadores.
 
- **[Feature/102-Kids evaluation (#102)](https://github.com/ISPP-G5/NexONG_Frontend/issues/102)**.
    - Creadas las pantallas de evaluación diaria y anual.
 
- **[Feature/116-Suggestion admin (#116)](https://github.com/ISPP-G5/NexONG_Frontend/issues/116)**.
    - Creada la pantalla "Sugerencias" para administradores.
    - Los administradores pueden ver las sugerencias en la pantalla correspondiente.
 
- **[Feature/124-Partners screen (#124)](https://github.com/ISPP-G5/NexONG_Frontend/issues/124)**.
    - Creada una pantalla para socios con un calendario de eventos y reuniones.
 
- **[Feature/125-Educator-activity-screen (#125)](https://github.com/ISPP-G5/NexONG_Frontend/issues/125)**.
    - Creada pantalla "Actividades" para educadores
 
- **[Feature/126-Partners add button partners (#126)](https://github.com/ISPP-G5/NexONG_Frontend/issues/126)**.
    - Añadido un botón para descargar un PDF con la información de las donaciones registradas.
 
- **[Feature/128-Volunteer agenda unsuscribe (#128)](https://github.com/ISPP-G5/NexONG_Frontend/issues/128)**.
    - Ahora los voluntarios tienen opción de cancelar su participación en eventos.


## 3.2. Mejoras Sprint 2

### Backend

- **[Remove the admin authentication for frontend (#69)](https://github.com/ISPP-G5/NexONG_Backend/issues/69)**.
    - Eliminada la autenticación de administradores.
 
- **[Feature/72 authentication frameworkgoogle (#104)](https://github.com/ISPP-G5/NexONG_Backend/issues/104)**.
    - Refactorizado sistema de autenticación para que utilice Djoser.

- **[Export Donations / Donation data (#81)](https://github.com/ISPP-G5/NexONG_Backend/issues/81)**.
    - Creados un CSV, un PDF y un Excel de los datos relativos a donaciones.
    - Añadida opción de descargarlos individualmente o en un ZIP.
 
- **[Files organisation (#82)](https://github.com/ISPP-G5/NexONG_Backend/issues/82)**.
    - Ahora al subir un archivo a la base de datos el nombre permanece igual.
 
- **[Update readme (#108)](https://github.com/ISPP-G5/NexONG_Backend/issues/108)**.
    - Actualizado el README de backend.

### Frontend

- **[Fix/82-Styles (#82)](https://github.com/ISPP-G5/NexONG_Frontend/issues/82)**.
    - Mejorados los estilos de toda la aplicación de forma más *responsive*.
 
- **[Feature/83-AdminProfile-Back-End (#83)](https://github.com/ISPP-G5/NexONG_Frontend/issues/83)**.
    - Mejorada la pantalla de perfil de administrador.
 
- **[Feature/92-Change favicon (#92)](https://github.com/ISPP-G5/NexONG_Frontend/issues/92)**.
    - Cambiado el favicon por defecto al logo de la organización.
 
- **[Fix/99-Agenda (#99)](https://github.com/ISPP-G5/NexONG_Frontend/issues/99)**.
    - Añadido contenido de la pantalla "Agenda 2030".
 
- **[Feature/115-Log Out button (#115)](https://github.com/ISPP-G5/NexONG_Frontend/issues/115)**.
    - Añadido a botón para cerrar sesión a la cabecera de los usuarios.
 
- **[Fix/121-Volunteers event (#121)](https://github.com/ISPP-G5/NexONG_Frontend/issues/121)**.
    - Ahora los voluntarios ven de un color distinto los eventos a los que se han apuntado.
    - Se muestra un mensaje Toast en lugar de un mensaje de alerta cuando un voluntario intenta unirse a un evento al que ya está inscrito.
    - El formulario ahora se cierra al pulsar el botón de aceptar.
 
- **[Fix/130-Profile update (#130)](https://github.com/ISPP-G5/NexONG_Frontend/issues/130)**.
    - Ahora para actualizar un perfil es suficiente con hacer un click en el botón en lugar de dos.


## 3.3. Arreglos Sprint 2

### Backend

- **[Feature/71 check all business logic (#71)](https://github.com/ISPP-G5/NexONG_Backend/issues/71)**.
    - Los usuarios ahora deben tener un objeto asociado al rol que tienen.
    - El *id_number* de un usuario ahora debe seguir el patrón de un DNI.
    - El precio de ambos tipos de eventos puede ser ahora float en lugar de solo integer.
    - Ahora al añadir un alumno a una clase se comprueba si ambos son de mañana.
    - Añadida una comprobación para el IBAN.
    - Añadida una comprobación para el formato del código postal.
    - Añadida una comprobación que evita 2 actividades de la misma clase al mismo tiempo.
    - Modificado *code* para que un alumno pueda tener familia y no centro educativo y viceversa.
    - Ahora una autorización solo puede ser añadida a un alumno y una actividad si la actividad contiene al alumno.
    - Añadida restricción en evaluaciones para que la clase del tipo de evaluación deba contener al alumno evaluado.
 
- **[Suggestion Model and CRUD (#90)](https://github.com/ISPP-G5/NexONG_Backend/issues/90)**.
    - Creado modelo de sugerencias.
    - Añadido CRUD de sugerencias.
    - Añadido CRUD de calificaciones.
 
- **[Download files and fix populate (#92)](https://github.com/ISPP-G5/NexONG_Backend/issues/92)**.
    - Ahora se pueden descargar archivos del backend.
    - Arreglados problemas del populate.
 
- **[Documents name (#99)](https://github.com/ISPP-G5/NexONG_Backend/issues/99)**.
    - Corregidos nombres incorrectos de documentos.
 
- **[Update Populate (#103)](https://github.com/ISPP-G5/NexONG_Backend/issues/103)**.
    - Actualizado el populate.json.
 
- **[PATCH missing in two API resources (#120)](https://github.com/ISPP-G5/NexONG_Backend/issues/120)**.
    - Añadida función PATCH a las evaluaciones.
    - Ahora la fecha de las donaciones puntuales tiene auto-add.
 
- **[Update homeDocument (#123)](https://github.com/ISPP-G5/NexONG_Backend/issues/123)**.
    - Ahora los documentos de la página de inicio tienen un atributo que indica su tipo:
        - DOCS_INSTICIONALES.
        - MEMORIAS_ANUALES.
        - MEMORIAS_ECONOMICAS.
        - BALANCE_CUENTAS.
        - OTROS_DOCS.
     
- **[Model fix in some fields (#129)](https://github.com/ISPP-G5/NexONG_Backend/issues/129)**.
    - Autorización de menores es un campo opcional ahora.
    - Documento de identificación escaneado es un campo opcional.
    - El documento de evaluaciones es obligatorio.
    - El documento de la página de inicio es obligatorio.
    - La autorización de salida del centro no es obligatoria.


### Frontend

- **[Fix/84-create-classes-events-projects (#110)](https://github.com/ISPP-G5/NexONG_Frontend/issues/110)**.
    - Los administradores pueden ver las clases.
    - Los administradores pueden ver los eventos en el calendario.
    - Los administradores pueden crear clases.
    - Los administradores pueden crear eventos.
 
- **[Fix/88-Volunteers form (#88)](https://github.com/ISPP-G5/NexONG_Frontend/issues/88)**.
    - El formulario de voluntarios ahora envía los datos al backend.
    - Mejorado el estilo del botón del formulario de voluntarios.
 
- **[Fix/101-AdminFamilies (#101)](https://github.com/ISPP-G5/NexONG_Frontend/issues/101)**.
    - Ahora la pantalla "Familias" para administradores muestra datos del backend.
 
- **[Fix/117-Educators Evaluation (#117)](https://github.com/ISPP-G5/NexONG_Frontend/issues/117)**.
    - Se puede volver a evaluar a un alumno tras los cambios en backend.
 
- **[Fix/118-AdminPartners (#118)](https://github.com/ISPP-G5/NexONG_Frontend/issues/118)**.
    - Ahora todos los socios pueden ver todas las reuniones.
 
- **[Fix/119-Admin event (#119)](https://github.com/ISPP-G5/NexONG_Frontend/issues/119)**.
    - Ahora los administradores no tienen opción de seleccionar voluntarios al crear un evento.
 
- **[Fix/122-Add educator (#122)](https://github.com/ISPP-G5/NexONG_Frontend/issues/122)**.
    - Se muestra un mensaje Toast en lugar de un mensaje de alerta cuando sucede un error al crear un educador.
    - Ahora un administrador puede aceptar a un educador mediante un botón.
 
- **[Fix/129-Admin families (#129)](https://github.com/ISPP-G5/NexONG_Frontend/issues/129)**.
    - Arreglada la pantalla "Familias" para administradores para funcionar con los últimos cambios de backend.
    - Ahora la pantalla "Familias" para administradores es *responsive*.



# 4. Sprint 3


## 4.1. Incrementos Sprint 3

### Backend

- **[Terms (#135)](https://github.com/ISPP-G5/NexONG_Backend/issues/135)**.
    - Añadida al modelo una tabla que registra quién ha aceptado qué versión de los términos y condiciones.

- **[Load tests (#137)](https://github.com/ISPP-G5/NexONG_Backend/issues/137)**.
    - Creados los tests de carga.

- **[Tests for admin (#138)](https://github.com/ISPP-G5/NexONG_Backend/issues/138)**.
    - Creados los tests unitarios de usuarios administradores.

- **[Tests for partner (#139)](https://github.com/ISPP-G5/NexONG_Backend/issues/139)**.
    - Creados los tests unitarios de usuarios socios.

- **[Tests for partner (#140)](https://github.com/ISPP-G5/NexONG_Backend/issues/140)**.
    - Creados los tests unitarios de usuarios familia/alumno.

- **[Tests for volunteer (#141)](https://github.com/ISPP-G5/NexONG_Backend/issues/141)**.
    - Creados los tests unitarios de usuarios voluntarios.

- **[Tests for educator (#142)](https://github.com/ISPP-G5/NexONG_Backend/issues/142)**.
    - Creados los tests unitarios de usuarios educadores.

### Frontend

- **[Feature/87-Volunteers Formation (#87)](https://github.com/ISPP-G5/NexONG_Frontend/issues/87)**.
    - Creado el segundo formulario para el registro de voluntarios. Al terminar el registro de voluntario, el usuario es redirigido a la pantalla de formación, con 3 vídeos.

- **[Feature/89-Volunteers Documentation (#89)](https://github.com/ISPP-G5/NexONG_Frontend/issues/89)**.
    - Una vez un nuevo voluntario ve los 3 vídeos, accede a la pantalla de documentación, donde descarga y envía los documentos necesarios para enviar su solicitud.

- **[Feature/120-Admin volunteers docs (#120)](https://github.com/ISPP-G5/NexONG_Frontend/issues/120)**.
    - Añadido botón para que un administrador pueda descargar un ZIP con todos los documentos entregados por un voluntario al rellenar su formulario.

- **[Feature/165-Recurring donations (#165)](https://github.com/ISPP-G5/NexONG_Frontend/issues/165)**.
    - Ahora es posible registrarse como socio desde la pantalla "Registrarse"; hay que completar un segundo formulario para los datos que faltan.
    - Rediseño de la pantalla "Donaciones" para volverla *responsive* y reducir la parte de donaciones recurrentes.
 
- **[Feature/166-Privacy policy (#166)](https://github.com/ISPP-G5/NexONG_Frontend/issues/166)**.
    - La casilla para aceptar los términos de privacidad incluye ahora un enlace a los mismos.

- **[Feature/167-Family daily and yearly evaluation (#167)](https://github.com/ISPP-G5/NexONG_Frontend/issues/167)**.
    - Las familias ahora pueden ver los resultados de las evaluaciones diarias y anuales de sus niños.
 
- **[Feature/168-Family authorizations (#168)](https://github.com/ISPP-G5/NexONG_Frontend/issues/168)**.
    - Las familias pueden firmar autorizaciones para sus niños.
 
- **[Feature/169-Family kids (#169)](https://github.com/ISPP-G5/NexONG_Frontend/issues/169)**.
    - Las familias pueden ver a sus niños y apuntar nuevos.
 
- **[Feature/170-Family calendars (#170)](https://github.com/ISPP-G5/NexONG_Frontend/issues/170)**.
    - Las familias pueden acceder a un calendario con clases, eventos y actividades.
 
- **[Feature/171-Registration of families (#171)](https://github.com/ISPP-G5/NexONG_Frontend/issues/171)**.
    - Es posible registrarse como familia desde la pantalla "Registrarse"; hay que completar dos formularios más para la información restante.
 
- **[Feature/179-Home page La Salle (#170)](https://github.com/ISPP-G5/NexONG_Frontend/issues/170)**.
    - Añadida información a la pantalla "La Salle".
 
- **[Feat/204-Schedule for classes (#204)](https://github.com/ISPP-G5/NexONG_Frontend/issues/204)**.
    - Ahora las clases tienen un horario.


## 4.2. Mejoras Sprint 3

### Backend

- **[Export Partner / Partners data (#78)](https://github.com/ISPP-G5/NexONG_Backend/issues/78)**.
    - Creados un CSV, un PDF y un Excel de los datos relativos a socios.
    - Añadida opción de descargarlos individualmente o en un ZIP.

- **[Export Volunteer / Volunteers data (#79)](https://github.com/ISPP-G5/NexONG_Backend/issues/79)**.
    - Creados un CSV, un PDF y un Excel de los datos relativos a voluntarios.
    - Añadida opción de descargarlos individualmente o en un ZIP.

- **[Export Students / Student data (#80)](https://github.com/ISPP-G5/NexONG_Backend/issues/80)**.
    - Creados un CSV, un PDF y un Excel de los datos relativos a alumnos.
    - Añadida opción de descargarlos individualmente o en un ZIP.

- **[Feedback of pilot users (#133)](https://github.com/ISPP-G5/NexONG_Backend/issues/133)**.

    Implementación del feedback proporcionado por los usuarios piloto (grupo 11 de ISPP y organización Manos Abiertas con Norte):
    - Al borrar un socio, sus donaciones ya no se eliminan.
    - Al borrar un educador, las clases asociadas a este ya no se se eliminan.
    - La fecha de una reunión no puede estar en el pasado ahora.
    - Educador y socio tienen un campo de descripción.
    - Añadida redirección de HTTP a HTTPS solo para el entorno de producción. HTTPS no está disponible para el entorno de desarrollo.
 
- **[Change in models (#134)](https://github.com/ISPP-G5/NexONG_Backend/issues/134)**.
    - Limitado el máximo de caracteres en algunos campos de los modelos de datos.
    - Habilitado el modelo y CRUD de horario.
    - Habilitado un campo en el usuario para almacenar si este ha aceptado los términos y condiciones y qué versión de estos.
    - La verificación por email se resuelve en backend ahora.
 
- **[Fix name and surname (#181)](https://github.com/ISPP-G5/NexONG_Backend/issues/181)**.
    - Ahora al registrarse no se permite introducir números en nombre o apellidos.
 
- **[Fix email validation screen (#183)](https://github.com/ISPP-G5/NexONG_Backend/issues/183)**.
    - Añadida en la validación de la cuenta una pantalla para avisar cuando la cuenta ya está activada.

### Frontend

- **[Fix/144-Information main page of home page (#144)](https://github.com/ISPP-G5/NexONG_Frontend/issues/144)**.
    - Añadida la información de la página principal.
 
- **[Fix/145-About us video and dossier (#145)](https://github.com/ISPP-G5/NexONG_Frontend/issues/145)**.
    - Añadido vídeo en la pantalla "Nosotros".
 
- **[Fix/146-History home page (#146)](https://github.com/ISPP-G5/NexONG_Frontend/issues/146)**.
    - Añadida información a la pantalla "Historia".
 
- **[Fix/147-Mission, view and values (#147)](https://github.com/ISPP-G5/NexONG_Frontend/issues/147)**.
    - Añadida información a la pantalla "Misión, Visión y Valores".
 
- **[Fix/148-Association information (#148)](https://github.com/ISPP-G5/NexONG_Frontend/issues/148)**.
    - Añadida información a la pantalla "Asociación".
 
- **[Fix/149-Summer school (#149)](https://github.com/ISPP-G5/NexONG_Frontend/issues/149)**.
    - Añadida información a la pantalla "Campamento de verano".
 
- **[Fix/150-Update images (#150)](https://github.com/ISPP-G5/NexONG_Frontend/issues/150)**.
    - Actualizadas las imágenes de la aplicación con las proporcionadas por la ONG.
 
- **[Fix/151-Transparencies (#151)](https://github.com/ISPP-G5/NexONG_Frontend/issues/151)**.
    - Completada la tabla de la pantalla "Transparencia".
 
- **[Fix/154-Log in and register with token (#154)](https://github.com/ISPP-G5/NexONG_Frontend/issues/154)**.
    - Implementada autenticación mediante tokens.
 
- **[Fix/163-Volunteers attendance (#163)](https://github.com/ISPP-G5/NexONG_Frontend/issues/163)**.
    - Se muestra un mensaje Toast en lugar de un mensaje de alerta cuando un volunatrio elimina su confirmación de asistencia.
    - Ahora los voluntarios ven el nombre y tipo de actividad de las actividades a las que pueden unirse.
 
- **[Fix/172-Feedback pilot users (#172)](https://github.com/ISPP-G5/NexONG_Frontend/issues/172)**.

    Implementación del feedback de los usuarios piloto (grupo 11 de ISPP y organización Manos Abiertas con Norte):
    - Revisión de erratas.
    - Cambio del nombre de la pestaña a Manos Abiertas.
    - Teléfonos más visibles en el pie de página.
    - Uso de mapas interactivos para "Dónde estamos".
    - Mejores mensajes de error en formularios de administrador.
    - Añadidos mensajes de éxito al borrar y editar.
    - Voluntarios más pequeños en cabecera.
    - Mensaje si no hay solicitudes en la pantalla de voluntarios para administradores.
    - Mensajes de error de educadores más detallados.
    - Cambio de campo de tiempo a solo hora y no día.
    - Mensaje de error en socios.
    - Mensaje de error en clases.
    - Los cambios aparecen inmediatamente al editar un evento.
    - Cambios de estilo en el calendario.
    - Eliminación de saltos de línea.
    - Corrección de error gramatical en mensajes de error de sugerencias.
 
- **[Feature/175-Social log in (#175)](https://github.com/ISPP-G5/NexONG_Frontend/issues/175)**.
    - Ahora es posible iniciar sesión mediante Google.
 
- **[Fix/194-Log in and register (#194)](https://github.com/ISPP-G5/NexONG_Frontend/issues/194)**.
    - Ahora se puede crear una cuenta e iniciar sesión sin la extensión Modheader.
 
- **[Fix/214-Toast error (#214)](https://github.com/ISPP-G5/NexONG_Frontend/issues/214)**.
    - Traducidos todos los mensajes Toast a español.
    - Eliminados los errores de los mensajes Toast.
    - Ajustado el color de todos los mensajes Toast a negro sobre blanco.
    - Eliminado el botón de inicio de sesión con Google.


## 4.3. Arreglos Sprint 3

### Backend

- **[Fix user model (#146)](https://github.com/ISPP-G5/NexONG_Backend/issues/146)**.
    - Al hacer POST de un usuario (registro) el frontend puede enviar el rol asociado.
    - Solo se permite enviar POST con rol de administrador o educador si el usuario es administrador.
 
- **[Fix user roles (#148)](https://github.com/ISPP-G5/NexONG_Backend/issues/148)**.
    - Reparación del método POST de usuarios para que pueda volver a realizarse la operación. Un administrador crea todos los modelos relativos a un usuario, y los demás roles solo crean los modelos que les corresponden.
    - Arreglados los permisos de HomeDocument para que todos los usuarios puedan realizar operaciones tipo GET pero solo los administradores puedan realizar POST, PUT y DELETE.
 
- **[Fix authentication systems (#151)](https://github.com/ISPP-G5/NexONG_Backend/issues/151)**.
    - Reparación de problemas detectados con el sistema de autenticación implementado.
 
- **[Fix Lesson validator and PATCH to User (#155)](https://github.com/ISPP-G5/NexONG_Backend/issues/155)**.
    - Reparación de los validadores de clase para poder realizar operaciones POST.
    - Añadida operación PATCH de usuarios.
 
- **[Fix PunctualDonation permissions (#157)](https://github.com/ISPP-G5/NexONG_Backend/issues/157)**.
    - Ahora todos los usuarios pueden realizar operaciones tipo POST a donaciones puntuales.
 
- **[Fix usable populate (#159)](https://github.com/ISPP-G5/NexONG_Backend/issues/159)**.
    - Contraseñas de usuarios cambiadas a "contraseña" y cifradas con el sistema de Django para poder ser testeadas desde frontend con populate.
 
- **[Fix download privileges (#169)](https://github.com/ISPP-G5/NexONG_Backend/issues/169)**.
    - Ahora solo los administradores pueden descargar los archivos exportados tales como Excel, CSV y PDF (en lugar de todos los usuarios, registrados o no).
 
- **[Fix email (#171)](https://github.com/ISPP-G5/NexONG_Backend/issues/171)**.
    - Cambiado el email de activación a español.
    - Inclusión en el email de los siguientes pasos a realizar para continuar con el registro.
 
- **[Fix user PATCH/PUT (#173)](https://github.com/ISPP-G5/NexONG_Backend/issues/173)**.
    - Ahora se puede editar un usuario.
 
- **[Fix EvaluationType permissions (#175)](https://github.com/ISPP-G5/NexONG_Backend/issues/175)**.
    - Ahora una familia puede ver los tipos de evaluación.
    - Arreglado un problema de tipos de evaluación en populate.

### Frontend

- **[Fix/162-Volunteers calendar (#162)](https://github.com/ISPP-G5/NexONG_Frontend/issues/162)**.
    - Ahora los voluntarios pueden apuntarse a clases y actividades además de eventos
 
- **[Fix/164-Donations export (#164)](https://github.com/ISPP-G5/NexONG_Frontend/issues/164)**.
    - Ahora las donaciones pueden ser exportadas en distintos formatos, no solo PDF.
 
- **[Fix/173-Admins families request (#173)](https://github.com/ISPP-G5/NexONG_Frontend/issues/173)**.
    - Los administradores pueden gestionar las solicitudes de familias.
    - Tienen una lista de las familias registradas en el sistema.
 
- **[Fix/174-Lesson event (#174)](https://github.com/ISPP-G5/NexONG_Frontend/issues/174)**.
    - En la pantalla "Clases" para administradores:
        - Añadidos botones y formularios para ver, crear, editar y borrar horarios.
        - Añadida opción a la creación y edición de clases para indicar si es por la mañana.
        - Ahora el eduador y la fecha de cada clase aparecen en la pantalla "Clases".
    - En la pantalla "Eventos" para administradores:
        - Añadidos botones y formularios para crear, editar y borrar actividades.

- **[Fix/178-Delete projects, schools (#178)](https://github.com/ISPP-G5/NexONG_Frontend/issues/178)**.
    - Eliminados los campos relativos a proyectos y escuelas en el menú lateral de administrador.
 
- **[Fix/185-Edit educators and volunteers (#185)](https://github.com/ISPP-G5/NexONG_Frontend/issues/185)**.
    - Ahora los administradores pueden editar y visualizar el perfil de educadores y voluntarios.
 
- **[Fix/190-Delete roles (#190)](https://github.com/ISPP-G5/NexONG_Frontend/issues/190)**.
    - Ahora se elimina el rol de un usuario en lugar del usuario en sí.
 
- **[Fix/210-Punctual-Donations (#210)](https://github.com/ISPP-G5/NexONG_Frontend/issues/210)**.
    - Ahora se pueden realizar donaciones puntuales de nuevo.
 
- **[Fix/212-Log In token (#212)](https://github.com/ISPP-G5/NexONG_Frontend/issues/212)**.
    - Arregladas las redirecciones tras el inicio de sesión.
 
- **[Fix/215-HomePage (#215)](https://github.com/ISPP-G5/NexONG_Frontend/issues/215)**.
    - Cambiados los links a imágenes de "Entidades Colaboradoras" por imágenes descargadas.
    - Cambiada imagen de la pantalla "Historia".
    - El texto de la pantalla "Club de verano" está centrado ahora.
 
- **[Fix/216-Profile update (#216)](https://github.com/ISPP-G5/NexONG_Frontend/issues/216)**.
    - Ahora un usuario puede actualizar su perfil sin introducir la contraseña.
    - Un usuario puede cambiar su email.
    - Corregida la redirección tras actualizar un perfil.
    - Ahora un usuario no admnistrador puede borrar su propia cuenta correctamente.
    - Corregida la redireción tras eliminar una cuenta.

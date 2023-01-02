# PARS_arche

## Socios

Adolfo Hernández Signoret 34%

Alejandro Álvarez Lozoya 33%

Isaac Gómez Cortéz 33%

## Objetivo

...La vida...

## Descripción literal
Inicio:
  Abres PARS, y puedes registrarte o acceder a tu cuenta con tu usuario/correo & contraseña. 
MAPA:
  Dentro de PARS se abre en la pestaña de MAPA donde puedes ver los eventos aceptados "verde", eventos privados en los que estás invitado "azul" y los eventos públicos disponibles "rojos". En esta misma pestaña puedes buscar mediante la lupa eventos o usuarios específicos.
HOME:
  Aquí puedes ver todos los eventos públicos destacados que ya pasaron, los eventos privados a los que no confirmaste y los eventos a los que si confirmaste. Con prioridad de los que si confirmaste. Estos eventos se ven en la forma de un corto musical con todas las fotos del evento, si fuiste a estos eventos, puedes calificar.
monEVENTOS:
  Aquí puedes ver los eventos que has confirmado/creado de manera más detallada (organizador, quienes van, donde, cuando, cover?). También puedes crear eventos dando en el botón de un más en la esquina superior derecha, o también puedes ver las invitaciones que has recibido en el botón de un buzón en la esquina superior derecha también. Para ver más información de cada evento puedes picarle y este llenará tu celular.
PERFIL:
  En esta última pestaña puedes ver como ven los demás tu perfil en forma de álbum que sea la imagen del evento de tu elección así como tu calificación promedio, puedes modificar tu nombre de usuario, tu voice note, tu mensaje de 20 caractéres, y puedes ver tu lista de eventos en forma de playlist. Cada evento como si fuera una canción cuyo nombre es el nombre del evento y la calificación en botellas. 
## Metas

1. Desarrollar una app funcional para el 24 de junio de 2023
  - Inicio
    - Registro de usuarios
    - Creación de cuenta
  - Dentro
    - HOME-MAPA-LUPA
    - Perfil
    - Mis Eventos
    - Feed Principal

### Clase Usuarios
atributos:
  - nombre de usuario
  - correo primario
  - correo de recuperación (opcional)
  - contraseña
  - fecha de nacimiento
  - puntos XP PARS
  - stigmas
  - carta QR
  - audio 10 segundos (opcional)
  
métodos:
  - seguir gente
  - dejar de seguir gente
  - ver a quien sigues
  - ver seguidores
  - ver puntos XP PARS
  - acceder a carta QR
  - modificar foto perfil
  - modificar audio perfil
  - modificar descripción perfil
  - modificar mensaje perfil

  - ver eventos populares
  - seleccionar evento
  - buscar eventos
  - unirse a evento
  - calificar evento concluido
  - ver organizador
  - buscar organizador
  - solicitud a organizador

  - crear evento
  - generar link evento
  - compartir invitación evento

### Clase eventos
atributos:
- nombre
- fecha
- lugar
- hora comienzo
- hora cierre (opcional)
- link
- cover (opcional)
- canción del evento (futuramente que a interfaz dependa de estas canciones)
- calificación (hasta que se publica y con botellas)
- foto 1
- foto 2
- foto 3
- foto 4
- foto 5
- foto 6
métodos:


## Reglas
- No puedes empalmar eventos
- Las fotos deben de ser subidas antes de que termine el evento, se pueden ir subiendo cada que se toman pero no se mostrarán hasta que el evento concluya.
- Si no calificas un evento al que fuiste te baja el XP.
- Las calificaciones son anónimas.
- El promedio de tus calificaciones se muestra en tu perfil.

# Capítulo III: Requirements Specification

## 3.1.User Stories.

### Lista de Épicas

| ID   | Título                                       | Descripción                                                                                                                                                          | Criterios de aceptación | EpicID         |
|------|----------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------|----------------|
| EP01 | Funcionalidades de la app             | Como usuario de la aplicación, quiero que las funcionalidades principales que me ofrece el servicio sean funcionales.                                  | No corresponde          | No corresponde |
| EP02 | Acceso a la aplicación                  | Como usuario de la aplicación, quiero acceder con mi información para hacer uso de las características disponibles.                                                                   | No corresponde          | No corresponde |
| EP03 | Uso del mapa                      | Como usuario de la aplicación, quiero acceder al mapa de la aplicación para realizar la reserva de vehículos y seguimiento de rutas                                                  | No corresponde          | No corresponde |
| EP04 | Accesibilidad de la Landing Page        | Como visitante, quiero que la información sobre la aplicación sea fácil de entender para poder comprender rápidamente su propósito. | No corresponde          | No corresponde |

### Lista de Historias de Usuario

<table>
  <tbody>
    <tr>
      <th>ID (HU)</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Criterios de aceptación</th>
      <th>Epic-ID</th>
    </tr>
    <tr>
      <td>US-01</td>
      <td>Filtro de vehículos</td>
      <td>Como usuario quiero filtrar por tipo de vehículo (scooter / bici / moto) para encontrar el que necesito.</td>
      <td>
        Escenario 1: Filtrado exitoso <br>
        Given que el usuario ingresa la app <br>
        When el usuario ingresa al mapa de vehículos, va a garage y luego busca vehículos a través del filtro <br>
        Then el sistema muestra la información de vehículos disponibles según los filtros que el usuario ha colocado. <br>
        <br>
        Escenario 2: Filtrado fallido<br>
        Given que el usuario selecciona un filtro de vehículos <br>
        When el usuario selecciona un vehículo no disponible o no cuenta con conexión a internet.  <br>
        Then el sistema muestra un mensaje de error indicando que no hay conexión a internet o no se encuentran vehículos según el filtro seleccionado.<br>
      </td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US-02</td>
      <td>Batería de vehículo</td>
      <td>Como usuario quiero ver el nivel de batería del vehículo para asegurar que llegue a mi destino.</td>
      <td>
        Escenario 1: Visualización exitosa<br>
        Given que el usuario ve un vehículo en el mapa<br>
        When selecciona dicho vehículo<br>
        Then el sistema muestra el nivel de batería actual en porcentaje.<br>
        <br>
        Escenario 2: Visualización fallida<br>
        Given que el usuario selecciona un vehículo<br>
        When la información de batería no está disponible por error de conexión o fallo del sistema<br>
        Then se muestra un mensaje de error indicando que no se puede mostrar el nivel de batería.<br>
      </td>
      <td>EP-01</td>
    </tr>
    <tr>
      <td>US-03</td>
      <td>Reserva de vehículo</td>
      <td>Como usuario quiero reservar un vehículo por un tiempo limitado para garantizar su disponibilidad.</td>
      <td>
        Escenario 1: Visualización exitosa<br>
        Given que el usuario selecciona un vehículo disponible<br>
        When presiona el botón de "Reservar"<br>
        Then el sistema bloquea el vehículo por un tiempo limitado y muestra confirmación de la reserva.<br>
        <br>
        Escenario 2: Visualización fallida<br>
        Given que el usuario selecciona un vehículo<br>
        When el vehículo ya ha sido reservado por otro usuario o no hay conexión<br>
        Then el sistema notifica que la reserva no pudo completarse y muestra opciones para intentar de nuevo.<br>
      </td>
      <td>EP-01</td>
    </tr>
    <tr>
      <td>US-04</td>
      <td>Inicio de sesión y registro</td>
      <td>Como usuario quiero poder iniciar sesión o registrarme en la app para usarla diariamente.</td>
      <td>
        Escenario 1: Inicio de sesión exitoso<br>
        Given que el usuario tiene una cuenta registrada<br>
        When ingresa sus credenciales correctas<br>
        Then el sistema permite el acceso a la app.<br>
        <br>
        Escenario 2: Registro exitoso<br>
        Given que el usuario no tiene una cuenta<br>
        When completa el formulario de registro con sus datos válidos<br>
        Then el sistema crea la cuenta y permite el acceso.<br>
        <br>
        Escenario 3: Fallo de autenticación<br>
        Given que el usuario ingresa credenciales incorrectas<br>
        When intenta iniciar sesión<br>
        Then el sistema muestra un mensaje de error.<br>
      </td>
      <td>EP-02</td>
    </tr>
    <tr>
      <td>US-05</td>
      <td>Datos de usuario</td>
      <td>Como usuario quiero poder crear un perfil para colocar mis datos.</td>
      <td>
        Escenario 1: Creación exitosa<br>
        Given que el usuario accede a su cuenta<br>
        When ingresa sus datos (nombre, correo, foto, etc.) y los guarda<br>
        Then el sistema actualiza el perfil con éxito.<br>
        <br>
        Escenario 2: Error en la creación<br>
        Given que el usuario intenta guardar sus datos<br>
        When alguno es inválido o falta completar un campo obligatorio<br>
        Then el sistema muestra un mensaje indicando el error.<br>
      </td>
      <td>EP-02</td>
    </tr>
    <tr>
      <td>US-06</td>
      <td>Suscripción de usuario</td>
      <td>Como usuario quiero pagar una suscripción a través de planes para obtener un mejor acceso a los servicios.</td>
      <td>
        Escenario 1: Pago exitoso<br>
        Given que el usuario selecciona un plan de suscripción<br>
        When ingresa su método de pago válido<br>
        Then el sistema procesa el pago y activa el plan.<br>
        <br>
        Escenario 2: Pago fallido<br>
        Given que el usuario selecciona un plan<br>
        When el método de pago es rechazado o hay error de conexión<br>
        Then el sistema muestra un mensaje de error y no activa el plan.<br>
      </td>
      <td>EP-02</td>
    </tr>
    <tr>
      <td>US-07</td>
      <td>Selección de plan</td>
      <td>Como usuario quiero seleccionar un plan específico para utilizar la app.</td>
      <td>
        Escenario 1: Selección exitosa<br>
        Given que el usuario está registrado<br>
        When accede a la sección de planes y selecciona uno<br>
        Then el sistema confirma la elección y muestra los beneficios del plan.<br>
        <br>
        Escenario 2: Selección fallida<br>
        Given que el usuario intenta seleccionar un plan<br>
        When el plan no está disponible o hay error de conexión<br>
        Then el sistema notifica que no se pudo completar la acción.<br>
      </td>
      <td>EP-02</td>
    </tr>
    <tr>
      <td>US-08</td>
      <td>Métodos de pago</td>
      <td>Como usuario quiero agregar mi tarjeta de crédito para acceder a uno de los planes de suscripción</td>
      <td>
        Escenario 1: Registro exitoso<br>
        Given que el usuario quiere suscribirse<br>
        When ingresa su tarjeta de crédito válida<br>
        Then el sistema la registra y la asocia a su perfil.<br>
        <br>
        Escenario 2: Registro fallido<br>
        Given que el usuario ingresa una tarjeta<br>
        When la tarjeta no es válida o el sistema la rechaza<br>
        Then se muestra un mensaje indicando el error.<br>
      </td>
      <td>EP-02</td>
    </tr>
    <tr>
      <td>US-09</td>
      <td>Visualización de mapa</td>
      <td>Como usuario quiero tener acceso a un mapa para acceder a los vehículos disponibles</td>
      <td>
        Escenario 1: Visualización exitosa<br>
        Given que el usuario ingresa a la app<br>
        When accede al mapa<br>
        Then el sistema muestra los vehículos disponibles cercanos en tiempo real.<br>
        <br>
        Escenario 2: Visualización fallida<br>
        Given que el usuario ingresa al mapa<br>
        When no hay conexión a internet<br>
        Then el sistema muestra un mensaje de error.<br>
      </td>
      <td>EP-03</td>
    </tr>
    <tr>
      <td>US-10</td>
      <td>Sección “Sobre Nosotros” de landing page</td>
      <td>Como usuario quiero tener acceso a la información de la aplicación para estar informado de las actualizaciones.</td>
      <td>
        Escenario 1: Acceso exitoso<br>
        Given que el usuario ingresa al menú de información<br>
        When selecciona la opción "Acerca de la app"<br>
        Then el sistema muestra la información, versión y novedades.<br>
        <br>
        Escenario 2: Acceso fallido<br>
        Given que el usuario ingresa a "Acerca de la app"<br>
        When no se puede recuperar la información<br>
        Then se muestra un mensaje de error.<br>
      </td>
      <td>EP-04</td>
    </tr>
    <tr>
      <td>US-11</td>
      <td>Sección “Ubicaciones” de landing page</td>
      <td>Como usuario quiero saber dónde se ubican presencialmente para acudir a uno de los locales.</td>
      <td>
        Escenario 1: Visualización exitosa<br>
        Given que el usuario accede a la sección de locales<br>
        When selecciona "Ver ubicaciones"<br>
        Then el sistema muestra un mapa o listado con direcciones de los locales físicos.<br>
        <br>
        Escenario 2: Visualización fallida<br>
        Given que el usuario accede a "Ver ubicaciones"<br>
        When no hay conexión<br>
        Then el sistema muestra un mensaje indicando que no se pudo cargar la información.<br>
      </td>
      <td>EP-04</td>
    </tr>
    <tr>
      <td>US-12</td>
      <td>Sección “Contacto” de landing page</td>
      <td>Como usuario quiero contactar con el soporte de la aplicación para resolver mis dudas.</td>
      <td>
        Escenario 1: Contacto exitoso<br>
        Given que el usuario necesita soporte<br>
        When selecciona "Contactar soporte"<br>
        Then el sistema ofrece opciones de contacto (chat, correo, teléfono) y registra el caso.<br>
        <br>
        Escenario 2: Contacto fallido<br>
        Given que el usuario selecciona "Contactar soporte"<br>
        When no hay conexión a internet<br>
        Then se muestra un mensaje indicando que el servicio de soporte no está disponible en ese momento.<br>
      </td>
      <td>EP-04</td>
    </tr>
    <tr>
      <td>US-13</td>
      <td>Notificación de fin de reserva</td>
      <td>Como usuario, quiero recibir una notificación antes de que finalice mi reserva para poder extenderla o prepararme para devolver el vehículo</td>
      <td>
        Escenario 1: Notificación exitosa<br>
        Given que el usuario tiene una reserva activa<br>
        When faltan 5 minutos para el fin de la reserva<br>
        Then el sistema envía una notificación push con opción para extender el tiempo.<br>
        <br>
        Escenario 2: Notificación fallida<br>
        Given que la reserva está por finalizar<br>
        When no hay conexión a internet<br>
        Then el sistema registra el intento y reintenta enviar la notificación al recuperar la conexión.<br>
      </td>
      <td>EP-01</td>
    </tr>
    <tr>
      <td>US-14</td>
      <td>Reportar problema con vehículo</td>
      <td>Como usuario, quiero reportar un problema con el vehículo para alertar a soporte y obtener ayuda rápida.</td>
      <td>
        Escenario 1: Reporte exitoso<br>
        Given que el usuario está usando el vehículo<br>
        When selecciona "Reportar problema" y elige una categoría (ej.: falla mecánica)<br>
        Then el sistema envía el reporte a soporte y muestra confirmación.<br>
        <br>
        Escenario 2: Reporte fallido<br>
        Given que el usuario intenta reportar un problema<br>
        When no hay conexión a internet<br>
        Then el sistema guarda el reporte localmente y lo envía al recuperar la conexión.<br>
      </td>
      <td>EP-01</td>
    </tr>
    <tr>
      <td>US-15</td>
      <td>Dashboard de estado de vehículos</td>
      <td>Como administrador, quiero ver el estado de la flota de vehículos para gestionar mantenimiento y redistribución.</td>
      <td>
        Escenario 1: Visualización exitosa<br>
        Given que el administrador inicia sesión<br>
        When accede al dashboard de vehículos<br>
        Then el sistema muestra ubicación, batería y estado de cada vehículo.<br>
        <br>
        Escenario 2: Error de carga<br>
        Given que el administrador accede al dashboard<br>
        When el servidor no responde<br>
        Then el sistema muestra un mensaje de error y opción para reintentar.<br>
      </td>
      <td>EP-05</td>
    </tr>
    <tr>
      <td>US-16</td>
      <td>Calificación de viaje</td>
      <td>Como usuario, quiero calificar mi experiencia después del viaje para feedback y mejora del servicio.</td>
      <td>
        Escenario 1: Calificación exitosa<br>
        Given que el usuario finaliza un viaje<br>
        When selecciona una puntuación (1-5 estrellas) y envía<br>
        Then el sistema guarda la calificación y muestra agradecimiento.<br>
        <br>
        Escenario 2: Calificación fallida<br>
        Given que el usuario intenta calificar<br>
        When no hay conexión a internet<br>
        Then el sistema guarda la calificación localmente y la envía después.<br>
      </td>
      <td>EP-04</td>
    </tr>
    <tr>
      <td>US-17</td>
      <td>Desbloqueo de vehículo con QR</td>
      <td>Como usuario, quiero desbloquear el vehículo escaneando un QR para agilizar el inicio del viaje.</td>
      <td>
        Escenario 1: Desbloqueo exitoso<br>
        Given que el usuario reserva un vehículo<br>
        When escanea el QR del vehículo<br>
        Then el sistema desbloquea el vehículo y inicia el viaje.<br>
        <br>
        Escenario 2: Desbloqueo fallido<br>
        Given que el usuario escanea el QR<br>
        When el QR no es válido o el vehículo ya está en uso<br>
        Then el sistema muestra un mensaje de error.<br>
      </td>
      <td>EP-04</td>
    </tr>
    <tr>
      <td>US-18</td>
      <td>Historial de viajes</td>
      <td>Como usuario, quiero ver el historial de mis viajes para trackear gastos y rutas.</td>
      <td>
        Escenario 1: Visualización exitosa<br>
        Given que el usuario inicia sesión<br>
        When accede a la sección "Mis Viajes"<br>
        Then el sistema muestra una lista con fecha, costo y distancia de cada viaje.<br>
        <br>
        Escenario 2: Error de carga<br>
        Given que el usuario accede al historial<br>
        When no hay conexión a internet<br>
        Then el sistema muestra un mensaje de error y opción para reintentar.<br>
      </td>
      <td>EP-04</td>
    </tr>
    <tr>
      <td>US-19</td>
      <td>Compartir viaje en redes sociales</td>
      <td>Como usuario, quiero compartir mi viaje en redes sociales para promover la app y obtener descuentos.</td>
      <td>
        Escenario 1: Compartir exitoso<br>
        Given que el usuario finaliza un viaje<br>
        When selecciona "Compartir viaje" y elige una red social<br>
        Then el sistema genera una plantilla con logo de WeRide y comparte automáticamente<br>
        <br>
        Escenario 2: Compartir fallido<br>
        Given que el usuario intenta compartir<br>
        When la red social no está disponible o no hay conexión<br>
        Then el sistema guarda el draft localmente y permite reintentar luego.<br>
      </td>
      <td>EP-04</td>
    </tr>
    <tr>
      <td>US-20</td>
      <td>Gestión de promociones</td>
      <td>Como administrador, quiero crear y gestionar promociones para atraer nuevos usuarios</td>
      <td>
        Escenario 1: Creación exitosa<br>
        Given que el administrador inicia sesión<br>
        When crea un código promocional con fecha de expiración y descuento<br>
        Then el sistema guarda la promoción y la muestra en el dashboard.<br>
        <br>
        Escenario 2: Creación fallida<br>
        Given que el administrador intenta crear una promoción<br>
        When el código ya existe o los datos son inválidos<br>
        Then el sistema muestra un mensaje de error específico.<br>
      </td>
      <td>EP-05</td>
    </tr>
  </tbody>
</table>

## 3.2. Impact Mapping.

Un mapa de impacto es una técnica colaborativa y visual de planificación estratégica que alinea los objetivos de un proyecto con las acciones necesarias para alcanzarlos. En esta sección , el equipo presenta los mapas de impacto realizados.


![User Persona](/assets/chapter03/Impact%20map%203.png)

![User Persona](/assets/chapter03/Impact%20map%202%20(1).png)


## 3.3. Product Backlog

| N° Orden | User Story ID | Título                                   | Descripción                                                                                                    | Story points |
|----------|---------------|------------------------------------------|----------------------------------------------------------------------------------------------------------------|--------------|
| 1        | US-01         | Filtro de vehículos                      | Como usuario quiero filtrar por tipo de vehículo (scooter / bici / moto) para encontrar el que necesito.       | 3            |
| 2        | US-02         | Batería de vehículo                      | Como usuario quiero ver el nivel de batería del vehículo para asegurar que llegue a mi destino.                | 3            |
| 3        | US-03         | Reserva de vehículo                      | Como usuario quiero reservar un vehículo por un tiempo limitado para garantizar su disponibilidad.             | 5            |
| 4        | US-04         | Inicio de sesión y registro              | Como usuario quiero poder iniciar sesión o registrarme en la app para usarla diariamente.                      | 5            |
| 5        | US-05         | Datos de usuario                         | Como usuario quiero poder crear un perfil para colocar mis datos.                                              | 2            |
| 6        | US-06         | Suscripción de usuario                   | Como usuario quiero pagar una suscripción a través de planes para obtener un mejor acceso a los servicios.     | 8            |
| 7        | US-07         | Selección de plan                        | Como usuario quiero seleccionar un plan específico para utilizar la app.                                       | 2            |
| 8        | US-08         | Métodos de pago                          | Como usuario quiero agregar mi tarjeta de crédito para acceder a uno de los planes de suscripción              | 2            |
| 9        | US-09         | Visualización de mapa                    | Como usuario quiero tener acceso a un mapa para acceder a los vehículos disponibles                            | 8            |
| 10       | US-10         | Sección “Sobre Nosotros” de landing page | Como usuario quiero tener acceso a la información de la aplicación para estar informado de las actualizaciones.| 1            |
| 11       | US-11         | Sección “Ubicaciones” de landing page    | Como usuario quiero saber dónde se ubican presencialmente para acudir a uno de los locales.                    | 1            |
| 12       | US-12         | Sección “Contacto” de landing page       | Como usuario quiero contactar con el soporte de la aplicación para resolver mis dudas.                         | 2            |
| 13       | US-13         | Notificación de fin de reserva      | Como usuario, quiero recibir una notificación antes de que finalice mi reserva para poder extenderla o prepararme para devolver el vehículo. | 3            |
| 14       | US-14         | Reportar problema con vehículo      | Como usuario, quiero reportar un problema con el vehículo para alertar a soporte y obtener ayuda rápida.                 | 3            |
| 15       | US-15         | Dashboard de estado de vehículos    | Como administrador, quiero ver el estado de la flota de vehículos para gestionar mantenimiento y redistribución.         | 8            |
| 16       | US-16         | Calificación de viaje               | Como usuario, quiero calificar mi experiencia después del viaje para feedback y mejora del servicio.                     | 2            |
| 17       | US-17         | Desbloqueo de vehículo con QR       | Como usuario, quiero desbloquear el vehículo escaneando un QR para agilizar el inicio del viaje.                         | 3            |
| 18       | US-18         | Historial de viajes                 | Como usuario, quiero ver el historial de mis viajes para trackear gastos y rutas.                                        | 2            |
| 19       | US-19         | Compartir viaje en redes sociales   | Como usuario, quiero compartir mi viaje en redes sociales para promover la app y obtener descuentos.                     | 2            |
| 20       | US-20         | Gestión de promociones              | Como administrador, quiero crear y gestionar promociones para atraer nuevos usuarios                                     | 5            |
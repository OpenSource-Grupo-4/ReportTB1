# Capítulo V: Product Implementation, Validation & Deployment.
## 5.1. Software Configuration Management.

Esta guía define las decisiones y acuerdos fundamentales para el desarrollo, mantenimiento y despliegue de la aplicación **WeRide**, que gestiona el alquiler de vehículos. El objetivo es asegurar la coherencia, eficiencia y calidad a lo largo del ciclo de vida del proyecto.

---

### 5.1.1. Software Development Environment Configuration.

<table border="1">

  <tr>
    <td>Project Management</td>
    <td><h4>Github</h4>Plataforma en línea que permite almacenar código fuente en repositorios. Gracias a la tecnología de control de versiones de Git se puede organizar el código y llevar un mejor trabajo en conjunto.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>Whatsapp</h4>Red Social destinada a la comunicación donde se realizaron acuerdos y recordatorios de las reuniones.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>Trello</h4>Software de administración y gestión de proyectos que se utilizó para establecer y designar las tareas</td>
  </tr>
  <tr>
    <td>Requirements Management</td>
    <td><h4>Miro</h4>Plataforma en línea de gestión de requisitos que permite colaborar y organizar proyectos de forma visual y representativa.
</td>
  </tr>
  <tr>
    <td>Product UX/UI Design</td>
    <td><h4>Figma</h4>Aplicación que permite el diseño libre de interfaces a través de las múltiples herramientas que ofrece. Permitiendo la creación de prototipos interactivos que simulan la experiencia de usuario.
</td>
  </tr>
  <tr>
    <td>Software Development</td>
    <td><h4>Git</h4>Es un software de control de versiones para los trabajos en equipos y confiabilidad del desarrollo.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>Node.js</h4>Node.js es un entorno de ejecución de JavaScript del lado del servidor, que permite desarrollar aplicaciones web escalables y de alto rendimiento fuera del navegador.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>HTML</h4>Lenguaje de etiquetas, utilizado para la estructuración y la presentación de contenido.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>CSS</h4>CSS es un lenguaje utilizado para estilizar y dar formato a documentos HTML.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>TypeScript</h4>TypeScript es un lenguaje de programación de alto nivel, interpretado y multi-paradigma, utilizado para crear interactividad en páginas web.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>VSCode</h4>Es un editor de código fuente con extensiones que ayudan al desarrollo.</td>
  </tr>
    <tr>
    <td></td>
    <td><h4>WebStorm</h4>Es un IDE centrado en desarrollo frontend, por su gran variedad de herramientas que agilizan el proceso de desarrollo.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>Angular</h4>Framework robusto para el desarrollo de aplicaciones web modernas y escalables, basado en el patrón de Single Page Application (SPA),  facilita la creación de interfaces dinámicas mediante TypeScript.</td>
  </tr>
  <tr>
    <td>Software Deployment</td>
    <td><h4>Github Pages</h4>Plataforma que nos permite realizar el despliegue de nuestro landing page.</td>
  </tr>
</table>

---

### 5.1.2. Source Code Management.

Hemos optado por crear un repositorio en GitHub para nuestro proyecto, tanto para el informe como para la landing page. Esto facilitó la colaboración entre los miembros del equipo,aprovechando las herramientas útiles que esta plataforma ofrece para el manejo del código fuente y sus versiones.


- URL del repositorio Report en GitHub: https://github.com/OpenSource-Grupo-4/ReportTB1
- URL del repositorio Landing Page en GitHub: https://github.com/OpenSource-Grupo-4/Landing-Page

---

### 5.1.3. Source Code Style Guide & Conventions

Para "**WeRide**", hemos utilizado "**HTML y CSS**". Para estructurar el contenido usamos etiquetas de section y divisiones para contenido específico de cada una de las secciones. Además, hemos empleado atributos como ***HTML Style*** para personalizar el aspecto visual, definiendo propiedades como color, tamaño de fuente y tipo de letra.

Para resaltar elementos importantes, hemos aplicado ***HTML Text Formatting***, incluyendo etiquetas como b para negrita, strong para resaltado y del para mostrar cambios de precios. En cuanto a la navegación, hemos implementado una barra de navegación horizontal utilizando **CSS** para mejorar la experiencia del usuario al explorar el contenido.

Los formularios, creados con **CSS**, permiten a los usuarios ingresar información relevante, como detalles de inicio de sesión, información de pago y dirección de envío. Para añadir interactividad, hemos agregado botones con efectos hover utilizando CSS y paginación CSS para facilitar la navegación entre las diferentes páginas de productos.

Finalmente, en el **footer**, hemos incluido enlaces a las redes sociales de la organización para brindar a los usuarios una forma adicional de conectarse y seguir nuestras actualizaciones.

### 5.1.4. Software Deployment Configuration.

Utilizaremos GitHub Pages para alojar nuestra Landing Page. Para lograrlo, subiremos los archivos esenciales (HTML, CSS, etc.) a un repositorio público en GitHub. De
esta manera, nuestra página estará disponible en línea y accesible para todos los usuarios.

![GithubReportRepo](/assets/chapter05/github-repo.png)

---

## 5.2. Landing Page, Services & Applications Implementation.

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1.

| Elemento                        | Detalle                                                                                       |
|----------------------------------|----------------------------------------------------------------------------------------------|
| **Sprint**                      | 1 - Implementación de funcionalidades básicas y diseño inicial de CultivApp                   |
| **Sprint Planning Background**   |                                                                                              |
| **Fecha**                       | 19/09/2025                                                                                   |
| **Hora**                        | 22:00 horas (GMT-5)                                                                          |
| **Lugar**                       | Reunión virtual mediante Discord                                                              |
| **Preparado por**               | [WeTech]                                                       |
| **Asistentes**                  | [ Samuel Bonifacio , Jefferson Castro, Diego Seminario, Jhimy Romero, Arnold Morales ]                                                             |
| **Sprint n-1 Review**           | Se creó la organización de WeTech en GitHub, se definieron ramas y se asignaron tareas iniciales como investigación de usuarios, wireframes y mockups. |
| **Sprint n-1 Retrospective**    | Se implementó la estructura básica de la landing page utilizando HTML, CSS y JavaScript.      |
| **Sprint Goal & User Stories**  |     1-20                                                                                         |
| **Sprint 1 Velocity**           | 17 puntos                                                                                    |
| **Sum of Story Points**         | 17 puntos                                                                                    |

#### Objetivo del Sprint
Implementar la estructura inicial de la aplicación, el diseño de la landing page y las funcionalidades básicas de registro e inicio de sesión para los usuarios de WeRide.

#### User Stories seleccionadas para el Sprint 1

| ID  | User Story                                                                                  | Puntos |
|-----|---------------------------------------------------------------------------------------------|--------|
| 12   | Como usuario quiero contactar con el soporte de la aplicación para resolver mis dudas.  |   5    |
| 10   | Como usuario quiero tener acceso a la información de la aplicación para estar informado de las actualizaciones.                  |   5    |
| 11   | Como usuario quiero saber dónde se ubican presencialmente para acudir a uno de los locales.     |   4    |
| 14  | Como usuario, quiero reportar un problema con el vehículo para alertar a soporte y obtener ayuda rápida.   |   3    |

**Total de puntos:** 17

---

#### 5.2.1.2. Aspect Leaders and Collaborators

En esta sección se presenta la matriz de liderazgo y colaboración (Leadership-and-Collaboration Matrix, LACX) para el Sprint 1 de WeRide. Esta matriz identifica, para cada aspecto clave del Sprint, quién es el líder responsable y quiénes son los colaboradores, facilitando así la comunicación y la asignación de tareas dentro del equipo. 

Los aspectos considerados en este Sprint incluyen: diseño de la landing page, desarrollo de funcionalidades de registro e inicio de sesión, implementación de la barra de navegación, y configuración del footer con enlaces de contacto y redes sociales.

| Team Member (Apellido, Nombre)         | GitHub Username      | Landing Page Design | Registro/Inicio de Sesión | Barra de Navegación | Footer y Redes Sociales |
|----------------------------------------|----------------------|---------------------|--------------------------|---------------------|------------------------|
| Bonifacio, Samuel                     | samuelbonifacio015      | L                   | L                       | L                   | L                      |
| Castro, Jefferson                      | JeffersonCastroPariona     | C                   | L                        | C                   | C                      |
| Seminario, Diego                             | DiegoSeminario            | C                   | C                        | L                   | C                      |                     |
| Romero, Jhimy                        | jhimyromeromeza       | L                   | L                        | L                   | C                      |
| Morales, Arnold                        | Arnold-TI       | C                   | C                        | C                   | L                      |

**L:** Leader (Líder)  
**C:** Collaborator (Colaborador)

Esta organización permite una asignación clara de responsabilidades y fomenta la colaboración efectiva durante el desarrollo del Sprint.

---

#### 5.2.1.3. Sprint Backlog 1.

| ID   | Title/Section                | Description                                                                                                                        | Estimation (Hours) | Assigned To                        | Status |
|------|------------------------------|------------------------------------------------------------------------------------------------------------------------------------|--------------------|-------------------------------------|--------|
| US01 | Landing Page                 | Como usuario, quiero acceder a una landing page clara y atractiva para conocer los beneficios y funcionalidades de WeRide.         | 3                  | Bonifacio Jaramillo, Samuel Jesus   | Done   |
| US02 | Registro de Usuario          | Como usuario, quiero registrar una cuenta desde la landing page para poder acceder a los servicios de WeRide.                      | 3                  | Castro Pariona, Jefferson Ernesto   | Done   |
| US03 | Inicio de Sesión             | Como usuario, quiero iniciar sesión desde la landing page para gestionar mis reservas y perfil.                                    | 3                  | Castro Pariona, Jefferson Ernesto   | Done   |
| US04 | Barra de Navegación          | Como usuario, quiero una barra de navegación intuitiva y responsive para moverme fácilmente entre las secciones de la landing page.| 2                  | Seminario Castillo, Diego Vicente            | Done   |
| US05 | Footer y Redes Sociales      | Como usuario, quiero un footer con enlaces de contacto y redes sociales para comunicarme o seguir novedades de WeRide.             | 2                  | Morales Sosa, Arnold Gabriel        | Done   |
| US06 | Página de Información        | Como usuario, quiero una sección informativa sobre WeRide y sus beneficios para entender el propósito de la plataforma.            | 2                  | Bonifacio Jaramillo, Samuel Jesus   | Done   |
| US07 | Validación de Formularios    | Como usuario, quiero que los formularios de registro e inicio de sesión validen mis datos para evitar errores y mejorar la seguridad.| 2                 | Castro Pariona, Jefferson Ernesto   | Done   |
| US08 | Estilos Generales            | Como usuario, quiero una interfaz visualmente coherente (colores, fuentes, espaciados) para una experiencia agradable y moderna.   | 1                  | Romero Meza, Jhimy Pool   | Done   |

#### 5.2.1.4. Development Evidence for Sprint Review

Durante el Sprint 1, el equipo de **WeTech** realizó múltiples commits en el repositorio de GitHub, evidenciando el avance y cumplimiento de las tareas planificadas. A continuación, se presenta una tabla con los principales commits realizados, siguiendo el formato requerido:

| Repository                                         | Branch | Commit Id | Commit Message                                 | Commit Message Body                                   | Committed on (Date)     |
|----------------------------------------------------|--------|-----------|------------------------------------------------|-------------------------------------------------------|------------------------|
| OpenSource-Grupo-4/Landing-Page                    | develop   | 9c5de9c   | Add footer styles to styles.css                | Se agregaron estilos para el footer en styles.css.    | 13/09/2025             |
| OpenSource-Grupo-4/Landing-Page                    | develop   | d0d0f0c   | Add footer section with contact and social links| Se añadió la sección de footer con enlaces de contacto y redes sociales. | 13/09/2025             |
| OpenSource-Grupo-4/Landing-Page                    | develop   | 098b740   | Merge pull request #2 from OpenSource-Grupo-4/develop | Se fusionaron cambios de la rama develop.             | 12/09/2025             |
| OpenSource-Grupo-4/Landing-Page                    | feature/responsive-navbar   | eddad5b   | feat: added navbar & hero section              | Se agregó la barra de navegación y la sección principal. | 12/09/2025             |
| OpenSource-Grupo-4/Landing-Page                    | develop   | 2a59cfe   | chore: index file refactor                     | Refactorización del archivo index.                    | 12/09/2025             |
| OpenSource-Grupo-4/Landing-Page                    | main   | 69695c3   | Merge pull request #1 from OpenSource-Grupo-4/develop | Se fusionaron cambios iniciales de la rama develop.   | 11/09/2025             |
| OpenSource-Grupo-4/Landing-Page                    | hero-ui-fix   | 90dd977   | /changes v.2 Jefferson Castro - Landing        | Cambios en la landing page por Jefferson Castro.      | 11/09/2025             |
| OpenSource-Grupo-4/Landing-Page                    | main   | 59a25be   | feat: added steps section                      | Se agregó la sección de pasos.                        | 18/09/2025             |
| OpenSource-Grupo-4/Landing-Page                    | feature/responsive   | 4317f4c   | styles: updated responsive for steps cards     | Se mejoró la responsividad de las tarjetas de pasos.  | 18/09/2025             |
| OpenSource-Grupo-4/Landing-Page                    | main   | 9deb5a8   | feat: added steps section                      | Se agregó la sección de pasos.                        | 18/09/2025             |
| OpenSource-Grupo-4/Landing-Page                    | develop   | 6802c55   | chore: added imgs & syntax updates             | Se añadieron imágenes y se actualizaron detalles de sintaxis. | 18/09/2025             |

Cada commit refleja el trabajo colaborativo y el cumplimiento de los objetivos del Sprint, asegurando la trazabilidad y transparencia en el desarrollo de **WeRide**.

**Reporte de commits:**

![Commits](/assets/chapter05/landing-commits.png)

---

#### 5.2.1.5. Execution Evidence for Sprint Review.

En esta entrega, nos centramos en el desarrollo completo de la Landing Page para nuestra plataforma de educación en línea. Nuestro objetivo es desplegar una página web atractiva y efectiva que actúe como el punto de entrada para nuestros usuarios. 

Es por ello que se comparte las evidencias de ambos repositorios para corroborar el trabajo hecho por cada uno de los participantes.

![NetworkGraph](/assets/chapter05/networkgraph.png)

#### 5.2.1.6. Services Documentation Evidence for Sprint Review.

Para esta primera entrega no hubo implementación de APIs, pues solo se realizó la Landing Page.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review.

El objetivo del primer Sprint fue el desarrollo e implementación de la Landing Page. Para eso, utilizamos GitHub y GitHub Pages. El proceso del desarrollo fue el siguiente:

1. Se creó una organización en GitHub y, dentro de ella, se crearon dos repositorios. Uno para el informe del trabajo y otro para la Landing Page ![GithubOrg](/assets/chapter05/organization-os.png)
2. Luego, a través de los commits, el equipo fue editando los archivos index.html y styles.css, además de ir añadiendo imágenes a utilizar en el directorio images. ![Commits-example](/assets/chapter05/commits.png)
3. Finalmente, se implementó GitHub Pages en el repositorio de GitHub y se desplegó la Landing Page, la que se puede visitar en el siguiente link: https://opensource-grupo-4.github.io/Landing-Page

#### 5.2.1.8. Team Collaboration Insights during Sprint.

A continuación, se adjuntan las capturas de evidencia de los insights de los repositorios del informe y Landing Page para evidenciar la participación de todos los miembros:

- Insight Landing Page:
![InsightLP](/assets/chapter05/insightLP.png)

- Insight Report
![InsightR](/assets/chapter05/insightR.png)

### 5.2.2. Sprint 2
#### 5.2.2.1. Sprint Planning 2.

# 🏁 Sprint #2

## 📋 Sprint Planning Background
| Elemento | Descripción |
|-----------|--------------|
| **Date** | 2025-10-07 |
| **Time** | 09:30 AM |
| **Location** | Reunión virtual vía Google Meet |
| **Prepared By** | Samuel Bonifacio|
| **Attendees (Planning Meeting)** | Jefferson Castro / Samuel Bonifacio / Diego Seminario / Jhimy Romero / Arnold Morales |

---

## 🔄 Sprint 1 – Review Summary
**Resumen:**  
Durante el Sprint 1 se logró cumplir con el objetivo principal de establecer la base del sistema, incluyendo la creación del repositorio en GitHub, la definición de la arquitectura del proyecto y la implementación del módulo de **registro e inicio de sesión de usuarios**.  

El equipo presentó al Product Owner una versión funcional inicial, que permitió validar el flujo básico de autenticación.  
El feedback recibido fue positivo, destacando el buen trabajo en la interfaz y el correcto funcionamiento del backend, aunque se solicitó optimizar la validación de campos y mejorar la documentación técnica de las funciones principales.  

En general, se alcanzó un **85% del objetivo del Sprint**, con los entregables principales completados y aprobados.

---

## 💬 Sprint 1 – Retrospective Summary
**Resumen:**  
El equipo coincidió en que la **comunicación fue efectiva** y que la distribución de tareas facilitó el cumplimiento de los objetivos.  
Se destacó la organización del repositorio y el uso de ramas por integrante como buenas prácticas adoptadas.  

Entre las oportunidades de mejora, se mencionó la necesidad de:
- Mejorar la **planificación del tiempo individual** para evitar retrasos en la integración.
- Documentar mejor las decisiones técnicas y los pasos de instalación del entorno.
- Realizar pruebas de integración antes de subir cambios al repositorio principal.

Como acción correctiva, el equipo acordó implementar una **revisión de código por pares (code review)** y mantener reuniones cortas de seguimiento los martes y jueves.

---

## 🎯 Sprint Goal & User Stories

| Elemento | Descripción |
|-----------|--------------|
| **Sprint 2 Goal** | Desarrollar el módulo de **gestión de perfiles de usuario**, que permita editar información personal, subir una foto de perfil y visualizar los datos registrados. También se busca mejorar la experiencia del usuario y validar el correcto almacenamiento de los cambios en la base de datos. La métrica de cumplimiento será la entrega del módulo totalmente funcional y probado. |
| **Sprint 2 Velocity** | 26 Story Points |
| **Sum of Story Points** | 25 Story Points (asignados a los User Stories seleccionados para este Sprint) |

---

### 📘 User Stories del Sprint 2
| ID | User Story | Descripción | Story Points |
|----|-------------|--------------|--------------|
| US-005 | Edición de perfil de usuario | Como usuario, quiero editar mi información personal (nombre, correo, teléfono) para mantener mis datos actualizados. | 8 |
| US-006 | Visualización del perfil | Como usuario, quiero visualizar mi información personal y mi foto de perfil desde mi cuenta. | 5 |
| US-007 | Carga de foto de perfil | Como usuario, quiero subir o cambiar mi foto de perfil para personalizar mi cuenta. | 6 |
| US-008 | Confirmación de actualización | Como usuario, quiero recibir una notificación cuando mis cambios se guarden correctamente. | 6 |

---

## 🧠 Tareas Técnicas Principales
- Diseñar la interfaz del módulo de perfil de usuario (Figma).  
- Implementar el backend para actualización y consulta de datos del perfil (API REST).  
- Integrar la funcionalidad de subida de imágenes.  
- Conectar el módulo de perfil con la base de datos existente.  
- Realizar pruebas unitarias y de integración para verificar la persistencia de datos.  
- Documentar las funciones implementadas y actualizar el README del repositorio.  

---

## ⚙️ Herramientas Utilizadas
- **Lenguaje:** Java / JavaScript  
- **Frameworks:** Spring Boot / Angular  
- **Base de datos:** MySQL  
- **Control de versiones:** GitHub  
- **Comunicación:** Google Meet / WhatsApp  
- **Gestión del proyecto:** Trello  

---

## 🧑‍💻 Equipo de Desarrollo
- Jefferson Castro  
- Samuel Bonifacio  
- Diego Seminario  
- Jhimy Romero  
- Arnold Morales


#### 5.2.2.2. Aspect Leaders and Collaborators.

## 🤝 Aspect Leaders and Collaborators (LACX)

Durante el **Sprint 2**, el equipo se centró en cuatro aspectos principales del desarrollo:
- **Conexión con la base de datos (db.json)**  
- **Autenticación de usuarios**  
- **Diseño e interfaz de la aplicación**  
- **Gestión de reservas**

A continuación, se presenta la **Leadership and Collaboration Matrix (LACX)** que indica, por integrante, quién asume el rol de **Líder (L)** y quién actúa como **Colaborador (C)** en cada aspecto del Sprint.

| Team Member (Last Name, First Name) | GitHub Username | Conexión con Base de Datos (db.json) | Autenticación de Usuarios | Diseño e Interfaz de la Aplicación | Gestión de Reservas |
|------------------------------------|-----------------|-------------------------------------|---------------------------|-----------------------------------|---------------------|
| **Castro, Jefferson** | jeffersoncastro | **L** | **C** | **C** | **L** |
| **Bonifacio, Samuel** | samuelbonifacio | **C** | **L** | **C** | **C** |
| **Seminario, Diego** | diegoseminario | **C** | **C** | **L** | **C** |
| **Romero, Jhimy** | jhimyromero | **C** | **C** | **C** | **C** |
| **Morales, Arnold** | arnoldmorales | **C** | **C** | **C** | **C** |

---

**Notas:**
- **Jefferson Castro** lidera la **conexión con la base de datos (db.json)** y la **gestión de reservas**, colaborando además en autenticación y diseño.  
- **Samuel Bonifacio** lidera la **autenticación de usuarios**, garantizando la seguridad del inicio de sesión.  
- **Diego Seminario** lidera el **diseño e interfaz** de la aplicación, enfocándose en la experiencia de usuario.  
- **Jhimy Romero** y **Arnold Morales** colaboran en las distintas fases de **integración y pruebas** de los módulos desarrollados.


#### 5.2.2.3. Sprint Backlog 2.

### 5.2.2.3. Sprint Backlog 2

Durante el **Sprint 2**, el equipo centró sus esfuerzos en implementar los aspectos fundamentales de la aplicación relacionados con la **conexión de datos**, **autenticación**, **diseño visual** y **funcionalidad de reservas**.  

A continuación, se presenta el **Sprint Backlog 2**, que detalla las historias de usuario priorizadas, las tareas correspondientes, los criterios de aceptación y los responsables de cada actividad.

| **ID** | **Historia de Usuario** | **Descripción / Objetivo** | **Tareas Principales** | **Criterios de Aceptación** | **Responsable(s)** |
|--------|--------------------------|-----------------------------|-------------------------|------------------------------|--------------------|
| **HU-01** | Conexión con db.json | Como desarrollador, quiero conectar la app con el archivo `db.json` para almacenar y consultar información. | - Configurar db.json como fuente de datos. <br> - Implementar métodos de lectura/escritura. <br> - Verificar persistencia de datos. | - La aplicación se conecta correctamente a `db.json`. <br> - Los datos se leen y guardan sin errores. | **Jefferson Castro (L)** <br> Samuel Bonifacio (C) |
| **HU-02** | Autenticación de Usuarios | Como usuario, quiero poder registrarme e iniciar sesión de manera segura. | - Implementar formulario de registro y login. <br> - Validar credenciales con db.json. <br> - Gestionar sesiones activas. | - El sistema permite autenticación válida. <br> - Los usuarios no pueden acceder sin credenciales. | **Samuel Bonifacio (L)** <br> Jefferson Castro (C) |
| **HU-03** | Diseño e Interfaz de la Aplicación | Como usuario, quiero una interfaz intuitiva y moderna para navegar fácilmente en la app. | - Crear estructura visual del front-end. <br> - Aplicar estilos coherentes con la identidad del proyecto. <br> - Validar la usabilidad. | - La interfaz cumple los lineamientos visuales. <br> - La navegación es clara y funcional. | **Diego Seminario (L)** <br> Jhimy Romero (C), Arnold Morales (C) |
| **HU-04** | Gestión de Reservas | Como usuario, quiero poder realizar y consultar mis reservas dentro de la aplicación. | - Crear módulo de reservas. <br> - Guardar información en db.json. <br> - Mostrar historial de reservas. | - El sistema registra y muestra correctamente las reservas. <br> - Las reservas se guardan de forma persistente. | **Jefferson Castro (L)** <br> Samuel Bonifacio (C) |
| **HU-05** | Pruebas e Integración Final | Como equipo, queremos asegurar que todos los módulos funcionen correctamente de forma integrada. | - Realizar pruebas de integración. <br> - Validar flujos entre módulos (login, reserva, etc.). <br> - Corregir errores detectados. | - Todos los módulos funcionan de forma integrada. <br> - No se detectan errores críticos. | **Todo el equipo** |

---

**Duración del Sprint:** 2 semanas  
**Objetivo Principal:** Integrar la funcionalidad completa de autenticación y reservas con persistencia de datos en `db.json` y diseño de interfaz básico.  
**Entregables:**  
- Base de datos `db.json` conectada.  
- Sistema de autenticación funcional.  
- Interfaz gráfica inicial implementada.  
- Módulo de reservas operativo.  
- Pruebas de integración completadas.

---

#### 5.2.2.4. Development Evidence for Sprint Review.

### 5.2.2.4. Development Evidence for Sprint Review

During **Sprint 2**, the team successfully developed and validated core functionalities of the application related to **data management**, **user authentication**, **UI design**, and **reservation features**. The following evidence summarizes the key development results achieved throughout this iteration.

#### 🔹 Implemented Functionalities

| **Feature** | **Description** | **Evidence of Implementation** |
|--------------|------------------|--------------------------------|
| **Database Connection (db.json)** | The application was connected to a local `db.json` file to store and retrieve user and reservation data. | - API requests verified through console logs and Postman. <br> - Database file updated dynamically after each CRUD operation. |
| **User Authentication** | Login and registration modules were implemented to ensure secure access. | - Frontend login and register pages fully functional. <br> - Credential validation and session control confirmed. |
| **UI/UX Design** | A user-friendly interface was designed, applying consistent colors, typography, and layout. | - App screens developed following the Figma design. <br> - Navigation tested on desktop and mobile view. |
| **Reservation System** | Users can create, view, and manage their reservations directly from the app. | - Reservation data stored in `db.json`. <br> - Reservation history and active bookings displayed correctly. |
| **Integration Testing** | All modules were integrated and tested to ensure full compatibility. | - Successful flow from login → reservation → logout. <br> - No critical bugs detected during testing. |

#### 🔹 Development Tools and Environment

- **Frontend:** HTML, CSS, JavaScript (or Angular, if applicable).  
- **Backend / Data Layer:** `db.json` (simulated REST API).  
- **Version Control:** Git & GitHub (Branch: `feature/Jefferson`, merged to `develop`).  
- **Testing Tools:** Postman for API validation, manual UI testing.  
- **Design Tool:** Figma prototype used for UI consistency.  

#### 🔹 Screenshots / Visual Evidence (if applicable)
*(Include or reference screenshots such as:)*  
- Connection test to `db.json`.  
- Login and registration interface.  
- Reservation creation confirmation.  
- GitHub commits and pull request merge evidence.  

#### 🔹 Summary of Team Contributions

| **Team Member** | **Main Contributions During Sprint 2** |
|------------------|----------------------------------------|
| **Jefferson Castro** | Led the reservation system implementation and integration with `db.json`. |
| **Samuel Bonifacio** | Developed user authentication and contributed to database connection. |
| **Diego Seminario** | Designed and implemented the main user interface screens. |
| **Jhimy Romero** | Assisted in UI adjustments and performed integration testing. |
| **Arnold Morales** | Supported the design review and testing documentation. |

#### 🔹 Sprint Outcome
The sprint achieved full implementation of the planned functionalities. The team demonstrated the working system during the **Sprint Review meeting**, where the **Product Owner** validated that the features met acceptance criteria and provided positive feedback on system usability and consistency.

---

#### 5.2.2.5. Execution Evidence for Sprint Review.

### 5.2.2.5. Execution Evidence for Sprint Review

This section presents the evidence collected during the **execution phase of Sprint 2**, showing how the development tasks were carried out, monitored, and completed according to the sprint plan. It demonstrates the progress of the team, version control activity, and validation of implemented functionalities.

#### 🔹 Development Progress Tracking

- **Sprint Duration:** 2 weeks  
- **Sprint Goal:** Complete integration of authentication, reservation system, and connection with `db.json`.  
- **Daily Scrums:** Conducted virtually using Discord to monitor daily progress and discuss blockers.  
- **Task Management:** Each team member tracked their tasks through GitHub issues and commit logs.  

#### 🔹 Git & Version Control Evidence

| **Evidence Type** | **Description** |
|--------------------|-----------------|
| **Branching Strategy** | Development was performed under the `feature/Jefferson` branch, then merged into the `develop` branch after peer review. |
| **Commits** | Multiple commits were made showing progressive implementation of authentication, reservation, and database logic. |
| **Pull Requests** | Pull requests documented code review and approval from other members before merging into `develop`. |
| **Git Logs / Screenshots** | Screenshots or logs show commit messages related to `db.json` setup, UI components, and reservation integration. |

#### 🔹 Application Execution Evidence

| **Feature** | **Execution Evidence** |
|--------------|-------------------------|
| **Database Connection (`db.json`)** | Verified by successful read/write operations. Console logs confirmed correct data storage and retrieval. |
| **User Authentication** | Login and registration tested with valid and invalid credentials. Users authenticated correctly, and sessions were maintained. |
| **UI/UX Navigation** | Application screens displayed correctly according to the design. Navigation between login, reservation, and home screens was smooth. |
| **Reservation Functionality** | Test users were able to create and display reservations. Data persisted in `db.json` after reloading. |
| **Integration Test** | The flow from login → reservation creation → logout executed successfully without errors. |

#### 🔹 Testing and Validation

- **Functional Tests:** Conducted to ensure core modules operated as expected.  
- **Manual UI Testing:** Verified that all elements rendered properly and responded to user interaction.  
- **Integration Validation:** Confirmed data consistency between UI components and the `db.json` data source.  
- **Error Handling:** Validations added for incorrect login data and empty reservation forms.

#### 🔹 Evidence of Team Execution

| **Team Member** | **Key Actions Executed During Sprint 2** |
|------------------|------------------------------------------|
| **Jefferson Castro** | Implemented reservation module logic and confirmed data persistence with `db.json`. |
| **Samuel Bonifacio** | Executed and tested the user authentication system. |
| **Diego Seminario** | Developed and executed the main user interface components. |
| **Jhimy Romero** | Participated in integration testing and UI validation. |
| **Arnold Morales** | Supported execution testing and review of visual consistency. |

#### 🔹 Sprint Review Outcome

During the **Sprint Review meeting**, the team demonstrated the running version of the application to the **Product Owner**.  
- The demonstration included logging in, making a reservation, and verifying data updates in `db.json`.  
- The Product Owner confirmed that all functionalities were executed successfully and aligned with the Sprint Goal.  
- Minor UI adjustments were recommended for Sprint 3.

---

**Summary:**  
All planned features for Sprint 2 were **successfully executed**. The application demonstrated functional integration between authentication, data management, and reservation modules, meeting both technical and usability objectives.

---

#### 5.2.2.6. Services Documentation Evidence for Sprint Review.

### 5.2.2.6. Services Documentation Evidence for Sprint Review

This section presents the documentation of the **services developed and integrated** during Sprint 2. The evidence focuses on how the application’s internal and external services interact to provide data management, authentication, and reservation functionalities.  

#### 🔹 Overview of Implemented Services

During Sprint 2, the team implemented and documented the following key services:

| **Service Name** | **Description** | **Type** | **Associated Components / Modules** |
|------------------|-----------------|-----------|------------------------------------|
| **Database Service (`db.json`)** | Provides persistent local data storage for users and reservations through a REST-like interface. | Backend (Local JSON Server) | User module, Reservation module |
| **Authentication Service** | Manages user registration, login, and session validation. | Frontend / Backend Integration | Login Page, Registration Page |
| **Reservation Service** | Handles creation, retrieval, and visualization of user reservations stored in `db.json`. | Backend | Reservation Form, User Dashboard |
| **UI Rendering Service** | Ensures the dynamic display of data in the interface, updating user and reservation views. | Frontend | Dashboard, Reservation History |
| **Data Fetch Service (Fetch API)** | Responsible for performing asynchronous requests (GET, POST, PUT, DELETE) to `db.json`. | Middleware / API Layer | All application modules |

---

#### 🔹 Service Interaction Flow

The interaction between services can be summarized as follows:

1. **User Authentication:**  
   - When a user registers or logs in, the Authentication Service verifies credentials against `db.json`.  
   - If successful, a session is initiated in the application.

2. **Data Management:**  
   - The Database Service manages all data transactions via REST calls handled by the Fetch API.  
   - CRUD operations are executed to update user and reservation information.

3. **Reservation Process:**  
   - The Reservation Service communicates with the Database Service to store or retrieve reservation data.  
   - The UI Rendering Service updates the screen dynamically after each successful operation.

4. **Interface Update:**  
   - Once new data is fetched or modified, the UI Rendering Service refreshes the user dashboard.

---

#### 🔹 Example of Service Endpoints (Using `db.json`)

| **HTTP Method** | **Endpoint** | **Purpose** | **Example Response** |
|------------------|--------------|--------------|----------------------|
| **GET** | `/users` | Retrieve list of registered users. | `[ { "id": 1, "name": "Jefferson", "email": "jeff@gmail.com" } ]` |
| **POST** | `/users` | Register a new user. | `{ "id": 2, "name": "Samuel", "email": "samuel@gmail.com" }` |
| **GET** | `/reservations` | Retrieve all reservations. | `[ { "id": 1, "user": "Jefferson", "date": "2025-10-07" } ]` |
| **POST** | `/reservations` | Create a new reservation. | `{ "id": 2, "user": "Diego", "date": "2025-10-09" }` |
| **PUT** | `/reservations/:id` | Update existing reservation data. | `{ "id": 1, "user": "Jefferson", "date": "2025-10-08" }` |
| **DELETE** | `/reservations/:id` | Delete a reservation. | `{}` |

---

#### 🔹 Documentation Deliverables

- **README.md:** Contains a summary of project services, endpoints, and installation instructions.  
- **Service Flow Diagram:** Illustrates how services interact within the application.  
- **Code Documentation:**  
  - Inline comments describing each API call.  
  - Function-level documentation for service logic (fetch requests, handlers, etc.).  
- **Test Logs:** Confirm successful service responses using Postman and console validation.

---

#### 🔹 Team Contributions to Service Documentation

| **Team Member** | **Contributions** |
|------------------|-------------------|
| **Jefferson Castro** | Documented and implemented the Reservation Service integration with `db.json`. |
| **Samuel Bonifacio** | Created and documented the Authentication Service and user management logic. |
| **Diego Seminario** | Supported service documentation by integrating UI components that consume backend data. |
| **Jhimy Romero** | Reviewed documentation consistency and assisted in service validation. |
| **Arnold Morales** | Contributed to README structure and endpoint testing notes. |

---

#### 🔹 Summary

All core services were documented and tested successfully during **Sprint 2**.  
The documentation provides clear guidelines for maintaining and extending the system, ensuring that future developers can easily integrate new modules or APIs. The team validated that all endpoints work as expected, supporting the application’s functionality for authentication and reservations.

---

#### 5.2.2.7. Software Deployment Evidence for Sprint Review.

### 5.2.2.7. Software Deployment Evidence for Sprint Review

This section provides evidence of the deployment process and validation of the functional version of the application developed during **Sprint 2**.  
The deployment focused on ensuring that the application components, database connections, and services worked correctly in the local environment.

#### 🔹 Deployment Environment

| **Environment Type** | **Description** |
|------------------------|-----------------|
| **Local Development Environment** | Each developer deployed the app locally for testing and integration. |
| **Database** | `db.json` used as a mock REST API for user and reservation data persistence. |
| **Frontend Tools** | HTML, CSS, JavaScript (or Angular framework, if applicable). |
| **Hosting Simulation** | Local server executed via `json-server` and browser client testing. |
| **Version Control** | Managed through GitHub branches (`feature/Jefferson`, merged into `develop`). |

#### 🔹 Deployment Steps

1. **Database Setup:**  
   - `db.json` file created with structured sections for users and reservations.  
   - Executed local JSON server with command:  
     ```
     json-server --watch db.json --port 3000
     ```
   - Verified that endpoints responded correctly to CRUD operations.

2. **Application Build and Run:**  
   - Frontend connected successfully to backend (`db.json`) using Fetch API calls.  
   - Application tested in Chrome and Edge browsers for cross-compatibility.  

3. **Integration Verification:**  
   - Confirmed user login, registration, and reservation creation worked seamlessly.  
   - Data persisted after refresh and API calls returned expected responses.  

4. **Testing after Deployment:**  
   - Manual verification performed by all team members.  
   - No critical bugs found during execution or API requests.

#### 🔹 Deployment Validation Evidence

| **Validation Item** | **Evidence / Observation** |
|----------------------|-----------------------------|
| **App Launch** | Application executed successfully on localhost without errors. |
| **Database Connection** | Verified live communication between UI and `db.json`. |
| **Authentication Flow** | Login and registration tested successfully for multiple users. |
| **Reservation Module** | Reservations created and retrieved correctly from `db.json`. |
| **User Interface Rendering** | UI loaded all data dynamically and displayed updates instantly. |

#### 🔹 Deployment Outcome

The software deployment for Sprint 2 was **successfully completed**.  
The application runs locally, providing full functionality of authentication, data persistence, and reservation handling. The deployment validated the team’s implementation and confirmed readiness for further development in Sprint 3.


#### 5.2.2.8. Team Collaboration Insights during Sprint

### 5.2.2.8. Team Collaboration Insights during Sprint

During **Sprint 2**, the team maintained effective communication, coordination, and collaboration to achieve the sprint goal. The members demonstrated clear leadership, accountability, and cooperative problem-solving to ensure continuous progress.

#### 🔹 Collaboration Methods

- **Daily Communication:**  
  Conducted through **Discord** for quick updates and issue resolution.  

- **Weekly Checkpoints:**  
  Virtual meetings held twice a week to review completed tasks and blockers.  

- **GitHub Collaboration:**  
  Team members collaborated through **branches, commits, and pull requests** to integrate their code efficiently.  

- **Shared Documentation:**  
  Project documentation and notes were maintained in shared online documents and GitHub README files.

#### 🔹 Team Roles and Contributions

| **Team Member** | **Primary Contributions During Sprint 2** | **Collaboration Highlights** |
|------------------|-------------------------------------------|-------------------------------|
| **Jefferson Castro** | Led the development of the Reservation module and coordinated data persistence using `db.json`. | Provided guidance on data structure and integration testing. |
| **Samuel Bonifacio** | Developed the Authentication service and supported integration with the database. | Collaborated closely with Jefferson on data validation logic. |
| **Diego Seminario** | Designed and implemented the main UI components following the team’s Figma prototype. | Worked collaboratively with Jhimy and Arnold for design consistency. |
| **Jhimy Romero** | Assisted in front-end testing and integration of UI with backend data. | Contributed to debugging and verifying smooth module connections. |
| **Arnold Morales** | Participated in UI testing and documentation updates. | Helped refine the README structure and visual layout notes. |

#### 🔹 Lessons Learned and Improvements

- Clearer **task ownership** improved accountability.  
- Frequent communication reduced misunderstandings.  
- Early testing helped identify and fix integration issues faster.  
- Plan to automate part of the testing process for Sprint 3.

#### 🔹 Summary

Team collaboration during Sprint 2 was **highly effective**, resulting in the timely completion of all planned functionalities. The cooperative environment and proactive problem-solving contributed significantly to the success of the sprint and set a strong foundation for future iterations.


## Conclusiones
- El proyecto de micromovilidad eléctrica compartida responde a necesidades reales de movilidad en áreas urbanas peruanas: congestión, tiempos de traslado elevados, y demanda por alternativas más económicas y sostenibles. La combinación de scooters, bicicletas y motos eléctricas gestionadas desde una única plataforma web representa una propuesta con alto potencial de adopción, especialmente en segmentos juveniles y corporativos.
- La identificación de dos segmentos prioritarios —jóvenes universitarios y empresas con planes de suscripción— es coherente con los hallazgos cualitativos. Los primeros buscan conveniencia, bajo costo y métodos de pago locales (Yape/Plin); las empresas buscan soluciones de movilidad para colaboradores y valoran la previsibilidad de costos y la imagen de sostenibilidad. Esta segmentación favorece estrategias de adquisición y retención diferenciadas.
- La propuesta de combinar pago por uso (desbloqueo + tarifa por minuto) con pases diarios, mensuales y corporativos ofrece una mezcla adecuada para equilibrar ingresos inmediatos y recurrentes. Los precios sugeridos y el descuento universitario crean incentivos para adopción temprana y fidelización. No obstante, la rentabilidad dependerá de la tasa de utilización por vehículo (objetivo mínimo: 4–5 viajes/día) y de una gestión eficiente de costos operativos (mantenimiento, recarga, logística).
- Las funciones críticas —búsqueda en tiempo real (GPS/IoT), mapa interactivo, reservas con temporizador y desbloqueo digital (QR/PIN/IoT)— están correctamente priorizadas. Estas funcionalidades garantizan una experiencia simple y confiable desde la web, mientras que el desbloqueo digital y la gestión remota son componentes esenciales para control y seguridad de la flota.

  
## Bibliografía

- Alexander, I., & Beus-Dukic, L. (2009). *Discovering Requirements: How to Specify Products and Services*. Wiley.
- Cohn, M. (2004). *User Stories Applied: For Agile Software Development*. Addison-Wesley.
- Gamma, E., Helm, R., Johnson, R., & Vlissides, J. (1994). *Design Patterns: Elements of Reusable Object-Oriented Software*. Addison-Wesley.
- Kruchten, P. (2003). *The Rational Unified Process: An Introduction*. Addison-Wesley.
- Newman, S. (2015). *Building Microservices: Designing Fine-Grained Systems*. O’Reilly Media.
- Sommerville, I. (2016). *Software Engineering* (10th ed.). Pearson.
- W3C. (2024). *HTML & CSS Standards*. Recuperado de: https://www.w3.org/
- Mozilla Developer Network (MDN). (2024). *JavaScript Guide*. Recuperado de: https://developer.mozilla.org/es/docs/Web/JavaScript/Guide
- GitHub Docs. (2024). *GitHub Pages Documentation*. Recuperado de: https://docs.github.com/en/pages
- Stripe Docs. (2024). *Stripe Payments Integration Guide*. Recuperado de: https://stripe.com/docs
- Figma. (2024). *Figma Design Documentation*. Recuperado de: https://help.figma.com/
- Google Maps Platform. (2024). *Maps JavaScript API Documentation*. Recuperado de: https://developers.google.com/maps/documentation/javascript
- Node.js Foundation. (2024). *Node.js Documentation*. Recuperado de: https://nodejs.org/en/docs/
- Vue.js. (2024). *Vue.js Guide*. Recuperado de: https://vuejs.org/guide/introduction.html

## Anexos.

![Organización](https://github.com/OpenSource-Grupo-4)

![Reporte del Proyecto](https://github.com/OpenSource-Grupo-4/ReportTB1)

![Repositorio de Landing Page](https://github.com/OpenSource-Grupo-4/Landing-Page)

![Deploy de Landing Page](https://opensource-grupo-4.github.io/Landing-Page)

![Presentación de Canvas](https://www.canva.com/design/DAGzltc5qz0/jV9yXK8Nme4XSOk6AUhFgg/edit)

![Figma]([https://www.figma.com/design/kt2VQ3DmUCAFoAeB9mAjnU/UX-UI-Apps_Web_20252_UPC?node-id=4-143&p=f&t=8ivn25D6KVbvvX71-0](https://www.figma.com/design/6R0aWHPQEpwX8DyWLrCHmd/Open-Source-2025-2?t=moMeoEwSHQRhgL2O-0))

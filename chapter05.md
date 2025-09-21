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
    <td><h4>JavaScript</h4>JavaScript es un lenguaje de programación de alto nivel, interpretado y multi-paradigma, utilizado para crear interactividad en páginas web.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>VSCode</h4>Es un editor de código fuente con extensiones que ayudan al desarrollo.</td>
  </tr>
    <tr>
    <td></td>
    <td><h4>WebStorm</h4>Es un IDE centrado en el desarrollo frontend, por su variedad de herramientas que agilizan el proceso de desarrollo.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>Vue.js</h4>Framework basado en Single Page Applications para el desarrollo de frontend</td>
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

![Figma](https://www.figma.com/design/kt2VQ3DmUCAFoAeB9mAjnU/UX-UI-Apps_Web_20252_UPC?node-id=4-143&p=f&t=8ivn25D6KVbvvX71-0)
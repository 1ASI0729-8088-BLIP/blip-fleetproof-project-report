# Capítulo V: Product Implementation, Validation & Deployment

## 5.1 Software Configuration Management

### 5.1.1 Software Development Environment Configuration

En esta sección se describen las herramientas de software seleccionadas para dar soporte a las distintas fases del ciclo de vida del producto digital. Se incluyen sus nombres, objetivos específicos dentro del proyecto y los enlaces de acceso o descarga, diferenciando entre soluciones SaaS y aplicaciones instalables.
* **Gestión de Proyectos y Tareas**

| Herramienta | Uso principal | Enlace / Ruta de Acceso |
|---|---|---|
| **Jira Software** | Organización de tareas y entregables mediante tableros ágiles, tanto a nivel individual como por módulo. | [https://jira.atlassian.com](https://jira.atlassian.com) |
| **GitHub Projects** | Seguimiento de proyectos con enfoque en historias de usuario, issues y Pull Requests en repositorios. | [https://github.com/features/issues](https://github.com/features/issues) |

* **Diseño de Experiencia y UI/UX**

| Herramienta | Uso principal | Enlace / Ruta de Acceso |
|---|---|---|
| **Figma** | Diseño colaborativo de wireframes, mockups y prototipos navegables para la aplicación y Landing Page. | [https://figma.com](https://figma.com) |
| **Miro** | Elaboración de user flows, wireflows, Big Picture Event Storming y mapas de arquitectura. | [https://miro.com](https://miro.com) |
| **UXPressia** | Creación de User Personas, Empathy Maps, Journey Maps e Impact Maps. | [https://uxpressia.com](https://uxpressia.com) |

* **Desarrollo de Software**

| Herramienta / Tecnología | Uso principal | Enlace / Ruta de Descarga |
|---|---|---|
| **Visual Studio Code** | Entorno de desarrollo ligero para la edición del Landing Page con HTML5, CSS3 y JavaScript. | [https://code.visualstudio.com](https://code.visualstudio.com) |
| **WebStorm** | IDE principal para el desarrollo del Frontend SPA utilizando Vue 3 y TypeScript. | [https://www.jetbrains.com/webstorm/](https://www.jetbrains.com/webstorm/) |
| **Rider / Visual Studio** | Entorno de desarrollo integrado para la construcción del Backend API con ASP.NET Core y C#. | [https://www.jetbrains.com/rider/](https://www.jetbrains.com/rider/) |
| **HTML5** | Lenguaje de marcado para estructurar el contenido de la Landing Page. | [https://developer.mozilla.org/es/docs/Web/HTML](https://developer.mozilla.org/es/docs/Web/HTML) |
| **CSS3** | Lenguaje de estilos para definir la apariencia visual y responsiva de la Landing Page. | [https://developer.mozilla.org/es/docs/Web/CSS](https://developer.mozilla.org/es/docs/Web/CSS) |
| **Vue 3** | Framework progresivo de JavaScript para construir interfaces de usuario reactivas en la Web Application. | [https://vuejs.org](https://vuejs.org) |

* **Diseño de Arquitectura de Software**

| Herramienta | Uso principal | Enlace / Ruta de Acceso |
|---|---|---|
| **Mermaid** | Modelado de arquitectura mediante Diagramas como Código (Contexto, Contenedores C3, Clases y Base de datos). | [https://mermaid.js.org](https://mermaid.js.org) |

* **Despliegue de Software**

| Herramienta / Plataforma | Uso principal | Enlace / Ruta de Acceso |
|---|---|---|
| **Netlify** | Despliegue automático y gratuito de la Landing Page estática y el Frontend SPA. | [https://www.netlify.com](https://www.netlify.com) |
| **Render / Azure** | Despliegue en la nube del Backend API (ASP.NET Core) y alojamiento de la base de datos PostgreSQL. | [https://render.com](https://render.com) |

* **Documentación de Software**

| Herramienta / Recurso | Uso principal | Enlace / Ruta de Acceso |
|---|---|---|
| **Markdown** | Edición y mantenimiento de los archivos `.md` asociados a la documentación del proyecto. | [https://www.markdownguide.org](https://www.markdownguide.org) |
| **GitHub** | Repositorio con control de versiones, utilizado además como espacio de documentación en issues y PRs. | [https://github.com](https://github.com) |
| **Git** | Sistema distribuido de control de versiones para la gestión del código fuente. | [https://git-scm.com](https://git-scm.com) |
| **GitFlow Workflow** | Modelo de ramificación para mantener el código y la documentación organizados. | [https://nvie.com/posts/a-successful-git-branching-model](https://nvie.com/posts/a-successful-git-branching-model) |
| **Conventional Commits** | Convención de mensajes de commit para mejorar la trazabilidad y facilitar la generación de changelogs. | [https://www.conventionalcommits.org](https://www.conventionalcommits.org) |
### 5.1.2 Source Code Management
El equipo empleará GitHub como repositorio de alojamiento y Git como sistema de control de versiones para todos los entregables del proyecto FleetProof. Se aplicará la estrategia de ramificación GitFlow Workflow, con el uso de Semantic Versioning y mensajes estructurados bajo la convención de Conventional Commits.

**Repositorios del Proyecto**

| Producto | Repositorio GitHub |
|---|---|
| **Organización BLIP** | [https://github.com/1ASI0729-8088-BLIP](https://github.com/1ASI0729-8088-BLIP) |
| **Landing Page** | [https://github.com/1ASI0729-8088-BLIP/blip-fleetproof-LandingPage](https://github.com/1ASI0729-8088-BLIP/blip-fleetproof-LandingPage) |
| **Project Report** | [https://github.com/1ASI0729-8088-BLIP/blip-fleetproof-project-report](https://github.com/1ASI0729-8088-BLIP/blip-fleetproof-project-report) |
| **Frontend Web App** | [https://github.com/1ASI0729-8088-BLIP/blip-fleetproof-frontend](https://github.com/1ASI0729-8088-BLIP/blip-fleetproof-frontend) |
| **Backend API** | [https://github.com/1ASI0729-8088-BLIP/blip-fleetproof-backend](https://github.com/1ASI0729-8088-BLIP/blip-fleetproof-backend) |

**Modelo GitFlow**

Se seguirá el enfoque planteado por Vincent Driessen, el cual define dos ramas principales:
* `main`: contiene las versiones estables listas para producción.
* `develop`: integra nuevas funcionalidades antes de pasar al entorno de producción.

| Tipo de rama | Uso principal | Convención de nombres | Ejemplo |
|---|---|---|---|
| **feature** | Desarrollo de funcionalidades nuevas. | `feature/<nombre-descriptivo>` | `feature/sprint1-landing` |
| **release** | Preparación de una versión previa al despliegue. | `release/vX.Y.Z` | `release/v1.0.0` |
| **hotfix** | Corrección rápida de errores en producción. | `hotfix/<problema>` | `hotfix/fix-mobile-menu` |

**Versionado Semántico**

Se implementará el esquema Semantic Versioning 2.0.0, con el formato:

**MAJOR.MINOR.PATCH**
* **MAJOR:** cambios incompatibles con versiones anteriores.
* **MINOR:** incorporación de nuevas funciones compatibles.
* **PATCH:** corrección de errores o mejoras menores.

**Conventional Commits**

Los mensajes de commit seguirán el estándar Conventional Commits para asegurar trazabilidad y generar changelogs automáticos.

Formato general: `(opcional-scope): descripción breve`

Tipos de commit definidos:
* `feat`: nueva funcionalidad
* `fix`: corrección de errores
* `docs`: cambios en documentación
* `style`: ajustes de formato (espacios, comas, etc.) sin afectar lógica
* `refactor`: modificaciones de código sin impacto en funciones o errores
* `test`: adición o modificación de pruebas
* `chore`: tareas de mantenimiento o generales

### 5.1.3 Source Code Style Guide & Coding Conventions

Con el objetivo de mantener un código ordenado, consistente y fácil de mantener entre todos los miembros del equipo, se han definido las siguientes convenciones. Todas las variables, funciones, clases, archivos y elementos estarán en inglés.

* Se utilizará inglés como idioma único para nombres de variables, funciones, clases, comentarios y documentación técnica.
* Se evitarán abreviaciones innecesarias y nombres genéricos como `data1`, `temp`, `info`, etc.

**HTML**
Atributos en minúsculas y nombres de clase con `kebab-case` (`section-title`, `hero-grid`).
* Estructura semántica clara: uso de etiquetas como `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`.
* Sangría con 4 espacios.
* Atributos ordenados de manera lógica: `id`, `class`, `type`, `name`, `placeholder`, `value`, `required`, etc.

**CSS**
* Para clases personalizadas: usar `kebab-case`.
* Se agruparán variables globales en la seccion `:root` (paleta de colores y espaciado).

**Google TypeScript Style Guide**
Basado en el Google TypeScript Style Guide, se adoptan las siguientes reglas para mantener un código limpio y coherente en el desarrollo de la Web Application (Vue 3):

Nombres y sintaxis:
* `camelCase` para variables, funciones y parámetros.
* `PascalCase` para clases, interfaces, enums y tipos.
* Constantes con `UPPER_CASE_WITH_UNDERSCORES` si son globales.

Módulos y imports:
* Preferir imports explícitos y ordenados: primero bibliotecas externas, luego internas.
* Evitar `default exports`, usar siempre `export const` o `export class`.

Tipado y declaraciones:
* Siempre tipar explícitamente los parámetros y valores de retorno de funciones.
* Evitar `any` excepto cuando sea estrictamente necesario.
* Usar `readonly` para propiedades que no deben cambiarse.
* Interfaces en lugar de `type` cuando sea posible.

Buenas prácticas:
* Preferir `const` sobre `let`, y evitar `var`.
* Evitar usar `this` fuera de clases.
* No mezclar funciones y lógica en componentes — delegar a servicios.

**Vue 3 Style Guide**
Seguiremos las prácticas recomendadas por la documentación oficial de Vue 3:

Componentes:
* Nombres en `PascalCase` y con sufijo `Component` (ej. `VehicleReportComponent.vue`).
* Evitar lógica compleja en los templates: delegar a métodos o *composables* (Composition API).
* Uso de `<script setup>` para mayor legibilidad y rendimiento.

**C# y ASP.NET Core Conventions**
Para el desarrollo del Backend RESTful API:
* Nombres de Clases, Métodos e Interfaces (con prefijo `I`) en `PascalCase`.
* Variables locales y parámetros en `camelCase`.
* Estructura de carpetas basada en el diseño de Bounded Contexts y Domain-Driven Design (DDD).

**Pruebas / Gherkin**
En caso de usar Gherkin (para especificaciones o pruebas de los escenarios descritos en las User Stories):
* Usaremos el formato estandarizado `Given`, `When` y `Then`.

### 5.1.4 Software Deployment Configuration

1. **Ingresar a Netlify**<br>
   Accedemos a la plataforma mediante nuestras credenciales de Github en "Log in with GitHub".
   <img src="https://res.cloudinary.com/dehoql1oc/image/upload/v1789627588/Captura_de_pantalla_2026-09-17_013830_jsr61y.png" alt="inicio" width="800">

2. **Autorizar a Netlify** <br>
   Damos permisos a Netlify de acceder a nuestra cuenta de GitHub para luego ir a la sección "Sites" y presionar "Add new site". Entonces, le damos a "Import an existing project".
   <img src="https://res.cloudinary.com/dehoql1oc/image/upload/v1789628043/Captura_de_pantalla_2026-09-17_015348_kblafi.png" alt="inicio" width="800">

3. **Escoger tu deploy** <br>
   En la parte de "Let's deploy your project with..." seleccionamos GitHub.
   <img src="https://res.cloudinary.com/dehoql1oc/image/upload/v1789628214/Captura_de_pantalla_2026-09-17_015637_q2g9g8.png" alt="inicio" width="800">

4. **Escoger tu repositorio** <br>
   Dado que nuestro repositorio está bajo una organización, la seleccionamos.
   <img src="https://res.cloudinary.com/dehoql1oc/image/upload/v1789628431/Captura_de_pantalla_2026-09-17_020020_uspnlf.png" alt="inicio" width="800">

5. **Configurar el despliegue** <br>
   Ahora procedemos a configurar el despliegue, colocando el Site Name y seleccionando el Team, también debemos escoger una rama que en este caso será la Main.
   <img src="https://res.cloudinary.com/dehoql1oc/image/upload/v1789628547/Captura_de_pantalla_2026-09-17_020208_tqyiqu.png" alt="inicio" width="800">

6. **Seguir configurando** <br>
   Seguimos configurando, pero esta vez seleccionando el "Publish directory" colocamos public, para finalmente darle a "Deploy demy-academy".
   <img src="https://res.cloudinary.com/dehoql1oc/image/upload/v1789628631/Captura_de_pantalla_2026-09-17_020333_kaqg4d.png" alt="inicio" width="800">

7. **Despliegue listo** <br>
   Ahora podemos observar que el deploy está listo y podremos ver el enlace de la web a la landing page recién desplegada.
   <img src="https://res.cloudinary.com/dehoql1oc/image/upload/v1789628688/Captura_de_pantalla_2026-09-17_020436_pvq8li.png" alt="inicio" width="800">

Ahora con la Landing Page desplegada, cada vez que se realize un push en la rama correspondiente, se actualizara automáticamente, de esta manera evitamos repetir los pasos. <br>
[Link de la Landing Page](https://fleetproof-landingpage.netlify.app/)

## 5.2 Landing Page, Services & Applications Implementation

### 5.2.1 Sprint 1
<img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" alt="Universidad Peruana de Ciencias Aplicadas" width="90">

#### 5.2.1.1 Sprint Planning 1

| Campo | Valor |
|---|---|
| Sprint # | Sprint 1 |
| Date | TODO |
| Time | TODO |
| Location | TODO |
| Prepared By | Reyes Limo Sebastian |
| Attendees | Reyes Limo Sebastian / Quintanilla Gonzalo / Morales Jefferson / Gómez De La Torre Rodrigo / Gorbeña Eduardo |
| Sprint 1 Goal | Our focus is on presenting FleetProof's value proposition and segment-specific calls to action through the first deployed Landing Page. We believe it delivers clarity to fleet companies and vehicle owners. This will be confirmed when visitors can understand the product and access the corresponding call-to-action for their segment. |
| Sprint 1 Velocity | TODO |
| Sum of Story Points | TODO |

#### 5.2.1.2 Aspect Leaders and Collaborators

| Team Member | GitHub Username | SCM and Rubric | Lean UX | UX Research | Requirements | Product Design and Landing Page |
|---|---|---|---|---|---|---|
| Reyes Limo Sebastian | llegastian11 | L | C | C | C | C |
| Quintanilla Gonzalo | Pendiente | C | L | C | C | C |
| Morales Jefferson | TODO | C | C | L | C | C |
| Gómez De La Torre Rodrigo | TODO | C | C | C | L | C |
| Gorbeña Eduardo | TODO | C | C | C | C | L |

#### 5.2.1.3 Sprint Backlog 1

| Sprint # | Story Id | Story Title | Task Id | Task Title | Task Description | Estimation (Hours) | Assigned To | Status |
|---|---|---|---|---|---|---:|---|---|
| Sprint 1 | US001 | View value proposition | T001 | Draft Landing Page content | Redactar propuesta de valor, segmentos y beneficios. | 2 | Gorbeña Eduardo | To-do |
| Sprint 1 | US002 | Fleet monitoring CTA | T002 | Implement fleet CTA | Crear call-to-action hacia flujo empresarial. | 2 | Gorbeña Eduardo | To-do |
| Sprint 1 | US003 | Vehicle report CTA | T003 | Implement vehicle CTA | Crear call-to-action hacia flujo particular. | 2 | Gorbeña Eduardo | To-do |
| Sprint 1 | US004 | Compare plans | T004 | Add plan comparison | Presentar tres planes con límites. | 3 | Gómez De La Torre Rodrigo | To-do |
| Sprint 1 | US005 | View legal pages | T005 | Add legal links | Crear Terms and Conditions y Privacy Policy. | 2 | Reyes Limo Sebastian | To-do |

#### 5.2.1.4 Development Evidence for Sprint Review

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on |
|---|---|---|---|---|---|
| TODO | TODO | TODO | TODO | TODO | TODO |

#### 5.2.1.5 Execution Evidence for Sprint Review

TODO: Incluir screenshots de Landing Page desplegada y video de navegación.

#### 5.2.1.6 Services Documentation Evidence for Sprint Review

Para AV1, los Web Services se registran como planificación técnica si todavía no forman parte del alcance implementado.

| Endpoint | HTTP Verb | Description | Status | Evidence |
|---|---|---|---|---|
| `/api/v1/plans` | GET | List plans | Planned | TODO |
| `/api/v1/report-requests` | POST | Create report request | Planned | TODO |

#### 5.2.1.7 Software Deployment Evidence for Sprint Review

TODO: Incluir URL desplegada, capturas del proveedor y versión `v1.0.0` del Landing Page.

#### 5.2.1.8 Team Collaboration Insights during Sprint

TODO: Incluir capturas de commits, Pull Requests, merges y contributors.

## 5.3 Validation Interviews

### 5.3.1 Diseño de Entrevistas

TODO: Definir tareas de validación para Landing Page y Web Application.

### 5.3.2 Registro de Entrevistas

TODO: Registrar entrevistas de validación por segmento.

### 5.3.3 Evaluaciones según heurísticas

TODO: Aplicar formato de evaluación UX por heurísticas.

## 5.4 Video About-the-Product

TODO: Incluir screenshot, URL Microsoft Stream, URL YouTube y duración.

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1 Software Configuration Management

### 5.1.1 Software Development Environment Configuration

| Actividad | Herramienta | Propósito | URL |
|---|---|---|---|
| Project Management | JetBrains YouTrack / Jira Software / Trello | Gestionar Product Backlog y Sprint Backlog. | TODO |
| UX Research | UXPressia | Elaborar User Personas, Empathy Maps, Journey Maps e Impact Maps. | https://uxpressia.com |
| UX/UI Design | Figma | Elaborar wireframes, mock-ups y prototipos. | https://figma.com |
| Wireflows and User Flows | FigJam / LucidChart / Overflow | Representar flujos de interacción. | TODO |
| EventStorming | FigJam / LucidChart / Miro | Representar eventos del dominio. | TODO |
| Architecture Diagrams | Structurizr / LucidChart / PlantUML / Mermaid | Elaborar diagramas C4, UML y database diagrams. | TODO |
| Version Control | GitHub | Gestionar repositorios, ramas, commits, Pull Requests, merges, tags y releases. | https://github.com/1ASI0729-8088-BLIP |
| Landing Page Development | HTML5, CSS3, JavaScript | Desarrollar Landing Page. | TODO |
| Frontend Development | Angular Framework, TypeScript, Angular Material | Desarrollar Frontend Web Application. | TODO |
| Backend Development | Spring Boot, Spring Data JPA, Java | Desarrollar RESTful Web Services con Java. | TODO |
| Relational DBMS | MySQL Server / PostgreSQL | Persistir información relacional del producto. | TODO |
| API Documentation | Swagger / OpenAPI | Documentar Web Services. | TODO |

### 5.1.2 Source Code Management

Organización GitHub: https://github.com/1ASI0729-8088-BLIP

| Producto | Repositorio | Branch principal | Releases requeridos |
|---|---|---|---|
| Project Report | https://github.com/1ASI0729-8088-BLIP/blip-fleetproof-project-report | `main`, `develop` | AV1, TB1, AV2, TB2 |
| Landing Page | TODO | `main`, `develop` | `v1.0.0`, `v2.0.0`, `v3.0.0`, `v4.0.0` |
| Frontend Web Application | TODO | `main`, `develop` | `v1.0.0`, `v2.0.0`, `v3.0.0` |
| Web Services | TODO | `main`, `develop` | `v1.0.0`, `v2.0.0` |

GitFlow:

- Los aportes del informe para AV1 nacen desde `develop` en `feature/sprint1-<scope>` y se revisan mediante Pull Request hacia `develop`.
- Las ramas se crean cuando comienza el trabajo; la rama de release se crea al preparar la entrega.
- Cada User Story se implementa en una rama `feature/usXXX-<short-name>`.
- Cada User Story cerrada debe entrar con Pull Request y merge hacia `develop`.
- Cada release se estabiliza en `release/vX.Y.Z`.
- Cada release aprobado se fusiona hacia `main`, se etiqueta con `vX.Y.Z` y se fusiona de regreso hacia `develop`.
- Cada hotfix nace desde `main`, se corrige, se fusiona hacia `main` y luego hacia `develop`.

### 5.1.3 Source Code Style Guide & Coding Conventions

TODO: Documentar convenciones para HTML, CSS, TypeScript y Java. Toda nomenclatura de código debe estar en inglés.

### 5.1.4 Software Deployment Configuration

TODO: Especificar configuración de despliegue de Landing Page, Frontend Web Application y Web Services.

## 5.2 Landing Page, Services & Applications Implementation

### 5.2.1 Sprint 1

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

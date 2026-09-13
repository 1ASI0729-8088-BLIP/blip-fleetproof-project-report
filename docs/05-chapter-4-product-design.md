# Capítulo IV: Product Design

En este capítulo se presenta el diseño de FleetProof, una plataforma web de investigación y monitoreo vehicular que aplica UX/UI Design para ofrecer una experiencia clara, consistente y accesible a empresas gestoras de flotas y usuarios particulares. El diseño se fundamenta estructuralmente en las User Stories, el Impact Mapping y un vocabulario de dominio estandarizado, asegurando un sistema coherente que prioriza la legibilidad de los reportes, la identificación de riesgos y el seguimiento de observaciones. Estos prototipos y representaciones visuales servirán como base fundamental para validar los flujos con los representantes de ambos segmentos antes de su implementación.


## 4.1 Style Guidelines

Los lineamientos de estilo de FleetProof buscan unificar la identidad visual y la comunicación del producto en todos sus puntos de contacto, tomando como base los principios de Material Design. Para ello, se estableció un Web Style Guide como repositorio común que contiene tipografías, paleta de colores, íconos e isotipos, asegurando consistencia visual entre la Web Application y el Landing Page. Además, estos lineamientos integran criterios de accesibilidad, como la comunicación del nivel de riesgo documentario mediante la combinación obligatoria de color, texto e íconos, garantizando una experiencia inclusiva.

### 4.1.1 General Style Guidelines

La identidad visual propuesta para FleetProof busca transmitir confianza, claridad y control, cualidades fundamentales para una plataforma que permite consultar antecedentes vehiculares, comparar reportes y monitorear cambios en el estado documentario de una flota. Su estilo se basa en los principios de simplicidad, jerarquía visual y consistencia, con una apariencia profesional y comprensible para administradores de flota, analistas, propietarios y compradores particulares.

#### Branding Overview

El nombre FleetProof combina dos conceptos centrales: “Fleet”, que significa flota y representa al segmento principal del proyecto, y “Proof”, que hace referencia a prueba o evidencia. Esta combinación expresa el propósito del producto: ayudar a tomar decisiones sobre vehículos a partir de información respaldada por fuentes, fechas y evidencias.

La marca busca asociarse con una gestión organizada y transparente, en la que el usuario pueda comprender qué cambió, identificar observaciones y dar seguimiento a su resolución.

#### Logo and Isotype
El logo propuesto utiliza el nombre FleetProof con letras sans serif de apariencia moderna y trazos limpios. Como referencia tipográfica para su implementación se propone Inter SemiBold, buscando facilitar la lectura y mantener coherencia con la interfaz web.

El nombre está acompañado por un isotipo que integra la silueta de un documento con una marca de verificación. El documento representa los reportes y el registro de evidencias; la verificación simboliza el proceso de revisión de información. Su significado se vincula con la trazabilidad del servicio, sin representar una certificación oficial ni garantizar la ausencia de riesgos.

La paleta propuesta combina azul marino (#16324F) y verde petróleo (#087F8C) sobre fondo blanco. El azul marino se utiliza para expresar seriedad y estabilidad; el verde petróleo aporta una identidad tecnológica y destaca el componente de verificación. La diferenciación entre ambos colores también permite reconocer visualmente las dos partes del nombre.

La composición aplica el principio de proximidad, agrupando símbolo y nombre como una unidad; el de contraste, diferenciando sus elementos del fondo; y el de simplicidad, evitando detalles decorativos que dificulten su reconocimiento. Se propone conservar un espacio libre alrededor del conjunto equivalente, como mínimo, a la altura de la letra “F”.

El isotipo podrá utilizarse de forma independiente como favicon o identificador de la plataforma. Su construcción sencilla está pensada para facilitar la adaptación a encabezados web, reportes y pantallas pequeñas, con una revisión de legibilidad en cada tamaño de uso.

<img width="2048" height="768" alt="Image" src="https://private-user-images.githubusercontent.com/129182231/651005254-1df8168e-04e1-4230-9edc-282509ba96fb.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3ODkzMzQxMzAsIm5iZiI6MTc4OTMzMzgzMCwicGF0aCI6Ii8xMjkxODIyMzEvNjUxMDA1MjU0LTFkZjgxNjhlLTA0ZTEtNDIzMC05ZWRjLTI4MjUwOWJhOTZmYi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwOTEzJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDkxM1QyMTEwMzBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1jZDYzZmIxMThjZmQ3NWRlZmVhYmRjZDA1MDZmM2I1YWExOTU2MTQxZjhmYjQ2YzNhMjc3NDMzYzNjYmU5Yjk4JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZyZXNwb25zZS1jb250ZW50LXR5cGU9aW1hZ2UlMkZwbmcifQ.VsO5pKRsRhHF-9ZXsHTaQRxYkQb2A-2t07XK6lzmEa4" />

#### Colores

La paleta cromática propuesta para FleetProof busca transmitir confianza, claridad y profesionalismo, valores relacionados con su propósito de organizar reportes vehiculares y facilitar el monitoreo documentario de flotas.

El azul marino (#16324F) constituye el color principal de la identidad y busca comunicar seriedad y estabilidad. Se utiliza en el logotipo y los encabezados para establecer una jerarquía visual clara. El verde petróleo (#087F8C) aporta un carácter tecnológico y permite destacar botones y elementos interactivos. Ambos se equilibran con el blanco (#FFFFFF), empleado como fondo principal para dar espacio al contenido y favorecer una presentación limpia.

Como colores secundarios, se incorporan el gris oscuro (#334155) para textos principales, el gris medio (#64748B) para información complementaria y el gris claro (#F1F5F9) para diferenciar tarjetas y superficies. Esta distribución aplica los principios de contraste y jerarquía, ayudando a distinguir información relevante sin sobrecargar la interfaz.

También se incluyen colores destinados a comunicar estados: verde (#2E7D32) para acciones completadas correctamente, ámbar (#F9A825) para advertencias y rojo (#D32F2F) para errores u observaciones críticas. Estos indicadores deben acompañarse de textos e iconos para que su significado no dependa únicamente del color.

El uso consistente de esta paleta en la plataforma, el sitio de presentación y los reportes busca reforzar el reconocimiento de FleetProof y facilitar una experiencia visual ordenada y comprensible.

<img...

#### Tipografía

La tipografía propuesta para FleetProof busca equilibrar modernidad, claridad y profesionalismo, en coherencia con una plataforma dedicada a la consulta de reportes vehiculares y al monitoreo documentario de flotas. Para ello, se selecciona Inter, una familia sans serif de trazos limpios que permite construir una identidad visual uniforme mediante distintos tamaños y grosores.

En títulos y encabezados se utiliza Inter SemiBold (600), con tamaños de 48, 36, 24 y 20 px, según su nivel de importancia. Esta diferenciación aplica el principio de jerarquía visual, orientando la atención desde los títulos principales hacia las secciones y tarjetas de información. Los tamaños mayores se adaptarán en pantallas pequeñas para evitar cortes y conservar una composición equilibrada.

Para textos de cuerpo y descripciones se propone Inter Regular (400) de 16 px, acompañado de un interlineado de aproximadamente 1,5 veces el tamaño de la letra. Los textos complementarios utilizan 14 px, mientras que las notas auxiliares pueden emplear 12 px, reservando este último tamaño para información no esencial. Estas decisiones buscan facilitar la lectura de reportes y evitar una presentación demasiado compacta.

Los botones y las etiquetas emplean Inter Medium (500) de 14 px, proporcionando énfasis suficiente para reconocer acciones como “Consultar reporte” sin competir visualmente con los encabezados.
El uso de una sola familia tipográfica refuerza los principios de consistencia y simplicidad. La variación controlada de tamaño, peso y espaciado permite organizar la información y mantener una experiencia visual coherente entre la plataforma, el sitio de presentación y los reportes de FleetProof.

<img...

### 4.1.2 Web Style Guidelines

TODO: Definir reglas responsive, estados, componentes, formularios, tablas, botones, alertas y accesibilidad.


## 4.2 Information Architecture

### 4.2.1 Organization Systems

TODO: Explicar jerarquia, secuencia y organización por audiencia.

### 4.2.2 Labeling Systems

TODO: Definir etiquetas breves para Landing Page y Web Application.

### 4.2.3 SEO Tags and Meta Tags

| Page | Title | Description | Keywords | Author |
|---|---|---|---|---|
| Landing Page | BLIP FleetProof | TODO | vehicle reports, fleet monitoring, Perú | BLIP |

### 4.2.4 Searching Systems

TODO: Definir busqueda por placa, estado, severidad, fecha, sede y responsable.

### 4.2.5 Navigation Systems

TODO: Definir navegación de Landing Page, sidebar de Web Application y rutas por segmento.

## 4.3 Landing Page UI Design

### 4.3.1 Landing Page Wireframe

TODO: Insertar wireframes Desktop y Mobile.

### 4.3.2 Landing Page Mock-up

TODO: Insertar mock-ups Desktop y Mobile.

## 4.4 Web Applications UX/UI Design

### 4.4.1 Web Applications Wireframes

TODO: Insertar wireframes de Web Application.

### 4.4.2 Web Applications Wireflow Diagrams

TODO: Insertar wireflows por User Goal.

### 4.4.3 Web Applications Mock-ups

TODO: Insertar mock-ups de Web Application.

### 4.4.4 Web Applications User Flow Diagrams

TODO: Insertar user flows con happy path y unhappy paths.

## 4.5 Web Applications Prototyping

TODO: Incluir enlace a prototipo interactivo y video de navegación.

## 4.6 Domain-Driven Software Architecture

### 4.6.1 Design-Level Event Storming

TODO: Identificar Bounded Contexts, Aggregates, Events, Commands and Queries.

### 4.6.2 Software Architecture Context Diagram

TODO: Insertar C4 Context Diagram.

### 4.6.3 Software Architecture Container Diagrams

TODO: Insertar C4 Container Diagram.

### 4.6.4 Software Architecture Components Diagrams

TODO: Insertar C4 Component Diagrams.

## 4.7 Software Object-Oriented Design

### 4.7.1 Class Diagrams

TODO: Insertar class diagrams por bounded context.

## 4.8 Database Design

### 4.8.1 Database Diagrams

TODO: Insertar database diagrams con tablas, columnas, constraints y relaciones.


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

<img width="1536" height="1024" alt="Image" src="https://github.com/user-attachments/assets/3e1b4518-2df0-461a-b5ac-11a54bac7472" />

#### Tipografía

La tipografía propuesta para FleetProof busca equilibrar modernidad, claridad y profesionalismo, en coherencia con una plataforma dedicada a la consulta de reportes vehiculares y al monitoreo documentario de flotas. Para ello, se selecciona Inter, una familia sans serif de trazos limpios que permite construir una identidad visual uniforme mediante distintos tamaños y grosores.

En títulos y encabezados se utiliza Inter SemiBold (600), con tamaños de 48, 36, 24 y 20 px, según su nivel de importancia. Esta diferenciación aplica el principio de jerarquía visual, orientando la atención desde los títulos principales hacia las secciones y tarjetas de información. Los tamaños mayores se adaptarán en pantallas pequeñas para evitar cortes y conservar una composición equilibrada.

Para textos de cuerpo y descripciones se propone Inter Regular (400) de 16 px, acompañado de un interlineado de aproximadamente 1,5 veces el tamaño de la letra. Los textos complementarios utilizan 14 px, mientras que las notas auxiliares pueden emplear 12 px, reservando este último tamaño para información no esencial. Estas decisiones buscan facilitar la lectura de reportes y evitar una presentación demasiado compacta.

Los botones y las etiquetas emplean Inter Medium (500) de 14 px, proporcionando énfasis suficiente para reconocer acciones como “Consultar reporte” sin competir visualmente con los encabezados.
El uso de una sola familia tipográfica refuerza los principios de consistencia y simplicidad. La variación controlada de tamaño, peso y espaciado permite organizar la información y mantener una experiencia visual coherente entre la plataforma, el sitio de presentación y los reportes de FleetProof.

<img width="1161" height="1355" alt="Image" src="https://github.com/user-attachments/assets/b2a7e56c-3543-4e6c-9eb7-c7f36cc95999" />

### 4.1.2 Web Style Guidelines

En esta sección se definen los estándares visuales y de interacción para las interfaces web de FleetProof, tomando como referencia el diseño de su landing page. Estos lineamientos buscan mantener una experiencia coherente, comprensible y adaptable a distintos dispositivos, facilitando la consulta de servicios, la comparación de planes y el contacto con la empresa.

La propuesta conserva el azul marino (#16324F), el verde petróleo (#087F8C), los fondos blancos y los tonos grises del diseño. Asimismo, utiliza la familia tipográfica Plus Jakarta Sans y componentes con bordes redondeados. Las reglas responsive y los estados de interacción descritos complementan el mockup de escritorio y deberán aplicarse durante el desarrollo.

#### Responsive Design: 
Se propone organizar la interfaz en tres rangos: móviles, con anchos inferiores a 768 px; tabletas, entre 768 y 1023 px; y escritorio, desde 1024 px. El contenido utilizará un contenedor centrado con un ancho máximo de 1280 px y márgenes interiores de 16 px en móviles y 24 px en pantallas mayores. Las secciones con texto e imagen se apilarán verticalmente en móviles. Las cuatro tarjetas de precios se distribuirán en una, dos o cuatro columnas según el espacio disponible. Se utilizarán distribuciones flexibles y alturas ajustables al contenido para evitar recortes y desplazamiento horizontal de la página.

#### Typography and Spacing: 
Se empleará Plus Jakarta Sans para títulos, párrafos y elementos interactivos. El encabezado principal conservará los 48 px y el peso 800 del diseño de escritorio, reduciéndose aproximadamente a 32 px en móviles. Los párrafos utilizarán tamaños de 16 a 18 px y un interlineado cercano a 1,5. Los tamaños de 12 px se reservarán para notas auxiliares. Se propone una escala de espaciado basada en 4, 8, 12, 16, 24 y 32 px, que permitirá agrupar elementos relacionados y separar visualmente las secciones.

#### Navigation: 
La barra superior mantendrá el logotipo, los enlaces Inicio, Servicios, Nosotros, Precios y Contacto, y la acción para agendar una demostración. La sección activa se identificará mediante texto destacado y una línea inferior verde petróleo, siguiendo el diseño proporcionado. Cuando el contenido no quepa horizontalmente, los enlaces se agruparán en un menú desplegable accesible mediante teclado. El pie de página conservará los enlaces de navegación y la información de contacto sobre fondo azul marino.
<img width="1274" height="91" alt="Image" src="https://github.com/user-attachments/assets/8a8bc205-edb4-48ee-aa5d-eb0c32d925cc" />

#### Buttons: 
Las acciones principales, como solicitar una demostración o enviar el formulario, utilizarán fondo verde petróleo (#087F8C), texto blanco y bordes redondeados de 12 px. Las acciones secundarias tendrán fondo blanco, texto azul marino y un borde definido. Se propone una altura mínima de 44 px y un espaciado interior suficiente para facilitar su selección. Las etiquetas expresarán acciones concretas, como “Consultar reporte” o “Solicitar cotización”. Los enlaces se utilizarán para navegar y los botones para ejecutar acciones.

#### Interaction States: 
Los controles tendrán estados normal, hover, foco, presionado y deshabilitado. Al pasar el cursor, se aplicará un cambio moderado de fondo o borde; al navegar con teclado, aparecerá un contorno de foco claramente visible. Los controles deshabilitados mostrarán una apariencia diferenciada y una explicación cuando la causa no sea evidente. Durante el envío de información, el botón mostrará un indicador y el texto “Enviando…”, evitando solicitudes duplicadas. Estos cambios conservarán las dimensiones del componente para impedir movimientos inesperados.

#### Cards: 
Las tarjetas agruparán servicios, beneficios y planes mediante un título, una descripción breve y, cuando corresponda, una acción. Se mantendrán fondos blancos o gris claro (#F1F5F9), bordes suaves y esquinas redondeadas de 12 a 16 px, presentes en el diseño. Las tarjetas de precios conservarán un orden común para nombre, importe, periodicidad, características y botón. Cualquier plan destacado incluirá una etiqueta explicativa además del cambio de color. Esta estructura facilita la comparación y aplica los principios de proximidad y consistencia.
<img width="1277" height="831" alt="Image" src="https://github.com/user-attachments/assets/b337f44f-1b91-4e91-ad98-a3ecd119981b" />

#### Forms: 
El formulario de contacto incluirá nombre, empresa, segmento de usuario, cantidad de unidades, correo electrónico y mensaje, tomando como referencia la landing page. Cada campo contará con una etiqueta visible, indicación de obligatoriedad y ejemplos cuando sean necesarios. Se propone adaptar los requisitos al segmento: para particulares, el campo empresa será opcional y se aceptará un correo personal. Los errores aparecerán junto al campo correspondiente con instrucciones específicas, como “Ingresa un correo electrónico válido”. Si el envío falla, se conservarán los datos ingresados y se ofrecerá la posibilidad de reintentar.

#### Tables: 
Para las vistas de vehículos y reportes de la aplicación se propone extender el mismo estilo visual mediante tablas con encabezados claros, separadores discretos y filas suficientemente espaciadas. Estas podrán mostrar placa, fecha de revisión, estado documentario y acciones disponibles. Los listados extensos incorporarán búsqueda, filtros y paginación. En móviles se priorizarán los datos esenciales o se permitirá desplazamiento horizontal dentro de la tabla. También se definirán mensajes para carga, ausencia de registros y errores, evitando que un espacio vacío genere incertidumbre.

#### Alerts and Status Indicators: 
Las confirmaciones utilizarán verde (#2E7D32), las advertencias ámbar (#F9A825) y los errores rojo (#D32F2F). Los mensajes informativos podrán utilizar azul marino sobre un fondo claro. Cada aviso incluirá un icono, una descripción y, cuando corresponda, una acción, como “Reintentar” o “Revisar observación”. El ámbar se combinará con texto oscuro para favorecer su lectura. Los estados documentarios deberán indicar su significado y la fecha de revisión; la falta de información se mostrará como “Sin verificar”, evitando confundirla con un resultado favorable.

#### Accessibility: 
La interfaz deberá permitir la navegación completa mediante teclado, mantener un orden de foco lógico y proporcionar etiquetas accesibles para campos y botones con iconos. Las imágenes informativas tendrán textos alternativos y los elementos decorativos no interferirán con los lectores de pantalla. Se verificará un contraste mínimo de 4,5:1 para texto normal y de 3:1 para texto grande, conforme al criterio de contraste de WCAG. Los errores y estados se comunicarán con texto e iconos, además del color. También se comprobará que el contenido pueda ampliarse sin perder información y se respetará la preferencia de movimiento reducido del usuario.

## 4.2 Information Architecture

La arquitectura de información de FleetProof busca facilitar el acceso a los servicios de consulta vehicular, reportes trazables y monitoreo documentario. Su estructura organiza los contenidos de acuerdo con las necesidades de empresas con flotas y de propietarios o compradores particulares, permitiendo avanzar desde una visión general hasta los detalles de cada vehículo, sus observaciones y evidencias.

En la landing page, la información se distribuye en las secciones Inicio, Servicios, Nosotros, Precios y Contacto. Esta estructura permite conocer la propuesta de valor, explorar los servicios, identificar una alternativa adecuada y solicitar atención. En la aplicación web, se propone organizar las funcionalidades alrededor de vehículos, reportes, alertas y seguimiento de observaciones.

Estas decisiones buscan reducir la sobrecarga de información, facilitar la navegación y mantener una relación clara entre cada vehículo, sus antecedentes y las acciones pendientes.

### 4.2.1 Organization Systems

FleetProof combinará diferentes sistemas de organización para que los usuarios puedan localizar información, comparar alternativas y completar sus tareas de manera ordenada.

#### Jerárquica:
La información se estructurará desde categorías generales hacia contenidos específicos. En la aplicación, el usuario podrá ingresar a Flota, seleccionar un vehículo, consultar sus reportes y revisar los hallazgos con sus respectivas fuentes y evidencias. El dashboard presentará un resumen de vehículos monitoreados y observaciones pendientes, desde el cual se accederá al detalle. Esta organización permitirá comprender dónde se encuentra cada contenido y profundizar sin mostrar toda la información simultáneamente.

#### Secuencial (Step-by-step):
Se aplicará en procesos que requieren un orden definido. Para solicitar un reporte, el usuario seleccionará o registrará un vehículo, confirmará los datos, enviará la solicitud y consultará el resultado cuando esté disponible. Para atender una observación, el flujo comprenderá revisar el hallazgo, asignar un responsable, registrar las acciones realizadas y adjuntar evidencia de resolución. Cada proceso mostrará su estado y permitirá corregir información antes de confirmar, reduciendo errores y solicitudes incompletas.

#### Por audiencia:
La información se adaptará a los dos segmentos principales del proyecto. Las empresas accederán a una visión consolidada de sus flotas, con opciones para organizar vehículos, revisar riesgos y coordinar la atención de observaciones. Los propietarios y compradores particulares tendrán una experiencia centrada en consultar uno o pocos vehículos, comprender sus antecedentes y recibir alertas. En la landing page, las descripciones de servicios y planes ayudarán a cada segmento a identificar la alternativa que corresponde a sus necesidades.

#### Por roles y responsabilidades:
Dentro de la plataforma, las opciones se organizarán según las tareas y permisos de cada usuario. El administrador de flota podrá gestionar vehículos y coordinar responsables; el analista documentario organizará consultas, resultados y evidencias; y el supervisor revisará los reportes antes de su publicación. Esta diferenciación complementará la organización por audiencia, mostrando a cada usuario las herramientas necesarias para su trabajo.

#### Por tópicos:
La landing page agrupará el contenido en Inicio, Servicios, Nosotros, Precios y Contacto, conservando su navegación actual. En la aplicación se proponen módulos como Flota o Mis vehículos, Reportes, Alertas, Casos de resolución y Suscripción. Cada módulo reunirá información relacionada con una necesidad concreta, facilitando el acceso directo sin recorrer secciones ajenas a la tarea.

#### Cronológica:
Los reportes, las alertas y las actividades de seguimiento se organizarán por fecha, mostrando primero los registros más recientes. Cada reporte conservará su fecha de elaboración y las fechas de consulta de sus fuentes. Esta organización facilitará reconocer cambios, comparar versiones y reconstruir el seguimiento de una observación.

Como apoyo visual, la sección Precios utilizará una cuadrícula de tarjetas con una estructura común para comparar servicios, beneficios y condiciones. Los vehículos y reportes podrán presentarse en tablas con filtros. Estas formas de presentación complementarán los sistemas de organización y facilitarán la exploración de conjuntos de información.


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


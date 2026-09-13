# Capítulo I: Introducción

## 1.1 Startup Profile

### 1.1.1 Descripción de la Startup

|                                                Miembro                                                 |                                                                                                                                                   Descripción                                                                                                                                                    |
|:------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| <img src="https://res.cloudinary.com/dehoql1oc/image/upload/v1789264840/foto_stbi6t.jpg" width="500"/> |**Gonzalo Samuel Quintanilla Pozo \- U202315007** <br>  Soy estudiante de la carrera de Ingeniería de Software en la UPC y tengo 21 años, como compañero me gusta apoyar y tomar iniciativa en trabajos grupales. Me especializo en los lenguajes CSS, Java y Python. Tengo experiencia desarrollando páginas web.|
|                                       <img src="" width="500"/>                                        |                                                                                                                                                                                                                                                                                                                  |
|                                       <img src="" width="500"/>                                        |                                                                                                                                                                                                                                                                                                                  | 
|                                       <img src="" width="500"/>                                        |                                                                                                                                                                                                                                                                                                                  | 
|                                       <img src="" width="500"/>                                        |                                                                                                                                                                                                                                                                                                                  | 


## 1.2 Solution Profile

FleetProof es una plataforma web orientada a la investigación y monitoreo de información vehicular, diseñada principalmente para 
empresas que administran flotas pequeñas y medianas y, de manera complementaria, para propietarios y compradores particulares.

### 1.2.1 Antecedentes y problemática

**What? (¿Qué?)**

**¿Cuál es el problema?**
La investigación vehicular peruana exige revisar múltiples fuentes con finalidades y formatos distintos. La información necesaria está dispersa, generando dependencia de hojas de cálculo, falta de trazabilidad en las consultas, ausencia de comparaciones estructuradas y detección tardía de papeletas o vencimientos documentarios.

**When? (¿Cuándo?)**

**¿Cuándo ocurre el problema?**
Ocurre de manera continua durante la gestión y operación de los vehículos. Surge específicamente cuando es necesario verificar la vigencia de documentación para cumplir controles, evitar vencimientos o evaluar el estado de una unidad antes de tomar una decisión de compraventa.

**Where? (¿Dónde?)**

**¿Dónde surge el problema?**
El problema se plantea en Perú, dentro del contexto de empresas que realizan transporte terrestre (taxi, buses, logística) y que están sujetas a supervisión y fiscalización oficial. También afecta al mercado automotor de particulares que lidian con trámites en distintas entidades.

**Who? (¿Quién?)**

**¿Quiénes están involucrados?**
Los principales involucrados son las empresas de transporte con flotas pequeñas o medianas, y los propietarios o compradores particulares de vehículos usados.

**¿Quién lo utilizará?**
Las empresas lo utilizarán mediante roles como propietarios, gerentes, jefes de operaciones, administradores de flota y analistas documentarios para monitorear el riesgo de múltiples unidades. Los usuarios particulares lo emplearán para investigar el historial de un vehículo antes de comprarlo y recibir alertas continuas.

**Why? (¿Por qué?)**

**¿Cuál es la causa del problema?**
La causa principal es que la información y documentación de habilitación (como ITV, SOAT/CAT, papeletas, etc.) se encuentra descentralizada en canales de diferentes entidades públicas (como SUTRAN o SAT) y privadas. Las consultas actuales son aisladas y no cuentan con mecanismos de seguimiento unificados.

**How? (¿Cómo?)**

**¿Cómo se resuelve actualmente?**
Actualmente, los administradores y usuarios dependen de consultas manuales página por página, utilizando portales individuales, archivos de Excel y aplicaciones de mensajería para coordinar las revisiones, guardar resultados y comparar información.

**How much? (¿Cuánto?)**

**¿Cuánto impacto o costo implica?**
El problema genera un impacto directo manifestado en horas de trabajo administrativo perdido por vehículo. Esto desencadena graves riesgos operativos, como unidades operando con documentos vencidos, sanciones económicas (multas), interrupción del viaje, retención del vehículo y malas decisiones de compra por información incompleta.

### 1.2.2 Lean UX Process

El enfoque Lean UX se aplica para comprender las experiencias y problemáticas de los administradores de flotas y propietarios particulares, validando hipótesis mediante experimentación rápida y retroalimentación constante.

#### 1.2.2.1 Lean UX Problem Statement

El estado actual de la verificación documentaria vehicular en el Perú se ha centrado principalmente en consultas aisladas realizadas sobre múltiples portales y reportes individuales orientados principalmente a la compraventa.

Lo que los productos o servicios existentes no logran abordar es el monitoreo continuo, la comparación histórica, la gestión colaborativa de observaciones y la consolidación del riesgo de una flota.

Nuestro producto abordará esta brecha mediante una plataforma web que registra vehículos, organiza consultas por fuente, genera reportes trazables y alerta sobre cambios que puedan afectar la operación.

Nuestro enfoque inicial serán las empresas con flotas pequeñas y medianas, y de manera complementaria, los propietarios y compradores particulares.

Sabremos que tenemos éxito cuando veamos un menor tiempo de preparación de reportes, una detección temprana de observaciones y el uso recurrente del sistema en nuestro público objetivo.

#### 1.2.2.2 Lean UX Assumptions

**Business Assumptions**
* Las empresas pagarán por reducir el trabajo manual y el riesgo operativo en la administración de sus vehículos.
* El monitoreo recurrente retendrá mejor a los clientes que la venta de un reporte unitario.
* Un modelo de planes de suscripción basado en el volumen de vehículos y reportes permitirá escalar el negocio de manera sostenible.

**Business Outcome Assumptions**
* Aumentará el porcentaje de clientes que genera un segundo reporte o que mantiene activa su suscripción.
* Disminuirá el tiempo promedio de preparación y revisión documentaria por cada vehículo.
* Aumentará el porcentaje de observaciones vehiculares que cuentan con un responsable asignado y evidencia registrada.

**User Assumptions**
* Los administradores de flota y analistas documentarios combinan actualmente múltiples portales, hojas de cálculo y aplicaciones de mensajería para realizar su trabajo.
* Los supervisores necesitan un resumen claro del nivel de riesgo y la trazabilidad del estado de toda su flota.
* Los compradores y propietarios particulares tienen grandes dificultades para interpretar los resultados registrales por su cuenta.

**User Outcome and Benefit Assumptions**
* Los usuarios podrán identificar unidades vehiculares críticas rápidamente para priorizar su atención.
* Los administradores evitarán repetir consultas innecesarias y no perderán las evidencias de regularizaciones pasadas.
* Los usuarios particulares lograrán comprender fácilmente los cambios en su vehículo y regularizar observaciones pendientes.

**Feature Assumptions**
* La carga masiva mediante archivos CSV reducirá significativamente el esfuerzo de adopción inicial empresarial.
* Una checklist estructurada por fuente reducirá las omisiones de información.
* La comparación histórica de estados (*snapshots*) hará visible la información nueva de forma inmediata.
* Un semáforo con explicación visual facilitará la priorización de vehículos en riesgo.
* Un sistema de gestión de casos con responsable y evidencia mejorará el seguimiento de las observaciones.


#### 1.2.2.3 Lean UX Hypothesis Statements

*   **Hypothesis 01:**

    Creemos que las empresas reducirán el esfuerzo de adopción inicial si cuentan con la función de carga masiva de vehículos mediante archivos CSV.

    Sabremos que hemos tenido éxito.

    Cuando el porcentaje mayoritario de empresas utilice activamente la función de importación masiva en lugar del registro manual individual.

*   **Hypothesis 02:**

    Creemos que los analistas documentarios reducirán las omisiones al investigar un vehículo si cuentan con un checklist operativo estructurado por cada fuente de consulta.

    Sabremos que hemos tenido éxito.

    Cuando aumente el porcentaje de checklists completados correctamente y disminuya el tiempo promedio de revisión documentaria por vehículo.

*   **Hypothesis 03:**

    Creemos que los clientes y usuarios particulares comprenderán fácilmente qué información es nueva si se les ofrece una comparación estructurada entre dos estados históricos o *snapshots*.

    Sabremos que hemos tenido éxito.

    Cuando aumente el porcentaje de clientes que genera un segundo reporte o mantiene activa su suscripción para monitoreo continuo.

*   **Hypothesis 04:**

    Creemos que los supervisores de flota identificarán unidades críticas rápidamente para priorizar acciones si se integra un semáforo de riesgo con evaluación determinística y explicación visual.

    Sabremos que hemos tenido éxito.

    Cuando disminuya el tiempo promedio que le toma a un administrador identificar un vehículo en estado crítico dentro de la plataforma.

*   **Hypothesis 05:**

    Creemos que los administradores de flota evitarán la pérdida de evidencias de regularización si utilizan un sistema de gestión de casos que incluya responsables asignados y registro de evidencias.

    Sabremos que hemos tenido éxito.

    Cuando aumente el porcentaje de observaciones vehiculares que se cierran exitosamente con un responsable asignado y evidencia adjunta en la plataforma.

#### 1.2.2.4 Lean UX Canvas

TODO: Insertar captura del Lean UX Canvas y explicar aprendizajes.

## 1.3 Segmentos objetivo

### Empresas con flotas

Empresas de taxi, buses, turismo, reparto, logística, alquiler y servicios con aproximadamente 5 a 100 unidades.

### Propietarios y compradores particulares

Personas que compran, venden o administran uno o pocos vehículos, incluidos conductores independientes y taxistas propietarios.

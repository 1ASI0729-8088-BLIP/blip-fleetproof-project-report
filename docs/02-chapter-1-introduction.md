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

#### 1.2.2.1 Lean UX Problem Statement

El estado actual de la verificación documentaria vehicular en Perú se concentra en consultas aisladas realizadas sobre múltiples portales y reportes individuales orientados principalmente a compraventa. Los productos existentes no cubren suficientemente el monitoreo continuo, la comparación histórica, la gestión colaborativa de observaciones y la consolidación del riesgo de una flota. FleetProof cubrirá esta brecha mediante una plataforma que registra vehículos, organiza consultas por fuente, genera reportes trazables y alerta cambios que puedan afectar la operación. El foco inicial serán empresas con flotas pequeñas y medianas; el segundo segmento serán propietarios y compradores particulares. El éxito se evidenciará mediante menor tiempo de preparación, detección temprana y uso recurrente.

#### 1.2.2.2 Lean UX Assumptions

##### Business Assumptions

- Las empresas pagarán por reducir trabajo manual y riesgo operativo.
- El monitoreo recurrente generará mayor retención que el reporte unitario.
- Los planes por volumen de vehículos y reportes permitirán escalar el modelo de negocio.

##### Business Outcome Assumptions

- Aumentará el porcentaje de clientes que genera un segundo reporte.
- Disminuirá el tiempo promedio de preparación y revisión.
- Aumentará el porcentaje de observaciones con responsable y evidencia.

##### User Assumptions

- Los administradores de flota combinan portales, hojas de cálculo y mensajería.
- Los supervisores necesitan resumen de riesgo y trazabilidad.
- Los particulares tienen dificultad para interpretar resultados registrales.

##### User Outcome and Benefit Assumptions

- Los usuarios identificarán unidades críticas rápidamente.
- Los usuarios evitaran repetir consultas y perder evidencias.
- Los usuarios comprenderán cambios y regularizaran observaciones.

##### Feature Assumptions

- La carga CSV reducirá esfuerzo de adopción empresarial.
- El checklist por fuente reducirá omisiones.
- La comparación de snapshots hará visible información nueva.
- El semáforo con explicación facilitará la priorización.
- Los casos con responsable y evidencia mejorarán seguimiento.
- Los planes con límites reales sostendrán monetización.

#### 1.2.2.3 Lean UX Hypothesis Statements

TODO: Redactar un hypothesis statement por cada Feature Assumption usando:

```text
We believe we will achieve [this business outcome]
If [these personas]
Attain [this benefit/user outcome]
With [this feature or solution]
```

#### 1.2.2.4 Lean UX Canvas

TODO: Insertar captura del Lean UX Canvas y explicar aprendizajes.

## 1.3 Segmentos objetivo

### Empresas con flotas

Empresas de taxi, buses, turismo, reparto, logística, alquiler y servicios con aproximadamente 5 a 100 unidades.

### Propietarios y compradores particulares

Personas que compran, venden o administran uno o pocos vehículos, incluidos conductores independientes y taxistas propietarios.

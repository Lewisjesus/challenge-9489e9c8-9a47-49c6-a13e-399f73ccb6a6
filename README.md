# Migración de Aplicación Monolítica a Cloud

Una empresa de fintech necesita migrar su aplicación monolítica, actualmente en funcionamiento on-premise, a una infraestructura cloud utilizando servicios de AWS. La aplicación debe mantener su funcionalidad y rendimiento, asegurando una transición suave y eficiente.

## Informacion General

| Campo | Valor |
|-------|-------|
| **Tema** | Migraciones de infraestructura |
| **Nivel** | senior-l1 |
| **Tipo** | mixed |
| **Tiempo estimado** | 10-12 horas |

## Fases del Reto

### Fase 0: Configuración del Proyecto

**Objetivo:** Obtener el proyecto base funcional enviando el Código Base a un asistente de IA, que lo analizará, corregirá errores y generará un ZIP listo para usar.

**Tiempo estimado:** 15-30 minutos

**Instrucciones:**

- Asegúrate de tener instalado para ejecutar el proyecto: Un IDE o editor de código.
- Copia todo el contenido del campo **Código Base** de este reto — incluyendo el texto de instrucciones que aparece al inicio.
- Abre un asistente de IA (Claude en claude.ai, ChatGPT o Gemini — se recomienda Claude), pega el contenido copiado en el chat y envíalo.
- El asistente analizará los archivos, corregirá errores y generará un archivo ZIP descargable. Descárgalo y extráelo en la carpeta donde quieras trabajar.
- Verifica que el proyecto arranca sin errores.

**Entregable:** El proyecto compila/arranca sin errores.

<details>
<summary>Pistas de conocimiento</summary>

- Copia el Código Base completo incluyendo el texto de instrucciones al inicio — esas instrucciones le indican al asistente exactamente qué hacer con los archivos.
- Si el asistente no genera el ZIP automáticamente al terminar el análisis, escríbele: "genera el ZIP ahora".
- Si el proyecto tiene errores al arrancar, comparte el mensaje de error con el mismo asistente para que lo corrija.

</details>

### Fase 1: Evaluación del Sistema Existente

**Objetivo:** Comprender la arquitectura y funcionalidades actuales de la aplicación monolítica.

**Tiempo estimado:** 2 horas

**Instrucciones:**

- Analiza la arquitectura actual de la aplicación.
- Identifica las funcionalidades críticas y sus dependencias.
- Evalúa las limitaciones técnicas y operacionales del sistema existente.

**Entregable:** Documento de evaluación con descripción detallada del sistema actual, sus componentes y dependencias.

<details>
<summary>Pistas de conocimiento</summary>

- Considera las interacciones entre componentes y cómo afectan la funcionalidad general.
- Piensa en cómo las decisiones de arquitectura actuales influyen en la migración.

</details>

### Fase 2: Diseño de la Arquitectura en Cloud

**Objetivo:** Proponer una arquitectura cloud que replique la funcionalidad del sistema monolítica, aprovechando los servicios de AWS.

**Tiempo estimado:** 4 horas

**Instrucciones:**

- Diseña una arquitectura cloud utilizando servicios de AWS que mantenga la funcionalidad y rendimiento del sistema original.
- Considera la escalabilidad, disponibilidad y seguridad en tu diseño.
- Identifica y justifica las decisiones de arquitectura clave.

**Entregable:** Documento de diseño de la arquitectura cloud, incluyendo diagramas y decisiones justificadas.

<details>
<summary>Pistas de conocimiento</summary>

- Piensa en cómo los servicios de AWS pueden mejorar la escalabilidad y disponibilidad del sistema.
- Considera los trade-offs entre costos y rendimiento.

</details>

### Fase 3: Planificación de la Migración

**Objetivo:** Crear un plan detallado para migrar la aplicación al cloud, minimizando el tiempo de inactividad y el riesgo.

**Tiempo estimado:** 3 horas

**Instrucciones:**

- Desarrolla un plan de migración que incluya timelines, recursos necesarios y posibles riesgos.
- Propone estrategias para minimizar el tiempo de inactividad durante la migración.
- Identifica y mitiga los riesgos asociados con la migración.

**Entregable:** Plan de migración detallado, incluyendo timelines, recursos y estrategias de mitigación de riesgos.

<details>
<summary>Pistas de conocimiento</summary>

- Considera fases de migración incremental para reducir el riesgo.
- Piensa en cómo comunicar el plan a las partes interesadas.

</details>

### Fase 4: Evaluación de la Migración

**Objetivo:** Evaluar el éxito de la migración y documentar las lecciones aprendidas.

**Tiempo estimado:** 1 hora

**Instrucciones:**

- Evalúa el rendimiento y funcionalidad de la aplicación en el cloud.
- Documenta las lecciones aprendidas y mejoras futuras.
- Propone recomendaciones para optimizar la arquitectura cloud.

**Entregable:** Documento de evaluación de la migración, incluyendo lecciones aprendidas y recomendaciones.

<details>
<summary>Pistas de conocimiento</summary>

- Compara el rendimiento antes y después de la migración.
- Piensa en cómo puedes mejorar aún más la arquitectura cloud.

</details>

## Dimensiones Evaluadas

- **queEs**: ¿Qué servicios de AWS utilizaste en tu diseño y por qué?
- **paraQueSirve**: ¿Cómo aseguraste que el sistema mantenga su funcionalidad y rendimiento durante la migración?
- **comoSeUsa**: ¿Cómo diseñaste la arquitectura cloud para aprovechar los servicios de AWS?
- **erroresComunes**: ¿Qué riesgos identificaste durante la migración y cómo los mitigaste?
- **queDecisionesImplica**: ¿Qué decisiones de arquitectura tomaste durante la migración y por qué?

## Criterios de Evaluacion

- Evalúa el sistema actual y documenta sus componentes y dependencias.
- Diseña una arquitectura cloud utilizando servicios de AWS.
- Crea un plan de migración detallado.
- Evalúa el éxito de la migración y documenta las lecciones aprendidas.

---

*Reto generado automaticamente por Challenge Generator - Pragma*

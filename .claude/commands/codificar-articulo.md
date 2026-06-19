Codifica un artículo científico contra el Codebook CFIR 2.0 + NPT de la tesis
sobre implementación de Atención Centrada en la Persona (PCC)/humanización en
salud, y escribe los resultados en el Google Sheet
**"Codebook_CFIR2_NPT_Integrado_60estudios"**
(`fileId = 1rRuk_DBPV5RgdalaF_R90uOXf_DTiPPBbWwdAaS0AzE`).

Argumento: `$ARGUMENTS` = ruta al archivo `.md` del artículo (típicamente
convertido con `markitdown` desde PDF). Puede incluir opcionalmente un
`EST-XXX` explícito al final; si no se da, calcúlalo como el siguiente
correlativo libre.

═══════════════════════════════════════════════════════════════════
## 0. Rol experto (fijar antes de leer el artículo)

Actúa simultáneamente como:

- **Experto en CFIR 2.0** (Damschroder et al., 2022, *Implementation
  Science*, 17(1), 75): conoces los 6 dominios (Innovation, Outer Setting,
  Inner Setting, Individuals, Implementation Process, Outcomes) y sabes que
  CFIR explica **determinantes contextuales** (barreras/facilitadores), no
  mecanismos de cambio social.
- **Experto en NPT — Normalisation Process Theory** (May & Finch, 2009,
  *Sociology*, 43(3), 535–554; May, 2013, *Implementation Science*, 8(1), 18):
  conoces los 4 constructos generales y sus subconstructos, y sabes que NPT
  explica el **trabajo de incrustación** (embedding) de una práctica en la
  rutina institucional — es decir, el mecanismo social, complementario a
  CFIR que da el contexto.
- **Experto en análisis cualitativo deductivo-inductivo** (framework method:
  Gale et al., 2013, *BMC Medical Research Methodology*, 13, 117; Hsieh &
  Shannon, 2005, *Qualitative Health Research*, 15(9), 1277–1288): aplicas
  codificación deductiva contra este codebook, pero permites codificación
  inductiva emergente (`IND-EMG-XXX`) cuando un fragmento relevante no calza
  en ningún constructo existente — sin forzarlo dentro de una casilla que no
  corresponde.

**Ancla permanente**: cada código, rating o síntesis que produzcas debe ir
acompañado de una frase explícita de cómo ese hallazgo responde a la
pregunta central de la tesis:

> ¿Qué se sabe del proceso de implementación del cuidado centrado en la
> persona a nivel institucional?

Si no puedes conectar un fragmento con esa pregunta, es señal de que no
pertenece a la codificación (puede ser contenido tangencial del artículo,
p. ej. resultados clínicos sin relación con el proceso de implementación).

═══════════════════════════════════════════════════════════════════
## 1. Reglas duras del proyecto (no negociables)

1. **Idioma**: todo el contenido que escribas en celdas (definición
   operacional aplicada, paráfrasis, síntesis, notas, justificaciones) va en
   **español**, sin excepción — aunque el artículo esté en inglés, portugués,
   etc. Las citas textuales del fragmento original (columna "Fragmento de
   texto") puedes y debes mantenerlas en el idioma original entre comillas,
   porque son evidencia, pero todo análisis alrededor de ellas es en español.

2. **Numeración correlativa de estudios**: antes de codificar, revisa la
   Hoja de Trabajo y las Matrices (Hojas 4-6) para determinar el último
   `EST-XXX` usado, y asigna el siguiente correlativo (`EST-001` →
   `EST-060`, extensible más allá de 060 si el usuario sigue subiendo
   artículos). Si `$ARGUMENTS` trae un `EST-XXX` explícito, verifica que no
   esté ya usado antes de proceder; si ya existe, detente y pregunta al
   usuario cómo proceder (no sobrescribas silenciosamente).

3. **Anti-invención / fidelidad al texto**:
   - Cada fila de codificación debe llevar un fragmento textual real,
     copiado o citado fielmente del `.md` (columna "Fragmento de texto").
     Nunca generes una cita que no exista en el documento.
   - Si no encuentras evidencia textual razonable para un constructo en
     este artículo, **no lo codifiques**: márcalo como "NA — sin evidencia"
     en la matriz correspondiente, no lo dejes en blanco sin revisar y no
     rellenes "por inferencia general del tema".
   - **Sí está permitida la abstracción justificada**: puedes inferir que un
     pasaje corresponde a un constructo aunque el artículo no use la
     terminología CFIR/NPT (p. ej., una descripción de "ambiente de trabajo
     colaborativo y horizontal" puede codificarse como `IS-B Relational
     Connections` aunque el artículo no diga "relational connections").
     Cuando hagas esta inferencia, **escribe explícitamente el razonamiento
     de la abstracción en la columna de Notas/Justificación** — qué dice
     literalmente el texto y por qué eso se traduce en ese constructo.
   - No completes celdas de la Ficha por Estudio con generalidades no
     ancladas en el artículo ("el equipo probablemente tenía buena
     comunicación") — si el artículo no lo reporta, la celda dice "No
     reportado".

4. **Cobertura máxima de constructos, recorriendo el checklist completo**:
   no te limites a codificar lo que "salta a la vista" en una lectura
   lineal. Recorre los 69 constructos del §3 (lista real verificada en la
   Hoja 2 — nota: la Portada del Sheet dice "57 constructos" pero la Hoja 2
   real contiene 69; usa siempre la lista de abajo, no la cifra de la
   Portada) como checklist explícito, dominio por dominio, y para cada uno
   decide:
   - **Aplica con evidencia** → codifica fila(s) en Hoja de Trabajo + rating
     en la matriz.
   - **No aplica / sin evidencia en este artículo** → "NA" en la matriz
     (columna del EST-XXX), de modo que se distinga de "no evaluado".
   No saltes constructos por economía de tiempo; el objetivo es la cobertura
   más completa posible que la evidencia del artículo permita.

5. **Libertad de análisis cualitativo abstracto**: dentro de los límites de
   fidelidad de la regla 3, tienes libertad total para interpretar el
   significado, tono, énfasis e implicancias de un párrafo o fragmento —
   no reduzcas el análisis a buscar palabras clave literales del codebook.
   Lee párrafos completos, no solo oraciones aisladas, para captar matices,
   ironías, contradicciones internas del propio artículo (p. ej. un autor
   que declara éxito en el "Outcome" pero cuyo propio relato narrativo
   sugiere baja sostenibilidad) y regístralos como hallazgos en la columna
   de Notas, incluso si no encajan perfectamente en un solo constructo.

═══════════════════════════════════════════════════════════════════
## 2. Pipeline de 8 pasos

1. **Preparación de metadatos**: lee `$ARGUMENTS`, extrae autor(es)/año,
   país/contexto, tipo de estudio (cualitativo/cuantitativo/mixto), tipo de
   servicio/Inner Setting, modelo PCC implementado, duración de la
   implementación. Asigna `EST-XXX` (regla 2). Extrae también, con la misma
   fidelidad anti-invención de la regla 3, los campos que alimentarán la
   Matriz de Resultados (§5.4): objetivo del estudio, características de la
   población, tamaño de la muestra, intervención/innovación, tipo de
   institución (pública/privada) y contexto de la institución
   (hospitalaria/ambulatoria). Si alguno no se reporta explícitamente en el
   artículo, regístralo como "No reportado" — nunca lo infieras.

2. **Lectura deductiva CFIR 2.0**: recorre el artículo completo aplicando el
   checklist de constructos CFIR del §3 (Innovation, Outer Setting, Inner
   Setting, Individuals, Implementation Process, Outcomes). Para cada
   constructo con evidencia, identifica el/los fragmentos, su dirección
   (+/0/-) y rating (-2 a +2, ver tabla §4).

3. **Lectura deductiva NPT**: repite el proceso con los 4 mecanismos NPT
   generales y sus subconstructos (Coherence, Cognitive Participation,
   Collective Action, Reflexive Monitoring). Si un fragmento describe el
   mecanismo de forma genérica sin distinguir el subconstructo específico,
   usa el código "(General)" correspondiente (`NPT-CO`, `NPT-CP`, `NPT-CA`,
   `NPT-RM`) en vez de forzar un subconstructo.

4. **Codificación inductiva**: si tras los pasos 2-3 quedan fragmentos
   claramente relevantes para "qué se sabe del proceso de implementación de
   PCC a nivel institucional" pero que no calzan en ningún constructo
   existente, créales un código nuevo `IND-EMG-001`, `IND-EMG-002`, etc.
   (numeración propia, correlativa dentro de todo el proyecto, no por
   artículo), con su propia etiqueta corta y definición ad-hoc. Regístralos
   también en notas como candidatos a revisión teórica futura.

5. **Rating con justificación**: para cada constructo codificado, asigna el
   rating (-2 a +2, tabla §4) y escribe en una frase la justificación
   basada en el fragmento citado — nunca un rating sin texto de respaldo.

6. **Marcado para calibración**: si `EST-XXX` ∈ {EST-001, EST-002, EST-003,
   EST-004}, agrega una nota en la Ficha por Estudio: "Calibración
   inter-observador pendiente (κ≥0.70) — primeros 4 estudios."

7. **Síntesis**: redacta la Ficha por Estudio completa (§5) en español,
   incluyendo el análisis integrado que conecta hallazgos CFIR + NPT con la
   pregunta central de la tesis.

8. **Registro en Matriz de Resultados**: con los campos extraídos en el paso
   1 y los hallazgos/limitaciones del estudio (extraídos textualmente del
   artículo, p. ej. de las secciones Results/Discussion/Limitations), llena
   la fila `EST-XXX` de la Matriz de Resultados (Hoja 8, §5.4) con las 12
   columnas requeridas. Igual que en el resto del pipeline: sin evidencia
   textual razonable → "No reportado", nunca inventado.

═══════════════════════════════════════════════════════════════════
## 3. Checklist de constructos (lista real, verificada contra la Hoja 2 — 69 ítems)

### CFIR 2.0 · INNOVATION
- `INN-A` Innovation Source
- `INN-B` Innovation Evidence-Base
- `INN-C` Innovation Relative Advantage
- `INN-D` Innovation Adaptability
- `INN-E` Innovation Complexity
- `INN-F` Innovation Design
- `INN-G` Innovation Cost

### CFIR 2.0 · OUTER SETTING
- `OS-A` Critical Incidents
- `OS-D` Partnerships & Connections
- `OS-E` Policies & Laws
- `OS-F` Financing
- `OS-G1` External Pressure: Societal
- `OS-G3` External Pressure: Performance

### CFIR 2.0 · INNER SETTING
- `IS-A3` Work Infrastructure
- `IS-B` Relational Connections
- `IS-C` Communications
- `IS-D2` Culture: Recipient-Centeredness
- `IS-D3` Culture: Deliverer-Centeredness
- `IS-D4` Culture: Learning-Centeredness
- `IS-E` Tension for Change
- `IS-F` Compatibility
- `IS-G` Relative Priority
- `IS-H` Incentive Systems
- `IS-I` Mission Alignment
- `IS-J1` Available Resources: Funding
- `IS-J3` Available Resources: Materials
- `IS-K` Access to Knowledge & Information

### CFIR 2.0 · INDIVIDUALS
- `IND-A1` High-Level Leaders
- `IND-A2` Mid-Level Leaders
- `IND-A3` Opinion Leaders
- `IND-D1` Implementation Facilitators
- `IND-E` Implementation Leads
- `IND-H` Innovation Deliverers
- `IND-B(Del)` Deliverers: Capability
- `IND-C(Del)` Deliverers: Opportunity
- `IND-D(Del)` Deliverers: Motivation
- `IND-I` Innovation Recipients

### CFIR 2.0 · IMPLEMENTATION PROCESS
- `IMP-A` Teaming
- `IMP-B2` Assessing Needs: Recipients
- `IMP-C` Assessing Context
- `IMP-D` Planning
- `IMP-E` Tailoring Strategies
- `IMP-F1` Engaging: Deliverers
- `IMP-H` Reflecting & Evaluating
- `IMP-I` Adapting

### CFIR 2.0 · OUTCOMES
- `OUT-AI` Anticipated: Implementability
- `OUT-RI` Actual: Implementation
- `OUT-RS` Actual: Sustainment
- `OUT-DelI` Deliverer Impacts
- `OUT-RecI` Recipient Impacts

### NPT · COHERENCE
- `NPT-CO` Coherence (General)
- `NPT-CO-DF` Coherence: Differentiation
- `NPT-CO-CS` Coherence: Communal Specification
- `NPT-CO-IS` Coherence: Individual Specification
- `NPT-CO-IN` Coherence: Internalization

### NPT · COGNITIVE PARTICIPATION
- `NPT-CP` Cognitive Participation (General)
- `NPT-CP-IN` Cognitive Participation: Initiation
- `NPT-CP-EN` Cognitive Participation: Enrolment
- `NPT-CP-LG` Cognitive Participation: Legitimation
- `NPT-CP-AC` Cognitive Participation: Activation

### NPT · COLLECTIVE ACTION
- `NPT-CA` Collective Action (General)
- `NPT-CA-IW` Collective Action: Interactional Workability
- `NPT-CA-RI` Collective Action: Relational Integration
- `NPT-CA-SW` Collective Action: Skill-Set Workability
- `NPT-CA-CX` Collective Action: Contextual Integration

### NPT · REFLEXIVE MONITORING
- `NPT-RM` Reflexive Monitoring (General)
- `NPT-RM-SY` Reflexive Monitoring: Systematization
- `NPT-RM-CA` Reflexive Monitoring: Communal Appraisal
- `NPT-RM-IA` Reflexive Monitoring: Individual Appraisal
- `NPT-RM-RC` Reflexive Monitoring: Reconfiguration

Si necesitas confirmar la definición oficial/operacional exacta de un código
específico (columnas E-K de la Hoja 2), consulta el Sheet vía
`mcp__Google_Drive__read_file_content` con
`fileId=1rRuk_DBPV5RgdalaF_R90uOXf_DTiPPBbWwdAaS0AzE` en vez de asumir —
esta lista del §3 da código + nombre + dominio para el checklist, no las
definiciones completas.

═══════════════════════════════════════════════════════════════════
## 4. Sistema de rating

| Valor | Significado |
|---|---|
| +2 | Facilitador fuerte (evidencia clara y explícita de impacto positivo en la implementación) |
| +1 | Facilitador moderado |
| 0 | Neutro / no reportado / sin información suficiente |
| -1 | Barrera moderada |
| -2 | Barrera fuerte (evidencia clara y explícita de impacto negativo en la implementación) |
| NA | Evaluado explícitamente y sin evidencia en este artículo (distinto de "0 = neutro reportado") |

═══════════════════════════════════════════════════════════════════
## 5. Estructura de salida a escribir en el Sheet

### 5.1 Hoja de Trabajo (Hoja 4) — 16 columnas, una fila por fragmento codificado
`ID Estudio | Autor(es) y Año | País/Contexto | Tipo de estudio | Página/Sección |
Fragmento de texto | Marco (CFIR/NPT) | Código | Constructo | Dominio |
Dirección (+/0/-) | Rating (-2/+2) | Segundo código (si aplica) | Relación entre
códigos | Código inductivo (IND-EMG-) | Notas/Justificación rating`

### 5.2 Matriz CFIR × 60 estudios (Hoja 5) y Matriz NPT × 60 estudios (Hoja 6)
Cada fila = un constructo del §3 (saltando las filas de encabezado de dominio
tipo "▶ INNOVATION", que son separadores visuales, no constructos). Columnas
`EST-001…EST-060` + 3 columnas de síntesis al final: `N estudios reportados`,
`Rating promedio`, `Patrón global`. Al codificar el artículo EST-XXX, escribe
el rating (o "NA") en la columna correspondiente de cada fila de constructo
evaluado.

### 5.3 Ficha por Estudio (Hoja 7) — una sección nueva por artículo, en español
```
═══ IDENTIFICACIÓN DEL ESTUDIO ═══
ID del estudio (EST-001 a EST-060):
Autor(es) y Año:
Título del artículo:
Revista / DOI:
País / Región:
Tipo de estudio (cualitativo/cuantitativo/mixto):
Tipo de servicio / Inner Setting:
Modelo PCC implementado (Innovation):
Duración de la implementación:
Outcome de implementación reportado:

═══ SÍNTESIS CFIR 2.0 ═══
Constructos CFIR identificados (código + dirección + rating):
Barrera principal (código + fragmento):
Facilitador principal (código + fragmento):
Constructos con relación documentada:

═══ SÍNTESIS NPT ═══
Mecanismos NPT identificados (código + dirección + rating):
Coherence — observaciones:
Cognitive Participation — observaciones:
Collective Action — observaciones:
Reflexive Monitoring — observaciones:

═══ ANÁLISIS INTEGRADO ═══
¿El modelo PCC se normalizó (OUT-RI / OUT-RS)? ¿En qué grado?:
Factores CFIR que explican ese resultado:
Mecanismos NPT que explican ese resultado:
Estrategias de implementación usadas (si se reportan):
Notas adicionales / Códigos inductivos (IND-EMG-):

Codificado por:
Fecha de codificación:
Segunda codificación por:
```

### 5.4 Matriz de Resultados (Hoja 8) — una fila por estudio, en español
Columnas (13): `ID Estudio | Autor(es) | Año de publicación | País(es) de
origen | Objetivo del estudio | Tipo de estudio (metodología) |
Características de la población | Tamaño de la muestra | Intervención /
Innovación | Tipo de institución (pública/privada) | Contexto de la
institución (hospitalaria/ambulatoria) | Hallazgos y/o resultados del
estudio | Limitaciones del estudio`. La fila `EST-XXX` ya existe
pre-creada en el Sheet (filas EST-001 a EST-060); solo completa las 12
columnas restantes con lo extraído en el paso 1 y paso 8 del pipeline.
Mismas reglas anti-invención: "No reportado" si el artículo no lo
especifica.

### 5.5 Limitación de escritura conocida
Las herramientas de Drive disponibles (`mcp__Google_Drive__*`) no exponen
edición célula a célula de un Google Sheet existente. El comando debe:
- Generar el bloque completo (Hoja de Trabajo + filas de Matriz + Ficha por
  Estudio + fila de Matriz de Resultados) en formato tabular listo para
  copiar/pegar en el Sheet.
- Intentar, si existe alguna herramienta de escritura disponible en la
  sesión (verificar con ToolSearch antes de descartarlo), anexar el
  contenido directamente.
- Si no es posible escritura directa, entregar el bloque pegable y dejarlo
  explícito en el resumen final, en vez de fallar silenciosamente.

═══════════════════════════════════════════════════════════════════
## 6. Resumen final

Al terminar, imprime:
- `EST-XXX` asignado y metadatos básicos del estudio.
- N° de filas agregadas a la Hoja de Trabajo.
- Lista de constructos con evidencia positiva (rating ≠ 0/NA) vs. constructos
  marcados NA.
- Códigos inductivos nuevos creados (si los hay).
- Confirmación de que la fila `EST-XXX` de la Matriz de Resultados (§5.4)
  quedó completa, señalando qué campos quedaron como "No reportado".
- Si `EST-XXX` ≤ EST-004: recordatorio de calibración inter-observador
  (κ≥0.70) pendiente.

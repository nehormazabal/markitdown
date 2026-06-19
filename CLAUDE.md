# Contexto del proyecto

Este repo (`markitdown`) se usa como entorno de trabajo para una tesis
doctoral sobre implementación de Atención Centrada en la Persona (PCC) /
humanización en salud a nivel institucional. El uso principal en este
repo no es el código fuente de la herramienta `markitdown` en sí, sino:

1. Convertir artículos científicos (PDF → `.md`) con `markitdown`.
2. Codificar cada artículo `.md` contra un marco teórico CFIR 2.0 + NPT
   usando el comando `/codificar-articulo`, y registrar los resultados en
   el Google Sheet **"Codebook_CFIR2_NPT_Integrado_60estudios"**
   (`fileId = 1rRuk_DBPV5RgdalaF_R90uOXf_DTiPPBbWwdAaS0AzE`).

No modificar el código fuente de `markitdown` como parte de estas tareas de
codificación, salvo que el usuario lo pida explícitamente.

## Comando principal

`.claude/commands/codificar-articulo.md` — define el proceso completo:
rol experto (CFIR 2.0, NPT, análisis cualitativo deductivo-inductivo),
reglas duras del proyecto, checklist de 69 constructos (verificado contra
la Hoja 2 real del Sheet — la Portada del Sheet dice "57" pero esa cifra
está desactualizada, no usarla), pipeline de 8 pasos, sistema de rating y
plantillas de salida (Hoja de Trabajo, Matrices CFIR/NPT, Ficha por
Estudio, Matriz de Resultados con metadatos/hallazgos de los 60 estudios).

## Reglas duras del proyecto (resumen — el detalle vive en el comando)

- Todo el contenido escrito en las celdas del codebook/Sheet va **en
  español**, incluso si el artículo fuente está en otro idioma. Las citas
  textuales del fragmento original pueden mantenerse en su idioma.
- Los artículos se codifican con un ID correlativo `EST-001` → `EST-060`
  (extensible), nunca se reutiliza ni se saltea un número sin revisar el
  Sheet primero.
- **Fidelidad sin invención**: cada código debe respaldarse en un fragmento
  textual real del artículo. Si no hay evidencia, se marca `NA`, no se
  inventa ni se infiere sin dejar constancia explícita del razonamiento de
  abstracción en la columna de notas.
- Se busca la **máxima cobertura posible de constructos** (CFIR + NPT),
  recorriendo el checklist completo en cada artículo, no solo los que
  "saltan a la vista".
- Se permite y se espera **abstracción cualitativa justificada** (leer
  párrafos completos, captar matices/contradicciones), siempre que quede
  anclada a evidencia textual citada.
- Toda codificación debe poder responder explícitamente a la pregunta
  central de la tesis: *¿qué se sabe del proceso de implementación del
  cuidado centrado en la persona a nivel institucional?*

## Limitación conocida

Las herramientas `mcp__Google_Drive__*` disponibles no permiten edición
célula a célula de un Google Sheet existente. El comando genera el bloque
de resultados en formato pegable y lo deja explícito en el resumen final si
no puede escribir directamente.

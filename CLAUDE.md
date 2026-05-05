# Guía para Claude Code

Este repositorio contiene prédicas y enseñanzas personales en español. Lo que sigue son las convenciones del proyecto y cómo colaborar acá.

## Idioma

- **Todo el contenido del repo está en español.** Nunca escribas texto de prédicas en otro idioma.
- También respondé al usuario en español.
- Tono: pastoral, devocional, claro y directo. Evitá jerga académica innecesaria, pero no banalices el texto bíblico.

## Estructura de cada prédica

Cada prédica vive en `predicas/NNN-tema/` con tres archivos principales:

1. **`notas.md`** — desarrollo completo / manuscrito. Estructura sugerida:
   - **Texto base** (con las versiones comparadas)
   - **Contexto** (autor, género literario, trasfondo histórico)
   - **Bosquejo** (3-4 puntos principales)
   - **Desarrollo** de cada punto: exégesis + ilustraciones
   - **Aplicación**
   - **Conclusión / llamado**
   - **Referencias y notas**

2. **`bosquejo.md`** — outline de una página, lo que se lleva al púlpito. Solo títulos, citas clave y bullets cortos.

3. **`presentacion.md`** — slides en formato Marp. Una idea por slide, texto mínimo, citas bíblicas destacadas. Ver [plantillas/presentacion.md](plantillas/presentacion.md).

Carpeta opcional `recursos/` dentro de la prédica para imágenes, citas largas o material de referencia.

## Numeración y nombres

- Las prédicas se numeran cronológicamente por orden de creación: `001-`, `002-`, `003-`...
- El nombre de la carpeta describe el tema o pasaje en kebab-case: `001-salmo-23`, `002-romanos-8-31`, `003-fe-y-obras`.
- Antes de crear una prédica nueva, mirá el último número en `predicas/` y usá el siguiente.

## Versiones bíblicas y citas

Solo usamos tres versiones: **RVR1960**, **NTV**, **NBLA**. Convenciones completas en [recursos/biblia.md](recursos/biblia.md).

Reglas rápidas:
- Formato corto: `Sal 23:1 (RVR1960)`.
- Cita en bloque: usá `>` markdown y poné la sigla al final entre paréntesis.
- Cuando compares versiones, mostralas en orden: RVR1960 → NTV → NBLA.
- Nunca inventes texto bíblico. **Siempre verificá las citas en [Bible Gateway](https://www.biblegateway.com/) antes de incluirlas en una prédica.** URLs:
  - `https://www.biblegateway.com/passage/?search={referencia}&version=RVR1960`
  - `https://www.biblegateway.com/passage/?search={referencia}&version=NTV`
  - `https://www.biblegateway.com/passage/?search={referencia}&version=NBLA`

## Duración

Las prédicas duran **entre 20 y 55 minutos**. Como referencia para el manuscrito: ~130-150 palabras por minuto al predicar. Si el desarrollo se va muy por encima de ese rango, avisá al usuario.

## Presentaciones (Marp)

- Todas las presentaciones usan el tema custom en [recursos/tema-marp.css](recursos/tema-marp.css). El frontmatter de cada `presentacion.md` lo declara.
- Una idea principal por slide. Texto mínimo — la slide acompaña, no reemplaza al predicador.
- Las citas bíblicas van destacadas (clase CSS `cita` o blockquote).
- Para ver/editar slides en vivo: `npm run slides`. Para exportar HTML: `npm run build`.

## Cómo colaborar en una prédica

El usuario suele traer ideas, pasajes y reflexiones, y construye la prédica de a poco. Pautas:

- **No inventes contenido teológico.** Si el usuario no dijo algo explícitamente, no lo pongas en su boca. Preguntá.
- Cuando aporte ideas, podés ayudar a estructurarlas, sugerir conexiones bíblicas, mejorar redacción y proponer ilustraciones — siempre marcando claramente lo que es sugerencia tuya vs lo que dijo el usuario.
- Trabajá iterativamente: una sección a la vez, confirmando antes de avanzar.
- Si una sección queda incompleta, dejala marcada con `> [pendiente: ...]` en lugar de rellenarla con material genérico.

## Qué NO hacer

- No escribas prédicas enteras de cero sin input del usuario.
- No mezcles versiones bíblicas más allá de las tres acordadas.
- No agregues comentarios doctrinales fuertes sin que el usuario los haya planteado.
- No borres notas o secciones existentes sin confirmación, aunque parezcan incompletas.

# Prédicas

Repositorio personal de prédicas y enseñanzas en español. Cada prédica vive en su propia carpeta y contiene:

- **Notas** (`notas.md`): manuscrito o desarrollo completo de la prédica.
- **Bosquejo** (`bosquejo.md`): outline rápido de una página para predicar.
- **Presentación** (`presentacion.md`): diapositivas en formato [Marp](https://marp.app/) para visualizar en web.

Duración objetivo de cada prédica: **20 a 55 minutos**.

Versiones bíblicas en uso: **Reina Valera 1960 (RVR1960)**, **Nueva Traducción Viviente (NTV)** y **Nueva Biblia de las Américas (NBLA)**. Convenciones de cita en [recursos/biblia.md](recursos/biblia.md).

## Estructura del repo

```
predicas/
├── predicas/                   # cada prédica en su carpeta numerada
│   └── 001-salmo-23/
│       ├── notas.md
│       ├── bosquejo.md
│       ├── presentacion.md
│       └── recursos/
│
├── plantillas/                 # templates para nuevas prédicas
│   ├── notas.md
│   ├── bosquejo.md
│   └── presentacion.md
│
├── recursos/
│   ├── biblia.md               # convenciones de cita
│   └── tema-marp.css           # estilo visual de las slides
│
├── CLAUDE.md                   # guía para Claude Code
└── .claude/                    # config del proyecto
```

Las prédicas se numeran cronológicamente por orden de creación: `001-`, `002-`, etc. El nombre de la carpeta describe brevemente el tema o pasaje (ej: `001-salmo-23`, `002-romanos-8`).

## Empezar una prédica nueva

1. Copiar la carpeta `plantillas/` a `predicas/NNN-tema/` (renombrando los archivos según corresponda).
2. Completar `notas.md` con el desarrollo, `bosquejo.md` con el outline y `presentacion.md` con las slides.

## Ver las presentaciones

Las presentaciones están en formato [Marp](https://marp.app/) (markdown puro con frontmatter).

**Modo servidor (recomendado para edición en vivo):**

```bash
npm install
npm run slides
```

Esto levanta un servidor local que muestra todas las presentaciones del repo. Cualquier cambio en los `.md` se refleja automáticamente.

**Exportar a HTML estático:**

```bash
npm run build
```

Genera un `presentacion.html` junto a cada `presentacion.md`. Se pueden abrir en cualquier navegador sin servidor.

## Versiones bíblicas

| Sigla    | Versión                          |
| -------- | -------------------------------- |
| RVR1960  | Reina Valera 1960                |
| NTV      | Nueva Traducción Viviente        |
| NBLA     | Nueva Biblia de las Américas     |

Formato estándar de cita: `Sal 23:1 (RVR1960)`. Detalles en [recursos/biblia.md](recursos/biblia.md).

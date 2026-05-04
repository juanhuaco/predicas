# Convenciones de citas bíblicas

En este repositorio usamos solamente tres versiones de la Biblia:

| Sigla    | Versión                          | Uso típico                                       |
| -------- | -------------------------------- | ------------------------------------------------ |
| RVR1960  | Reina Valera 1960                | Versión base, lectura tradicional                |
| NTV      | Nueva Traducción Viviente        | Lenguaje contemporáneo, claridad                 |
| NBLA     | Nueva Biblia de las Américas     | Precisión literal, comparación textual           |

## Formato de cita

**Cita corta en línea**: usá la abreviatura del libro + capítulo:versículo + sigla entre paréntesis.

```
Sal 23:1 (RVR1960)
Jn 3:16 (NTV)
Ef 2:8-10 (NBLA)
```

**Cita en bloque**: usá `>` markdown y poné la sigla al final entre paréntesis.

```markdown
> Jehová es mi pastor; nada me faltará. En lugares de delicados pastos me hará descansar; junto a aguas de reposo me pastoreará.
> — Sal 23:1-2 (RVR1960)
```

**Comparación de versiones**: siempre en este orden — RVR1960 → NTV → NBLA.

```markdown
**Sal 23:1**

> Jehová es mi pastor; nada me faltará. — *RVR1960*
> El Señor es mi pastor; tengo todo lo que necesito. — *NTV*
> El Señor es mi pastor, nada me faltará. — *NBLA*
```

## Abreviaturas de libros

### Antiguo Testamento

| Libro          | Abrev. | Libro          | Abrev. |
| -------------- | ------ | -------------- | ------ |
| Génesis        | Gn     | Eclesiastés    | Ec     |
| Éxodo          | Ex     | Cantares       | Cnt    |
| Levítico       | Lv     | Isaías         | Is     |
| Números        | Nm     | Jeremías       | Jer    |
| Deuteronomio   | Dt     | Lamentaciones  | Lm     |
| Josué          | Jos    | Ezequiel       | Ez     |
| Jueces         | Jue    | Daniel         | Dn     |
| Rut            | Rt     | Oseas          | Os     |
| 1 Samuel       | 1 S    | Joel           | Jl     |
| 2 Samuel       | 2 S    | Amós           | Am     |
| 1 Reyes        | 1 R    | Abdías         | Abd    |
| 2 Reyes        | 2 R    | Jonás          | Jon    |
| 1 Crónicas     | 1 Cr   | Miqueas        | Miq    |
| 2 Crónicas     | 2 Cr   | Nahúm          | Nah    |
| Esdras         | Esd    | Habacuc        | Hab    |
| Nehemías       | Neh    | Sofonías       | Sof    |
| Ester          | Est    | Hageo          | Hag    |
| Job            | Job    | Zacarías       | Zac    |
| Salmos         | Sal    | Malaquías      | Mal    |
| Proverbios     | Pr     |                |        |

### Nuevo Testamento

| Libro             | Abrev. | Libro          | Abrev. |
| ----------------- | ------ | -------------- | ------ |
| Mateo             | Mt     | 1 Timoteo      | 1 Ti   |
| Marcos            | Mr     | 2 Timoteo      | 2 Ti   |
| Lucas             | Lc     | Tito           | Tit    |
| Juan              | Jn     | Filemón        | Flm    |
| Hechos            | Hch    | Hebreos        | Heb    |
| Romanos           | Ro     | Santiago       | Stg    |
| 1 Corintios       | 1 Co   | 1 Pedro        | 1 P    |
| 2 Corintios       | 2 Co   | 2 Pedro        | 2 P    |
| Gálatas           | Gá     | 1 Juan         | 1 Jn   |
| Efesios           | Ef     | 2 Juan         | 2 Jn   |
| Filipenses        | Fil    | 3 Juan         | 3 Jn   |
| Colosenses        | Col    | Judas          | Jud    |
| 1 Tesalonicenses  | 1 Ts   | Apocalipsis    | Ap     |
| 2 Tesalonicenses  | 2 Ts   |                |        |

## Notas

- Para rangos de versículos: `Sal 23:1-3` (con guion simple).
- Para versículos no contiguos: `Sal 23:1, 4`.
- Para múltiples capítulos: `Sal 23:1 — 24:2`.
- Cuando el contexto ya dejó claro el libro, podés solo poner `v. 4` o `vv. 4-6`.

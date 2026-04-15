# Poemario Beta — Plan de Documentación Unificada

> Rodrigo Gaete · Poesía digital, experimental y política

## Inventario de poemarios digitales

| Colección | Ubicación | Medio | Estado | Poemas |
|-----------|-----------|-------|--------|--------|
| **Poemario Beta** | `Poemario Beta/` | Web interactivo (HTML) | Live | 7 poemas + perfil + contraportada |
| **29092020** | `29092020/` | Web interactivo (HTML) | Live en GH Pages | 3 poemas (Cap I–II) |
| **Los números NO existen** | `Poemario Beta/Recursos/*.pdf` | PDF descargable | Completo | (poemario hermano, enlazado desde Beta) |
| **Octubre Revolucionario** | `Poesía Animada/` | Video After Effects | ⚠️ Deprecado | 1 pieza de videopoesía |
| **Poemarios (académico)** | `antropologia-corrupcion/Poemarios/` | Metodología de investigación | En desarrollo | Contrapoética del archivo (tesis doctoral) |

---

## Mapa temático transversal

```
2019 ──── Octubre Revolucionario (estallido social)
  │         └─ Videopoesía: animación After Effects
  │
2020 ──── 29092020 (plebiscito Apruebo/Rechazo)
  │         ├─ "Poesías sangrantes mith" — Cap I: desorden chileno
  │         └─ "Cartografía del eco" — Cap II: metro, memoria
  │
2020 ──── Poemario Beta (experimentación de estéticas)
  │         ├─ "Poesías sangrantes mith" — sueño en apruebo
  │         ├─ "En tiempos de cuarentena" — COVID + teatro capital
  │         ├─ "Títulares Falsos" — noticias, 15 Nov 2019
  │         ├─ "El Sigle" — ciudad bajo toque de queda
  │         ├─ "Ciper" — crítica mediática, dropdown interactivo
  │         ├─ "Respuesta Anti poética a Carlos Peña" — modernidad
  │         └─ "Modernidad" — identidad, autonomía
  │
  ? ──── Los números NO existen (PDF, descargable)
  │
2025+ ─── Contrapoética del Archivo (tesis doctoral)
            ├─ Títulos de merced + geometría del despojo
            ├─ Transcripciones corporativas → poesía
            ├─ Testimonios comunidades (La Negra)
            └─ Marcos normativos como material poético
```

## Ejes temáticos

| Eje | Colecciones | Descripción |
|-----|-------------|-------------|
| 🏛️ Poesía política chilena | Beta, 29092020, Octubre | Estallido, plebiscito, Zurita |
| 🎭 Experimentación formal | Beta, 29092020 | Capas HTML, interactividad, ruptura de género |
| 📢 Activismo lingüístico | Beta, Contrapoética | Contra tecnocracia, restitución de voz |
| 🌆 Territorio urbano | 29092020, Beta | Ciudad, consignas, memoria colectiva |
| 🔬 Arte como investigación | Contrapoética | Autoetnografía + arts-based research |

---

## Stack técnico actual

| Colección | Stack | Build | Deploy |
|-----------|-------|-------|--------|
| Poemario Beta | HTML5 + Bootstrap 4.5 + CSS | Ninguno | Sin deploy (local) |
| 29092020 | HTML5 + Bootstrap 4.5 + CSS | Ninguno | GitHub Pages |
| Los números NO existen | PDF | N/A | Descarga desde Beta |
| Octubre Revolucionario | After Effects → MP4 | N/A | ⚠️ Deprecado |
| Contrapoética | Markdown (README) | N/A | Incrustado en antropologia-corrupcion |

---

## Plan de acción — Documentación

### Fase 1: README por colección (Must · Effort S)

- [ ] **Poemario Beta/README.md** — Crear con: propósito, índice de poemas con sinopsis, stack, cómo abrir, enlace a PDF hermano
- [ ] **29092020/README.md** — Ya existe, actualizar: agregar sinopsis de cada poema y enlace cruzado a Beta

### Fase 2: Índice maestro (Should · Effort M)

- [ ] **Crear documento central** (p.ej. en `vientonorte.github.io` o como repo propio) que vincule todas las colecciones con:
  - Cronología visual
  - Mapa temático
  - Links directos a cada poema
  - Ficha técnica por colección

### Fase 3: Consolidación técnica (Could · Effort L)

- [ ] Evaluar migrar Poemario Beta a GitHub Pages (actualmente sin deploy)
- [ ] Unificar CSS/Bootstrap entre Beta y 29092020 (comparten stack)
- [ ] Versionar PDF "Los números NO existen" con metadata adecuada
- [ ] Considerar landing unificada de poesía en `vientonorte.github.io/poesia/`

### Fase 4: Archivo y cross-references (Could · Effort S)

- [ ] Enlazar desde `antropologia-corrupcion/Poemarios/README.md` hacia Beta y 29092020
- [ ] Agregar sección "Obra poética" en portafolio profesional
- [ ] Documentar que Octubre Revolucionario está deprecado pero su video final está archivado

---

## Decisiones pendientes

| Decisión | Opciones | Impacto |
|----------|----------|---------|
| ¿Poemario Beta se publica en GH Pages? | Sí (nuevo deploy) / No (solo local) | Visibilidad pública |
| ¿Landing unificada de poesía? | Sección en hub / Repo propio / Dentro de portafolio | Arquitectura de info |
| ¿Consolidar Beta + 29092020 en un solo repo? | Merge / Mantener separados con cross-links | Simplicidad vs. historia |
| ¿Dónde vive el video de Octubre? | YouTube / Drive / Eliminado | Preservación digital |

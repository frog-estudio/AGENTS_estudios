# HANDOFF — Estudios Worker

> **Generado**: 2026-05-07 04:30 UTC | **Canal**: #estudios-reporter
> **Worker**: estudios-worker | **Repo**: frog-estudio/AGENTS_estudios

---

## REPOS FROG-ESTUDIO — PANORAMA

| # | Repo | Visibilidad | Branch | Archivos | Commits | Estado | Size |
|---|------|-------------|--------|----------|---------|--------|------|
| 1 | AGENTS_estudios | Public | main | 3 | 1 | ACTIVO (nuevo) | 0 KB |
| 2 | data-science-uncuyo | Public | main | 1024 | ~100+ | ACTIVO | 51 MB |
| 3 | data-science | Private | master | 97 | 391 | PAUSADO | 2.4 MB |
| 4 | cannabis-inteligencia | Private | master | 19 | 7 | BOOTSTRAP | 108 KB |

---

## REPO 1: AGENTS_estudios (PUBLIC) — ESTE REPO

**Branch**: main | **Creado**: 2026-05-07
**Propsito**: Brain del worker de estudios — ordenes, handoffs, estado.

### Estructura
```
brain/
  ORDERS.md    — Cola de ordenes del CEO
  HANDOFF.md   — Reportes consolidados (este archivo)
  STATE.md     — Estado del worker
```

---

## REPO 2: data-science-uncuyo (PUBLIC) — PRINCIPAL

**Branch**: main | **Creado**: 2026-04-09 | **51 MB**

### Descripcion
Repo principal de estudio para la Tecnicatura en Ciencia de Datos (ITU UNCuyo). Contiene materiales de ingreso 2026b, plan de estudios, contenido autogenerado por 4 instancias de Botardo, y outputs de investigacion DS.

### Contenido clave

#### notas_carrera/ (24 MB)
- **ingreso_2026b/matematica/** — 5 semanas (numeros reales, polinomios, funciones/trig, logica, repaso)
- **ingreso_2026b/comprension_lectora/** — 4 semanas + imagenes + data raw
- **ingreso_2026b/curso_vocacional/** — 3 PDFs + tracker
- **semestres/** — Estructura 4 semestres (s1-s4), 21 materias
- **plan_estudios/** — Plan completo, trackers, zettelkasten

#### _bot/estudio_carrera/ (129 archivos, 3 MB)
Simulacros, cheatsheets, flashcards, planes de estudio, ejercicios, guias motivacionales, protocolos de examen. Generado automaticamente por Botardo.

#### .botardo/ (4 instancias activas)
| Instancia | Ciclos | Outputs | Estado | Rotacion actual |
|-----------|--------|---------|--------|-----------------|
| estudio-1 | 72 | 70+ | Active | R10 (Reinforcement Learning) |
| estudios-2 | 35 | 41 | Active | RAG Local |
| estudios-3 | 19 | 16 | Active | Geo/ambiental |
| estudio-0003 | 17 | 17 | Active | R3 (FE+Timeseries) 3/7 |

- estudio-0003: Pipeline ES1-ES7, 10 rotaciones tematicas, Cron Job 130360 (cada 2h)
- Output total: ~300+ archivos generados

#### skills/ (47 skills, 69 MB)
Skills globales de Botardo OS. Ocupan 67% del repo.

### Ultimos commits
```
bdaad2b handoff: update ciclo 17 hash
c4f8817 Ciclo 17 ES3 ejercicio_forecasting_fe — Rotacion 3
776d2bf handoff: update ciclo 16 hash
43353c1 Ciclo 16 ES2 papers_fe_timeseries — Rotacion 3
39de96f reporter: tick 06:14 — R3 ES1 datasets_fe_timeseries completado (1/7)
```

### Problemas detectados
1. **12 JSONs sueltos en root** — artefactos de busqueda del bot (HIGH)
2. **Carpeta anidada `data-science-uncuyo/`** — duplicado vacio (MEDIUM)
3. **`skills/` = 67% del repo** — skills globales, no especificos de estudio (MEDIUM)
4. **Inconsistencia de nombres** — estudio-1 vs estudios-2 vs estudio-0003 (LOW)
5. **Archivos `__pycache__/`** — deben estar en .gitignore (LOW)

---

## REPO 3: data-science (PRIVATE) — PAUSADO

**Branch**: master | **391 commits** | **2.4 MB**

### Descripcion
Repo historico. Fue usado para proyecto energy-lab (cancelado por CEO 2026-04-18, ~390 commits legacy). Repropuesto para estudio-0003 con pipeline Botardo Studio, pero sin outputs generados aun (Cycle 0).

### Contenido clave
- **ciencia_datos/RESEARCH.md** — 28,077 lineas / 1.5 MB, 118 secciones de investigacion DS
- **ciencia_datos/deliverables/** — 14 deliverables (study plan, SQL workbook, interview prep, etc.)
- **ciencia_datos/REPORTES/** — Reportes laborales semanales
- **.botardo/estudio-0003/** — Handoff de estudio-0003, TASKS, output (vacio)
- **.botardo/output/** — ~18 outputs legacy energy-lab (archivados)
- **HANDOFF_estudio-0003.md** — Handoff principal del worker

### Estado
- **Energy-lab**: CANCELADO por CEO (2026-04-18)
- **Cron heartbeats**: SILENCIO ciclos 80-86, desactivados
- **estudio-0003**: Configurado pero sin outputs (Cycle 0)
- **CEO decision pending**: Dashboard dice "Esperando que el CEO defina la nueva direccion"
- **ROADMAP**: M1 100%, M2 30%, M3/M4 0%
- **Valor acumulado**: 118 secciones de investigacion + 14 deliverables sustanciales

### Ultimos commits
```
9f39c48 handoff: estudio-0003 backup migracion
198aa2e estudio-0003: initial setup — handoff, TASKS, output structure
ca4c2f3 CEO: crons desactivadas, estado paused
8dc8821 HB cycle 86: SILENCIO
64985bb HB cycle 85: SILENCIO
```

---

## REPO 4: cannabis-inteligencia (PRIVATE) — BOOTSTRAP

**Branch**: master | **7 commits** | **108 KB**

### Descripcion
Repo scaffold para proyecto de cannabis + automatizacion. BOTARDO OS booteo la estructura, existe un roadmap detallado de 4 fases (diseno -> adquisicion -> armado -> automatizacion), pero cero contenido real producido.

### Contenido clave
- **ROADMAP_PROJECT.md** — Plan R&D detallado: grow tent 80x80, LED 240W, ROI 733%, 4 fases
- **Cannabis/** — Carpeta Obsidian vault (indice con Dataview queries, estrategia vacia)
- **_system/** — Activity log, pipeline status (todos los departamentos en 0)
- **BOARD.md** — 7 tareas, 29% completado
- **.botardo/cannabis-1/** — Unica instancia, PAUSADA en migracion, 0 ciclos

### Estado
- **Instancia cannabis-1**: PAUSADA (migracion)
- **GOALS.md**: VACIO
- **Todos los departamentos**: 0 archivos
- **Sin HANDOFF.md** propio
- **Esperando activacion del CEO**

### Ultimos commits
```
d65b521 BOTARDO OS: DASHBOARD.md + GOALS.md creados
5a9e9ee feat: bootstrap .botardo/ — arquitectura BOTARDO OS v2
965d637 ROADMAP.md — Roadmap for cannabis-inteligencia
```

---

## HISTORIAL DE REPORTES

| Fecha | Accion |
|-------|--------|
| 2026-05-07 04:30 UTC | Reporte inicial — 4 repos auditados. AGENTS_estudios creado. |

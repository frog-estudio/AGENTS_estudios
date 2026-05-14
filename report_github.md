# REPORTE GITHUB — frog-estudio

> Generado: 2026-05-15T03:30:00-03:00
> Cuenta: frog-estudio
> Email: estudios-reporter@botardo.os
> Total repos: 5
> Sandbox: estudios-reporter (Reporter)
> Canal: Discord / #estudios-reporter
> Mi repo AGENT: AGENTS_estudios
> Modelo: CRON Model v2.0 (ver brain/CRON_MODEL.md)
> Estructura: ver brain/AGENT_REPO_STRUCTURE.md v2.0

---

## Resumen Ejecutivo

| Metrica | Valor |
|---------|-------|
| Total repos | 5 |
| Repos activos | 2 |
| Repos inactivos | 2 |
| Repos vacios | 0 |
| Repos archive | 0 |
| Sin clasificar | 1 |
| Ultima actividad | 2026-05-14 (botardo-os) |
| Tamano total | ~64.8 MB |
| Mi repo AGENT | AGENTS_estudios (EXCLUSIVO — solo yo escribo) |

**Nota**: El repo `botardo-os` pertenece a la cuenta `bautiarmanicode` pero el token tiene acceso. Se incluye en el reporte por estar accesible. No se escribe en el bajo ninguna circunstancia.

---

## Mi Posesion — Repos donde YO escribo

> CRITICO: Solo pusheo a estos repos. Los demas son read-only o de otra sandbox.

| Repo | Rol | Que hago ahi | Frecuencia de push |
|------|-----|-------------|-------------------|
| AGENTS_estudios | Mi casa | report_github.md, REPOS.md, brain/ (ORDERS, HANDOFF, STATE) | Cada reporte/orden |
| data-science-uncuyo | Trabajo | HANDOFF_REPORTER.md, reportes del pipeline | Cada reporter tick (4h) |

---

## Mapa de Repos — Toda la cuenta

| # | Repo | Categoria | Estado | Owner | Prioridad | Ultimo commit | Archivos | Lenguaje principal | Funcion |
|---|------|-----------|--------|-------|-----------|---------------|----------|-------------------|---------|
| 1 | AGENTS_estudios | AGENT | ACTIVO | YO (estudios-reporter) | HIGH | 2026-05-14 | 5 | N/A (Markdown) | Brain del worker de estudios |
| 2 | data-science-uncuyo | PROYECTO | ACTIVO (completado) | YO (estudios-reporter) | HIGH | 2026-05-12 | 1049 | Python/Markdown | Carrera DS UNCuyo — 70/70 outputs |
| 3 | data-science | PROYECTO | INACTIVO (PAUSADO) | YO (estudios-reporter) | MEDIUM | 2026-05-04 | 97 | Markdown | Historico energy-lab + estudio-0003 |
| 4 | cannabis-inteligencia | PROYECTO | INACTIVO (BOOTSTRAP) | BOTARDO_OS (bautiarmanicode) | LOW | 2026-04-16 | 19 | Markdown | Scaffold cannabis — sin contenido real |
| 5 | botardo-os | TOOL | ACTIVO | BOTARDO_OS (bautiarmanicode) | HIGH | 2026-05-14 | 1758 | Python/Markdown/TypeScript | Hub central BOTARDO OS (READ-ONLY para mi) |

---

## Detalle por Repo

### 1. AGENTS_estudios

**Categoria**: AGENT | **Estado**: ACTIVO | **Prioridad**: HIGH | **Owner**: YO (estudios-reporter)

**URL**: https://github.com/frog-estudio/AGENTS_estudios
**Lenguaje principal**: N/A (Markdown)
**Tamano**: 10 KB
**Ultimo commit**: 2026-05-14 — "report: github account scan — estudios-reporter — 2026-05-15"
**Total archivos**: 5

**Descripcion**: Repo AGENT exclusivo del worker estudios-reporter. Funciona como cerebro del worker: contiene la cola de ordenes del CEO (ORDERS.md), el reporte consolidado (HANDOFF.md), el estado del worker (STATE.md), el reporte GitHub (report_github.md) y el mapa de repos (REPOS.md). Es el unico repo donde el worker tiene permiso de escritura ademas de data-science-uncuyo.

**Estructura**:
```
AGENTS_estudios/
  report_github.md       # Este reporte
  REPOS.md               # Mapa de repos
  brain/
    ORDERS.md            # Cola de ordenes del CEO (1 DONE)
    HANDOFF.md           # Reportes consolidados
    STATE.md             # Estado del worker
```

**Archivos clave**:
- README.md: No existe
- _CRON.md: No existe
- _CONTEXT.md: No existe
- _LOG.md: No existe
- TASKS.md: No existe
- brain/ORDERS.md: Cola de ordenes — 1 orden (001, DONE), sin pendientes
- brain/HANDOFF.md: Reporte de 4 repos auditados con detalle
- brain/STATE.md: Estado ACTIVE, session 2026-05-07, 1 orden completada

**Ultimos 5 commits**:
1. e6b8c65 — report: github account scan — estudios-reporter — 2026-05-15
2. 5bda216 — worker: reporte inicial — 4 repos auditados, orden 001 DONE
3. 76e3a68 — initial structure

**Contenido detallado**:
El repo es minimalista por diseno. Solo contiene 5 archivos Markdown en una estructura plana con un subdirectorio brain/. Fue creado el 2026-05-07 como parte del onboarding de estudios-reporter. La estructura sigue el modelo AGENT_REPO v2.0 de BOTARDO OS, aunque de forma simplificada: carece de memory/, output/, proposals/, inbox/ y apps/. Tiene un report_github.md previo que sera sobrescrito por este reporte. El HANDOFF.md contiene un panorama detallado de los 4 repos de frog-estudio con problemas detectados y estado actual. Las ordenes (ORDERS.md) estan al dia con 1 orden completada y ninguna pendiente.

**Problemas detectados**:
- Falta README.md en raiz (el repo no tiene descripcion visible en GitHub)
- No tiene estructura completa de AGENT_REPO v2.0 (falta memory/, output/, proposals/)
- Estructura minimalista pero funcional para las necesidades actuales

**Recomendaciones**:
- Agregar README.md basico que describa el proposito del repo
- Considerar agregar memory/ si el worker acumula conocimiento entre sesiones

---

### 2. data-science-uncuyo

**Categoria**: PROYECTO | **Estado**: ACTIVO (completado) | **Prioridad**: HIGH | **Owner**: YO (estudios-reporter)

**URL**: https://github.com/frog-estudio/data-science-uncuyo
**Lenguaje principal**: Python/Markdown
**Tamano**: 52189 KB (~51 MB)
**Ultimo commit**: 2026-05-12 — "reporter: tick 14:14 — reorg PRE-BOTARDO OS v3 detectada, estructura post-audit"
**Total archivos**: 1049
**Branch**: main

**Descripcion**: Repo principal de estudio para la Tecnicatura Universitaria en Ciencia de Datos (ITU UNCuyo). Es el repositorio mas grande de la cuenta frog-estudio y contiene materiales de ingreso 2026b, plan de estudios detallado, notas de carrera reales del CEO, y outputs de 4 pipelines Botardo Studio que generaron 70/70 entregables de estudio. El pipeline estudio-0003 completo las 10 rotaciones tematicas (ES1-ES7 x R1-R10) abarcando datasets, papers, ejercicios, herramientas, cheat sheets, cursos MOOC y tutoriales E2E.

**Estructura**:
```
data-science-uncuyo/
  _TICK.md                    # TICK Model (sistema nervioso)
  _CONTEXT.md                 # Contexto del proyecto
  _LOG.md                     # Log de operaciones
  README.md                   # Descripcion del repo
  GOALS.md                    # Metas y deadlines
  TASKS.md                    # Tareas del proyecto
  worklog.md                  # Bitacora de trabajo
  HANDOFF_REPORTER.md         # Output del reporter (yo)
  notas_carrera/              # Notas reales del CEO (24 MB)
    ingreso_2026b/            # Matematica, CL, Vocacional
    modulos_especificos/      # Modulos May-Jun 2026
    plan_estudios/            # Plan general, trackers, zettelkasten
    semestres/                # Estructura 4 semestres (s1-s4)
  .botardo/                   # Infraestructura BOTARDO OS
    estudio-0003/             # Pipeline activo (completo 70/70)
  _review/                    # Archivos movidos en auditoria (NO BORRAR)
    _bot_legacy/              # ~136 archivos legacy
    skills/                   # 47+ skills del sistema (~69 MB)
    search_cache/             # 15 JSONs temporales
    estudio-1/                # Pipeline anterior + outputs
    estudio-2/                # Pipeline anterior + outputs
    estudio-3/                # Pipeline anterior + outputs
    handoff_legacy/           # Handoffs antiguos
    botardo_output/           # Outputs de estudios-3
```

**Archivos clave**:
- README.md: Descripcion del repo con estructura, pipeline Botardo Studio (69/70 al momento de escritura, hoy 70/70)
- _CONTEXT.md: Reglas, identidad, estructura del proyecto
- _LOG.md: Log de operaciones del sistema
- TASKS.md: Tareas del proyecto
- HANDOFF_REPORTER.md: Output del reporter (generado por estudios-reporter cada 4h)
- GOALS.md: Metas y deadlines del CEO

**Ultimos 5 commits**:
1. ec2697b — reporter: tick 14:14 — reorg PRE-BOTARDO OS v3 detectada, estructura post-audit
2. 3fda759 — orden: reorganizacion pre-BOTARDO OS v3 — legacy estudios 1/2/3 + outputs + handoffs a _review
3. 0246df5 — reporter: tick 10:14 — PROGRAMA COMPLETO 70/70, todas las rotaciones finalizadas
4. 9788a38 — handoff: hash C70 ES7
5. 96fe3f2 — Ciclo 70 ES7 tutorial_dqn_inventario — PROGRAMA COMPLETO 70/70

**Contenido detallado**:
El repo es el resultado de un programa de estudio automatizado de 10 rotaciones tematicas (R1 a R10) que cubrio: datasets publicos y especializados, papers de ML/DL, ejercicios practicos de Python, herramientas de Data Science, cheat sheets de referencia, cursos MOOC gratuitos y tutoriales E2E completos. Se generaron 70 entregables de estudio. Las rotaciones abarcaron temas como Computer Vision, Finanzas, Sports Analytics, Deep Learning, NLP, MLOps, Series Temporales y Reinforcement Learning.

El repo tambien contiene las notas reales de carrera del CEO organizadas en notas_carrera/ con material de ingreso (matematica 5 semanas, comprension lectora, curso vocacional), plan de estudios con trackers y zettelkasten. Tras una auditoria PRE-BOTARDO OS v3 (commit 3fda759), los outputs de pipelines legacy (estudio-1, estudios-2, estudios-3), handoffs antiguos, skills del sistema (~69 MB, 67% del repo) y archivos dudosos fueron movidos a _review/. El repo quedo limpio con la estructura esencial del proyecto y los materiales de carrera.

El programa estudio-0003 completo el 2026-05-11 con 70/70 outputs. El repo esta ahora en estado de mantenimiento. El reporter (yo) monitorea cambios cada 4h via CRON Job 130353.

**Problemas detectados**:
- **_review/ = ~69 MB (67% del repo)** — Skills del sistema y contenido legacy ocupan la mayoria del espacio. Considerar remover si no se necesitan
- **Programa completado, sin nuevas ordenes** — El repo no tiene actividad productiva desde 2026-05-12
- **Job 130360 (estudio-0003 worker) aun activo** — El cron job del pipeline sigue corriendo cada 2h a pesar de estar 70/70 completo

**Recomendaciones**:
- Desactivar Job 130360 (estudio-0003 worker) — el programa esta completo
- Considerar limpiar _review/skills/ para reducir el tamano del repo de 51 MB
- Definir proximos pasos: retomar estudio con nuevas rotaciones o archivar el repo

---

### 3. data-science

**Categoria**: PROYECTO | **Estado**: INACTIVO (PAUSADO) | **Prioridad**: MEDIUM | **Owner**: YO (estudios-reporter) / BOTARDO_OS

**URL**: https://github.com/frog-estudio/data-science
**Lenguaje principal**: N/A (Markdown)
**Tamano**: 1212 KB (~1.2 MB)
**Ultimo commit**: 2026-05-04 — "handoff: estudio-0003 backup migracion"
**Total archivos**: 97
**Branch**: master

**Descripcion**: Repo historico que sirvio para dos propositos: (1) energy-lab, un proyecto de investigacion en Data Science aplicada a energia que genero 118 secciones de investigacion y ~18 outputs antes de ser cancelado por el CEO en 2026-04-18; y (2) estudio-0003, un pipeline Botardo Studio que fue configurado pero nunca genero outputs aqui (fue migrado a data-science-uncuyo). Tiene 391 commits legacy. El repo esta en estado PAUSADO — los crons heartbeat fueron desactivados y el CEO no ha definido nueva direccion.

**Estructura**:
```
data-science/
  README.md                   # Descripcion del repo (energy-lab)
  ROADMAP.md                  # Roadmap del proyecto
  ACUMULAR_ESTUDIOS.md        # Plan de acumulacion de estudios
  STATUS.md                   # Status general
  TASKS.md                    # Tareas
  HANDOFF_estudio-0003.md     # Handoff principal del worker
  ciencia_datos/              # Investigacion DS
    RESEARCH.md               # 28,077 lineas / 1.5 MB, 118 secciones
    DS_Study_Plan.md          # Plan de estudio
    DS_Career_Action_Plan.md  # Plan de carrera
    DS_Interview_Prep_Guide.md # Guia de entrevistas
    deliverables/             # 14 deliverables
    REPORTES/                 # Reportes semanales
    trackers/                 # Trackers de evaluacion
  .botardo/                   # Infraestructura BOTARDO OS
    estudio-0003/             # Setup migrado (sin outputs)
    output/                   # ~18 outputs legacy energy-lab
    handoff/                  # Handoffs de sesiones
    lab/                      # Laboratorio DS
```

**Archivos clave**:
- README.md: Descripcion del proyecto como "Energy Lab — Data Science"
- TASKS.md: Tareas del proyecto (sin cambios recientes)
- HANDOFF_estudio-0003.md: Handoff del worker estudio-0003
- ciencia_datos/RESEARCH.md: 28,077 lineas de investigacion en DS — el asset mas valioso del repo

**Ultimos 5 commits**:
1. 9f39c48 — handoff: estudio-0003 backup migracion
2. 198aa2e — estudio-0003: initial setup — handoff, TASKS, output structure
3. ca4c2f3 — CEO: crons desactivadas, estado paused
4. 8dc8821 — HB cycle 86: SILENCIO
5. 64985bb — HB cycle 85: SILENCIO

**Contenido detallado**:
El valor principal de este repo reside en ciencia_datos/RESEARCH.md, un archivo masivo de 28,077 lineas que contiene 118 secciones de investigacion en Data Science cubriendo temas avanzados de ML, deep learning, NLP, time series y MLOps. Tambien hay 14 deliverables sustanciales en ciencia_datos/deliverables/ que incluyen planes de estudio, workbooks de SQL, guias de entrevistas y trackers de progreso.

El proyecto energy-lab genero ~18 outputs de investigacion en .botardo/output/ antes de ser cancelado por el CEO en abril 2026. Los heartbeats del pipeline fueron desactivados progresivamente (SILENCIO en ciclos 80-86). El estudio-0003 fue configurado aqui con estructura de handoff y TASKS, pero nunca genero outputs — fue migrado completamente a data-science-uncuyo. Desde el commit del 2026-05-04 (backup migracion), el repo ha estado completamente inactivo.

**Problemas detectados**:
- **Repo PAUSADO sin direccion definida** — 391 commits legacy sin actividad nueva
- **RESEARCH.md = 1.5 MB** — Asset valioso pero potencialmente duplicado o superado
- **Branch master** — No migrado a main (inconsistencia con otros repos)
- **Sin README actualizado** — Describe energy-lab pero el proyecto fue cancelado

**Recomendaciones**:
- Definir el futuro del repo: migrar research a data-science-uncuyo, archivar, o reactivar
- Actualizar README para reflejar estado PAUSADO
- Migrar branch de master a main para consistencia
- Evaluar si RESEARCH.md tiene contenido unico no cubierto por estudio-0003 outputs

---

### 4. cannabis-inteligencia

**Categoria**: PROYECTO | **Estado**: INACTIVO (BOOTSTRAP) | **Prioridad**: LOW | **Owner**: BOTARDO_OS (bautiarmanicode)

**URL**: https://github.com/bautiarmanicode/cannabis-inteligencia
**Lenguaje principal**: N/A (Markdown)
**Tamano**: 16 KB
**Ultimo commit**: 2026-04-16 — "BOTARDO OS: DASHBOARD.md + GOALS.md creados"
**Total archivos**: 19
**Branch**: master

**Descripcion**: Repo scaffold para proyecto de cannabis + automatizacion/inteligencia artificial. BOTARDO OS booteo la estructura basica en abril 2026 con roadmap, board y sistema .botardo/. Existe un ROADMAP_PROJECT.md detallado de 4 fases (diseno, adquisicion, armado, automatizacion) con proyeccion de ROI 733%, pero cero contenido real fue producido. Todos los departamentos estan en 0 archivos. La instancia cannabis-1 esta pausada en migracion con 0 ciclos ejecutados. El repo pertenece a la cuenta bautiarmanicode y esta en estado de bootstrap puro.

**Estructura**:
```
cannabis-inteligencia/
  README.md                   # Auto-generado por BOTARDO OS
  00_INDEX.md                 # Indice del proyecto
  01_AI_INSIGHTS.md           # Insights de IA (vacio)
  ROADMAP.md                  # Roadmap general
  ROADMAP_PROJECT.md          # Roadmap R&D detallado
  BOARD.md                    # 7 tareas, 29% completado
  GOALS.md                    # VACIO
  STATUS.md                   # Status del proyecto
  Cannabis/                   # Carpeta Obsidian vault
    00_INDEX.md
    00_Estrategia/00_INDEX.md
  _system/                    # Sistema BOTARDO OS
  .botardo/                   # Infraestructura BOTARDO OS
    PROJECT.md
    cannabis-1/ (TASKS.md, handoff.md)
```

**Archivos clave**:
- README.md: Auto-generado por BOTARDO OS, describe estado "Low activity"
- ROADMAP_PROJECT.md: Plan R&D detallado con grow tent 80x80, LED 240W, ROI 733%
- GOALS.md: VACIO
- BOARD.md: 7 tareas, 29% completado

**Ultimos 5 commits**:
1. d65b521 — BOTARDO OS: DASHBOARD.md + GOALS.md creados
2. 5a9e9ee — feat: bootstrap .botardo/ — arquitectura BOTARDO OS v2
3. 965d637 — ROADMAP.md — Roadmap for cannabis-inteligencia
4. 5e69008 — BOARD.md — Task board for cannabis-inteligencia
5. 43c9e64 — Auto-Maintainable: STATUS.md generated by BOTARDO OS

**Contenido detallado**:
El repo es un scaffold puro sin contenido ejecutivo. La unica actividad real fue el bootstrapping por BOTARDO OS que creo la estructura basica: README auto-generado, roadmap, board, y sistema .botardo/. El ROADMAP_PROJECT.md contiene un plan R&D ambicioso de 4 fases para cultivo indoor automatizado con monitoreo por IA, pero no hay ningun codigo, sensor, ni dato producido. La instancia cannabis-1 nunca ejecuto ciclos (0 ciclos, PAUSADA en migracion). El repo parece estar en espera de activacion del CEO, sin actividad desde abril 2026. Notablemente, el repo pertenece a la cuenta bautiarmanicode (no frog-estudio directamente).

**Problemas detectados**:
- **Sin contenido real** — Solo estructura scaffold, cero ejecucion
- **Branch master** — Inconsistencia con convencion main
- **Pertenece a bautiarmanicode** — No es un repo de frog-estudio directamente
- **Sin HANDOFF.md** propio en raiz
- **GOALS.md vacio** — Sin objetivos definidos

**Recomendaciones**:
- Definir si el proyecto sigue vigente o se archiva
- Si se activa, crear HANDOFF.md y definir GOALS
- Si no, mover a estado ARCHIVE

---

### 5. botardo-os

**Categoria**: TOOL | **Estado**: ACTIVO | **Prioridad**: HIGH | **Owner**: BOTARDO_OS (bautiarmanicode) — **READ-ONLY PARA MI**

**URL**: https://github.com/bautiarmanicode/botardo-os
**Lenguaje principal**: Python/Markdown/TypeScript
**Tamano**: 11694 KB (~11.4 MB)
**Ultimo commit**: 2026-05-14 — "Merge branch 'main'"
**Total archivos**: 1758
**Branch**: main

**Descripcion**: El cerebro central del ecosistema BOTARDO OS. Es un sistema operativo para agentes autonomos que orquesta multiples proyectos via Discord + Git + Markdown + Cron. El repo contiene toda la documentacion de arquitectura (brain/), un dashboard web Next.js 16 (dashboard/), templates de agentes, patrones de R&D (22 documentados), un catalogo de 56+ personalidades (The Agency), boot prompts y SOUL cards (sandbox/), y un sistema de misiones IDA y VUELTA para coordinar sandboxes. Es el hub que conecta al CEO con multiples proyectos (VISTTA LAB, Musica, Gaming, Fanvue, Estudios).

**Estructura**:
```
botardo-os/
  README.md                   # Documentacion completa del sistema
  _CRON.md                    # CRON del hub central
  _CONTEXT.md                 # Contexto del proyecto
  _LOG.md                     # Log de operaciones
  .env                        # Variables de entorno
  brain/                      # Cerebro del sistema (30+ archivos)
    PRINCIPIOS.md             # 10 leyes inmutables
    NAVEGACION.md             # Mapa de 540 archivos
    ARCHITECTURE.md           # Arquitectura v3.4
    CRON_MODEL.md             # Modelo de ejecucion v2.0
    CRON_INDEX.md             # Registro de CRONs
    ECOSYSTEM_STRUCTURE.md    # Proyectos, cuentas, slots
    GOALS.md                  # Objetivos y KPIs
    ORDERS.md                 # Ordenes de self-improvement
    MISIONES/                 # Misiones por cuenta (IDA+VUELTA)
    personas/                 # The Agency (56+ personalidades)
    TEMPLATES/                # Plantillas vivas
    ARKER_CRONS/              # CRONs de otros sandboxes
  dashboard/                  # Web app Next.js 16
    src/app/                  # Paginas (brain, crons, infra, kpis, etc.)
    src/components/           # Sidebar, markdown, toast
    public/data/              # dashboard.json
  r&d/                        # Investigacion y desarrollo
    patterns/                 # 22 patrones documentados
    archive/                  # Docs legacy (incl. SANDMAN)
    vault/                    # Frameworks de referencia
  sandbox/                    # Boot prompts y SOUL cards
  templates/                  # Agent templates (L0, L1, L2)
  incubation/                 # Skills en incubacion
  registry/                   # Registros del ecosistema
  _review/                    # Referencia historica (no editar)
```

**Archivos clave**:
- README.md: Documentacion completa del sistema — 570 lineas describiendo arquitectura, leyes, CRONs, infraestructura, patrones y roadmap
- _CRON.md: CRON del hub central con T01-T07 (sistema nervioso), P01 (auditoria completada), C01 (vacio)
- _CONTEXT.md: Identidad, reglas, estructura post-audit, issues detectados
- _LOG.md: Historial de operaciones del hub

**Ultimos 5 commits**:
1. 22a499d — Merge branch 'main'
2. b9ce6fe — sandbox UUID
3. 70e80eb — feat: AGENT_ repo model v2.0 — 1 sandbox = 1 repo
4. 04b8064 — sandbox UUID
5. cafaea2 — nav: actualizar NAVEGACION v1.1

**Contenido detallado**:
BOTARDO OS es el proyecto mas activo y complejo de la cuenta bautiarmanicode. Con 1758 archivos y 540+ documentos Markdown, constituye el cerebro evolutivo que orquesta todo el ecosistema de agentes autonomos del CEO. El sistema opera bajo 10 leyes inmutables donde el principio fundamental es "el sistema PROPONE, el CEO DISPONE" — nada se ejecuta sin firma del CEO.

La arquitectura se organiza en 3.5 capas: CAPA 1 (Orquestador via Discord), CAPA 2 (CRON Loops que ejecutan tareas en sandbox), CAPA 2.5 (Evolucion via BOTARDO-AGENCY que propone mejoras sin auto-aplicarlas), y CAPA 3 (Web On-Demand para tareas pesadas). Actualmente tiene 1 CRON activo (BOTARDO-DEV, Job 127122 cada 2h) y 11 CRONs planificados sin motor. El dashboard web (Next.js 16) se auto-deploya via Vercel.

El hub central gestiona 6 proyectos: BOTARDO OS (hub), VISTTA LAB (peluqueria), Musica, Gaming, Fanvue Ops y Estudios. El CEO opera desde 9 cuentas Google y 7 cuentas GitHub con ~27 slots de sandbox disponibles. El sistema esta en Fase 2 (CAPA 2) del roadmap, con la Fase A de inventario en progreso.

**Problemas detectados**:
- **botardo-os/ es un subdirectorio que DUPLICA el repo** — 432 archivos cruzados
- **.env commiteado en raiz** — Contiene DATABASE_URL local
- **22 patrones documentados** — Existen pero no todos implementados

**Recomendaciones**:
- Limpiar subdirectorio botardo-os/ duplicado
- Mover .env a .gitignore
- Continuar Fase A del roadmap (inventario de sandboxes)

---

## REPOS.md — Mis Repos (para guardar en mi AGENT_)

> Este archivo se guarda como REPOS.md en la raiz del repo AGENT_. Lo leo cada ciclo para saber donde trabajar.

| # | Repo | URL | Rol (leo/escribo) | Tipo | Descripcion |
|---|------|-----|-------------------|------|-------------|
| 1 | AGENTS_estudios | https://github.com/frog-estudio/AGENTS_estudios | ESCRIBO | AGENT | Mi casa — brain, ordenes, handoffs, reportes |
| 2 | data-science-uncuyo | https://github.com/frog-estudio/data-science-uncuyo | ESCRIBO | PROYECTO | Carrera DS UNCuyo — HANDOFF_REPORTER.md |
| 3 | data-science | https://github.com/frog-estudio/data-science | LEO | PROYECTO | Historico energy-lab (PAUSADO) |
| 4 | cannabis-inteligencia | https://github.com/bautiarmanicode/cannabis-inteligencia | LEO | PROYECTO | Scaffold cannabis (BOOTSTRAP) |
| 5 | botardo-os | https://github.com/bautiarmanicode/botardo-os | LEO (READ-ONLY) | TOOL | Hub central BOTARDO OS — NUNCA escribo |

---

## Acciones Recomendadas para el CEO

### Urgentes

| # | Accion | Repo | Razon |
|---|--------|------|-------|
| 1 | Desactivar Job 130360 (estudio-0003 worker) | data-science-uncuyo | Programa completo 70/70, el cron sigue corriendo cada 2h sin efecto |
| 2 | Definir futuro de data-science | data-science | Repo PAUSADO con 391 commits legacy, CEO no definio nueva direccion |
| 3 | Definir futuro de cannabis-inteligencia | cannabis-inteligencia | Repo BOOTSTRAP sin contenido real desde abril 2026 |

### Mejoras

| # | Accion | Repo | Razon |
|---|--------|------|-------|
| 1 | Agregar README.md a AGENTS_estudios | AGENTS_estudios | Repo sin descripcion visible en GitHub |
| 2 | Limpiar _review/skills/ (~69 MB) | data-science-uncuyo | Skills del sistema ocupan 67% del repo |
| 3 | Migrar branch master a main | data-science, cannabis-inteligencia | Inconsistencia con convencion main |
| 4 | Actualizar README de data-science | data-science | Describe energy-lab pero proyecto fue cancelado |
| 5 | Evaluar contenido unico de RESEARCH.md | data-science | Verificar si hay valor no cubierto por estudio-0003 |

### Archivar / Borrar

| # | Repo | Razon | Destino |
|---|------|-------|---------|
| 1 | cannabis-inteligencia | Sin contenido real en 4+ semanas | Archive o eliminar |
| 2 | _review/skills/ en data-science-uncuyo | ~69 MB de skills globales no relacionadas con estudio | Limpiar del repo |

---

## Memoria para Otros Agentes

### Que hay en esta cuenta
La cuenta frog-estudio tiene 4 repos dedicados al proyecto de Estudios del ecosistema BOTARDO OS. El repo principal es data-science-uncuyo con un programa de estudio automatizado completo (70/70 outputs de DS para la carrera UNCuyo), apoyado por un brain repo (AGENTS_estudios) y un repo historico (data-science) con investigacion DS legacy. Tambien hay acceso al repo botardo-os de la cuenta bautiarmanicode que es el hub central del ecosistema.

### Que puede usar otro agente
- data-science/ciencia_datos/RESEARCH.md — 28,077 lineas de investigacion DS (ML, DL, NLP, MLOps)
- data-science/ciencia_datos/deliverables/ — 14 deliverables (study plans, SQL workbooks, interview prep)
- data-science-uncuyo/_review/estudio-1/output/ — ~90 outputs de estudio generados
- AGENTS_estudios/brain/HANDOFF.md — Panorama detallado de los repos con problemas detectados

### Que NO tocar
- AGENTS_estudios — Escritura exclusiva de estudios-reporter. Otros agentes: read-only.
- data-science-uncuyo/HANDOFF_REPORTER.md — Escritura exclusiva de estudios-reporter.
- botardo-os — Escritura exclusiva de BOTARDO_OS (bautiarmanicode). Nunca escribir desde otra sandbox.

### Quien escribe en que

| Repo | Sandbox owner | Solo lectura para |
|------|-------------|-------------------|
| AGENTS_estudios | estudios-reporter (YO) | Todos los demas |
| data-science-uncuyo | estudios-reporter (YO) | Todos los demas |
| data-science | estudios-reporter / BOTARDO_OS | Todos los demas |
| cannabis-inteligencia | BOTARDO_OS (bautiarmanicode) | Todos los demas |
| botardo-os | BOTARDO_OS (bautiarmanicode) | Todos los demas |

### Contacto
- CEO: 34U70 (Discord UID: 819724611737878550)
- Canal: #estudios-reporter (Discord server del CEO)
- Proyecto: Estudios DATA — Tecnicatura Ciencia de Datos UNCuyo

---

*report_github.md — frog-estudio — Generado por estudios-reporter — 2026-05-15T03:30:00-03:00*

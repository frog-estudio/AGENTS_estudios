# REPORTE GITHUB — frog-estudio

> Generado: 2026-05-15T03:04:00+08:00
> Cuenta: frog-estudio
> Email: z@container
> Total repos: 5 (4 propios + 1 externo con acceso)
> Sandbox: estudios-reporter (Reporter 4h + Worker 1h)
> Canal: Discord / #estudios-reporter
> Mi repo AGENT: AGENTS_estudios
> Modelo: CRON Model v2.0 (Reporter + Worker dual sandbox)

---

## Resumen Ejecutivo

| Metrica | Valor |
|---------|-------|
| Total repos (frog-estudio) | 4 |
| Repos activos | 2 (data-science-uncuyo, AGENTS_estudios) |
| Repos inactivos | 1 (data-science — paused) |
| Repos bootstrap | 1 (cannabis-inteligencia) |
| Sin clasificar | 0 |
| Ultima actividad | 2026-05-12 06:17 UTC (data-science-uncuyo) |
| Tamaño total (frog-estudio) | ~54 MB |
| Repo externo con acceso | botardo-os (bautiarmanicode, 10.6 MB, private) |
| Mi repo AGENT | AGENTS_estudios (EXCLUSIVO — solo yo escribo) |

---

## Mi Posesion — Repos donde YO escribo

> CRÍTICO: Solo pusheo a estos repos. Los demás son read-only o de otra sandbox.

| Repo | Rol | Qué hago ahí | Frecuencia de push |
|------|-----|-------------|-------------------|
| AGENTS_estudios | Mi casa | brain/ORDERS.md, brain/HANDOFF.md, brain/STATE.md, report_github.md, REPOS.md | Cada ciclo (1h worker / 4h reporter) |
| data-science-uncuyo | Reporter output | HANDOFF_REPORTER.md — reporte consolidado de los 3 repos monitoreados | Cada 4h (solo si hay cambios) |

---

## Mapa de Repos — Toda la cuenta frog-estudio

| # | Repo | Categoria | Estado | Owner | Prioridad | Ultimo commit | Archivos | Lenguaje principal | Funcion |
|---|------|-----------|--------|-------|-----------|---------------|----------|-------------------|---------|
| 1 | AGENTS_estudios | AGENT | ACTIVO | YO (estudios-reporter) | HIGH | 2026-05-07 | 5 | Markdown | Brain del worker — ordenes, handoffs, memoria |
| 2 | data-science-uncuyo | PROYECTO | ACTIVO | YO (estudios-reporter) | HIGH | 2026-05-12 | 1049 | Markdown | Estudio DS UNCuyo — 70 outputs, notas carrera |
| 3 | data-science | PROYECTO | INACTIVO | YO (estudios-reporter) | MEDIUM | 2026-05-04 | 97 | Markdown | Repo historico — energy-lab cancelado, paused |
| 4 | cannabis-inteligencia | EXPERIMENTO | BOOTSTRAP | NADIE | LOW | 2026-04-16 | 19 | Markdown | Scaffold cannabis — sin contenido real |

## Repo Externo con Acceso

| # | Repo | Cuenta | Categoria | Estado | Owner | Acceso |
|---|------|--------|-----------|--------|-------|--------|
| 5 | botardo-os | bautiarmanicode | SISTEMA | ACTIVO | BOTARDO_OS | READ-ONLY (NUNCA escribir) |

---

## Detalle por Repo

### 1. AGENTS_estudios

**Categoria**: AGENT | **Estado**: ACTIVO | **Prioridad**: HIGH | **Owner**: YO (estudios-reporter)

**URL**: https://github.com/frog-estudio/AGENTS_estudios
**Lenguaje principal**: Markdown | **Tamaño**: 4 KB
**Ultimo commit**: 2026-05-07 — "worker: reporte inicial — 4 repos auditados, orden 001 DONE"
**Total archivos**: 3 (antes de este reporte)

**Descripcion**: Repo cerebro del worker de estudios. Contiene la cola de ordenes del CEO (brain/ORDERS.md), los reportes consolidados de handoff entre sesiones (brain/HANDOFF.md), y el estado del worker (brain/STATE.md). Este es el UNICO repo donde escribo archivos de operacion — report_github.md, REPOS.md, y actualizaciones de brain/. Ninguna otra sandbox debe escribir aqui.

**Estructura**:
```
AGENTS_estudios/
  brain/
    ORDERS.md    — Cola de ordenes del CEO (1 orden DONE)
    HANDOFF.md   — Reporte consolidado de todos los repos
    STATE.md     — Estado del worker (ACTIVE)
  report_github.md  — Este reporte
  REPOS.md          — Mapa de repos
```

**Archivos clave**:
- README.md: No existe
- brain/ORDERS.md: 1 orden (001 DONE), sin pendientes
- brain/HANDOFF.md: Reporte detallado de 4 repos con estructura, contenido y problemas
- brain/STATE.md: ACTIVE, 1 orden completada, 0 errores

**Ultimos 5 commits**:
1. 2026-05-07 — worker: reporte inicial — 4 repos auditados, orden 001 DONE
2. 2026-05-07 — initial structure

**Contenido detallado**:
Este repo es minimalista por diseño — funciona como el cerebro operativo del worker de estudios. La orden 001 (auditoria inicial de todos los repos de frog-estudio) fue completada el 2026-05-07, generando un HANDOFF.md exhaustivo con el panorama completo de los 4 repos de la cuenta. Desde entonces, no hay ordenes pendientes — el worker ejecuta ticks cada 1h buscando PENDING orders y el reporter ejecuta ticks cada 4h monitoreando cambios. El estado es ACTIVE con 0 errores. Con este reporte, el repo pasa de 3 a 5 archivos (agregando report_github.md y REPOS.md).

**Problemas detectados**:
- Falta README.md explicando el proposito del repo
- Falta estructura base completa (memory/, proposals/) segun AGENT_REPO_STRUCTURE.md v2.0

**Recomendaciones**:
- Agregar README.md con descripcion del proposito del repo
- Crear directorio memory/ para conocimiento persistente entre sesiones

---

### 2. data-science-uncuyo

**Categoria**: PROYECTO | **Estado**: ACTIVO | **Prioridad**: HIGH | **Owner**: YO (estudios-reporter)

**URL**: https://github.com/frog-estudio/data-science-uncuyo
**Lenguaje principal**: Markdown | **Tamaño**: 51 MB
**Ultimo commit**: 2026-05-12 06:17 UTC — "reporter: tick 14:14 — reorg PRE-BOTARDO OS v3 detectada"
**Total archivos**: 1049 | **Branch**: main (publico)

**Descripcion**: Repo principal de la Tecnicatura Universitaria en Ciencia de Datos (ITU UNCUYO). Es el repositorio mas grande y activo de la cuenta frog-estudio. Contiene tres tipos de contenido: (1) notas reales del CEO para la carrera en notas_carrera/, (2) 70 outputs generados por el pipeline Botardo Studio en .botardo/estudio-0003/output/ cubriendo 10 rotaciones tematicas de DS, y (3) archivos de infraestructura del sistema de reporteo (_TICK.md, _CONTEXT.md, _LOG.md, HANDOFF_REPORTER.md). Ademas contiene un directorio _review/ con 862 archivos legacy movidos durante la auditoria PRE-BOTARDO OS.

**Estructura**:
```
data-science-uncuyo/                    (1049 archivos, 51 MB)
  .botardo/                             (82 archivos — infraestructura)
    estudio-0003/                       (72 archivos — PIPELINE COMPLETO 70/70)
      output/                           (70 outputs ES1-ES7 x 10 rotaciones)
      handoff.md                        (estado FINALIZADO)
    AGENTS.md, CONTEXT.md, CRON_*.md    (config BOTARDO OS)
  _review/                              (862 archivos — legacy movidos, NO BORRAR)
    _bot_legacy/estudio_carrera/        (~136 archivos — simulacros, exams)
    skills/                             (~69 MB — 47 skills del sistema)
    estudio-1/                          (72 archivos — legacy)
    estudio-2/                          (38 archivos — legacy)
    estudio-3/                          (48 archivos — legacy)
    botardo_output/                     (27 archivos — outputs root legacy)
    search_cache/                       (15 JSON — cache busquedas)
  notas_carrera/                        (96 archivos — contenido real del CEO)
    ingreso_2026b/                      (matematica, CL, vocacional)
    plan_estudios/                      (plan general, trackers)
    semestres/                          (estructura 4 semestres)
  Raiz                                  (_TICK.md, _CONTEXT.md, HANDOFF_REPORTER.md, etc.)
```

**Archivos clave**:
- README.md: Documentacion completa del repo
- _CONTEXT.md: Identidad del TICK, reglas, estructura
- _LOG.md: Registro de operaciones — onboarding, auditorias PRE-BOTARDO OS
- HANDOFF_REPORTER.md: Reporte consolidado (tick #25)
- .botardo/estudio-0003/handoff.md: Estado FINALIZADO 70/70

**Ultimos 5 commits**:
1. 2026-05-12 — reporter: tick 14:14 — reorg PRE-BOTARDO OS v3 detectada
2. 2026-05-12 — orden: reorganizacion pre-BOTARDO OS v3 — legacy a _review
3. 2026-05-12 — reporter: tick 10:14 — PROGRAMA COMPLETO 70/70
4. 2026-05-12 — handoff: hash C70 ES7
5. 2026-05-12 — Ciclo 70 ES7 tutorial_dqn_inventario — PROGRAMA COMPLETO 70/70

**Contenido detallado**:
Este repo alcanzo un milestone importante el 2026-05-12: el programa de estudio-0003 se completo con 70/70 outputs. Las 10 rotaciones tematicas cubrieron: DS General/Tabular, Argentina-LatAm DS, Feature Engineering+Timeseries, Data-Centric AI+Fairness, Python Avanzado+SWE, Anomaly Detection+AutoML, FinTech Quant Finance, Sports Analytics, Computer Vision, y Reinforcement Learning. Cada rotacion genero 7 outputs (ES1 datasets, ES2 papers, ES3 ejercicio, ES4 herramientas, ES5 cheatsheet, ES6 cursos MOOC, ES7 tutorial). El pipeline fue gestionado por 4 instancias previas de Botardo (estudio-1 a estudio-3, ahora movidas a _review/) antes de ser consolidado en estudio-0003. La auditoria PRE-BOTARDO OS (3 versiones) reorganizo el repo completamente. El reporter monitorea cada 4h generando HANDOFF_REPORTER.md.

**Problemas detectados**:
- Job 130360 (estudio-0003 worker, cada 2h) sigue activa — requiere desactivacion CEO (HIGH)
- _review/ tiene 862 archivos pendientes de revision CEO (MEDIUM)
- README menciona "69/70 outputs" pero ya son 70/70 (LOW)

**Recomendaciones**:
- Desactivar Job 130360 — programa completo
- CEO debe decidir sobre _review/ (mantener/archivar/borrar)
- Actualizar README.md para reflejar 70/70

---

### 3. data-science

**Categoria**: PROYECTO | **Estado**: INACTIVO (paused) | **Prioridad**: MEDIUM | **Owner**: YO (estudios-reporter)

**URL**: https://github.com/frog-estudio/data-science
**Lenguaje principal**: Markdown | **Tamaño**: 1.2 MB
**Ultimo commit**: 2026-05-04 — "handoff: estudio-0003 backup migracion"
**Total archivos**: 97 | **Branch**: master (privado)

**Descripcion**: Repo historico con dos vidas: primero como energy-lab (cancelado por CEO, ~390 commits legacy), luego repropuesto para estudio-0003. Los outputs se migraron a data-science-uncuyo, dejando este repo paused. Contiene material de investigacion DS valioso (RESEARCH.md con 118 secciones, 1.5 MB) y 14 deliverables educativos.

**Estructura**:
```
data-science/                          (97 archivos, 1.2 MB)
  .botardo/                            (infraestructura BOTARDO OS)
    estudio-0003/                      (handoff backup — sin outputs)
    output/                            (18 outputs legacy energy-lab)
  ciencia_datos/                       (contenido educativo)
    RESEARCH.md                        (118 secciones, 1.5 MB)
    deliverables/                      (14 entregables)
    trackers/, REPORTES/, D*.md        (planes, roadmaps, briefs)
  Raiz                                  (ROADMAP.md, STATUS.md, DASHBOARD.md)
```

**Archivos clave**:
- README.md: Documentacion de energy-lab (desactualizada)
- ciencia_datos/RESEARCH.md: 28,077 lineas de investigacion DS
- TASKS.md: Tareas del proyecto
- HANDOFF_estudio-0003.md: Handoff backup

**Ultimos 5 commits**:
1. 2026-05-04 — handoff: estudio-0003 backup migracion
2. 2026-05-04 — estudio-0003: initial setup
3. 2026-04-28 — CEO: crons desactivadas, estado paused
4. 2026-04-28 — HB cycle 86: SILENCIO
5. 2026-04-28 — HB cycle 85: SILENCIO

**Contenido detallado**:
Este repo fue el hogar del proyecto energy-lab (~390 commits de investigacion sobre monitoreo energetico, CAMMESA, dashboards Grafana). Cancelado por CEO el 2026-04-18. Repropuesto para estudio-0003 pero migrado a data-science-uncuyo. El contenido mas valioso: RESEARCH.md (118 secciones de ML, DL, NLP, timeseries, MLOps) y 14 deliverables (guias de estudio, planes de carrera, SQL workbooks). Sin actividad productiva ni monitoreo activo.

**Problemas detectados**:
- README.md describe energy-lab cancelado — desactualizado
- Repo "zombie" sin actividad productiva
- estudio-0003 handoff backup redundante
- No tiene HANDOFF.md propio

**Recomendaciones**:
- Decidir si archivar, repurponer, o mantener
- Mover RESEARCH.md y deliverables a data-science-uncuyo si se preservan

---

### 4. cannabis-inteligencia

**Categoria**: EXPERIMENTO | **Estado**: BOOTSTRAP | **Prioridad**: LOW | **Owner**: NADIE

**URL**: https://github.com/frog-estudio/cannabis-inteligencia
**Lenguaje principal**: Markdown | **Tamaño**: 16 KB
**Ultimo commit**: 2026-04-16 — "BOTARDO OS: DASHBOARD.md + GOALS.md creados"
**Total archivos**: 19 | **Branch**: master (privado)

**Descripcion**: Repo scaffold para proyecto de cannabis con automatizacion. BOTARDO OS booteo estructura (ROADMAP, BOARD, DASHBOARD, GOALS, STATUS). Existe roadmap detallado de 4 fases (grow tent 80x80, LED 240W, ROI 733%). Sin contenido real producido: GOALS.md vacio, departamentos en 0, instancia cannabis-1 pausada. 29 dias sin actividad.

**Estructura**:
```
cannabis-inteligencia/                 (19 archivos, 108 KB)
  .botardo/cannabis-1/                 (instancia pausada, 0 ciclos)
  Cannabis/                            (Obsidian vault scaffold)
  _system/                             (activity log, pipeline status)
  Raiz                                  (ROADMAP, BOARD, DASHBOARD, GOALS, STATUS)
```

**Archivos clave**:
- README.md: Auto-generado por BOTARDO OS
- ROADMAP_PROJECT.md: Plan R&D detallado — 4 fases
- BOARD.md: 7 tareas, 29% completado
- GOALS.md: VACIO

**Ultimos 5 commits**:
1. 2026-04-16 — BOTARDO OS: DASHBOARD.md + GOALS.md creados
2. 2026-04-15 — feat: bootstrap .botardo/ — arquitectura BOTARDO OS v2
3. 2026-04-14 — ROADMAP.md — Roadmap for cannabis-inteligencia
4. 2026-04-14 — BOARD.md — Task board for cannabis-inteligencia
5. 2026-04-06 — Auto-Maintainable: STATUS.md generated by BOTARDO OS

**Contenido detallado**:
Proyecto en fase de planificacion pura. Roadmap ambicioso: planta indoor automatizada con sensores, riego, analisis Python. ROI proyectado 733% en 6 meses. Ejecucion cero: no hay sensores, codigo, datos reales, ni imagenes de progreso. Instancia cannabis-1 nunca arranco ciclos. Necesita decision del CEO: activar, archivar, o cancelar.

**Problemas detectados**:
- 29 dias sin actividad
- GOALS.md vacio, sin HANDOFF.md
- Sin contenido real producido

**Recomendaciones**:
- CEO debe decidir: activar, archivar, o eliminar
- Si activa: definir GOALS, configurar cron, crear HANDOFF.md

---

### 5. botardo-os (EXTERNO — READ-ONLY)

**Categoria**: SISTEMA | **Estado**: ACTIVO | **Prioridad**: N/A | **Owner**: BOTARDO_OS (bautiarmanicode)

**URL**: https://github.com/bautiarmanicode/botardo-os
**Lenguaje principal**: Python | **Tamaño**: 10.6 MB
**Ultima actividad**: 2026-05-14 19:00 UTC

**Descripcion**: Cerebro evolutivo de BOTARDO OS. Repo externo de bautiarmanicode. Solo acceso de lectura. NUNCA escribir aqui.

---

## Acciones Recomendadas para el CEO

### Urgentes

| # | Accion | Repo | Razon |
|---|--------|------|-------|
| 1 | Desactivar Job 130360 (estudio-0003 worker) | data-science-uncuyo | Programa completo 70/70 — consume recursos sin proposito |
| 2 | Decidir futuro de _review/ (862 archivos) | data-science-uncuyo | Auditoria movio legacy — CEO debe decidir mantener/archivar/borrar |

### Mejoras

| # | Accion | Repo | Razon |
|---|--------|------|-------|
| 1 | Agregar README.md | AGENTS_estudios | Falta documentacion del cerebro |
| 2 | Actualizar README (69/70 -> 70/70) | data-science-uncuyo | Desactualizado |
| 3 | Mover RESEARCH.md a data-science-uncuyo | data-science | Preservar contenido valioso |
| 4 | Definir GOALS.md | cannabis-inteligencia | Sin direccion definida |

### Archivar / Borrar

| # | Repo | Razon | Destino |
|---|------|-------|---------|
| 1 | _review/skills/ (69 MB) | Skills del sistema, no del proyecto | Borrar |
| 2 | data-science | Repo zombie desde migracion | ARCHIVE |
| 3 | cannabis-inteligencia | 29 dias sin actividad | ARCHIVE |

---

## Memoria para Otros Agentes

### Que hay en esta cuenta
La cuenta frog-estudio tiene 4 repos enfocados en educacion y ciencia de datos. El repo principal (data-science-uncuyo) contiene 70 outputs de un programa completo de estudio DS (10 rotaciones x 7 etapas), notas de carrera reales del CEO, y contenido legacy de instancias previas.

### Que puede usar otro agente
- data-science-uncuyo (publico): 70 outputs educativos en .botardo/estudio-0003/output/
- data-science-uncuyo (publico): notas_carrera/ con planes de estudio y trackers
- data-science-uncuyo (publico): HANDOFF_REPORTER.md con estado consolidado

### Que NO tocar
- AGENTS_estudios: SOLO estudios-reporter escribe aqui
- .botardo/ en cualquier repo: Infraestructura BOTARDO OS
- _review/ en data-science-uncuyo: CEO decide su destino
- botardo-os: Repo de bautiarmanicode — NUNCA escribir

### Quien escribe en que

| Repo | Sandbox owner | Solo lectura para |
|------|-------------|-------------------|
| AGENTS_estudios | YO (estudios-reporter) | Todos los demas |
| data-science-uncuyo | YO (estudios-reporter) | Todos los demas |
| data-science | YO (estudios-reporter) | Todos los demas |
| cannabis-inteligencia | NADIE | Todos |
| botardo-os (bautiarmanicode) | BOTARDO_OS | Yo (read-only) |

### Contacto
- CEO: Bauti (34U70)
- Canal Discord: #estudios-reporter
- Cuenta GitHub: frog-estudio
- Cuenta principal: bautiarmanicode

---
*report_github.md — frog-estudio — Generado por estudios-reporter — 2026-05-15T03:04:00+08:00*

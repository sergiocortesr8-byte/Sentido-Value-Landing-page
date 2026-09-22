---
name: analisis-embudo-conversion
description: "Diagnostica el embudo de ventas de Sentido Value (DM high-ticket en Instagram): mide dónde se caen los prospectos entre el anzuelo y el cierre, prioriza la fuga más grande y propone el arreglo con mayor impacto. Úsala cuando Sergio quiera saber en qué etapa está perdiendo ventas o revisar la salud del embudo."
allowed-tools: Read Write Glob
metadata:
  author: Imperio Digital (adaptado para Sentido Value)
  version: "2.0-sentidovalue"
---

# Análisis de Embudo de Conversión — Sentido Value

Versión adaptada al embudo real de Sentido Value: **captación orgánica en Instagram → DM → llamada → venta de programa high-ticket ($297–$1.500 USD)**. Trabaja siempre junto al playbook **Closer de DMs** (las 6 fugas ya documentadas son el punto de partida del diagnóstico).

## Cuándo Usar Este Skill

- Saber en qué etapa del embudo se pierden más prospectos.
- Priorizar qué arreglar primero para acercarse a la meta de **US$15.000/mes**.
- Revisar la salud del embudo (semanal/mensual) y detectar degradación.
- Traducir las métricas de Instagram (Windsor) + las conversaciones de DM en un diagnóstico accionable.

**NO** la uses para: diseño de A/B tests, gestión de campañas de ads, ni redacción de mensajes (eso es el Closer de DMs / rol de ventas).

---

## Principio Fundamental

**ARREGLA LA FUGA MÁS GRANDE PRIMERO.** Una mejora de 10% en el peor punto de abandono supera una de 50% en un paso que ya convierte bien. En Sentido Value la fuga histórica #1 es el **agendamiento** (etapa "Sí a la llamada → Agenda confirmada"): empieza el diagnóstico ahí salvo que los datos digan otra cosa.

---

## El Embudo de Sentido Value (7 etapas)

| # | Etapa | Qué mide | Fase del Closer |
|---|-------|----------|-----------------|
| 1 | **Alcance → Anzuelo** | Personas que ven el contenido/ad y comentan "YO" o responden la historia | Top of funnel |
| 2 | **Anzuelo → DM responde** | De los que comentaron, cuántos entran a conversación en DM | Fase 1 (Apertura) |
| 3 | **DM → Discovery con dolor** | Cuántos llegan a expresar su meta + dolor real | Fase 2 |
| 4 | **Discovery → Calificado** | Con intención + presupuesto viable | Fase 3 |
| 5 | **Calificado → Agenda confirmada** | Con **día y hora fijados** (no solo "sí") | Fases 4–5 |
| 6 | **Agenda → Show (asiste)** | Cuántos llegan a la llamada | Fase 6 (pre-frame) |
| 7 | **Show → Venta** | Cierres del programa | Llamada de venta |

---

## Fase 1: Brief

Pide (o estima) por cada etapa:

| Entrada | Qué preguntar | Por defecto |
|---------|---------------|-------------|
| **Período** | "¿Qué rango de fechas cubren los datos?" | Últimos 30 días |
| **Volúmenes por etapa** | "¿Cuántos anzuelos, respuestas, discoveries, calificados, agendas, shows y ventas?" | Debe proveerse o estimarse |
| **Fuente de tráfico** | "¿Orgánico (historias/reels) o ads? ¿Mezcla?" | Orgánico |
| **Ticket promedio** | "¿Qué mezcla de $297 / $997 / $1.500 estás cerrando?" | Ver CLAUDE.md §7 |
| **Meta** | "Objetivo de ingresos y de nº de ventas del mes" | US$15.000/mes |
| **Sospechas** | "¿Qué etapa crees que está fallando?" | Agendamiento (histórico) |

**PUNTO DE CONTROL:** confirma el brief y los datos antes de continuar. Si faltan datos, ver §Recuperación.

---

## Fase 2: Mapear

Construye el embudo etapa por etapa con: **volumen absoluto**, **tasa de conversión entre etapas**, **tasa de abandono** (inversa) y **conversión acumulada**. Si vas a graficarlo, carga la skill `dataviz` y usa la marca navy/dorado.

### Benchmarks de referencia (DM high-ticket orgánico)

Rangos orientativos — **calíbralos con los datos reales de Sergio** apenas existan 2–3 meses de historia. No son benchmarks de web/e-commerce.

| Etapa | Conversión de referencia | Nota |
|-------|--------------------------|------|
| Anzuelo → DM responde | 60–85% | Muchos comentan pero no siguen la conversación |
| DM → Discovery con dolor | 40–60% | Depende de la calidad del primer mensaje (Fase 1) |
| Discovery → Calificado | 40–60% | Filtro de intención + presupuesto |
| Calificado → Agenda confirmada | 50–70% | **Fuga histórica de Sentido Value — vigilar** |
| Agenda → Show | 50–70% | Sube con pre-frame + recordatorio con dolor |
| Show → Venta | **25–30%** | Regla: si superas 40%, **sube precios** |

**Regla del oro (cash por agenda):** ingresos del mes ÷ nº de agendas. Si es menor al 30% del valor del programa, hay que mejorar cierre o ajustar precio.

**PUNTO DE CONTROL:** presenta el mapa y confirma que los números son correctos antes de analizar.

---

## Fase 3: Analizar

**1. Reporte de desempeño** — conversión y abandono por etapa, comparación vs. referencia (arriba/en/debajo), y **la fuga más grande** (mayor oportunidad absoluta, no solo mayor %).

**2. Diagnóstico de abandono** — para cada etapa débil, cruza con las **6 fugas del Closer** (CLAUDE.md §5) y da 3–5 hipótesis:
- **Anzuelo → DM:** primer mensaje con pregunta cerrada, respuesta tardía, anzuelo poco desafiante.
- **DM → Discovery:** no se llega al dolor real; se salta a vender; recurso soltado sin pregunta.
- **Discovery → Calificado:** no se pre-califica presupuesto; tiempo perdido en no-calificados.
- **Calificado → Agenda:** CTA permisivo ("¿te parece?"), "sí" sin fecha, precio deflectado al link, link soltado sin acompañar.
- **Agenda → Show:** sin pre-frame ni recordatorio; follow-up logístico y tardío.
- **Show → Venta:** objeciones no aisladas; sin check de temperatura; oferta no anclada a valor.

**3. Matriz de prioridad** (impacto × esfuerzo):

| Etapa | Abandono | Potencial | Esfuerzo | Prioridad |
|-------|----------|-----------|----------|-----------|

**4. Plan de acción** — top 3 arreglos por relación impacto/esfuerzo, recomendación concreta por arreglo (referida a la fase del Closer que lo corrige) y cómo medir que funcionó.

---

## Fase 4: Pulir

**Dashboard de monitoreo** (sugerido, marca navy/dorado): conversión por etapa semanal, línea de tendencia, y umbral de alerta por etapa. Alimentar la parte alta (alcance→anzuelo) con datos de Instagram vía Windsor.

**Cadencia de revisión:**
- **Semanal:** chequeo rápido de salud (agendas y shows de la semana).
- **Mensual:** análisis completo + recalibrar benchmarks con datos reales.
- **Trimestral:** ¿siguen siendo correctas las etapas y el ticket promedio para la meta de $15k?

---

## Anti-Patrones

- **Optimizar el anzuelo cuando la fuga está en el agendamiento** — más tráfico a un cierre roto solo multiplica la frustración.
- **Ignorar números absolutos** — 30% de cierre sobre 5 llamadas son pocas ventas; a veces el problema es volumen de agendas, no la tasa.
- **Métrica única** — la conversión global esconde la etapa específica que falla. Desglosa siempre.
- **Benchmarking sin contexto** — no compares con web/e-commerce; usa los rangos high-ticket y, cuando existan, los datos reales de Sergio.
- **Diagnosticar sin segmentar** — orgánico vs. ads, y por tipo de anzuelo (CTA directo vs. recurso), cuentan historias distintas.

---

## Recuperación

- **Sin datos:** ayuda a definir el tracking mínimo (contar por etapa: anzuelos, respuestas, discoveries, calificados, agendas, shows, ventas) y propone un plan de 30 días de recolección antes de analizar.
- **Etapas poco claras:** mapea desde lo que HACE el prospecto en cada paso, no el proceso interno.
- **Todo se ve mal:** prioriza sin piedad — una sola etapa, la de mayor impacto absoluto, y empieza ahí (probablemente el agendamiento).
- **Sergio quiere rediseñar todo el embudo:** primero exprime el embudo actual; rediseña solo tras agotar las ganancias rápidas.

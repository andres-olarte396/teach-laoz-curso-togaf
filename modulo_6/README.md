# Modulo 6: Planificacion y Migracion

> Phases E y F del ADM: Del analisis al roadmap.

---

## Descripcion

Este modulo cubre las fases E (Opportunities and Solutions) y F (Migration Planning) del ADM. Aprenderás a identificar work packages, consolidar gap analysis, priorizar proyectos y construir roadmaps de arquitectura con arquitecturas de transicion.

**Duracion**: 6 horas
**Nivel**: Avanzado
**Prerrequisitos**: Modulo 5 (Arquitectura Tecnologica)

---

## Objetivos de Aprendizaje

Al completar este modulo, seras capaz de:

- Identificar y evaluar work packages
- Consolidar gap analysis de todos los dominios
- Aplicar frameworks de priorizacion de proyectos
- Crear architecture roadmaps efectivos
- Disenar transition architectures

---

## Contenido

### Tema 6.1: Phase E - Opportunities and Solutions

| Subtema | Archivo | Tiempo |
|---------|---------|--------|
| 6.1.1 | [Evaluacion de Work Packages](6.1.1_evaluacion_work_packages.md) | 40 min |
| 6.1.2 | [Analisis de Brechas Consolidado](6.1.2_analisis_brechas_consolidado.md) | 45 min |

### Tema 6.2: Phase F - Migration Planning

| Subtema | Archivo | Tiempo |
|---------|---------|--------|
| 6.2.1 | [Priorizacion de Proyectos](6.2.1_priorizacion_proyectos.md) | 40 min |
| 6.2.2 | [Architecture Roadmap](6.2.2_architecture_roadmap.md) | 45 min |
| 6.2.3 | [Transition Architectures](6.2.3_transition_architectures.md) | 40 min |

---

## Artefactos Clave

### Architecture Roadmap

```
2026              2027              2028
Q1  Q2  Q3  Q4    Q1  Q2  Q3  Q4    Q1  Q2
|---|---|---|---| |---|---|---|---| |---|---|

[=== Foundation ===]
    [======= Commerce Platform =======]
              [======= Store Modernization =======]
    [=============== ERP Upgrade =================]
                        [=== Analytics ===]

*       *         *         *         *
|       |         |         |         |
v1.0  v2.0     v3.0     v4.0      Target
```

### Matriz de Priorizacion

| Proyecto | Valor | Riesgo | Costo | Score |
|----------|-------|--------|-------|-------|
| A | Alto | Bajo | Medio | 85 |
| B | Medio | Medio | Bajo | 70 |
| C | Alto | Alto | Alto | 60 |

---

## Ruta de Aprendizaje

```
6.1.1 Work Packages --> 6.1.2 Gap Consolidado
                              |
                              v
6.2.1 Priorizacion --> 6.2.2 Roadmap --> 6.2.3 Transiciones
```

---

## Tecnicas de Priorizacion

| Tecnica | Uso |
|---------|-----|
| Value vs Effort | Cuadrante simple |
| WSJF | SAFe, costo de delay |
| MoSCoW | Categorizacion |
| Scoring ponderado | Multiples criterios |

---

## Ejercicio Practico

1. Consolida los gaps de un proyecto en los 4 dominios
2. Identifica 5+ work packages potenciales
3. Prioriza usando al menos 2 tecnicas diferentes
4. Crea un roadmap de 2 anos con 2-3 transiciones

---

## Conexion con Otros Modulos

| Entrada desde | Salida hacia |
|---------------|--------------|
| Gap Analysis (todos los dominios) | Implementation Governance |
| Architecture Definition | Change Management |
| Stakeholder Priorities | Project Portfolio |

---

## Siguiente Modulo

[Modulo 7: Gobierno e Implementacion](../modulo_7/)

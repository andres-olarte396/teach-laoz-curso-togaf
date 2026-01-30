# Modulo 7: Gobierno e Implementacion

> Phases G y H del ADM: Asegurando el exito de la arquitectura.

---

## Descripcion

Este modulo cubre las fases G (Implementation Governance) y H (Architecture Change Management) del ADM. Aprenderás a establecer contratos de arquitectura, realizar compliance reviews y gestionar cambios arquitectonicos de manera efectiva.

**Duracion**: 5 horas
**Nivel**: Avanzado
**Prerrequisitos**: Modulo 6 (Planificacion y Migracion)

---

## Objetivos de Aprendizaje

Al completar este modulo, seras capaz de:

- Crear y gestionar Architecture Contracts
- Ejecutar Compliance Reviews sistematicos
- Identificar y evaluar triggers de cambio
- Implementar un proceso de gestion de cambios arquitectonicos
- Operar un Architecture Board efectivo

---

## Contenido

### Tema 7.1: Phase G - Implementation Governance

| Subtema | Archivo | Tiempo |
|---------|---------|--------|
| 7.1.1 | [Architecture Contract](7.1.1_architecture_contract.md) | 40 min |
| 7.1.2 | [Compliance Reviews](7.1.2_compliance_reviews.md) | 45 min |

### Tema 7.2: Phase H - Change Management

| Subtema | Archivo | Tiempo |
|---------|---------|--------|
| 7.2.1 | [Triggers de Cambio](7.2.1_triggers_cambio.md) | 35 min |
| 7.2.2 | [Proceso de Gestion de Cambios](7.2.2_proceso_gestion_cambios.md) | 45 min |

---

## Artefactos Clave

### Architecture Contract

```markdown
ARCHITECTURE CONTRACT
=====================
Proyecto: [Nombre]
Version: 1.0
Fecha: [Fecha]

PARTES
- Architecture Team (proveedor)
- Project Team (consumidor)

COMPROMISOS
- Cumplir estandares definidos
- Usar building blocks aprobados
- Participar en compliance reviews

ENTREGABLES
- Solution Architecture Document
- ADRs para decisiones mayores
- Compliance assessment pre-go-live
```

### Proceso de Cambio

```
SOLICITUD --> EVALUACION --> APROBACION --> IMPLEMENTACION
    ^                             |              |
    |                             v              v
    +-------- RECHAZO        BOARD         VALIDACION
```

---

## Ruta de Aprendizaje

```
7.1.1 Contract --> 7.1.2 Compliance
                        |
                        v
7.2.1 Triggers --> 7.2.2 Proceso Cambios
```

---

## Niveles de Aprobacion

| Nivel | Aprobador | Criterio |
|-------|-----------|----------|
| Menor | Domain Architect | < $10K, 1 sistema |
| Significativo | Chief Architect | $10K-$100K |
| Mayor | Architecture Board | > $100K, cross-domain |
| Estrategico | CIO/Steering | Transformacional |

---

## Ejercicio Practico

1. Redacta un Architecture Contract para un proyecto
2. Crea un checklist de compliance por dominio
3. Define los triggers de cambio para tu organizacion
4. Disena el proceso de RFC arquitectonico

---

## Conexion con Otros Modulos

| Entrada desde | Salida hacia |
|---------------|--------------|
| Migration Planning | Continuous Improvement |
| Architecture Roadmap | Architecture Repository |
| Transition Architectures | Updated Baseline |

---

## Siguiente Modulo

[Modulo 8: Building Blocks y Repositorio](../modulo_8/)

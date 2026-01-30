# Modulo 8: Building Blocks y Repositorio

> Gestionando los activos arquitectonicos de la empresa.

---

## Descripcion

Este modulo cubre los conceptos de building blocks (ABB y SBB), el catalogo empresarial, el Enterprise Continuum y la estructura del repositorio de arquitectura. Estos elementos son fundamentales para la reutilizacion y gobierno de la arquitectura.

**Duracion**: 5 horas
**Nivel**: Intermedio-Avanzado
**Prerrequisitos**: Modulo 7 (Gobierno e Implementacion)

---

## Objetivos de Aprendizaje

Al completar este modulo, seras capaz de:

- Diferenciar entre ABB y SBB
- Crear y gestionar un catalogo de building blocks
- Entender y aplicar el Enterprise Continuum
- Disenar la estructura del Architecture Repository
- Gobernar efectivamente los activos arquitectonicos

---

## Contenido

### Tema 8.1: Building Blocks

| Subtema | Archivo | Tiempo |
|---------|---------|--------|
| 8.1.1 | [ABB vs SBB](8.1.1_abb_vs_sbb.md) | 40 min |
| 8.1.2 | [Catalogo de Building Blocks](8.1.2_catalogo_building_blocks.md) | 45 min |

### Tema 8.2: Architecture Repository

| Subtema | Archivo | Tiempo |
|---------|---------|--------|
| 8.2.1 | [Enterprise Continuum](8.2.1_enterprise_continuum.md) | 40 min |
| 8.2.2 | [Estructura del Repositorio](8.2.2_estructura_repositorio.md) | 45 min |

---

## Conceptos Clave

### ABB vs SBB

```
ABB (Architecture Building Block)
+----------------------------------+
| "API Gateway"                    |
| - Definicion funcional           |
| - Requisitos, interfaces         |
| - Independiente de producto      |
+----------------------------------+
            |
            | se realiza como
            v
SBB (Solution Building Block)
+----------------------------------+
| "Kong Enterprise 3.4"            |
| - Producto especifico            |
| - Configuracion, deployment      |
| - Vendor, version                |
+----------------------------------+
```

### Enterprise Continuum

```
FOUNDATION <-----> COMMON <-----> INDUSTRY <-----> ORG-SPECIFIC

   TOGAF          Patrones        Retail           RetailCorp
   TRM            genericos       Reference        Custom
                                  Model

<-- Mas generico              Mas especifico -->
```

---

## Ruta de Aprendizaje

```
8.1.1 ABB vs SBB --> 8.1.2 Catalogo
                          |
                          v
8.2.1 Continuum --> 8.2.2 Repositorio
```

---

## Componentes del Repositorio

| Componente | Contenido |
|------------|-----------|
| Metamodel | Estructura de artefactos |
| Landscape | Baseline, Target, Transiciones |
| SIB | Estandares, guidelines |
| Reference Library | Arquitecturas de referencia |
| Governance Log | Decisiones, waivers |

---

## Ejercicio Practico

1. Define 5 ABBs para tu dominio de aplicacion
2. Mapea cada ABB a sus SBBs aprobados
3. Clasifica tus activos en el Enterprise Continuum
4. Disena la estructura de carpetas del repositorio

---

## Conexion con Otros Modulos

| Entrada desde | Salida hacia |
|---------------|--------------|
| Solution Architectures | Reutilizacion en proyectos |
| Governance Decisions | Architecture Capability |
| Change Requests | Updated Repository |

---

## Siguiente Modulo

[Modulo 9: Marco de Capacidad de Arquitectura](../modulo_9/)

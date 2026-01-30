# Modulo 5: Arquitectura Tecnologica

> Phase D del ADM: Infraestructura y Plataformas.

---

## Descripcion

Este modulo cubre la Phase D del ADM, enfocada en la arquitectura tecnologica. Incluye modelos de referencia, estandares tecnologicos, plataformas cloud y la consolidacion de trazabilidad entre todos los dominios.

**Duracion**: 6 horas
**Nivel**: Intermedio-Avanzado
**Prerrequisitos**: Modulo 4 (Arquitectura de SI)

---

## Objetivos de Aprendizaje

Al completar este modulo, seras capaz de:

- Utilizar modelos de referencia tecnologica (TRM)
- Definir estandares tecnologicos empresariales
- Disenar arquitecturas cloud y multi-cloud
- Crear matrices de trazabilidad cross-domain
- Realizar analisis de impacto entre dominios

---

## Contenido

### Tema 5.1: Modelos y Estandares

| Subtema | Archivo | Tiempo |
|---------|---------|--------|
| 5.1.1 | [Modelos de Referencia Tecnologica](5.1.1_modelos_referencia_tecnologica.md) | 45 min |
| 5.1.2 | [Estandares Tecnologicos](5.1.2_estandares_tecnologicos.md) | 40 min |
| 5.1.3 | [Plataformas Cloud](5.1.3_plataformas_cloud.md) | 45 min |

### Tema 5.2: Consolidacion Cross-Domain

| Subtema | Archivo | Tiempo |
|---------|---------|--------|
| 5.2.1 | [Matrices de Trazabilidad](5.2.1_matrices_trazabilidad.md) | 40 min |
| 5.2.2 | [Analisis de Impacto Cross-Domain](5.2.2_analisis_impacto_cross_domain.md) | 45 min |

---

## Artefactos Clave

### Technology Reference Model (TRM)

```
+--------------------------------------------------+
|                 APLICACIONES                      |
+--------------------------------------------------+
|              SERVICIOS DE APLICACION              |
| +------------+ +------------+ +------------+      |
| |  API Mgmt  | |  Identity  | | Integration|      |
| +------------+ +------------+ +------------+      |
+--------------------------------------------------+
|              SERVICIOS DE PLATAFORMA              |
| +------------+ +------------+ +------------+      |
| | Containers | |  Database  | |  Messaging |      |
| +------------+ +------------+ +------------+      |
+--------------------------------------------------+
|              INFRAESTRUCTURA                      |
| +------------+ +------------+ +------------+      |
| |  Compute   | |  Storage   | |  Network   |      |
| +------------+ +------------+ +------------+      |
+--------------------------------------------------+
```

### Matriz de Trazabilidad

| Capacidad | Aplicacion | Tecnologia |
|-----------|------------|------------|
| Ventas Online | Ecommerce | AWS EKS |
| CRM | Salesforce | Salesforce Cloud |
| Logistica | WMS | Azure VMs |

---

## Ruta de Aprendizaje

```
5.1.1 TRM --> 5.1.2 Estandares --> 5.1.3 Cloud
                                        |
                                        v
              5.2.2 Impacto <-- 5.2.1 Trazabilidad
```

---

## Patrones Cloud

| Patron | Descripcion |
|--------|-------------|
| Cloud-Native | Disenado para cloud desde inicio |
| Lift & Shift | Migracion sin cambios |
| Hybrid | Combinacion on-prem + cloud |
| Multi-Cloud | Multiples proveedores |

---

## Ejercicio Practico

1. Define un TRM simplificado para tu organizacion
2. Crea un catalogo de estandares tecnologicos
3. Evalua aplicaciones para migracion cloud (6Rs)
4. Construye una matriz de trazabilidad capacidad-app-tech

---

## Conexion con Otros Modulos

| Entrada desde | Salida hacia |
|---------------|--------------|
| Application Architecture | Opportunities & Solutions |
| Data Architecture | Migration Planning |
| Gap Analysis por dominio | Gap Analysis consolidado |

---

## Siguiente Modulo

[Modulo 6: Planificacion y Migracion](../modulo_6/)

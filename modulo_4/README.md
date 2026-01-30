# Modulo 4: Arquitectura de Sistemas de Informacion

> Phase C del ADM: Datos y Aplicaciones.

---

## Descripcion

Este modulo cubre la Phase C del ADM, que incluye tanto la arquitectura de datos como la arquitectura de aplicaciones. Aprenderás a modelar datos, gestionar el portafolio de aplicaciones e implementar patrones de integracion.

**Duracion**: 8 horas
**Nivel**: Intermedio-Avanzado
**Prerrequisitos**: Modulo 3 (Arquitectura de Negocio)

---

## Objetivos de Aprendizaje

Al completar este modulo, seras capaz de:

- Crear modelos de datos conceptuales y logicos
- Implementar practicas de gobierno de datos
- Gestionar inventarios de aplicaciones
- Desarrollar matrices de aplicacion-datos
- Aplicar patrones de integracion empresarial

---

## Contenido

### Tema 4.1: Arquitectura de Datos

| Subtema | Archivo | Tiempo |
|---------|---------|--------|
| 4.1.1 | [Modelado Conceptual de Datos](4.1.1_modelado_conceptual_datos.md) | 45 min |
| 4.1.2 | [Modelado Logico de Datos](4.1.2_modelado_logico_datos.md) | 45 min |
| 4.1.3 | [Gobierno de Datos](4.1.3_gobierno_datos.md) | 40 min |

### Tema 4.2: Arquitectura de Aplicaciones

| Subtema | Archivo | Tiempo |
|---------|---------|--------|
| 4.2.1 | [Inventario de Aplicaciones](4.2.1_inventario_aplicaciones.md) | 40 min |
| 4.2.2 | [Matriz Aplicacion-Datos](4.2.2_matriz_aplicacion_datos.md) | 35 min |
| 4.2.3 | [Patrones de Integracion](4.2.3_patrones_integracion.md) | 50 min |

---

## Artefactos Clave

### Modelo Conceptual de Datos

```
+----------+       +----------+       +----------+
| CLIENTE  |------>| PEDIDO   |------>| PRODUCTO |
+----------+       +----------+       +----------+
     |                  |                  |
     v                  v                  v
+----------+       +----------+       +----------+
| Direccion|       | Linea    |       | Categoria|
+----------+       +----------+       +----------+
```

### Matriz CRUD

| Aplicacion | Cliente | Pedido | Producto |
|------------|---------|--------|----------|
| CRM | CRUD | R | R |
| Ecommerce | CR | CRUD | R |
| ERP | R | RU | CRUD |

### Patrones de Integracion

| Patron | Uso |
|--------|-----|
| Request-Reply | APIs sincronas |
| Publish-Subscribe | Eventos asincronos |
| File Transfer | Batch processing |
| Shared Database | Legacy (evitar) |

---

## Ruta de Aprendizaje

```
4.1.1 Conceptual --> 4.1.2 Logico --> 4.1.3 Gobierno
                                           |
                                           v
4.2.3 Integracion <-- 4.2.2 Matriz <-- 4.2.1 Inventario
```

---

## Ejercicio Practico

1. Crea un modelo conceptual de datos para un dominio de negocio
2. Desarrolla un inventario de aplicaciones con scoring TIME
3. Construye una matriz CRUD para tus sistemas principales
4. Identifica que patrones de integracion se usan actualmente

---

## Conexion con Otros Modulos

| Entrada desde | Salida hacia |
|---------------|--------------|
| Business Architecture | Technology Architecture |
| Capability Map | Integration Architecture |
| Gap Analysis Negocio | Gap Analysis consolidado |

---

## Siguiente Modulo

[Modulo 5: Arquitectura Tecnologica](../modulo_5/)

# Limpieza y Resumen de Datos de Ventas en Google Sheets

Este proyecto aborda la limpieza, estandarización y estructuración de un conjunto de datos transaccionales de ventas multiciudad (Bogotá, Guadalajara, Monterrey, etc.) para productos tecnológicos (laptops, tablets, auriculares y teléfonos).

---

## 🎯 Objetivo del Proyecto

Transformar un conjunto de datos brutos e inconsistentes en una base de datos analítica depurada, permitiendo calcular métricas de rendimiento comercial por ciudad, categoría de producto e ID de cliente.

---

## 🛠️ Herramientas y Funciones Utilizadas

* **Google Sheets / Excel**
* **Limpieza y Validación:** Eliminación de duplicados, estandarización de fechas, corrección de nombres de ciudades e imputación de valores faltantes.
* **Fórmulas de Agregación:** `SUMAR.SI`, `CONTAR.SI`, `PROMEDIO.SI` y `SI.ERROR`.
* **Modelado y Análisis:** Tablas dinámicas (*Pivot Tables*) para resúmenes ejecutivos por categoría de producto y territorio.

---

## 📂 Estructura del Libro de Trabajo

* `Datos Limpios`: Tabla principal estructurada con datos depurados (Fecha de venta, Ciudad, Producto, Precio unitario, Cantidad, Monto total, Cliente, Email, ID de orden).
* `Resumen`: Tablas consolidadas con agregaciones de ventas y promedios transaccionales.

---

## 🚀 Cómo Explorar este Proyecto

1. Abre la hoja de cálculo en **Google Sheets** o **Microsoft Excel**.
2. Consulta la pestaña `Datos Limpios` para revisar la estructura de la base de datos depurada.
3. Examina la pestaña `Resumen` para visualizar la segmentación comercial por ciudad y tipo de producto.

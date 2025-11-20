# Dashboard Tableau – Análisis de Reviews del Cliente

Este repositorio contiene un dashboard creado en **Tableau** para analizar más de 23,000 reviews de clientes de la empresa GreatFit. El objetivo es identificar patrones de satisfacción, frecuencia de devoluciones, distribución de ratings y comportamiento por división de productos, utilizando visualizaciones interactivas y análisis descriptivo.

---

## 📊 Principales Visualizaciones

- **Total de reviews analizadas:** 23,486  
- **Distribución de ratings (1 a 5)** con conteo por categoría.  
- **Reviews mencionando devoluciones**, clasificando entre “True” y “False”.  
- **Total de malas reseñas (ratings bajos).**  
- **Análisis por división del producto:**
  - General  
  - General Petite  
  - Intimates  
- **Gráfica de recomendación:** porcentaje de usuarios que recomiendan vs. no recomiendan.  

---

## 🔧 Arquitectura y Flujo del Proyecto

### 1. Preparación y Limpieza de Datos
- Estandarización de columnas: rating, recomendación, devoluciones, división.
- Eliminación de valores duplicados.
- Conversión de tipos de datos según requerimientos de Tableau.

### 2. Modelado en Tableau
- Creación de campos calculados para:
  - Identificar “malas reviews”
  - Clasificar recomendaciones
  - Agrupar niveles de rating
- Perfiles interactivos mediante filtros y parámetros dinámicos.

### 3. Visualizaciones
- Barras verticales para conteo de reviews por rating.
- Barras horizontales para devoluciones.
- Pie chart para recomendación.
- Barras apiladas para calificaciones por división.
- Indicadores KPI para métricas clave.

---

## 🛠️ Herramientas

- **Tableau Desktop**
- **Limpieza inicial en Excel / CSV**
- **Cálculos y campos personalizados en Tableau**
- **Dashboard interactivo orientado a experiencia de usuario**




# 📊 Dashboard de HR Analytics en Power BI

## 1️⃣ Cargar Datos
- Importar dataset (Excel / CSV / Base de datos).
- Transform Data → verificar tipos de datos (ingresos en moneda, porcentajes correctos).

---

## 2️⃣ Revisar Model View
- Verificar relaciones entre tablas.
- Confirmar cardinalidad correcta (1:*).

---

# 📈 Visualizaciones

## 🔹 Card – Cantidad de Empleados
- Visual tipo **Card**.
- Validar resultado con Q&A (ej. “¿Cuántos empleados hay?”).

---

## 🔹 Pie Chart – Distribución por Género
- **Leyenda:** Gender  
- **Valores:** Total Employees  
- Analizar proporción hombres vs mujeres.

---

## 🔹 Gráfico de Barras – Edad vs Cantidad de Empleados

### Paso 1: Visual inicial
- **Eje X:** Age  
- **Eje Y:** Número de Employees
- **Leyenda:** Attrition
### Paso 2: Agrupación
- En age -> crear grupos
- Crear **bins en Age** (grupos de edad).
- Reemplazar Age por Age (bin) en el eje.

---

## 🔹 Mapa – Ubicaciones
- Ubicación: Office
- Validar ubicaciones
- Corregir categoría de datos en el modelo (.XLS).
- Realizar conexión en el model view (City ↔ Office).
- Agregar campos: **Latitude, Longitude y tamaño de burbuja (Total Employees)**.
- Validar ubicaciones correcta.

---

## 🔹 Gráfico de Barras – Empleados por Años en la Empresa y Attrition
- **Eje X:** YearsAtCompany  
- **Eje Y:** Total Employees  
- **Leyenda:** Attrition  

---

## 🔹 Gráfico de Influencias (Key Influencers)

Analizar impacto sobre **Attrition** considerando:
- Overtime  
- YearsAtCompany  
- Performance Rating  
- Stock Option Level  
- Marital Status  

Revisar segmentaciones principales (Top segments).

---

## 🔹 Matriz – Departamentos e Ingreso Promedio Mensual
- **Columnas:** Department  
- **Columnas:** Average Monthly Income  
- Validar resultados con Q&A.

---

## 🔹 Gauge
- Indicador visual de métrica clave.
- Agregar Gauge para:
  - Job Satisfaction  
  - Performance Rating  

---

# 🎨 Orden y Layout
- Diseño limpio y alineado.
- Distribución clara de visualizaciones.
- Consistencia visual y jerarquía adecuada.

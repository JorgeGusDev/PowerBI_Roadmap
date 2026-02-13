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
- **Valores:** Total Employees  

### Paso 2: Agrupación
- Crear **bins en Age** (grupos de edad).
- Reemplazar Age por Age (bin) en el eje.

---

## 🔹 Mapa – Ubicaciones
- **Campo:** OFFICE  
- Corregir categoría de datos en el modelo (.XLS correctamente tipificado).
- Realizar conexión geográfica (City ↔ Office).
- Agregar **Latitude, Longitude y Total Employees**.
- Validar geocodificación correcta.

---

## 🔹 Gráfico de Barras – Empleados por Años en la Empresa y Attrition
- **Eje X:** YearsAtCompany  
- **Valores:** Total Employees  
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
- **Filas:** Department  
- **Valores:** Average Monthly Income  
- Validar resultados con Q&A.

---

## 🔹 Gauge
- Indicador visual de métrica clave.
- Agregar slicers para:
  - Job Satisfaction  
  - Performance Rating  

---

# 🎨 Orden y Layout
- Diseño limpio y alineado.
- Distribución clara de visualizaciones.
- Consistencia visual y jerarquía adecuada.

# 📞 Análisis de Planes de Telefonía - Megaline

## 📊 Descripción General

Este proyecto tiene como objetivo analizar el comportamiento de los usuarios con respecto al consumo de servicios bajo los planes tarifarios **"Surf"** y **"Ultimate"** ofrecidos por Megaline. El fin principal es identificar cuál de estos planes aporta mayores ingresos a la empresa y, por ende, cuál debería ser priorizado en futuras estrategias de marketing y asignación presupuestal.

Se parte de una muestra de **500 clientes**, con datos sobre nombre, ubicación, plan contratado, consumo de minutos, mensajes de texto y datos móviles a lo largo del año **2018**.

---

## 🎯 Objetivo

Determinar, a través de análisis descriptivo, visualizaciones y pruebas estadísticas, qué plan genera mayores ingresos para Megaline y proporciona mayor rentabilidad.

---

## 🔍 Enfoque Metodológico

1. **Preparación de Datos**
   - Limpieza de valores nulos y duplicados.
   - Conversión de tipos de datos.
   - Validación de la coherencia en los registros.

2. **Transformación**
   - Cálculo mensual de consumo por cliente.
   - Clasificación de usuarios por tipo de plan.
   - Consolidación de métricas relevantes para el análisis comparativo.

3. **Análisis Exploratorio**
   - Estudio de distribución y tendencias de consumo (llamadas, SMS, datos).
   - Estimación de ingresos individuales y totales por plan.
   - Visualización de patrones mensuales.

4. **Pruebas de Hipótesis**
   - Comparación de ingresos promedio entre planes.
   - Evaluación de diferencias regionales (área NY-NJ vs. resto del país).

---

## 📈 Resultados Clave

### Consumo y Rentabilidad
- El plan **Ultimate** tiene un mayor ingreso promedio por usuario (**$70**) en comparación con **Surf** (**$51**).
- Sin embargo, **Surf cuenta con el doble de usuarios**, lo que compensa su menor ARPU (Average Revenue Per User).

### Ingresos por Excedentes
- Aproximadamente el **25%** de los usuarios del plan Surf exceden sus límites mensuales, generando cargos adicionales.
- El plan Ultimate rara vez genera ingresos extra debido a sus beneficios ilimitados.

### Popularidad y Comportamiento del Cliente
- Surf parece ser más popular, posiblemente por su percepción de menor costo, aunque esta hipótesis no puede confirmarse con los datos actuales.

### Pruebas de Hipótesis
- Se **rechaza** la hipótesis nula de igualdad de ingresos promedio entre los planes: existen diferencias significativas.
- También se **rechaza** la hipótesis nula entre regiones (NY-NJ vs. otras): se encontraron diferencias estadísticamente significativas.

---

## ✅ Conclusión

El plan **Surf** representa la **opción más rentable** para Megaline gracias a su mayor base de usuarios y la posibilidad de generar ingresos por cargos adicionales. Este análisis permite optimizar decisiones relacionadas con campañas publicitarias, precios y desarrollo de nuevos productos.

---

## 🛠️ Tecnologías Utilizadas

- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- SciPy (pruebas estadísticas)
- Jupyter Notebook

---

## 👤 Autor

**César Eduardo Cruz Cabrera**  
📧 cesareduardocruzcabrera@gmail.com  
🔗 [LinkedIn - César Eduardo Cruz Cabrera](https://www.linkedin.com/in/cesar-eduardo-cruz-cabrera)


# Análisis de Planes de Telefonía - Megaline

## 📊 Descripción del Proyecto

Este proyecto tiene como objetivo comprender en profundidad el comportamiento de los usuarios en relación con los consumos asociados a los planes de telefonía **"Surf"** y **"Ultimate"**, ofrecidos por la compañía Megaline. El propósito final es identificar cuál de estos planes contribuye de manera más significativa a los ingresos de la empresa y, por lo tanto, cuál debería recibir mayor enfoque presupuestal en publicidad.

La muestra de datos contiene información de 500 clientes: nombre, ubicación, plan de prepago, cantidad de llamadas, mensajes de texto y datos móviles utilizados durante el año 2018.

---

## 🧠 Objetivo

Analizar el comportamiento de los clientes y determinar, a través de visualizaciones, métricas descriptivas y pruebas estadísticas, qué plan genera más ingresos para la empresa.

---

## 🔍 Enfoque Metodológico

1. **Preparación de los Datos**
   - Limpieza de valores faltantes y duplicados.
   - Conversión de tipos de datos cuando fue necesario.
   - Validación de la integridad y consistencia del conjunto de datos.

2. **Transformación de Datos**
   - Cálculo mensual de consumo individual por cliente.
   - Agrupación de usuarios según su tipo de plan.
   - Consolidación de los datos más relevantes en un solo DataFrame para análisis global.

3. **Análisis Exploratorio**
   - Análisis descriptivo de minutos, mensajes y datos móviles consumidos.
   - Comparación de ingresos generados por cada plan.
   - Visualización de los patrones de consumo.

4. **Pruebas de Hipótesis**
   - Comparación de ingresos promedio entre los planes Surf y Ultimate.
   - Comparación de ingresos entre regiones, especialmente el área NY-NJ frente al resto del país.

---

## 🧾 Resultados y Conclusiones

### 🔹 Comparación de Consumo
- Ambos planes presentan patrones similares de consumo mensual, con tendencia creciente.
- El plan **Surf** tiene un ingreso promedio menor por usuario ($51) comparado con el **Ultimate** ($70), pero el **doble de usuarios**.

### 🔹 Ingresos por Excedentes
- El 25% de los usuarios del plan Surf superan los minutos incluidos, generando ingresos adicionales.
- El plan Ultimate rara vez presenta cargos por excedente, ya que incluye muchos beneficios.

### 🔹 Rentabilidad del Plan Surf
- A pesar del menor ingreso promedio, Surf resulta **más rentable** gracias a su base de usuarios más amplia y cargos por excedente.

### 🔹 Preferencias del Usuario
- La popularidad del plan Surf podría estar relacionada con una percepción de menor costo, aunque esto no se puede confirmar con los datos actuales.

### 🔹 Prueba de Hipótesis
- Se **rechazó** la hipótesis nula de igualdad de ingresos promedio entre planes: existen diferencias significativas.
- Se **rechazó** la hipótesis nula de igualdad de ingresos promedio entre NY-NJ y otras regiones: hay diferencias significativas.

---

## ✅ Conclusión Final

El plan **Surf**, con su mayor base de usuarios y posibilidad de generar ingresos por cargos adicionales, es el **más rentable para Megaline**. Este análisis proporciona información valiosa para la toma de decisiones estratégicas y ajustes en el presupuesto de marketing.

---

## 🛠️ Herramientas Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- SciPy (para pruebas estadísticas)
- Jupyter Notebook

---

## 📫 Contacto

César Eduardo Cruz Cabrera  
📧 cesareduardocruzcabrera@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/cesar-eduardo-cruz-cabrera)


# 🧪Análisis del experimento de la página de destino

Prueba ANOVA y de permutación

## 📌Descripción del proyecto

Este proyecto analiza el rendimiento de cuatro páginas de destino (A, B, C y D) creadas para aumentar la fidelización de usuarios en un sitio de e-commerce recientemente lanzado.

El análisis se centra en la variable “tiempo que el usuario pasa en el sitio” (en segundos), utilizando técnicas de estadística inferencial para determinar si existen diferencias significativas entre las páginas.

El conjunto de datos está basado en un ejemplo del libro
“Practical Statistics for Data Scientists” de Peter Bruce, Andrew Bruce y Peter Gedeck.

## 🎯Objetivos

- Comparar el tiempo promedio de permanencia entre páginas
- Determinar si las diferencias observadas son estadísticamente significativas
- Aplicar y comparar distintos enfoques estadísticos:
- ANOVA
- Pruebas post-hoc (Tukey HSD)
- Prueba de permutación
- Apoyar decisiones de marketing basadas en evidencia

## 📂Conjunto de datos

- 20 usuarios
- 4 páginas de destino
- 5 usuarios por página
- Variables
- Page: Página de destino (A, B, C, D)
- Time: Tiempo en el sitio (segundos)

## 🛠️Tecnologías utilizadas

- Python
- Pandas / NumPy – Manipulación de datos
- Matplotlib / Seaborn – Visualización
- Statsmodels – ANOVA
- SciPy – Estadística
- YData Profiling – Análisis exploratorio automático

## 🔍Metodología

1️⃣ Exploración de datos

- Verificación de valores faltantes
- Estadísticas descriptivas por grupo
- Visualización con boxplots y medias

2️⃣ ANOVA (Analysis of Variance)

- Evaluación de diferencias globales entre páginas

- Hipótesis:
  - H₀: No hay diferencias en el tiempo medio entre páginas
  - H₁: Al menos una página difiere significativamente

3️⃣ Prueba post-hoc (Tukey HSD)

- Comparaciones múltiples entre pares de páginas
- Identificación de qué páginas presentan diferencias significativas

4️⃣ Prueba de permutación

- Enfoque no paramétrico
- Generación de la distribución nula mediante 10.000 permutaciones
- Comparación de la varianza observada con la distribución bajo H₀

## 📊Resultados principales

- La Página B presenta el mayor tiempo promedio de permanencia
- El ANOVA indica diferencias significativas entre páginas
- La prueba Tukey HSD confirma que la Página B difiere del resto
- La prueba de permutación respalda los resultados inferenciales
- Evidencia sólida para elegir la Página B como mejor landing page

## 📈Conclusiones de negocio

- La Página B genera mayor engagement

- Recomendación:
  - Implementar Página B como landing principal
  - Usar el diseño como base para futuras campañas
  - El análisis demuestra cómo la estadística reduce el riesgo en decisiones de marketing


## 🚀Posibles extensiones

- A/B testing con mayor tamaño muestral
- Métricas adicionales (conversion rate, bounce rate)

Pruebas no paramétricas alternativas (Kruskal-Wallis)

Dashboard interactivo para stakeholders

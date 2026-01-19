# Análisis Geoestadístico para Agricultura de Precisión

## Resumen del Proyecto
Este proyecto implementa un modelo de análisis de datos para monitorear la salud del suelo en un cultivo de alta densidad (62 bloques). El análisis combina **estadística inferencial** y **visualización geoespacial** para optimizar la aplicación de fertilizantes y enmiendas, reduciendo el impacto ambiental y aumentando la eficiencia económica.

## Impacto del Análisis
* **Diagnóstico de Nutrientes:** Se identificó una dinámica no lineal de Nitratos con una tendencia de agotamiento crítico al cierre de 2024.
* **Optimización de Recursos:** El análisis espacial permite pasar de una fertilización uniforme a una de **Tasa Variable (VRA)**.
* **Validación Científica:** Uso de pruebas de normalidad (Shapiro-Wilk) y comparativas (ANOVA) para asegurar que las decisiones agronómicas no sean producto del azar.

## Stack Tecnológico
* **Lenguaje:** Python 3.x
* **Librerías:** Pandas, Numpy, Matplotlib, Seaborn.
* **Estadística:** Scipy (ANOVA, Shapiro-Wilk, Pearson).

## Visualizaciones Incluidas
* **Heatmap Espacial:** Localización exacta de zonas ácidas que requieren intervención.
* **Tendencia No Lineal:** Gráfico de series de tiempo que muestra las fluctuaciones reales de nitratos (incluyendo periodos de agotamiento y recuperación).
* **Análisis de Variabilidad:** Boxplots interanuales para medir la estabilidad del pH.

<img width="1589" height="1189" alt="Graficos_suelos" src="https://github.com/user-attachments/assets/113e33fe-bc78-48ad-956e-d8ecde8282d3" />


## Recomendaciones Estratégicas
1. **Encalado Selectivo:** Aplicación de Carbonato de Calcio únicamente en bloques identificados con pH < 5.8 (Zonas rojas del Heatmap), estimando un ahorro del **18% en costos de insumos**.
2. **Reposición de Nitrógeno:** El modelo detectó un "gap" de nutrientes en 2023-2024. Se recomienda un ajuste del **+15% en el plan de fertilización nitrogenada** para recuperar la fertilidad del suelo en el próximo ciclo.
3. **Monitoreo de Precisión:** Sustituir el muestreo general por un monitoreo intensificado en los bloques con mayor volatilidad de nutrientes detectada por el modelo.

## Autor
**Andres Florez** *Ingeniero Agrícola | Data Analyst* [LinkedIn](linkedin.com/in/andres-florez-agtech)

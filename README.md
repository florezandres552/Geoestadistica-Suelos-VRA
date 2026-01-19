# Análisis Geoestadístico para Manejo de Suelos

## Resumen del Proyecto
Este proyecto utiliza técnicas de **Ciencia de Datos** para analizar la variabilidad del pH y nutrientes en un cultivo de 62 bloques. El objetivo es transitar de un manejo de "promedios" a un manejo de **Precisión**, aplicando insumos solo donde el suelo lo requiere.

## Stack Tecnológico
* **Python** (Pandas, Numpy)
* **Visualización:** Seaborn & Matplotlib (Heatmaps espaciales)
* **Estadística Inferencial:** Scipy (Pruebas ANOVA y Shapiro-Wilk)

## Visualización de Resultados

Para este análisis, se implementaron cuatro visualizaciones clave que permiten tomar decisiones agronómicas basadas en datos:

<img width="1489" height="1190" alt="Graficos_suelos" src="https://github.com/user-attachments/assets/994595b3-867b-4bcf-8149-750e9b4979f9" />

1. **Mapa de Calor Espacial (Precision Agriculture):** Representa la distribución real del pH en el campo. Las zonas en rojo indican niveles críticos de acidez que requieren enmiendas inmediatas.
2. **Dinámica Temporal de Nutrientes:** Un gráfico de líneas que muestra la fluctuación de Nitratos por bloque a lo largo de 5 años, resaltando el promedio general para identificar desviaciones.
3. **Distribución por Año (Boxplots):** Utilizado para validar visualmente el test ANOVA, demostrando la estabilidad del suelo en el tiempo.
4. **Matriz de Correlación:** Permite entender la relación entre el pH, la conductividad y los nitratos para evitar efectos antagónicos durante la fertilización.

## Hallazgos Críticos
* **Estabilidad:** El test ANOVA (p > 0.05) confirmó que el pH no ha sufrido degradación significativa en 5 años.
* **Heterogeneidad:** El mapa de calor identificó sectores con pH < 5.5 que requieren intervención inmediata, mientras el 70% del cultivo está en rangos óptimos.

## Recomendación Agronómica
Implementar un plan de **Encalado Variable**. Basado en los mapas de calor, se estima un ahorro del **18% en carbonato de calcio** al evitar aplicaciones en bloques neutros/alcalinos.

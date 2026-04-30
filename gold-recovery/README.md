# Gold Recovery Prediction

## Introducción

La industria minera genera grandes volúmenes de datos durante el proceso de extracción y refinamiento de minerales.  
En este proyecto se desarrolló un modelo predictivo para estimar la recuperación de oro durante diferentes etapas del proceso de producción, utilizando variables operativas registradas por sensores industriales.

Este proyecto demuestra mi capacidad para aplicar ciencia de datos en un entorno industrial real, combinando análisis estadístico con modelos predictivos para optimizar procesos.

---

## Contexto del problema

Durante el proceso de flotación y purificación del mineral, pequeñas variaciones en los parámetros de operación pueden afectar directamente el porcentaje de recuperación del oro.

El problema principal fue:

**¿Es posible predecir la recuperación de oro utilizando los datos históricos del proceso industrial?**

Resolver este problema puede ayudar a:

- mejorar la eficiencia operativa
- reducir pérdidas económicas
- detectar desviaciones en producción
- apoyar la toma de decisiones técnicas

---

## Objetivo del proyecto

El objetivo principal fue construir un modelo capaz de:

- predecir la recuperación de oro
- analizar las variables más relevantes del proceso
- evaluar la calidad del modelo
- identificar oportunidades de mejora operacional

---

## Herramientas utilizadas

Para el desarrollo del proyecto se utilizaron:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Análisis exploratorio de datos

Durante el análisis exploratorio se realizaron las siguientes actividades:

- revisión de valores faltantes
- eliminación de columnas inconsistentes
- comparación entre datos de entrenamiento y prueba
- análisis de distribución de variables
- detección de outliers
- análisis de correlaciones

Se identificó que algunas variables del proceso mostraban una relación directa con la recuperación del mineral, especialmente aquellas relacionadas con:

- concentración del mineral
- tamaño de partícula
- parámetros de flotación
- composición química del material

---

## Metodología del proyecto

El proyecto se desarrolló en las siguientes etapas:

### 1. Preparación de datos
- limpieza del dataset
- alineación entre train y test
- tratamiento de valores nulos
- selección de variables relevantes

### 2. Ingeniería de variables
- cálculo de métricas de recuperación
- validación de fórmulas del proceso
- reducción de variables redundantes

### 3. Entrenamiento del modelo
Se probaron modelos como:

- Random Forest
- Linear Regression
- Decision Tree

### 4. Evaluación del modelo
Se utilizó como métrica principal:

- sMAPE (Symmetric Mean Absolute Percentage Error)

---

## Resultados

Después del entrenamiento y validación, el modelo logró estimar la recuperación del oro con un nivel aceptable de precisión para un problema industrial.

Resultados principales:

- mejor desempeño con Random Forest
- reducción del error respecto al baseline
- mayor precisión en etapas intermedias del proceso
- variables operativas con mayor impacto identificadas

La hipótesis inicial fue:

**Los datos operativos del proceso permiten predecir la recuperación del oro.**

Esta hipótesis se cumplió, ya que el modelo fue capaz de capturar patrones relevantes dentro del proceso industrial.

---

## Conclusiones

Los resultados mostraron que:

- sí es posible predecir la recuperación del oro con machine learning
- algunas variables tienen mayor influencia que otras
- la limpieza de datos fue crítica para mejorar el rendimiento
- el modelo puede servir como apoyo para monitoreo operativo

Esto demuestra que la analítica predictiva puede aportar valor dentro del sector industrial.

---

## Recomendaciones

Con base en los resultados obtenidos, se recomienda:

- incorporar más datos históricos
- mejorar la calidad de captura de sensores
- aplicar modelos más avanzados
- monitorear variables críticas en tiempo real
- implementar alertas tempranas para desviaciones

---

## Mi aporte en el proyecto

Mi contribución específica en este proyecto incluyó:

- limpieza y validación de datos industriales
- análisis exploratorio del proceso
- cálculo manual de métricas de recuperación
- selección de variables relevantes
- entrenamiento de modelos predictivos
- evaluación del desempeño del modelo
- interpretación de resultados técnicos
- documentación del proyecto

Este proyecto fortaleció mis habilidades en:

- análisis de datos industriales
- machine learning aplicado
- interpretación estadística
- resolución de problemas reales

---

## Impacto profesional

Este proyecto refuerza mi perfil como profesional en datos porque demuestra mi capacidad para:

- analizar procesos complejos
- construir modelos predictivos
- comunicar resultados técnicos
- generar valor mediante datos

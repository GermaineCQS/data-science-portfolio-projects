# 🚗 Predicción de precios de autos usados

## 📌 Contexto
El mercado de autos usados requiere estimaciones precisas del precio para apoyar
la toma de decisiones tanto de vendedores como de compradores.

## 🎯 Objetivo
Construir un modelo de machine learning capaz de predecir el precio de autos usados
a partir de sus características técnicas y de uso, comparando distintos enfoques
de modelado.

## 🧠 Desarrollo del proyecto
- Exploración inicial y análisis de calidad del dataset
- Limpieza de datos y tratamiento de valores faltantes
- Ingeniería de características con codificación one-hot
- Implementación de un modelo baseline (predicción constante)
- Entrenamiento de modelos de regresión (Regresión Lineal y Random Forest)
- Comparación de modelos mediante la métrica RMSE
- Exportación de resultados para dashboards (CSV)

## 🛠 Tecnologías utilizadas
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## 📊 Resultados
Los modelos entrenados mejoraron el rendimiento frente al baseline. La comparación
por RMSE permitió seleccionar el modelo de mejor desempeño y generar una tabla
de resultados lista para visualización.

## 📂 Contenido de la carpeta
- `notebook.ipynb`: análisis exploratorio, feature engineering y entrenamiento
- `src/`: scripts de modelado y evaluación (cuando aplique)
- `results/`: métricas y comparaciones de desempeño

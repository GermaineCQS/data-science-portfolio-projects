# ⛏️ Optimización de recuperación de oro

Proyecto de ciencia de datos orientado a predecir la recuperación de oro en un
proceso industrial. Se trabaja con tres datasets (train, test y full) y se
evalúa el desempeño mediante la métrica sMAPE.

## 🎯 Objetivo
Construir un modelo predictivo que estime la recuperación en las etapas
rougher y final, minimizando el error mediante validación cruzada.

## 🧠 Desarrollo del proyecto
- Carga de datos y exploración inicial
- Verificación del cálculo de recuperación
- Análisis de columnas ausentes en test
- Limpieza e imputación de valores faltantes
- Detección y eliminación de anomalías
- Entrenamiento con modelos multi-output
- Evaluación con sMAPE y comparación de modelos

## 🛠 Tecnologías utilizadas
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## 📊 Resultados
Se entrenaron modelos de regresión multi-salida (Lineal y Random Forest),
seleccionando el mejor desempeño con sMAPE y validación cruzada.

## 📂 Contenido de la carpeta
- `data/`: datasets originales del proyecto
- `notebook.ipynb`: análisis y modelado completo
- `src/`: scripts auxiliares (futuro)
- `results/`: métricas y resultados (futuro)

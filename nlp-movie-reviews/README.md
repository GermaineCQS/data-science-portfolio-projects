# 🎬 Clasificación de reseñas de películas con NLP

## 📌 Contexto
Las plataformas de entretenimiento reciben miles de reseñas escritas por usuarios.
Analizar manualmente este volumen de texto no es viable ni escalable.

## 🎯 Objetivo
Desarrollar un modelo de procesamiento de lenguaje natural (NLP) capaz de clasificar
reseñas de películas según su sentimiento, utilizando técnicas clásicas de machine learning.

## 🧠 Desarrollo del proyecto
- Limpieza y normalización del texto
- Tokenización y eliminación de stopwords
- Lematización para reducir las palabras a su forma base
- Vectorización del texto mediante TF-IDF
- Entrenamiento de modelos de clasificación
- Evaluación del desempeño con la métrica AUC-ROC

## 🛠 Tecnologías utilizadas
- Python
- Pandas
- NLTK
- Scikit-learn
- Jupyter Notebook

## 📊 Resultados
El modelo final logró un desempeño competitivo, mostrando una buena capacidad
para distinguir entre reseñas positivas y negativas, validado mediante AUC-ROC.

## 📂 Contenido de la carpeta
- `notebook.ipynb`: análisis exploratorio y entrenamiento del modelo
- `src/`: scripts de preprocesamiento y entrenamiento (cuando aplique)
- `results/`: métricas y resultados finales

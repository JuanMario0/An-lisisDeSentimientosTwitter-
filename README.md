📊 Proyecto: Análisis de Sentimientos en Tweets 🐦
Este proyecto tiene como objetivo clasificar el sentimiento de tweets en categorías como Positive, Negative, Neutral e Irrelevant utilizando técnicas de Machine Learning y Procesamiento de Lenguaje Natural (NLP). 🚀

📌 Descripción
El proyecto consiste en entrenar un modelo de Machine Learning para predecir el sentimiento de tweets. Utilizamos un conjunto de datos de entrenamiento y validación para entrenar y evaluar el modelo, y luego lo probamos con nuevos datos para ver su rendimiento en situaciones reales. 🧠💡

🛠️ Herramientas y Tecnologías
Lenguaje de programación: Python 🐍

Bibliotecas principales:

Pandas 🐼: Para manipulación de datos.

NLTK 📚: Para preprocesamiento de texto (tokenización, eliminación de stopwords, etc.).

Scikit-learn 🔧: Para vectorización de texto (TF-IDF) y entrenamiento del modelo (Naive Bayes).

Algoritmo de Machine Learning: Naive Bayes Multinomial 🎓.

📂 Estructura del Proyecto
Preprocesamiento de datos:

Limpieza de tweets (eliminación de URLs, menciones, stopwords, etc.).

Conversión del texto a una representación numérica usando TF-IDF.

Entrenamiento del modelo:

Uso del algoritmo Naive Bayes Multinomial para entrenar el modelo.

Evaluación del modelo:

Cálculo de métricas como accuracy, precision, recall y F1-score.

Pruebas con nuevos datos:

Predicción del sentimiento de tweets nuevos.

📊 Resultados
Accuracy: 70.1% 🎯

Classification Report:

Positive: F1-score de 0.75 🌟

Negative: F1-score de 0.71 🔥

Neutral: F1-score de 0.68 ⚖️

Irrelevant: F1-score de 0.61 🧩

El modelo funciona mejor para las clases Positive y Negative, pero tiene margen de mejora en las clases Irrelevant y Neutral.


Cómo usar el proyecto
Clona el repositorio:

bash
Copy
git clone https://github.com/tu-usuario/tu-repositorio.git
cd tu-repositorio
Instala las dependencias:

bash
Copy
pip install -r requirements.txt
Ejecuta el código:

Abre el notebook .ipynb y ejecuta las celdas para entrenar y probar el modelo.

Prueba con nuevos datos:

Modifica la lista de new_tweets en el notebook para probar el modelo con tus propios tweets.

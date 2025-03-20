Análisis de Sentimientos de Comentarios sobre Alexa

Descripción

Este proyecto realiza un análisis de sentimientos sobre un dataset de comentarios de usuarios sobre el asistente virtual Alexa. El objetivo es clasificar los comentarios en positivos, negativos o neutros utilizando técnicas de procesamiento de lenguaje natural (NLP).

Tecnologías Utilizadas

Python

Pandas (para la manipulación del dataset)

NLTK y spaCy (para procesamiento de texto)

Scikit-learn (para entrenamiento de modelos de clasificación)

Matplotlib y Seaborn (para visualización de datos)

Dataset

El dataset utilizado contiene comentarios de usuarios sobre Alexa, con etiquetas de sentimiento asociadas (positivo, negativo o neutro). Se puede descargar desde aqui (si tienes un enlace, agrégalo).

Pasos del Análisis

Carga y exploración de datos: inspección inicial del dataset.

Limpieza de texto: eliminación de caracteres especiales, stopwords y lematización.

Análisis exploratorio: visualización de la distribución de sentimientos.

Vectorización del texto: uso de TF-IDF para transformar los datos textuales.

Entrenamiento del modelo: clasificación con algoritmos como Naïve Bayes, SVM o Random Forest.

Evaluación del modelo: métricas de desempeño como accuracy, precision y recall.

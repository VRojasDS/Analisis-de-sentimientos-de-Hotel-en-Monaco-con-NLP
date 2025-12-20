📊 Análisis de Sentimientos de Reseñas de un Hotel en Mónaco (TripAdvisor)
📌 Descripción del Proyecto

Este proyecto se hizo un análisis de sentimientos sobre reseñas de usuarios obtenidas desde TripAdvisor para un hotel ubicado en Mónaco.
A partir de los textos de las reseñas y sus calificaciones numéricas, se busca identificar la percepción de los clientes y evaluar la relación entre el sentimiento expresado y el rating otorgado.

El proyecto se centra en técnicas de Procesamiento de Lenguaje Natural (NLP) y aprendizaje automático, con énfasis en métricas de evaluación para clasificación.

🗂️ Dataset

El conjunto de datos contiene las siguientes columnas:

Descripción
*reviews	Texto de la reseña escrita por el usuario
*ratings	Calificación numérica otorgada por el cliente

Consideraciones

*Las reseñas provienen de usuarios reales de TripAdvisor.
*Los ratings se utilizaron para generar etiquetas de sentimiento (positivo / negativo).

⚙️ Preprocesamiento de Datos

Las principales etapas de preprocesamiento incluyen:

Limpieza de texto (minúsculas, eliminación de signos y caracteres especiales).

Eliminación de stopwords.

Tokenización.

Vectorización del texto (TF-IDF / embeddings, según el modelo).

Transformación de ratings en etiquetas binarias de sentimiento.

Ejemplo:

Ratings altos → Sentimiento Positivo

Ratings bajos → Sentimiento Negativo

🧠 Modelado

Se entrenaron modelos de clasificación para predecir el sentimiento de una reseña a partir de su texto.

Posibles enfoques utilizados:

Modelos clásicos de Machine Learning.

Redes neuronales para NLP.

Modelos preentrenados (opcional).

📈 Métricas de Evaluación

El desempeño del modelo se evaluó utilizando métricas estándar para clasificación:

Accuracy

Precision

Recall

F1-Score (macro y weighted)

Estas métricas permiten analizar el rendimiento del modelo considerando el posible desbalance de clases.

📊 Visualización de Resultados

Se generaron visualizaciones para facilitar la interpretación de los resultados:

Distribución de sentimientos positivos y negativos.

Relación entre ratings y sentimiento.

Gráficos de conteo y métricas de evaluación.

🛠️ Tecnologías Utilizadas

Python

Pandas

NumPy

Scikit-learn

NLTK / spaCy

Matplotlib / Seaborn

PyTorch / TensorFlow (si aplica)

🚀 Objetivo Final

El propósito de este proyecto es:

Comprender la percepción de los clientes del hotel.

Evaluar la coherencia entre calificaciones numéricas y lenguaje utilizado.

Aplicar técnicas de NLP a un problema real de análisis de opiniones.

Documentar un flujo completo de análisis de sentimientos en un contexto turístico.

📌 Posibles Mejoras

Uso de modelos Transformer (BERT, RoBERTa).

Clasificación multiclase de sentimientos.

Análisis de aspectos específicos del hotel (servicio, limpieza, ubicación).

Dashboard interactivo para visualización de resultados.

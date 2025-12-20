📊 Análisis de Sentimientos de Reseñas de un Hotel en Mónaco (TripAdvisor)
📌 Descripción del Proyecto

Este proyecto se hizo un análisis de sentimientos sobre reseñas de usuarios obtenidas desde TripAdvisor para un hotel ubicado en Mónaco.
A partir de los textos de las reseñas y sus calificaciones numéricas, se busca identificar la percepción de los clientes y evaluar la relación entre el sentimiento expresado y el rating otorgado.

El proyecto se centra en técnicas de Procesamiento de Lenguaje Natural (NLP) y aprendizaje automático, con énfasis en métricas de evaluación para clasificación.

🗂️ Dataset

El conjunto de datos contiene las siguientes columnas:

Descripción
* reviews	Texto de la reseña escrita por el usuario
* ratings	Calificación numérica otorgada por el cliente

Consideraciones

* Las reseñas provienen de usuarios reales de TripAdvisor.
* Los ratings se utilizaron para generar etiquetas de sentimiento (positivo / negativo).

⚙️ Preprocesamiento de Datos
Las principales etapas de preprocesamiento incluyen:
* Extraccion de datos
* Análisis
* Tokenización.
* Vectorización del texto (TF-IDF / embeddings, según el modelo).

🧠 Modelado
Se entrenaron modelos de clasificación para predecir el sentimiento de una reseña a partir de su texto.
* XLNet de procesamiento de lenjuage natural
* Regresión Logistica

📈 Métricas de Evaluación
El desempeño del modelo se evaluó utilizando métricas estándar para clasificación:

* Accuracy: 92%
* Precision: 79%
* Recall (weighted): 92%
* F1-Score (weighted): 90%
Estas métricas permiten analizar el rendimiento del modelo considerando el posible desbalance de clases.

📊 Visualización de Resultados
Se generaron visualizaciones para facilitar la interpretación de los resultados:

* Distribución de sentimientos positivos y negativos.
* Relación entre ratings y sentimiento.
🛠️ Tecnologías Utilizadas

Python
* Pandas, NumPy, Scikit-learn, Transoformadores, Matplotlib, Seaborn y Pytorch


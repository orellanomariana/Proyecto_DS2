Proyecto_DS2
Proyecto de Ciencia de Datos: Maximizando el Engagement - Análisis de Instagram 📊
Objetivo 🎯
Este proyecto busca analizar y optimizar el compromiso en Instagram mediante el estudio de métricas de interacción en publicaciones de cuentas públicas. El análisis se enfoca en:

Comparar métricas de interacción, como 'likes' y 'comentarios', entre distintos tipos de cuentas (celebridades, marcas, etc.).
Identificar patrones en el uso de hashtags, frecuencia de publicaciones y el impacto de características de las publicaciones en el compromiso del público.
Implementar técnicas de aprendizaje automático para predecir el compromiso futuro y optimizar estrategias de publicación.
Contexto 🌍
Este proyecto se desarrolló en el curso de Coder House Data Science II: Machine Learning para la Ciencia de Datos. Involucra etapas como recolección, limpieza y transformación de datos, codificación de variables y análisis de sentimientos en captions.

Problema Comercial 💼
En el marketing digital, empresas y celebridades buscan maximizar su impacto en redes sociales. Este proyecto explora los factores que influyen en el engagement en Instagram, identificando las mejores prácticas para mejorar la efectividad de las campañas.

Proceso Metodológico 🛤️
1. Data Wrangling
1.1 Recolección de Datos 📥: Recolección de datos de fuentes como bases de datos, archivos CSV y APIs. 1.2 Comprensión de los Datos 🔍: Análisis inicial de las características de los datos. 1.3 Limpieza de Datos 🧹: Identificación y tratamiento de valores faltantes e inconsistencias. 1.4 Transformación de Datos 🔄: Conversión y escalado de variables, codificación de variables categóricas. 1.5 Enriquecimiento de Datos 🌟: Creación de nuevas variables a partir de los datos existentes. 1.6 Consolidación de Datos 📚: Combinación de datos en un único dataset para el análisis.

Estado Actual 🚧
Limpieza y Transformación: Completadas.
Análisis Exploratorio de Datos (EDA): Realizado, revelando insights clave sobre el engagement.
Conclusiones del EDA 📝
Tipo de Publicación: Las publicaciones con múltiples imágenes generan el mayor engagement, mientras que los videos tienen los valores más bajos de interacción.
Longitud del Texto y Sentimiento: No muestran un impacto significativo en el engagement.
Horario de Publicación: Los mejores horarios son a las 13:00, 01:00 y 21:00.
Relación Followers y Engagement: Las cuentas con entre 1,000 y 10,000 seguidores presentan el mayor engagement. El engagement rate disminuye ligeramente al aumentar el número de seguidores.
Correlaciones: Fuerte correlación positiva entre el engagement rate y los likes; correlación moderada entre likes y comments, así como entre likes y followers.
En resumen, las publicaciones con múltiples imágenes son las más efectivas, y los mejores horarios para publicar son a las 13:00, 01:00 y 21:00. Las cuentas con 1,000 a 10,000 seguidores obtienen el mayor engagement.

Modelado Predictivo 🔮
Modelos Implementados
Se implementaron varios modelos de clasificación y regresión para predecir y clasificar el engagement, con un enfoque en el modelo de Decision Tree combinado con Gradient Boosting, el cual mostró el mejor rendimiento.

Modelos de Clasificación
Se desarrollaron y evaluaron varios modelos para clasificar el engagement:

Decision Tree (con Gradient Boosting): Mejor rendimiento, alcanzando un accuracy de hasta 64% después de ajustes y optimizaciones.
Otros modelos probados: Random Forest, Regresión Logística, K-Nearest Neighbors, SVM.
Modelos de Regresión
Para predecir el número de likes y el engagement rate se probaron:

RandomForestRegressor: MAE 0.273681, MSE 0.164302, R² 0.408202.
Otros modelos probados: Regresión Lineal, Support Vector Regression (SVR), GradientBoostingRegressor.
Aunque RandomForestRegressor ofreció el mejor desempeño en regresión, el modelo de clasificación con Decision Tree y Gradient Boosting fue el más efectivo en general para categorizar el engagement.

Resultados Comparativos y Conclusión Final 🏆
Decision Tree (Gradient Boosting) - Clasificación:
Accuracy: 64%
Precision: 0.62 (promedio macro)
Recall: 0.61 (promedio macro)
Curva ROC: AUC de 0.79 a 0.87, indicando buen desempeño en la clasificación de engagement.
RandomForestRegressor - Regresión:
MAE: 0.273681
MSE: 0.164302
R²: 0.408202
En conclusión, el modelo de Decision Tree con Gradient Boosting fue el mejor para predecir categorías de engagement en Instagram, superando a otros modelos en términos de precisión y desempeño general.

Próximos pasos y cierre 🌟
Mejoras futuras: A medida que se recopilen más datos y se identifiquen nuevas tendencias en el comportamiento de los seguidores, el modelo podrá adaptarse y mejorar, ofreciendo recomendaciones cada vez más precisas para maximizar el engagement. Esto permitirá ajustar las estrategias de contenido en Instagram, ayudando a las cuentas a mantenerse relevantes y efectivas en sus interacciones.

Este proyecto ha sido una experiencia enriquecedora, y aunque no alcancé métricas "perfectas", disfruté mucho cada etapa del proceso. Agregaré este proyecto a mi portafolio, ya que representa todos los conocimientos que he adquirido en ciencia de datos hasta ahora. Agradezco profundamente a mi profesor y a los tutores por su dedicación y apoyo constante, quienes nos inspiran a seguir avanzando en este fascinante camino hacia la ciencia de los datos. Queda camino por recorrer, pero la cima está cada vez más cerca.

¡Gracias por todo y nos vemos en el siguiente desafío! 🚀


---


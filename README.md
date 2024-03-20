<center><h1>ProyectoBedu:HeartSmart</h1></center>
<center><h5>Modelo que determina el porcentaje de probabilidad de una persona de padecer un ataque cardiaco e imagenes relacionada a la salud del corazón </h5></center>
<hr>

![Logo de mi proyecto](https://github.com/DYI-murri/ProyectoBedu/blob/main/Recursos/Fondo%20de%20pantalla%20horizontal%20collage%20de%20fotos%20saturado%20color%20marr%C3%B3n.png)

Este proyecto se divide en dos implementaciones distintas. En una de ellas, se centra en determinar el porcentaje de probabilidad que tiene una persona de padecer un ataque cardíaco. En la otra, se entrena un modelo de clasificación de imágenes relacionadas con la salud del corazón, como los electrocardiogramas (ECG).Para obtener una visión más completa del proyecto, que incluye este proyecto, puedes acceder a la presentación a través de este enlace: https://www.canva.com/design/DAF_mR20zbE/gxZF3-UJmknkhJOcb74ObQ/view?utm_content=DAF_mR20zbE&utm_campaign=designshare&utm_medium=link&utm_source=editor

<center><h2>Objetivo del proyecto</h2></center>
El proyecto "HeartSmart" tiene como objetivo principal desarrollar un modelo de machine learning que determine con precisión la probabilidad de que un individuo sea susceptible a problemas cardíacos graves. Este modelo utilizará datos de salud y biométricos para realizar predicciones personalizadas sobre el riesgo de enfermedades cardíacas, permitiendo así una intervención temprana y preventiva para mejorar la salud cardiovascular de los individuos.Esto ayudará a educar y concienciar a las personas sobre la importancia de la salud cardíaca y promoverá cambios positivos en el estilo de vida para prevenir enfermedades cardíacas. 


<center><h2>Justificacion</h2></center>
La justificación para llevar a cabo el proyecto "HeartSmart" radica en la creciente prevalencia de enfermedades cardíacas y la necesidad de herramientas avanzadas para su detección temprana y prevención. Las enfermedades cardíacas son una de las principales causas de morbilidad y mortalidad en todo el mundo, y muchas de estas condiciones pueden prevenirse con cambios en el estilo de vida y una intervención médica oportuna. El desarrollo de un modelo de machine learning preciso para predecir el riesgo de enfermedades cardíacas puede permitir una identificación temprana de personas en riesgo, lo que a su vez puede facilitar intervenciones preventivas, como cambios en la dieta, aumento de la actividad física y seguimiento médico regular. 

<center><h2>Problemática</h2></center>

La problemática detrás del proyecto "HeartSmart" reside en la creciente prevalencia de enfermedades cardíacas y la necesidad urgente de mejorar la detección temprana, la prevención y la educación sobre la salud cardiovascular. A nivel mundial, las enfermedades cardíacas representan una de las principales causas de morbilidad y mortalidad, sin embargo, la falta de herramientas precisas y personalizadas para evaluar el riesgo individual y la escasez de información y educación sobre la salud del corazón contribuyen a la identificación tardía y al subtratamiento de estas enfermedades. En respuesta, el proyecto "HeartSmart" busca abordar esta problemática mediante el desarrollo de modelos de machine learning para una detección más precisa del riesgo cardiovascular, junto con herramientas educativas personalizadas, con el fin de reducir la carga de enfermedades cardíacas y mejorar la calidad de vida de las personas. 


<center><h2>Descripcion del contenido del proyecto</h2></center>
El proyecto consta de un notebook que se encuentra dentro de la carpeta 'Proyecto' y el archivo denominado 'Proyecto SmartHeart' en este repositorio. Este archivo está dividido por secciones para una mejor organización y comprensión del proyecto:

<h4>Sección 1: Información sobre los datasets utilizados</h4>
En esta sección, se proporciona información detallada sobre los conjuntos de datos utilizados en el proyecto. Se explora cómo se recopiló la información y se contextualiza dentro del dataset.Para obtener más detalles sobre la recolección de datos y el contexto del dataset, se brindará información específica en esta sección.


<h4>Sección 2: Importación de Librerías y Extracción de Datos</h4>

En esta sección, se realizan dos tareas fundamentales para el desarrollo del proyecto. En primer lugar, se importan las librerías necesarias para llevar a cabo el análisis y la implementación del modelo. Luego, se procede a la extracción de los datos del dataset, preparándolos para su posterior análisis y procesamiento.La importación de las librerías adecuadas es esencial para garantizar que todas las funciones y métodos requeridos estén disponibles durante el desarrollo del proyecto. Además, la extracción de datos del dataset proporciona el punto de partida necesario para comenzar a explorar y trabajar con la información relevante.

<h4>Sección 3: Limpieza de Datos</h4>
En esta sección, se lleva a cabo el proceso de limpieza de datos, que incluye la identificación y manejo de datos duplicados, así como la clasificación de los tipos de variables presentes en el dataset. Además, se realiza la conversión de variables categóricas a tipo objeto para su posterior uso en el análisis.La eliminación de datos duplicados es crucial para garantizar la integridad y precisión de los resultados del análisis. Asimismo, la correcta clasificación de los tipos de variables facilita el procesamiento y análisis de los datos. La conversión de variables categóricas a tipo objeto es un paso importante para preparar los datos para su uso en modelos de análisis y visualización.

<h4>Sección 3: Análisis y Exploración de Datos</h4>
En esta sección, se realiza un análisis exhaustivo de los datos utilizando diversas técnicas y herramientas. Se comienza con el método describe() para obtener estadísticas descriptivas clave, como promedio, moda, desviación estándar y rango intercuartílico.Posteriormente, se profundiza en el análisis mediante la utilización de gráficos como boxplots, violinplots, scatterplots, histogramas y gráficas de barras. Estas visualizaciones proporcionan una comprensión más clara de la distribución y las relaciones entre las variables, lo que permite identificar patrones y tendencias significativas en los datos.Este análisis y exploración detallados son fundamentales para obtener información valiosa sobre el conjunto de datos y proporcionan una base sólida para el desarrollo de modelos y la toma de decisiones posteriores.

<h4>Sección 4: Bootstrap</h4>
En esta sección, se aplica la técnica de bootstrap para estimar la distribución de una estadística de interés a partir de datos de muestra. Se realiza un análisis detallado de la distribución utilizando intervalos de confianza y frecuencia.El método de bootstrap es una técnica de remuestreo que permite generar múltiples muestras de los datos originales, lo que proporciona una estimación robusta de la distribución de la estadística de interés. Se exploran los intervalos de confianza para evaluar la incertidumbre en las estimaciones y se analizan las frecuencias para comprender la variabilidad de los resultados.El uso de bootstrap proporciona una herramienta poderosa para la inferencia estadística y permite tomar decisiones fundamentadas basadas en la distribución de los datos.

<h4>Sección 4: Procesamiento de Datos</h4>
En esta sección, se lleva a cabo el procesamiento de datos utilizando las técnicas de Ordinal Encoder y MinMaxScaler.
El Ordinal Encoder se utiliza para codificar variables categóricas en variables numéricas ordinales, lo que permite que los algoritmos de aprendizaje automático trabajen de manera efectiva con estas variables.
Por otro lado, el MinMaxScaler se emplea para escalar características numéricas en un rango específico, generalmente entre 0 y 1. Esto ayuda a reducir la disparidad en las magnitudes de las características y mejora la convergencia de los algoritmos de aprendizaje automático.
El procesamiento de datos es una etapa crucial en el flujo de trabajo de análisis de datos, ya que prepara los datos de manera adecuada para su posterior modelado y análisis.

<h4>Sección 5: Selección de Características</h4>

En esta sección, se exploran diversas técnicas de selección de características para identificar las variables más relevantes para el modelo. Se utilizan métodos como la correlación de Pearson, Recursive Feature Elimination with Cross-Validation (RFE-CV), Selección de características con Random Forest y Selección de características con Árboles de Decisión.
La correlación de Pearson se emplea para medir la relación lineal entre variables numéricas, identificando aquellas con mayor correlación con la variable objetivo. El método RFE-CV realiza una selección iterativa de características utilizando validación cruzada para encontrar el conjunto óptimo de características.Además, se utilizan modelos de aprendizaje automático como Random Forest y Árboles de Decisión para evaluar la importancia de las características y seleccionar las más relevantes para el modelo final.Esta selección de características es fundamental para mejorar la eficiencia y la precisión del modelo, al reducir la dimensionalidad y eliminar características irrelevantes o redundantes.

<h4>Sección 6: Entrenamiento de Modelos</h4>
En esta sección, se lleva a cabo el entrenamiento de varios modelos utilizando la biblioteca Lazypredict. Se comparan y evalúan simultáneamente diversos modelos, incluyendo ExtraTreesRegressor, DecisionTreeRegressor, XGBRegressor, RandomForestRegressor, BaggingRegressor, y otros.
A continuación, se muestran los resultados de la evaluación de los modelos, incluyendo métricas como el coeficiente de determinación (R²), el error cuadrático medio (MSE), y el tiempo de entrenamiento. Estos resultados proporcionan una visión general del rendimiento de cada modelo y ayudan a seleccionar el más adecuado para la tarea de predicción de la probabilidad de padecer un ataque cardíaco.

|Modelo	|R²	|MSE	|Tiempo de Entrenamiento (segundos)|
|ExtraTreesRegressor	|0.90|	0.09	|0.24|
|DecisionTreeRegressor|	0.90|	0.09|	0.02|
|XGBRegressor|	0.90	|0.09|	0.21|
|RandomForestRegressor|	0.88|	0.10|	0.34|
|BaggingRegressor|	0.86|	0.11|	0.06|

Estos resultados son fundamentales para seleccionar el modelo más adecuado para la tarea de predicción y brindan información valiosa sobre su desempeño y eficiencia.


<h4>Sección 7: Optimización de Modelos</h4>
En esta sección, se realiza la optimización de los parámetros de los mejores modelos seleccionados utilizando la técnica Grid Search. Esta técnica permite explorar exhaustivamente un espacio de búsqueda de hiperparámetros para encontrar la combinación óptima que maximice el rendimiento del modelo.

Se emplea la biblioteca Scikit-learn para llevar a cabo la búsqueda en la cuadrícula, ajustando los parámetros de los modelos seleccionados a través de validación cruzada. Se exploran diferentes combinaciones de parámetros para determinar aquellas que maximizan las métricas de evaluación, como el coeficiente de determinación (R²) o el error cuadrático medio (MSE).

La optimización de los modelos es un paso crucial en el desarrollo de un sistema de aprendizaje automático, ya que permite mejorar su rendimiento y precisión al ajustar los parámetros de manera óptima para los datos específicos del problema.


<h4>Modelo No Supervisado</h4>
En esta sección, se lleva a cabo una implementación de clustering utilizando el algoritmo K-Means. El clustering es una técnica de aprendizaje no supervisado que agrupa datos similares en clusters o grupos.

El algoritmo K-Means es uno de los métodos de clustering más utilizados y eficientes. Se basa en la partición de los datos en k grupos, donde k es un parámetro predefinido. El objetivo es minimizar la varianza dentro de cada grupo y maximizar la distancia entre los grupos.

Se utiliza la implementación de K-Means de la biblioteca Scikit-learn para agrupar los datos en clusters. Se exploran diferentes valores de k y se evalúa la calidad del clustering utilizando métricas como la inercia o el coeficiente de silueta.

La implementación de clustering con K-Means proporciona una forma efectiva de explorar la estructura subyacente de los datos y puede revelar patrones interesantes o grupos naturales en los datos sin etiquetar.


<h4>Implementación de Imágenes</h4>
En esta sección, se lleva a cabo la implementación de un modelo de redes neuronales convolucionales (CNN) para la clasificación de imágenes. Se extrae un conjunto de imágenes, se preprocesan y se utilizan para entrenar el modelo CNN.

Durante el entrenamiento del modelo CNN, se observan los registros de entrenamiento y validación, como la pérdida y la precisión, a lo largo de cada época. Por ejemplo, al final del entrenamiento se pueden ver registros como:

Epoch 100/100
21/21 [==============================] - 0s 24ms/step - loss: 5.6349e-04 - accuracy: 1.0000 - val_loss: 1.1951 - val_accuracy: 0.7626

Estos registros muestran la pérdida y la precisión tanto en el conjunto de entrenamiento como en el conjunto de validación.

Después del entrenamiento, se evalúa el modelo utilizando un conjunto de prueba separado y se observan métricas como la pérdida y la precisión en este conjunto de prueba. Por ejemplo:

5/5 [==============================] - 0s 8ms/step - loss: 0.5694 - accuracy: 0.8786
Pérdida en el conjunto de prueba: 0.5694392919540405
Precisión en el conjunto de prueba: 0.8785714507102966

Estos registros muestran la pérdida y la precisión en el conjunto de prueba, lo que proporciona una evaluación final del rendimiento del modelo CNN en datos no vistos.

La implementación de imágenes y el entrenamiento de modelos CNN son fundamentales para tareas de clasificación de imágenes y pueden proporcionar soluciones efectivas para una variedad de problemas en el campo de la visión por computadora.   


<h4>Conclusiones</h4>
En resumen, los modelos basados en árboles, como ExtraTreesRegressor, DecisionTreeRegressor y XGBRegressor, destacan por su excelente rendimiento, con puntajes R² cercanos a 0.90. Estos modelos superan claramente a otros, como MLPRegressor, SVR y GradientBoostingRegressor.

Por otro lado, el modelo de imágenes muestra un bajo valor de pérdida en el conjunto de prueba y una alta precisión del 81.43%. Esto indica una capacidad efectiva para predecir la probabilidad de un ataque cardíaco basándose en imágenes de ECG.

Estos resultados sugieren que tanto los modelos de aprendizaje supervisado como el modelo de imágenes tienen un rendimiento prometedor en la predicción de la probabilidad de padecer un ataque cardíaco. Sin embargo, es importante realizar una evaluación más detallada y comparativa de los modelos antes de tomar decisiones finales sobre su implementación en un entorno de producción.

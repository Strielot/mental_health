ESPAÑOL


Introducción:

La principal idea de esta investigación, es predecir bajo cierta información, si una persona ha asistido a un especialista de salud mental, o si está dentro del denominador común de asistencia.

Se analizaron en conjunto a especialistas, preguntas que tengan que ver directamente con el estado de salud mental de un individuo, para coincidir si es efectivo que se ha ido a terapia, o sus pares similares han asistido, preguntas como historial familiar, ocupación, hábitos, vida social, etc.

Se genera una red neuronal para poder hacer un aprendizaje automático de los parámetros y poder definir el estado actual segun el cuestionario.


Dónde se encuentran éstos Datos?

Éstos datos se encuentran directamete desde el sitio de Kaggle:

https://www.kaggle.com/datasets/bhavikjikadara/mental-health-dataset


Método de uso:

El código consta de 3 grandes partes a poder modificar.

El primero se encuenta en la experimentación de la mejor red neuronal, los hiperparámetros que se probar son disminuidos, pero si se quiere llegar a una mejor predicción, se pueden usar más parámetros. 
Desde la lista de "parameters" en nuestra configuración de red neuronal, podemos setear los parámetros que queremos investigar para dar con el mejor modelo, se puden probar incluso desde la construcción de la red secuencial con nuevas capas.

La segunda parte se encuentra luego en la lista de aprendizaje automático, en la cual podemos incorporar en la lista distintos modelos, y ponerlos a prueba para poder comprobar qué modelo funciona mejor con nuestra información. Si se quieren agregar nuevos modelos a probar, se deben ingresar desde el diccionario "model_list"

Para terminar, podemos ingresar una predicción, para esto solamente basta con crear una lista de respuestas a los atributos que se han entrenado, y poner a prueba nuestro modelo para conseguir los resultados. De momento se han realizado 2 pruebas, una con un elemento de nuestra lista positiva y una negativa.


Resultados:

Los Resultados demuestran que en las predicciones cumplen con los porcentajes óptimos, en ambos modelos usados en conjunto, lo que le da una mayor fuerza a la hipótesis generada. Es importante destacar que éste proceso no es definitivo, y que los expertos que participaron en esta investigación pusieron un énfasis en que bajo ningun concepto se debia hacer caso absoluto a este resultado, si bien es preventivo, se debe realizar un análisis más profundo caso a caso, pero se puede integrar como resultados prioritarios a tratar.

Dentro de mi aprendizaje automático tenemos a Naive Bayes con un alto recall, de 1. Puede ser que tengamos un caso de overfitting (sobre todo por el nivel de loss) y estémos obteniendo muchos positivos, esto reduce drásticamente la precisión.


Alcance de la información:

En el estudio podemos extender éste análisis a personas que tengan una primera orientación en temas de salud, o presenten algun síntoma relacionado con salud mental, logrando asi facilitar un estudio preventivo y poder derivar a un paciente a un respectivo análisis a través de una encuesta. También dentro de la encuesta se puede extender con nuevas preguntas, haciendo incluso más detallado el análisis.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

ENGLISH

Introduction:
The main idea of this research is to predict, based on certain information, whether a person has visited a mental health specialist or falls within the common denominator of those who have sought assistance.

Specialists collaborated to analyze the survey, to have it directly related to an individual's mental health status, to determine if it is effective to infer whether they have attended therapy or if their peers with similar profiles have. These questions include family history, occupation, habits, social life, etc.

A neural network is generated to perform machine learning on the parameters and define the current state according to the survey.

Where is this Data Located?

This data is available directly from the Kaggle website:

https://www.kaggle.com/datasets/bhavikjikadara/mental-health-dataset

Method of Use:

The code consists of three major parts.

The first one involves experimenting with the best neural network. The hyperparameters tested are just few, but if better predictions are desired, more parameters can be used. From the "parameters" list in our neural network configuration, we can set the parameters we want to investigate to find the best model. New layers can also be tested in the sequential network construction.

The second part is in the machine learning list, where we can incorporate different models and test them to see which one works best with our data, if new ones want to be added, the "model_list" dictionary should be modified.

Finally, we can make a prediction by simply creating a list of responses and test our model to get the results. So far, two tests have been conducted, one with a positive element from our list and a negative one.

Results:

The results show that the predictions meet optimal percentages in both models used together, giving more strength to the generated hypothesis. It is important to highlight that this process is not definitive, and the experts who participated in this research emphasized that these results should not be taken as absolute. While they are preventive, a more in-depth analysis should be conducted on a case-by-case basis. However, these results can be integrated as priority findings to address.

In our machine learning, we have Naive Bayes with a high recall of 1. This may indicate overfitting (especially due to the level of loss) and we may be obtaining many positives, which drastically reduces precision.

Scope of the Information:

This study can be extended to people seeking initial guidance on health issues or presenting symptoms related to mental health, facilitating a preventive study and enabling a patient to be referred for a respective analysis through a survey. The survey can also be extended with new questions, making the analysis even more detailed.


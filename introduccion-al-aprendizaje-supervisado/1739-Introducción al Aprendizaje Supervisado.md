### 
## Objetivos de aprendizaje

* ¿Qué es el aprendizaje automático?
* Categorización de aprendizaje automático
* Clasificación y regresión
* Clasificación binaria y multiclase


## ¿Qué es el aprendizaje automático?
<iframe width="560" height="315" src="https://www.youtube.com/embed/gmvvaobm7eQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Categorización del aprendizaje automático

![ML Categorization.png](https://dphi-live.s3.amazonaws.com/media_uploads/ML_Categorization_f99b6268dba44106851425bf55fcb584.png)


## Algoritmos de aprendizaje supervisado

Hablemos de los conjuntos de datos que tienen variables de entrada y de destino (etiquetas para los datos), desde la predicción de la tasa de supervivencia de una persona en el conjunto de datos Titanic, donde ya se da la tasa de supervivencia, hasta la predicción del precio de la vivienda según las características de la misma, donde se proporcionan los precios de la vivienda.

Los algoritmos que trabajan con estos conjuntos de datos se conocen como algoritmos de aprendizaje supervisado.

Se llama aprendizaje supervisado porque el proceso de aprendizaje de un algoritmo a partir del conjunto de datos de entrenamiento puede considerarse como un profesor que supervisa el proceso de aprendizaje. Conocemos las respuestas correctas; el algoritmo realiza iterativamente predicciones sobre los datos de entrenamiento y es corregido por el profesor. El aprendizaje se detiene cuando el algoritmo alcanza un nivel de rendimiento aceptable.

## Algoritmos de aprendizaje no supervisado

El aprendizaje no supervisado es aquel en el que hay datos no etiquetados (o ninguna variable destino) en el conjunto de datos.

Los algoritmos de aprendizaje no supervisado pretenden encontrar alguna estructura en el conjunto de datos.

Se denominan aprendizaje no supervisado porque, a diferencia del aprendizaje supervisado, no hay respuestas correctas y no hay un profesor. Los algoritmos se dejan solos para descubrir y presentar la estructura interesante en los datos.

## Algoritmos de aprendizaje por refuerzo

Un robot da un gran paso adelante y luego se cae. La siguiente vez, da un paso más pequeño y es capaz de mantener el equilibrio. El robot intenta variaciones como ésta muchas veces; finalmente, aprende el tamaño correcto de los pasos que debe dar y camina con firmeza. Ha tenido éxito.

Lo que vemos aquí se llama aprendizaje por refuerzo. El robot aprende a caminar en función de la recompensa (mantenerse en equilibrio) y el castigo (caerse). Esta retroalimentación se considera "refuerzo" por hacer o no hacer una acción.

En términos sencillos, el aprendizaje por refuerzo consiste en aprender las mejores acciones en función de la recompensa o el castigo.

## Tipos de algoritmos de aprendizaje supervisado

El aprendizaje supervisado puede dividirse a su vez en dos tipos:

* Clasificación
* Regresión

## Clasificación vs Regresión

![regression.png](https://dphi-live.s3.amazonaws.com/media_uploads/regression_1414d8e4641141be9e72202a67804f52.png)
![clasificacion.png](https://dphi-live.s3.amazonaws.com/media_uploads/clasificacion_ed5917b7f5084d7fa0c02d93a15dba93.png)

Para decidir si usar un modelo de regresión o de clasificación, la primera pregunta que debes hacerte es:

¿Su variable objetivo tiene un valor continuo o es discreta (binaria o multiclase)?

## Regresión
Si la respuesta es un valor continuo, se trata de una regresión.

Si está tratando de predecir cantidades como la altura, los ingresos, el precio o las puntuaciones, debe utilizar un modelo que dé como resultado un número continuo.

Así, si su objetivo es determinar la temperatura de mañana, debe utilizar un modelo de regresión.

## Clasificación

Pasemos al segundo caso, en el que puede ver que la variable objetivo está dividida en clases. Utilizarás la clasificación.

* Cuando el número de clases es 2, se conoce como Clasificación binaria. Por ejemplo, si mañana hará frío o calor es un problema de clasificación binaria con dos categorías: Caliente y Frío.

* Cuando el número de clases es superior a 2, se denomina clasificación multiclase. Por ejemplo, clasificar las películas como buenas, regulares o malas según las críticas.

![clasificacion-rregresion.png](https://dphi-live.s3.amazonaws.com/media_uploads/clasificacion-rregresion_268c8ae5392b4a69a5c200042db94d30.png)

Entender las características de su variable objetivo es esencial antes de empezar a ejecutar modelos y formar predicciones.

**En este curso, nos centraremos en la clasificación.
**

## Introducción al Machine Learning

### Validación cruzada

Es una técnica que se utiliza para evaluar el rendimiento de un modelo de aprendizaje automático. Consiste en dividir los datos en una parte para entrenamiento, luego, entrenar el modelo y evaluarlo con los datos restantes.

La validación cruzada es una buena manera de estimar el rendimiento del modelo en datos nuevos. Supongamos que tenemos un conjunto de datos de entrenamiento con 1.000 elementos. Si utilizamos la validación cruzada, dividiremos 800 datos para entrenamiento y con los 200 restantes evaluaremos el rendimiento del modelo.

### Subentrenamiento

Es un problema que ocurre cuando un modelo no se adapta lo suficiente a los datos de entrenamiento. El subentrenamiento puede hacer que el modelo sea malo para predecir los datos de entrenamiento y los datos nuevos.

El subentrenamiento se puede causar por varios factores como:

* La falta de datos de entrenamiento.
* La separación de los datos de entrenamiento y prueba.
* La selección de un modelo demasiado simple.

### Error de bias y error de varianza

Ambos errores pueden afectar negativamente el rendimiento del modelo de aprendizaje automático. Un modelo con estos tipos de errores puede ser más propenso a fallar en los datos que no se parecen a los datos de entrenamiento.

### Tipos de aprendizaje automático

Hay 2 tipos principales: Aprendizaje supervisado y no supervisado.

* **Aprendizaje Supervisado:** Los algoritmos aprenden de los datos que están etiquetados. Esto significa que los datos tienen un valor de salida conocido que el algoritmo puede utilizar para aprender.
  
  Ejemplo: Un algoritmo de aprendizaje supervisado que se puede utilizar para predecir el precio de una casa en función de su tamaño, número de habitaciones y ubicación.

* **Aprendizaje NO Supervisado:** Los algoritmos aprenden de los datos que no están etiquetados. Esto significa que los datos no tienen un valor de salida conocido y el algoritmo debe descubrir los patrones en los datos por sí mismo.


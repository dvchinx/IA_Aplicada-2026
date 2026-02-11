
## Datos e introducción a la programación

### La importancia de los datos en la IA

Los datos son el alma de la inteligencia artificial. Sin datos de calidad, los modelos de IA no pueden aprender ni tomar decisiones precisas.

Datos limpios y representativos son cruciales para la formación de modelos de IA efectivos.

La recopilación, limpieza y etiquetado de datos son pasos críticos en el proceso de construcción de modelos de IA.

### Los diferentes tipos de datos en la IA

Los datos son un pilar fundamental. En esta sección, exploraremos los diversos tipos de datos que se utilizan en IA y cómo se clasifican en estructurados y no estructurados.

* **Datos estructurados:** Se presentan en tablas o bases de datos con una organización predefinida. Son altamente organizados y fáciles de procesar.
  
  Ej: Datos en una hoja de cálculo con columnas para nombre, edad y dirección.

* **Datos no estructurados:** Carecen de una organización predefinida y pueden presentarse en diversas formas, como texto, imágenes o audio.
  
  Ej: Son comunes en aplicaciones de NLP, visión por computadora y reconocimiento de voz.

### Aplicaciones de datos estructurados

Son esenciales en áreas como la toma de decisiones empresariales, análisis financiero y predicción de tendencias.

**Ejemplo:** Uso de datos estructurados en la detección de fraudes bancarios.

* Ideales para modelar relaciones y tendencias cuantificables.
* Los algoritmos de IA pueden procesar grandes volúmenes de datos estructuras de manera eficiente.

### Aplicaciones de datos no estructurados

Se encuentran desde el análisis de sentimientos en redes sociales hasta la interpretación de imágenes médicas.

**Ejemplo:** Detección de sueño o cansancio en conductores de vehículos.

* Generalmente, usa técnicas avanzadas de IA, como el aprendizaje profundo (deep learning).
* Pueden revelar información valiosa en áreas como el diagnóstico médico, traductores, chatbots, entre otros.

### Clasificación de datos según su naturaleza

**Cualitativos:** Se refieren a cualidades o modalidades que no pueden expresarse numéricamente. Pueden clasificarse en los siguientes:

* **Ordinales:** Si siguen un orden o una secuencia. 
  Ej: El abecedario, los meses del año, entre otros.
* **Categóricos:** Si no siguen ningún orden. 
  Ej: El estado civil de las personas: Soltero, casado, viudo, ...

**Cuantitativos:** Se refieren a cantidades o valores números. Pueden clasificarse en los siguientes:

* **Discretos:** Si toman valores enteros (0, 1, 2, 3, ...).
  Ej: El número de hijos, número de alumnas, entre otros.
* **Continuos:** Si pueden tomar cualquier valor dentro de un intervalo.
  Ej: La estatura, el peso de una persona, entre otros.

### Importancia de la verificación de calidad de los datos

Antes de utilizar datos en proyectos de IA, es crucial verificar su calidad. La presencia de datos incorrectos o atípicos puede afectar significativamente el rendimiento de los modelos.

**Ejemplo:** Datos de sensores médicos de un sistema de diagnóstico.

* La calidad de los datos influye en la precisión y confiabilidad de los resultados de IA. 
* La verificación de calidad de los datos incluye la ==limpieza, la validación y la transformación de datos==.

### Detección de datos atípicos

La detección de datos atípicos es esencial para identificar valores inusuales o anómalos en un conjunto de datos.

**Ejemplo:** Edades menores a la edad permitida para votar en una base de datos de personas.

* Los datos atípicos pueden surgir debido a errores, fraudes o condiciones excepcionales.
* Los datos atípicos pueden contener información valiosa sobre eventos raros como la detección de fraudes. ==Es importante entender el contexto==.

### Tratamiento de datos atípicos

Una estrategia consiste en ==reemplazar== los datos atípicos con valores correctos, percentiles, valores del dominio o incluso predicciones de modelos.

* El reemplazo depende de la naturaleza de los datos y la disponibilidad de información de referencia.
* El reemplazo puede ayudar a preservar la integridad del conjunto de datos.

La ==remoción== es otra opción que puede ser efectiva cuando los datos atípicos son erróneos. Sin embargo, esta debe realizarse con cuidado, ya que puede llevar a la pérdida de información valiosa.

### Detección de datos faltantes

La detección de datos perdidos es el primer paso para garantizar la calidad de los datos. Existen varias formas de detectar datos faltantes, ya sea a través de ==inspección manual== o mediante la generación de ==informes== específicos.

+ La detección temprana de datos perdidos es esencial para evitar sesgos y resultados incorrectos en análisis de IA.
+ Los informes de datos perdidos proporcionan una visión general de la cantidad y ubicación de datos faltantes.

### Estrategias de manejo de datos faltantes

Existe la eliminación, imputación y consideración de datos perdidos como una categoría.

* **Eliminación:** Eliminar casos o variables con datos perdidos. Esto puede ==simplificar== el conjunto de datos, pero también conlleva a la ==pérdida de información==.

* **Categoría:** En algunos casos, los ==datos perdidos== pueden considerarse como una ==categoría== válida, lo que permite preservar la información sobre la ausencia de datos.

* **Imputación:** Se refiere a imputar valores faltantes utilizando técnicas como la media, un valor constante u otro método más avanzado.
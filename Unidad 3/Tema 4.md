
## Introducción a los Algoritmos de Aprendizaje Automático no Supervisado

### K-means

Funciona eligiendo k crentroides al azar y luego asignando cada punto de datos al grupo cuyo centroide está más cerca. El algoritmo luego actualiza los centroides para que representen el centro de los puntos de datos en cada grupo.

Este proceso se repite hasta que los datos estén bien agrupados.

### DBSCAN

Density-based spatial clustering of applications with noise (DBSCAN), es un algoritmo de agrupación que se basa en la densidad de los datos.

Identifica los puntos de datos que son densamente conectados. Estos puntos de datos se denominan puntos núcleo. Los puntos de datos que no son puntos núcleo se agrupan en grupos basados en la densidad de sus vecinos.

### Hierarchical clustering

Es un algoritmo de agrupación que construye una jerarquía de grupos. Comienza dividiendo los datos en dos grupos. Luego, cada grupo se divide en subgrupos y este proceso continúa hasta que todos los datos estén en grupos individuales.

Puede ser jerárquico aglomerativo o jerárquico divisivo.

### PCA - Principal component analysis

Es un algoritmo de reducción de dimensionalidad que conserva la mayor varianza posible en los datos.

Calcula las direcciones principales de varianza en los datos y, luego, proyecta los datos en estas direcciones. PCA se puede utilizar para reducir el número de variables en un conjunto de datos sin perder información.

### Clusting-based anomaly detection

Es un enfoque para la detección de anomalías que utiliza algoritmos de agrupación.

Funciona agrupando los datos en grupos normales. Luego, los datos que no pertenecen a ningún grupo normal se consideran anomalías, lo que es esencial en la detección de fraudes y la ciberseguridad.


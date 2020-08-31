# Análisis Inteligente de Datos

## Trabajo Final: Métodos de Clasificación

### Supervisada: bajopeso (target=LOW)
a.1- Elija y justifique las variables que considere pertinentes para la clasificación.
a.2- Pruebe al menos dos métodos de clasificación distintos y compare la bondad de
clasificación de cada uno de los métodos mediante un algoritmo no ingenuo (matriz de
confusión mínimamente).
a.3- Analice el cumplimiento de los supuestos si fuera necesario y en caso de cumplirse utilice
un algoritmo robusto.
a.4- Concluya en términos del problema con qué algoritmo se quedaría y por qué.

### No Supervisada: seguros

b.1- Seleccione las variables pertinentes y la distancia que va a utilizar.
b.2- Utilice al menos dos algoritmos para realizar una clusterización.
b.3- Decida criteriosamente la cantidad de clusters.
b.4- Elija una clusterización y explique las características de los agrupamientos logrados.

## Estructura

- seeding.Rmd: código en R con la implementación de los criterios de partición de los datos originales acordes al seed 37754499
- supervised.Rmd: código en R con el análisis exploratorio del dataset bajopeso y la implementación de las distintas clasificaciones supervisadas.
- non_supervised.Rmd: código en R con el análisis exploratorio del dataset seguros y la implementación de las distintas clasificaciones no supervisadas.
- resources: carpeta conteniendo los distintos recursos a ser utilizado para el desarrollo. Contiene tanto los datasets de partición generados bajopeso.csv y seguros.csv como la segmentación de datos en train y validation para el análisis de clasificación supervisada:
  - bajopeso_train.csv
  - bajopeso_val.csv
  - bajopeso_train_acm.csv
  - bajopeso_val_acm.csv


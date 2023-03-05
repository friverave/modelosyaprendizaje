# modelosyaprendizaje
Prueba Final

El presente proyecto, consistió en predecir si una masa localizada en las mamas es benigno o maligno. 
El análisis se realizó en la base de datos de breast_cancer_wisconsin.csv. (https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29).
Primero se procedió a revisar como se encontraba la base de datos, nombrar cada columna y eliminar los datos marcados con "?".
Con la información filtrada se realizó un histograma donde se puede analizar visualmente la cantidades de casos positivos con tumor maligno y negativos con tumor benigno. 
En segundo lugar se dividió la base de datos en traing con 80% y test con el 20%. Se entrenaron tres algoritmos: Randomforest, KNN y Regresión Logística.
Finalmente se evaluó con la matriz de confusión en el set de prueba y en el set de entrenamiento, teniendo como resultados que el mejor modelo aplicado es el de Randomforest. Las mètricas obtenidas son las siguientes: 

SET DE ENTRENAMIENTO

|METRICA| RANDOM FOREST | KNN | REGRESION LOGISTICA |
| ------------- | ------------- | ------------- | ------------- |
| VERDADERO NEGATIVO  | 351  | 309  | 351  |
| FALSO POSITIVO  | 0  | 42  | 0  |
| FALSO NEGATIVO  | 0  | 102  | 194  |
| VERDADERO POSITIVO  | 194 | 92  | 0  |

SET DE PRUEBA

|METRICA| RANDOM FOREST | KNN | REGRESION LOGISTICA |
| ------------- | ------------- | ------------- | ------------- |
| VERDADERO NEGATIVO  | 90  | 72  | 92  |
| FALSO POSITIVO  | 2  | 20  | 0  |
| FALSO NEGATIVO  | 0  | 28  | 45  |
| VERDADERO POSITIVO  | 45  | 17  | 0  |

En base a los resultados, se puede observar que el modelo randomforest es el que logra minimizar los falsos negativos tanto como en el set de entreamiento como en el set de prubea. Cuyo error es el más grave y el que se tiene que poner más atención.

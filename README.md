# modelosyaprendizaje
Prueba Final
El presente proyecto, consistió en predecir si una masa localizada en las mamas es benigno o maligno. 
El análisis se realizó en la base de datos de breast_cancer_wisconsin.csv. (https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29).
Primero se procedió a revisar como se encontraba la base de datos, nombrar cada columna y eliminar los datos marcados con "?".
Con la información filtrada se realizó un histograma donde se puede analizar visualmente la cantidades de casos positivos con tumor maligno y negativos con tumor benigno. 
En segundo lugar se dividió la base de datos en traing con 80% y test con el 20%. Se entrenaron tres algoritmos: Randomforest, KNN y Regresión Logística.
Finalmente se evaluó con la matriz de confusión en el set de prueba y en el set de entrenamiento, teniendo como resultados que el mejor modelo aplicado es el de Randomforest. 

|METRICA| RANDOMFOREST | KNN | REGRESION LOGISTICA |
| ------------- | ------------- | ------------- | ------------- |
| VERDADERO NEGATIVO  | Content Cell  | Content Cell  | Content Cell  |
| FALSO POSITIVO  | Content Cell  | Content Cell  | Content Cell  |
| FALSO NEGATIVO  | Content Cell  | Content Cell  | Content Cell  |
| VERDADERO POSITIVO  | Content Cell  | Content Cell  | Content Cell  |

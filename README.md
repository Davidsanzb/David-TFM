# David-TFM

Repositorio creado para almacena el código utilizado en el TFM.

## Descripción

Este proyecto corresponde al Trabajo de Fin de Máster (TFM) en Bioinformática y cuyo objetivo es desarrollar un análisis de los fundamentos y un análisis técnico comparativo del rendimiento de los algoritmos de machine learning y deep learning aplicados a una base de datos. Se abordan 10 algoritmos de clasificación y 3 de regresión mediante la librería Scikit-learn y 2 redes neuronales desarrolladas en TensorFlow/Keras.

## Metodología 

- **Dataset:** Wisconsin Breast Cancer Dataset (WDBC).

- **Preprocesamiento:** Eliminación de variables irrelevantes, escalado con StandardScaler y partición estratificada en entrenamiento (80%) y test (20%).
  
- **Modelos de clasificación (10):**
  - Logistic Regression.
  - Support Vector Machines (SVM).
  - Decission Tree.
  - Random Forest.
  - Gradient Boosting.
  - KNN.
  - Naive Bayes.
  - Multi-Layer Perceptron(MLP).
  - AdaBoost.
  - XGBoost.

- **Modelos de regresión (3):**
  - Linear Regression.
  - Ridge Regression.
  - Lasso Regression.

- **Redes neuronales (2):**
  - Redes neuronales de clasificación.
  - Redes neuronales de regresión.

## Resultados

- Clasificación: Compara las matrices de confusión y las curvas ROC para cada uno de los modelos y el impacto en las diferentes métricas (Accuracy, Precision, Recall y F1-score).
- Regresión: Estimar el impacto de cada variable predictora sobre el rendimiento de cada modelo y compara las diferentes métricas (MSE, MAE y R²) complementado con gráficos que representa los valores reales frente a los predichos.
- Redes neuronales: Desempeño competitivo tanto en clasificación como en regresión, gracias a su capacidad de modelar relaciones no lineales.

## Estructura del repositorio

Se observa una carpeta denominada "Codigo_TFM", dentro de esta carpeta vamos a encontar otras 4 carpetas: 

1. **Clasificación** ---> Almacena el código empleada para la realización de los algoritmos de clasificación.
2. **Regresión** ---> Almacena el código empleado para la realización de los algoritmos de regresión.
3. **Redes Neuronales** ---> ALmacena el código para la realización de las redes neuronales.
4. **data** ---> Almacena la base de datos utilizada.


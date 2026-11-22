# Sistema Predictivo de Abandono de Clientes (Churn Prediction)

Sistema de predicción del abandono de clientes en empresas de telecomunicaciones mediante técnicas de aprendizaje estadístico supervisado.

## 1. Descripción del proyecto

El proyecto consiste en desarrollar un sistema predictivo capaz de identificar clientes con riesgo de abandonar los servicios de una empresa de telecomunicaciones, utilizando algoritmos de aprendizaje automático para analizar sus características sociodemográficas, contractuales y de servicio.

## 2. Objetivo

Diseñar, entrenar y evaluar modelos de aprendizaje supervisado que permitan anticipar el abandono de clientes (Churn), facilitando la identificación de usuarios con mayor probabilidad de cancelar sus servicios.

## 3. Conjunto de datos

Se utilizó el dataset **Telco Customer Churn**, compuesto originalmente por:

- 7,043 registros de clientes.
- 21 variables.
- Variable objetivo: Churn (Yes/No).

Durante el preprocesamiento se identificaron 11 valores faltantes en el atributo `TotalCharges`, los cuales fueron eliminados. Como resultado, se obtuvo un conjunto de 7,032 registros para el modelado.

**Fuente del dataset:**  
https://www.kaggle.com/datasets/blastchar/telco-customer-churn

## 4. Tecnologías utilizadas

- Python.
- Google Colab.
- Pandas y NumPy.
- Scikit-learn.
- Weka Explorer.
- GitHub.

## 5. Procesamiento de los datos

Se realizaron las siguientes actividades:

1. Carga y validación del conjunto de datos.
2. Identificación y tratamiento de valores faltantes.
3. Limpieza y normalización de variables categóricas.
4. Estandarización de variables numéricas.
5. Codificación de variables categóricas mediante One-Hot Encoding.
6. División del conjunto de datos en entrenamiento y prueba.

## 6. Modelos implementados

### Experimentación en Python

- Regresión Logística.
- Random Forest Classifier.
- Gradient Boosting Classifier.

### Experimentación en Weka

- Regresión Logística.
- Random Forest.
- LogitBoost.

## 7. Resultados principales

En la experimentación realizada en Python, Gradient Boosting presentó el mejor resultado general, alcanzando un AUC de 0.8392, un Recall de 0.8075 y un F1-Score de 0.6176 sobre el conjunto de prueba.

En Weka, LogitBoost obtuvo el mejor equilibrio general en las métricas de clasificación, mientras que Regresión Logística alcanzó el mayor AUC (0.831).

## 8. Finalidad del sistema

El sistema busca proporcionar una herramienta de apoyo para las empresas de telecomunicaciones, permitiendo identificar anticipadamente a los clientes con riesgo de abandono y orientar las estrategias de fidelización y retención.

## 9. Estado del proyecto

El proyecto cuenta con las etapas de preprocesamiento, entrenamiento y evaluación experimental de los modelos. La publicación del código y el despliegue de la aplicación predictiva forman parte de las actividades de desarrollo y publicación del proyecto.

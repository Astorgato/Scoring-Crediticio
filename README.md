## 🧠 Credit Scoring Model – Random Forest + Interpretability

Este proyecto implementa un modelo de Scoring Crediticio utilizando Random Forest con regularización Ridge, enfocado en la evaluación del riesgo crediticio y la interpretabilidad del modelo mediante herramientas como SHAP y LIME.
El objetivo es predecir la probabilidad de incumplimiento de pago de un cliente (default) y comprender los factores que más influyen en esa predicción.

## 📋 Descripción del Proyecto

El scoring crediticio es una técnica empleada por instituciones financieras para estimar la probabilidad de que un cliente cumpla con sus obligaciones financieras.
Este proyecto aplica Machine Learning supervisado para desarrollar un modelo explicable y con métricas sólidas de desempeño.

El flujo principal del proyecto es:

Carga y exploración de datos

Preprocesamiento y selección de características

Entrenamiento de modelo Random Forest

Aplicación de regularización Ridge

Evaluación de métricas de desempeño

Interpretabilidad de predicciones con SHAP y/o LIME

Visualización de resultados y reflexión sobre interpretabilidad

## ⚙️ Tecnologías y Librerías Utilizadas

Lenguaje: Python 3.10+

Librerías principales:

pandas, numpy – Manipulación y análisis de datos

scikit-learn – Entrenamiento del modelo, métricas y regularización

matplotlib, seaborn – Visualización de datos y resultados

shap, lime – Interpretabilidad del modelo


## 🔍 Metodología
### Preprocesamiento

Codificación de variables categóricas.

Estandarización de variables numéricas.

División en train/test (80/20).

### Entrenamiento del Modelo
Algoritmo: Random Forest Classifier

Regularización adicional: Ridge (L2) para controlar la magnitud de los coeficientes y reducir overfitting.

### Evaluación
Se utilizan las siguientes métricas:

Precisión (Accuracy)

Recall (Sensibilidad)

F1-Score

AUC-ROC

También se genera la matriz de confusión y curvas de ROC y Precision-Recall.

### Interpretabilidad
SHAP: Permite explicar la contribución de cada variable a la predicción individual y global.

LIME: Analiza explicaciones locales de decisiones puntuales del modelo.

### Visualización
Importancia de características.

Gráficos de métricas.

Visualizaciones SHAP y LIME.

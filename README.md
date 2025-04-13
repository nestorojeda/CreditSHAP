# Análisis de Riesgo de Impago en Tarjetas de Crédito

## Descripción
Este proyecto forma parte del curso de Calibración, Métricas y Explicabilidad de Modelos de IA de la Universidad Alfonso X el Sabio. Se enfoca en el análisis predictivo para determinar el riesgo de impago en tarjetas de crédito utilizando técnicas de machine learning.

## Contenido
El proyecto incluye:
- Análisis exploratorio de datos (EDA)
- Implementación de modelos de clasificación:
  - Random Forest
  - Gradient Boosting
  - Regresión Logística
- Evaluación comparativa con métricas supervisadas
- Explicabilidad de modelos mediante SHAP
- Reflexión crítica sobre limitaciones y mejoras

## Dataset
Se utiliza el dataset ["Default of Credit Card Clients"](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients) de la UCI Machine Learning Repository, que contiene datos de 30.000 clientes con información sobre:
- Variables demográficas (límite de crédito, sexo, educación, estado civil, edad)
- Historial de pagos de los últimos 6 meses
- Montos facturados y pagados

## Requisitos
Para ejecutar este proyecto necesitas las siguientes dependencias:
```
pip install -r requirements.txt
```

## Estructura del Proyecto
- `notebook.ipynb`: Jupyter Notebook con todo el análisis, modelos y visualizaciones
- `requirements.txt`: Dependencias necesarias para ejecutar el proyecto
# Telecom X – Predicción de Cancelación de Clientes (Churn)

## Descripción del Proyecto

Este proyecto tiene como objetivo desarrollar modelos de Machine Learning capaces de predecir la cancelación de clientes (churn) en la empresa Telecom X.

El análisis se basa en datos previamente tratados en la Parte 1 del desafío, donde se realizó el proceso de limpieza y transformación de los datos.

## Objetivos

- Preparar los datos para el modelado predictivo.
- Analizar las variables relacionadas con la cancelación de clientes.
- Construir modelos de clasificación.
- Evaluar el desempeño de los modelos.
- Identificar los factores más importantes que influyen en el churn.

## Estructura del Proyecto
TelecomX-Churn

│

├── TelecomX_ML_Churn.ipynb
├── datos_tratados.csv
└── README.md
## Tecnologías utilizadas

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

## Modelos utilizados

- Regresión Logística
- Random Forest

## Métricas de evaluación

Los modelos fueron evaluados utilizando:

- Accuracy
- Precision
- Recall
- F1-score
- Matriz de confusión

## Principales factores de cancelación

Las variables que más influyen en la cancelación de clientes son:

- Tiempo de permanencia (tenure)
- Cargos mensuales (MonthlyCharges)
- Tipo de contrato
- Tipo de servicio de internet
- Método de pago

## Conclusión

Los modelos desarrollados permiten identificar clientes con mayor probabilidad de cancelar el servicio. Esta información puede ayudar a Telecom X a implementar estrategias de retención y mejorar la fidelización de sus clientes.

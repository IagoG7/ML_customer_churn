# 🧠 ML - Customer Churn Prediction / Predicción de Abandono de Clientes

## 📌 Problem Statement / Planteamiento del Problema

**EN**  
This project aims to predict whether a customer will churn or not from a telecom company, based on historical data. Customer churn is a major issue for many businesses, as retaining customers is often more cost-effective than acquiring new ones. Predicting it in advance allows companies to implement better retention strategies.

**ES**  
Este proyecto tiene como objetivo predecir si un cliente va a abandonar o no una empresa de telecomunicaciones, basándose en datos históricos. El abandono de clientes es un problema importante para muchas empresas, ya que retener clientes es más rentable que adquirir nuevos. Predecirlo con antelación permite implementar estrategias de fidelización más efectivas.

---

## 📊 Dataset

**EN**  
The dataset used is public and was obtained from Kaggle:  
🔗 [Customer Churn Dataset - Kaggle](https://www.kaggle.com/datasets/muhammadshahidazeem/customer-churn-dataset)

It includes customer data such as:
- Contract type
- Subscribed services
- Monthly charges
- Customer tenure
- And more

**ES**  
El dataset utilizado es público y fue obtenido de Kaggle:  
🔗 [Customer Churn Dataset - Kaggle](https://www.kaggle.com/datasets/muhammadshahidazeem/customer-churn-dataset)

El dataset contiene información de clientes como:
- Tipo de contrato
- Servicios contratados
- Cargos mensuales
- Tiempo como cliente
- Otras variables

---

## 🧪 Proposed Solution / Solución Propuesta

**EN**  
A complete supervised Machine Learning pipeline is applied to solve a binary classification problem (Churn: Yes / No). The trained model is saved in `joblib` format for reuse. The project follows a clear, structured and reproducible approach.

**ES**  
Se realiza un pipeline completo de Machine Learning supervisado para resolver un problema de clasificación binaria (Churn: Sí / No). El modelo entrenado se guarda en formato `joblib` para su reutilización. Se sigue un enfoque claro, estructurado y reproducible.

---

## 🗂️ Estructura del repositorio / Repository Structure

```bash
ML_customer-churn/
├── README.md                    # Explicación del proyecto
└── src/
    ├── data_sample/            # ✅ Muestra del dataset (máx 5MB)
    ├── img/                    # ✅ Imágenes usadas en el proyecto
    ├── models/                 # ✅ Modelos entrenados (.pkl / .joblib / .h5)
    ├── notebooks/              # ✅ Notebooks de trabajo y prueba
    ├── results_notebook/       # ✅ Notebook final con todo el flujo limpio y funcional
    └── utils/                  # ✅ Funciones auxiliares (preprocesado, métricas, etc.)
```

---

## 🎯 Goal / Objetivo

**EN**  
To demonstrate the ability to carry out a complete end-to-end Machine Learning project, including exploratory analysis, feature engineering, training, evaluation and model saving.

**ES**
Demostrar la capacidad para desarrollar un proyecto completo de Machine Learning de principio a fin, incluyendo análisis exploratorio, ingeniería de características, entrenamiento, evaluación y guardado del modelo.


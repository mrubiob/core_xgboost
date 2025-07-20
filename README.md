# XGBoost Heart Disease Prediction

Este repositorio contiene dos notebooks dedicados a la predicción de enfermedades cardíacas utilizando el algoritmo **XGBoost**. Se incluye el desarrollo de un pipeline de machine learning completo, desde el análisis exploratorio hasta la optimización de hiperparámetros.

## 📘 Notebook 1: `DEA_xgboost.ipynb`

**Objetivo:** Implementar un pipeline completo de clasificación con énfasis en EDA, preprocesamiento, modelado y optimización de hiperparámetros.

**Contenido:**
- Descripción del dataset UCI Heart Disease.
- Análisis Exploratorio de Datos (EDA).
- Limpieza e imputación de datos faltantes.
- Codificación de variables categóricas.
- Divisiones de entrenamiento/prueba.
- Entrenamiento con XGBoost.
- Evaluación de métricas: Accuracy, Precision, Recall, F1.
- Optimización de hiperparámetros con `GridSearchCV`.

## 📗 Notebook 2: `ML_CoreXGBoost.ipynb`

**Objetivo:** Consolidar el conocimiento con una implementación refinada del modelo XGBoost, utilizando el conjunto de datos preprocesado.

**Contenido:**
- Pipeline compacto de preprocesamiento + entrenamiento.
- Uso de `Pipeline`, `ColumnTransformer` y validación cruzada.
- Comparación de métricas antes y después de la optimización.

## ✅ Resultados Destacados

- **XGBoost sin optimizar:**
  - Accuracy: ~0.956
  - F1-Score: ~0.965
- **XGBoost optimizado:**
  - Accuracy: ~0.974
  - F1-Score: ~0.979

## 🛠️ Requisitos

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost
```

## ▶️ Ejecución
Simplemente abre los notebooks en Jupyter o Google Colab y ejecuta las celdas secuencialmente.

## 📄 Licencia
Uso educativo.

## Autora
Marcela Rubio Briones  - Machine Learning (b2b-sonda-ds-mayo-2025)

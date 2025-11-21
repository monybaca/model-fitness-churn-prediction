# Model Fitness Churn Prediction

Este proyecto analiza la deserción (churn) de clientes en la cadena de gimnasios **Model Fitness**, con el objetivo de predecir la probabilidad de que un usuario abandone el servicio, identificar patrones de comportamiento y proponer estrategias efectivas de retención. Se utilizan modelos de machine learning y técnicas de clustering para segmentar clientes y comprender mejor los factores que influyen en su permanencia.

---

## 📌 Objetivo
- Predecir la probabilidad de churn para cada cliente.
- Analizar patrones generales de uso y comportamiento.
- Identificar características clave que influyen en la deserción.
- Segmentar clientes mediante **clustering** para personalizar estrategias.
- Proponer acciones concretas para reducir la pérdida de clientes.

---

## 🧹 Preparación y Limpieza de Datos
El proceso incluyó:
- Revisión de valores faltantes y estructura general.
- Estandarización de variables numéricas.
- Transformación y creación de características relevantes.
- Normalización de columnas para clustering.
- Identificación de outliers y corrección cuando fue necesario.

---

## 📊 Análisis Realizado
- Exploración inicial del dataset (uso del gimnasio, contratos, pagos, demografía).
- Correlación de variables con la probabilidad de churn.
- Comparaciones entre clientes que permanecen y los que abandonan.
- Gráficos de distribución, boxplots, relaciones y tendencias.

---

## 🤖 Modelos de Machine Learning
Se entrenaron y compararon varios modelos:

- **Regresión Logística**  
- **Random Forest**  
- **Gradient Boosting**  
- **SVM (opcional)**  

Para cada uno se calculó:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-score**
- Matriz de confusión

El modelo seleccionado fue el que ofreció el mejor equilibrio entre precisión y recall.

---

## 🔍 Segmentación (Clustering)
Se aplicó **K-Means** para dividir a los clientes en grupos según sus características:

- Frecuencia de uso  
- Duración del contrato  
- Gastos adicionales  
- Compromiso con el gimnasio  

Cada clúster fue interpretado para generar estrategias de marketing personalizadas.

---

## 📈 Resultados Principales
- El modelo final logró predecir churn con alta precisión y recall.
- Se identificaron variables clave como: duración del contrato, frecuencia de visitas, y servicios adicionales consumidos.
- El clustering permitió encontrar perfiles de clientes con riesgos diferentes.
- Se generaron recomendaciones de retención específicas por segmento.

---

## 🛠 Tecnologías Utilizadas
- **Python**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Matplotlib / Seaborn**
- **Jupyter Notebook**

---

## 📁 Archivos del Proyecto
- `model-fitness-churn-prediction.ipynb` — Notebook principal con todo el análisis.
- Dataset con información de usuarios, pagos y visitas.

---

## 📬 Contacto
Proyecto desarrollado como parte del portafolio analítico de **Monica Baca**.

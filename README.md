# 🧠 Segmentación de Clientes con Clustering
## Análisis de Campañas de Marketing con Machine Learning

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Análisis%20de%20Datos-black?logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?logo=scikitlearn)
![Estado](https://img.shields.io/badge/Proyecto-Completado-success)

---

# 📌 Descripción del Proyecto

Este proyecto tiene como objetivo realizar una **segmentación de clientes** utilizando técnicas de **clustering** sobre un dataset de campañas de marketing.

A través del análisis de datos y algoritmos de Machine Learning, se identificaron grupos de clientes con comportamientos de compra similares para apoyar la toma de decisiones estratégicas en marketing.

El proyecto incluye:

✔️ Limpieza de datos  
✔️ Análisis Exploratorio de Datos (EDA)  
✔️ Ingeniería de características  
✔️ Tratamiento de valores nulos  
✔️ Detección de outliers  
✔️ Escalamiento de variables  
✔️ Clusterización con KMeans  
✔️ Evaluación del modelo  
✔️ Visualización con PCA  

---

# 📂 Información del Dataset

El dataset contiene información de clientes relacionada con:

- Datos demográficos
- Ingresos económicos
- Historial de compras
- Respuesta a campañas
- Compras web, catálogo y tienda
- Frecuencia de consumo

## Variables principales

| Variable | Descripción |
|---|---|
| Income | Ingreso anual del cliente |
| Recency | Días desde la última compra |
| Total_Gastado | Gasto total del cliente |
| Total_Compras | Número total de compras |
| Education | Nivel educativo |
| Marital_Status | Estado civil |

---

# ⚙️ Tecnologías Utilizadas

- 🐍 Python
- 📊 Pandas
- 🔢 NumPy
- 📈 Matplotlib
- 🎨 Seaborn
- 🤖 Scikit-Learn
- 📓 Google Colab

---

# 🔎 Análisis Exploratorio de Datos (EDA)

Durante el análisis se realizaron:

## ✅ Tratamiento de valores nulos
Imputación de valores faltantes usando la mediana.

## ✅ Ingeniería de características
Se crearon nuevas variables:
Edad
Total_Gastado
Total_Compras

## ✅ Detección de Outliers

Aplicando el método IQR:
IQR = Q3 - Q1

## ✅ Análisis de correlación

Se utilizaron:

- Heatmaps
- Pairplots
- Scatterplots
- Boxplots
---

# 🤖 Modelo de Clusterización

La segmentación se realizó utilizando el algoritmo:

## KMeans

KMeans(n_clusters=4)

### Variables utilizadas para clustering

- Income
- Edad
- Total_Gastado
- Total_Compras
- Recency
  
---
# 📏 Evaluación del Modelo

## Silhouette Score
Silhouette\ Score = 0.239

## Davies-Bouldin Score

Davies{-}Bouldin\ Score = 1.548

---

# 📉 Visualización con PCA

Se aplicó PCA (Principal Component Analysis) para reducir dimensiones y visualizar los clusters encontrados en un espacio bidimensional.

Esto permitió observar patrones diferenciados de comportamiento entre clientes.

---

# 📊 Hallazgos Principales

## 🔹 Análisis Univariado

- La mayoría de clientes presenta ingresos medios.
- Existen outliers importantes en Income.
- El gasto total presenta alta variabilidad.

## 🔹 Análisis Bivariado

- Existe relación positiva entre ingresos y gasto total.
- Los clientes con mayores ingresos realizan más compras.
- Algunos niveles educativos presentan mayores ingresos promedio.

## 🔹 Hallazgos del Clustering

- Se identificaron 4 segmentos de clientes.
- Algunos clusters representan clientes de alto valor.
- Otros clusters muestran bajo gasto y baja frecuencia de compra.

---

# 🚀 Impacto del Proyecto

Los resultados obtenidos pueden ayudar a:

- Mejorar estrategias de marketing
- Personalizar campañas
- Incrementar conversiones
- Optimizar inversión publicitaria
- Identificar clientes de alto valor

---

# ⭐ Conclusión

Este proyecto demuestra cómo las técnicas de Machine Learning pueden transformar datos de clientes en información estratégica para la toma de decisiones.

A través del análisis exploratorio, el preprocesamiento y la aplicación de KMeans, fue posible identificar segmentos diferenciados de clientes que pueden ser utilizados para desarrollar estrategias de marketing más eficientes y personalizadas.

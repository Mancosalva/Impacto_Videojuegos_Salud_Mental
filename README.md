
# Impacton de los Videojuegos en la Salud Mental

![Banner](Banner.jpg)

## Autores:
Dylan Jhoan Velandia Velandia - 2210072, Juan Diego Manosalva Salamanca - 2220059

---

## Objetivo
Analizar el impacto de los videojuegos en la salud mental de los jugadores, identificando la relación entre hábitos de juego e indicadores de bienestar físico, emocional y social como la calidad del sueño, el rendimiento académico/laboral, el aislamiento social y el riesgo de adicción.

---

## Dataset (Gaming and Mental Health)

[Gaming and Mental Health — Kaggle](https://www.kaggle.com/datasets/shaistashahid/gaming-and-mental-health)

> Dataset con ~1000 individuos. Incluye variables demográficas, patrones de juego, calidad del sueño, estado de ánimo, rendimiento académico/laboral, síntomas de abstinencia, aislamiento social y actividad física.

---

## Modelos

**Regresión (variable objetivo: `sleep_hours`):**
- LinearRegression, Ridge, Lasso

**Clasificación (variable objetivo: `gaming_addiction_risk_level`):**
- DecisionTreeClassifier, RandomForestClassifier, SVC (kernels: linear, poly, rbf)

**Deep Learning (Keras/TensorFlow):**
- 3 arquitecturas DNN para clasificación y regresión (64→128→128 / 64→64→128→128→256→256 / 128×10→40)

**Aprendizaje No Supervisado:**
- PCA (reducción a 2 componentes), KMeans (4 clusters), DBSCAN

---

## Enlace del código

[Google Colab](Proyecto_Final_IA1.ipynb)

## Diapositivas

[Ver presentación PDF](Impacto%20de%20los%20videojuegos%20en%20la%20salud%20mental.pdf)

---
## Enlace del video

[YouTube](https://www.youtube.com/watch?v=VARFCYP7FEo)


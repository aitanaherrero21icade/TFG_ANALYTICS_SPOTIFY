# Análisis del impacto de las características sociodemográficas y del tipo de suscripción en la satisfacción de los usuarios con las recomendaciones personalizadas de Spotify

Este repositorio contiene el código, los datos y la documentación asociados al Trabajo de Fin de Grado (TFG) de Aitana Herrero Castro, realizado en la Facultad de Ciencias Económicas y Empresariales – ICADE (Universidad Pontificia Comillas).

## Objetivo del estudio

Analizar cómo variables como la edad, el género y el tipo de suscripción influyen en la satisfacción de los usuarios con las recomendaciones personalizadas ofrecidas por el algoritmo de Spotify.

---

## Metodología

El análisis combina diferentes técnicas de Data Science:

- **Preprocesamiento de datos**
- **Análisis exploratorio (EDA)**
- **Reducción de dimensionalidad (PCA)**
- **Segmentación de usuarios (K-means clustering)**
- **Modelado explicativo (Regresión lineal múltiple)**
- **Modelado predictivo (Regresión logística y Random Forest)**

---

## Estructura del repositorio

- `Spotify_data.xlsx` → Dataset utilizado (extraído de Kaggle)
- `TFG_Spotify_Aitana.ipynb` → Notebook con todo el análisis realizado
- `README.md` → Descripción general del proyecto

---

## Resultados clave

- Los usuarios entre 20 y 35 años muestran mayores niveles de satisfacción.
- Los usuarios con cuenta gratuita reportan una valoración más alta del sistema que los usuarios Premium.
- El análisis de clustering identifica tres perfiles diferenciados de uso.
- Los modelos predictivos presentan una capacidad limitada (R² ≈ 0.035), lo que sugiere la necesidad de incluir variables adicionales (emociones, contexto de uso, etc.).

---

## Conclusiones

Este estudio pone de relieve la importancia de adaptar los sistemas de recomendación a perfiles más diversos, considerando no solo el historial de escucha, sino también factores sociodemográficos y actitudinales. Se propone también una mayor transparencia y personalización activa del algoritmo.

---

## Contacto

**Autora**: Aitana Herrero Castro  
**Universidad**: Universidad Pontificia Comillas (ICADE)  
**Curso**: 2024–2025  
**Correo**: aitanaherrero@alu.comillas.edu

---

## Fuente del dataset

Spotify User Behavior Dataset  
https://www.kaggle.com/datasets/meeraajayakumar/spotify-user-behaviour-dataset

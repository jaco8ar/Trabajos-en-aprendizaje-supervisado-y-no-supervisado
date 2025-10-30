# Aprendizaje Supervisado y No Supervisado

Este repositorio contiene dos notebooks desarrollados como parte de proyectos académicos enfocados en el análisis y modelado de datos mediante técnicas de Machine Learning supervisadas y no supervisadas. Cada notebook aborda un tipo de aprendizaje distinto, aplicando metodologías completas de análisis, preprocesamiento, modelado, evaluación y conclusión.

## Estructura del repositorio

- Equipo9_Microproyecto2.ipynb — Aprendizaje no supervisado
- Equipo9_Microproyecto3.ipynb — Aprendizaje supervisado
- README.md

## Proyecto 1 — Clustering: Análisis de Enfermedades Cardíacas

**Objetivo:** Identificar grupos de pacientes con características similares a partir de variables clínicas, aplicando técnicas de clustering.

**Dataset:** `heart_disease_patients.csv`

**Metodología:**
- Preprocesamiento de datos y selección de variables representativas.
- Determinación del número óptimo de clústeres mediante:
  - Método del codo
  - Estadístico de gap
  - Análisis de la silueta
- Aplicación de K-Means y análisis jerárquico mediante dendrogramas.
- Caracterización e interpretación de cada clúster.

**Principales hallazgos:**
- Se identificaron tres grupos principales que diferencian niveles de salud cardiovascular según edad, presión arterial y condición física.
- Las tendencias muestran una clara relación entre juventud, menor presión arterial y mejor salud cardíaca.
- El colesterol no resultó ser un factor decisivo en la segmentación de los datos.

## Proyecto 2 — Clasificación: Predicción de Posiciones en FIFA 21

**Objetivo:** Clasificar jugadores según su posición en el campo (portero, defensor, mediocampista o delantero) utilizando Árboles de Decisión y Clasificación Bayesiana.

**Dataset:** `players_21.csv`

**Metodología:**
- Análisis exploratorio y preprocesamiento de datos (limpieza, selección de características, balanceo de clases).
- Implementación de Árboles de Decisión y Clasificación Bayesiana.
- Evaluación mediante accuracy, precision, recall, F1-score y matrices de confusión.
- Comparación entre ambos modelos.

**Resultados:**
- El Árbol de Decisión alcanzó una precisión del 84% en entrenamiento y 82% en prueba, superando al modelo Bayesiano (76% y 75% respectivamente).
- Los arqueros fueron clasificados perfectamente en ambos modelos (1.00 de precisión y recall).
- El Árbol de Decisión mostró mejor desempeño al reducir confusiones entre mediocampistas y defensores.

**Conclusión:**
El Árbol de Decisión ofrece un mejor balance entre precisión y capacidad de generalización, siendo la opción más adecuada para la clasificación de posiciones en FIFA.

## Tecnologías utilizadas

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Scipy

## Autores

- Luis Alejandro Varela Ojeda
- Juan Manuel Rodríguez Sánchez
- Jacobo Ochoa Ramírez
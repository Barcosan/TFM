# Proyecto de Predicción de Resultados en Partidos de la NBA

Este proyecto utiliza datos estadísticos de jugadores y equipos de la NBA entre los años 2007 y 2021 para crear un modelo de predicción que estime la probabilidad de victoria de un equipo sobre otro en un partido. Utilizamos diversas técnicas de preprocesamiento, análisis exploratorio, selección de características y creación de modelos de machine learning para lograr este objetivo.

## Estructura del Proyecto

El proyecto está contenido en un cuaderno Jupyter (`NBA_.ipynb`), y está dividido en varias secciones importantes:

### 1. **Importación de Librerías**
   Esta sección carga las librerías necesarias para la manipulación de datos, visualización y modelado. Las librerías principales utilizadas incluyen:
   - `pandas` y `numpy` para la manipulación de datos.
   - `matplotlib` y `seaborn` para visualización.
   - Librerías de `sklearn` para preprocesamiento, selección de características y modelado.

### 2. **Carga de Datos**
   Se cargan los datos estadísticos de jugadores y equipos en formato CSV, los cuales contienen información como puntos, asistencias, rebotes, entre otros.

### 3. **Análisis Exploratorio de Datos (EDA)**
   En esta sección, realizamos un análisis inicial de los datos, incluyendo visualizaciones para entender la distribución de las características más relevantes y la relación entre ellas. Aquí también se tratan los datos faltantes.

### 4. **Preprocesamiento de los Datos**
   En este paso, se normalizan y estandarizan las variables numéricas, y se codifican las variables categóricas. Este paso es crucial para asegurar que los datos estén en un formato adecuado para los modelos de machine learning.

### 5. **Selección de Características**
   Se lleva a cabo un proceso de selección de características basado en la correlación con la variable objetivo y utilizando métodos automáticos como `SelectKBest`, `SelectPercentile`, y `RFE`. Esta sección es importante para mitigar la maldición de la dimensionalidad y reducir la complejidad del modelo.

### 6. **Modelado**
   Aquí, se entrenan varios modelos de clasificación, como Regresión Logística y Random Forest. Se evalúan las métricas de rendimiento como precisión, recall y curva ROC.

### 7. **Evaluación del Modelo**
   Se evalúa el rendimiento del modelo final utilizando datos de prueba. Las métricas de evaluación permiten medir qué tan bien el modelo predice el resultado de un partido.

### 8. **Seleccionar los equipos para ver la probabilidad de que uno gane a otro, indicando quien juega en casa y quien fuera (Chung 251)** 

## Cómo Usar este Proyecto

1. **Requisitos Previos**: Asegúrate de tener instaladas las librerías necesarias. 

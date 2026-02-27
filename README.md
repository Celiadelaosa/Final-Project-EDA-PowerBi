# 📊Proyecto-Final: Análisis Exploratorio y Dashboard de Salud Nutricional

## 📌 Descripción del proyecto

Este proyecto tiene como objetivo analizar la relación entre los valores nutricionales, indicadores clínicos, el estilo de vida y las características demográficas de una muestra de individuos , utilizando Python para el análisis exploratorio de datos (EDA) y Power BI para la construcción de un dashboard interactivo.

El trabajo integra limpieza, transformación, análisis descriptivo y análisis estadístico básico de los datos, finalizando con la visualización estructurada de los principales hallazgos.

## 🎯 Objetivos

- Realizar la limpieza y transformación de un conjunto de datos de salud nutricional.

- Analizar descriptivamente las variables principales.

- Estudiar posibles relaciones entre las variables.

- Construir un dashboard interactivo que permita explorar visualmente los resultados.

- Documentar y organizar el proyecto siguiendo buenas prácticas de repositorio.

## 🗂️ Conjunto de datos

El dataset incluye variables relacionadas con:

- Índice de Masa Corporal (IMC)

- Presión arterial sistólica y diastólica

- Nivel de actividad física

- Consumo calórico

- Variables nutricionales

- Factores económicos


Durante el proceso se realizaron tareas de:

- Corrección de formatos numéricos (separadores decimales)

- Conversión de tipos de datos

- Creación de variables derivadas (categorías de IMC, rangos de edad)

- Ordenación personalizada de variables categóricas

- Verificación de coherencia y consistencia de los datos

## 🛠️ Herramientas utilizadas

-Python

  --Pandas
  
  --Matplotlib
  
  --Seaborn
  
-Jupyter Notebook

-VS Code

-Power BI

## 🔎 Fases del proyecto
1️⃣ Limpieza y transformación de datos

Se realizó la adecuación de formatos, conversión de variables numéricas y creación de nuevas columnas derivadas necesarias para el análisis.

2️⃣ Análisis exploratorio de datos (EDA)

Se llevó a cabo un análisis descriptivo y estadístico para identificar:

Distribuciones de variables

Relaciones entre IMC y presión arterial

Asociación entre actividad física y consumo calórico

Posible influencia del factor económico

3️⃣ Construcción del Dashboard

Se diseñó un dashboard interactivo en Power BI que incluye:

KPIs generales

Comparaciones por categorías de IMC

Análisis por nivel de actividad física

Visualización de la relación continua entre IMC y presión arterial mediante gráfico de dispersión

Segmentadores para facilitar la exploración

## 📈 Principales hallazgos

Se observa una relación positiva entre IMC y presión arterial, aunque con variabilidad individual.

Los niveles de actividad física se asocian con diferencias en el consumo calórico.

El factor económico no muestra una relación significativa con los principales indicadores de salud.

Algunas variables nutricionales presentan patrones débiles o inconsistentes.


## 📁 Organización del repositorio
```text
📦 PROYECTO_FINAL
├── 📂 DATA
│   ├── 📂 nutririon_processed
│   │   └── nutrition_clean.csv  # Datos limpios tras la transformación
│   └── 📂 nutrition_raw
│       ├── demographic.csv
│       ├── diet.csv
│       ├── examination.csv
│       └── questionnaire.csv
│
├── 📂 NOTEBOOKS
│   ├── nutrit_carga_limpieza.ipynb
│   ├── nutrit_eda.ipynb
│   └── nutrition_clean.csv
│
├── 📊 DB_nutrition.pbix        # Visualizaciones en Power BI
└──📄 Informe_explicativo_nutrition.pdf   # Documento detallado del análisis
```

## 👩‍💻 Autora
Celia de la Osa

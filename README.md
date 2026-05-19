🌐 Available languages:
- 🇬🇧 English: README.md
- 🇪🇸 Español: [README_ES.md](README_ES.md)
  
# 📊 Nutritional Health Analysis: EDA & Interactive Dashboard

## 📌 Project Overview

This project explores the relationship between nutritional values, clinical indicators, lifestyle habits, and demographic characteristics within a sample population.

The analysis combines Python-based Exploratory Data Analysis (EDA) with an interactive Power BI dashboard to identify patterns, relationships, and meaningful insights from the data.

The workflow includes data cleaning, transformation, descriptive analysis, basic statistical analysis, and data visualization.

---
## 🎯 Project Objectives

- Clean and transform a nutritional health dataset
- Perform descriptive analysis of key variables
- Identify potential relationships between health indicators
- Build an interactive dashboard for data exploration
- Organize and document the project following repository best practices

---
## 🗂️ Dataset Information

The dataset contains variables related to:

- Body Mass Index (BMI)
- Systolic and diastolic blood pressure
- Physical activity level
- Caloric intake
- Nutritional indicators
- Economic factors

Data preparation tasks included:

- Correcting numeric formats (decimal separators)
- Converting data types
- Creating derived variables (BMI categories, age groups)
- Custom sorting of categorical variables
- Validating data consistency and quality

---


## 🛠️ Tools & Technologies

- Python
   - Pandas
   - Matplotlib
   - Seaborn
- Jupyter Notebook
- VS Code
- Power BI

---
## 🔎 Project Workflow

### 1. Data Cleaning & Transformation

Data formatting issues were corrected and new derived variables were created to prepare the dataset for analysis.

### 2. Exploratory Data Analysis (EDA)

Descriptive and statistical analysis was performed to identify:

- Variable distributions
- Relationships between BMI and blood pressure
- Associations between physical activity and caloric intake
- Potential effects of economic factors

### 3. Dashboard Development

An interactive Power BI dashboard was developed including:

- General KPIs
- BMI category comparisons
- Physical activity analysis
- Scatter plots showing BMI vs blood pressure relationships
- Interactive filters and slicers

---
## 📈 Key Findings

- A positive relationship was observed between BMI and blood pressure, although individual variability exists.
- Physical activity levels appear associated with differences in caloric intake.
- Economic factors did not show a significant relationship with the main health indicators.
- Some nutritional variables displayed weak or inconsistent patterns.

---

## 💡 Project Value

This project demonstrates skills in:

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Statistical interpretation
- Data visualization
- Dashboard design using Power BI

---


## 📁 Repository Structure
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

## 👩‍💻 Author
Celia de la Osa

# 🏢 Salifort Motors - Predicción de Rotación de Empleados

## 📌 Descripción del proyecto

Este proyecto analiza los factores asociados a la rotación de empleados en Salifort Motors utilizando técnicas de Análisis Exploratorio de Datos (EDA) y modelos de Machine Learning.

El objetivo es identificar las variables que influyen en la salida de empleados y entregar información útil para apoyar la toma de decisiones del área de Recursos Humanos.

---

## 🎯 Objetivos

- Analizar el comportamiento de los empleados.
- Identificar factores asociados a la rotación.
- Construir modelos predictivos.
- Comparar el rendimiento de distintos algoritmos.
- Entregar recomendaciones basadas en datos.

---

## 🛠 Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## 📂 Estructura del proyecto

```text
salifort-motors-employee-attrition/

├── data/
├── notebooks/
├── images/
├── README.md
├── requirements.txt
└── LICENSE
```

---

## 📈 Estado

✅Proyecto en construcción.

Próximamente se incorporarán:

- Análisis exploratorio de datos (EDA)
- Visualizaciones
- Modelos de Machine Learning
- Resultados
- Conclusiones
- Recomendaciones para el negocio

---

# 📊 Visualizaciones principales

## Rotación de empleados

Esta gráfica muestra la distribución de empleados que permanecieron en la empresa y aquellos que abandonaron la organización.

![Rotación de empleados](images/employee_turnover.png)

## Nivel de satisfacción

Comparación del nivel de satisfacción entre los empleados que permanecieron y quienes abandonaron la empresa.

![Nivel de satisfacción](images/satisfaction_level.png)


## Rotación según salario

Distribución de la rotación de empleados según el nivel salarial.

![Rotación por salario](images/salary_turnover.png)


## Matriz de correlación

Relación entre las principales variables analizadas durante el análisis exploratorio de datos.

![Matriz de correlación](images/correlation_matrix.png)


## Matriz de confusión

Resultados del modelo de Machine Learning utilizados para evaluar el rendimiento del modelo predictivo.

![Matriz de confusión](images/confusion_matrix.png)

# 📈 Resultados del modelo

Se entrenaron dos modelos de clasificación para predecir la rotación de empleados:

- Logistic Regression
- XGBoost


El modelo XGBoost obtuvo el mejor desempeño general.

| Modelo | Accuracy | Precision | Recall | F1 Score | ROC AUC |
|---------|---------:|----------:|--------:|---------:|--------:|
| Logistic Regression | 0.84 | 0.51 | 0.21 | 0.30 | 0.82 |
| XGBoost | 0.98 | 0.96 | 0.93 | 0.95 | 0.98 |


# 📌 Conclusiones

Los resultados muestran que variables como:

- Satisfaction Level
- Tenure
- Number of Projects
- Last Evaluation

son los factores con mayor influencia en la rotación de empleados.

El modelo XGBoost fue el de mejor rendimiento, alcanzando aproximadamente un 98% de Accuracy y un ROC-AUC cercano a 0.98.

# 🚀 Cómo ejecutar el proyecto

1. Clonar el repositorio

git clone https://github.com/angelarayarobles/salifort-motors-employee-attrition.git

2. Instalar dependencias

pip install -r requirements.txt

3. Abrir

notebooks/salifort_motors_employee_attrition.ipynb

# 👨‍💻 Autor

Ángel Araya Robles

• Ingeniería Industrial
• Google Data Analytics Professional Certificate
• GitHub:
https://github.com/angelarayarobles


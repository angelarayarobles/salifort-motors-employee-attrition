# 🏢 Salifort Motors - Predicción de Rotación de Empleados


## Contenido

- Descripción
- Objetivos
- Tecnologías
- Estructura
- Visualizaciones
- Resultados
- Conclusiones
- Instalación
- Autor
- 

## 📌 Descripción del proyecto

Este proyecto analiza los factores asociados a la rotación de empleados en Salifort Motors utilizando técnicas de Análisis Exploratorio de Datos (EDA) y modelos de Machine Learning.

El objetivo es identificar las variables que influyen en la salida de empleados y entregar información útil para apoyar la toma de decisiones del área de Recursos Humanos.


## Problema de negocio

La alta rotación de empleados genera costos de contratación, capacitación y pérdida de conocimiento dentro de la empresa.

Este proyecto busca identificar los factores asociados a la salida de empleados para apoyar decisiones estratégicas del área de Recursos Humanos.

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

✅Proyecto finalizado.

Incluye:

- Limpieza de datos
- Análisis exploratorio (EDA)
- Visualizaciones
- Logistic Regression
- XGBoost
- Comparación de modelos
- Conclusiones

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


## Insights principales

- Los empleados con menor satisfacción abandonan con mayor frecuencia.
- La antigüedad es una de las variables más importantes.
- El número de proyectos influye en la rotación.
- El nivel salarial bajo presenta una mayor proporción de abandono.


# 📈 Resultados del modelo

Se entrenaron dos modelos de clasificación para predecir la rotación de empleados:

- Logistic Regression
- XGBoost


El modelo XGBoost obtuvo el mejor desempeño general.

| Modelo | Accuracy | Precision | Recall | F1 Score | ROC AUC |
|---------|---------:|----------:|--------:|---------:|--------:|
| Logistic Regression | 0.84 | 0.51 | 0.21 | 0.30 | 0.82 |
| XGBoost | 0.98 | 0.96 | 0.93 | 0.95 | 0.98 |

## Modelo seleccionado

Se seleccionó XGBoost porque obtuvo:

- Mayor Accuracy
- Mayor Precision
- Mayor Recall
- Mayor F1 Score
- Mejor ROC-AUC

Por ello se considera el modelo más adecuado para identificar empleados con mayor riesgo de abandonar la empresa.


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


Proyecto desarrollado como parte del Google Data Analytics Professional Certificate y ampliado con técnicas de Machine Learning para fortalecer el portafolio profesional.

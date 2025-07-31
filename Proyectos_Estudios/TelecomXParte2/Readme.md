# Desafío Telecom X - Parte 2: Predicción de Cancelación (Churn)

## 📣 Descripción del Proyecto

Este proyecto es la segunda parte del desafío de Telecom X, donde el objetivo principal es desarrollar modelos de Machine Learning para predecir la probabilidad de que un cliente cancele sus servicios. Se construyó un pipeline completo, desde la preparación de datos hasta la interpretación de los resultados, con el fin de proporcionar a la empresa una herramienta predictiva y estratégica para la retención de clientes.

## 🎯 Objetivos del Desafío

* **Preparar los datos** para el modelado (tratamiento de nulos, codificación de variables, etc.).
* **Entrenar y evaluar** dos modelos de clasificación: `LogisticRegression` y `RandomForestClassifier`.
* **Evaluar el rendimiento** de los modelos utilizando métricas clave como `Accuracy`, `Precision`, `Recall`, `F1-Score` y `ROC AUC`.
* **Interpretar los resultados**, incluyendo la importancia de las variables, para entender los factores que impulsan la cancelación.
* **Crear una conclusión estratégica** con recomendaciones de negocio para mitigar la evasión.

## 🚀 Tecnologías y Bibliotecas Utilizadas

* **Python 3.x**
* **Pandas:** Para la manipulación y análisis de datos.
* **NumPy:** Para operaciones numéricas eficientes.
* **Matplotlib y Seaborn:** Para la visualización de datos y resultados.
* **Scikit-learn:** Para el preprocesamiento de datos y la construcción de los modelos de Machine Learning.

## 📂 Estructura del Proyecto

El proyecto está contenido en un único notebook de Jupyter, `TelecomXprojectP2.ipynb`, que sigue la siguiente estructura:

1.  **Carga de bibliotecas y datos:** Importación de librerías y carga del archivo `clientes_telecom_limpio.csv`.
2.  **Análisis Exploratorio y Preprocesamiento:** Limpieza de datos, manejo de nulos y codificación de variables.
3.  **Modelado:** Entrenamiento de los modelos `LogisticRegression` y `RandomForestClassifier`.
4.  **Evaluación de Modelos:** Comparación del rendimiento de los modelos con métricas de clasificación.
5.  **Interpretación y Conclusión Estratégica:** Análisis de la importancia de las variables y resumen de los hallazgos clave.

## 💡 Cómo Ejecutar el Proyecto

1.  Asegúrate de tener Python y las bibliotecas mencionadas instaladas.
2.  Coloca el archivo `clientes_telecom_limpio.csv` en la misma carpeta que el notebook.
3.  Abre el notebook `TelecomXprojectP2.ipynb` en tu entorno de desarrollo (ej. Jupyter Notebook, VS Code).
4.  Ejecuta las celdas del notebook en orden para reproducir el análisis completo.
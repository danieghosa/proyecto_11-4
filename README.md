## **Proyecto de Predicción de Enfermedades Cardíacas**

### **Descripción del Proyecto**

Este proyecto se enfoca en desarrollar un modelo de machine learning para predecir la presencia y severidad de enfermedades cardíacas en pacientes. El objetivo es proporcionar una herramienta que pueda asistir a los profesionales de la salud en el diagnóstico temprano y la planificación del tratamiento.

### **Qué Hice**

1. **Análisis Exploratorio de Datos (EDA):**  
   * Carga y exploración del dataset para entender su estructura y características.  
   * Visualización de la distribución de las variables y su relación con la enfermedad cardíaca.  
   * Identificación y tratamiento de valores faltantes y atípicos.  
2. **Preprocesamiento de Datos:**  
   * Manejo de valores faltantes mediante imputación y eliminación de columnas.  
   * Codificación de variables categóricas usando One-Hot Encoding.  
   * Escalado de características numéricas con StandardScaler.  
3. **Modelado:**  
   * Selección y entrenamiento de un modelo de Regresión Logística para predecir la enfermedad cardíaca.  
   * División de los datos en conjuntos de entrenamiento y prueba para evaluar el rendimiento del modelo.  
4. **Evaluación del Modelo:**  
   * Utilización de métricas como precisión, recall, F1-score y la matriz de confusión para evaluar el rendimiento del modelo.  
   * Análisis de los resultados para determinar la efectividad del modelo en la predicción de enfermedades cardíacas.

### **Cómo se Usa**

1. **Requisitos:**  
   * Python 3.x  
   * Librerías: pandas, numpy, matplotlib, seaborn, scikit-learn  
2. **Instalación:**  
   * Clonar el repositorio.  
   * Instalar las dependencias usando pip install \-r requirements.txt.  
3. **Uso:**  
   * Ejecutar el notebook Proyecto\_Modulo\_ML.ipynb en Jupyter Notebook o Google Colab.  
   * El notebook contiene el código para cargar los datos, preprocesarlos, entrenar el modelo y evaluar su rendimiento.  
   * Los resultados del modelo se mostrarán en el notebook, incluyendo las métricas de evaluación y las predicciones.

### **Modelo Seleccionado y Justificación**

Se seleccionó el modelo de Regresión Logística por su eficacia en problemas de clasificación multiclase y su capacidad para proporcionar probabilidades de pertenencia a cada clase. Aunque es un modelo lineal, demostró un buen rendimiento en este conjunto de datos, ofreciendo un equilibrio entre precisión y interpretabilidad.

### **Conclusiones Finales**

* El proyecto demostró la viabilidad de utilizar machine learning para predecir enfermedades cardíacas a partir de datos de pacientes.  
* El modelo de Regresión Logística logró una precisión adecuada, pero su rendimiento puede mejorarse con más datos y una selección de características más exhaustiva.  
* El análisis reveló la importancia de un preprocesamiento de datos adecuado, incluyendo el manejo de valores faltantes y el escalado de características.  
* Este proyecto puede servir como base para desarrollar una herramienta de apoyo a la decisión clínica que ayude a los médicos a identificar pacientes de alto riesgo y a personalizar los tratamientos.
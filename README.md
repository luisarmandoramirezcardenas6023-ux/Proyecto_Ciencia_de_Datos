# 📈 Proyecto de Ciencia de Datos: Predicción de Fuga de Clientes (Churn Rate)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1eJn7Od1yLuUcJcmmDy4MFfBrD_kqappQ?usp=sharing) ← **Haz clic aquí para ejecutar el cuaderno interactivo en tiempo real.**

Este repositorio contiene una solución analítica integral desarrollada en Python para la predicción y análisis de la pérdida de clientes (Churn Rate). El sistema procesa perfiles de usuarios mediante técnicas avanzadas de ciencia de datos y entrena modelos de Machine Learning para identificar comportamientos de riesgo, transformando métricas estadísticas en estrategias óptimas de retención y rentabilidad para el negocio.

## 🛠️ ¿Qué problemas soluciona?
La pérdida imprevista de clientes afecta directamente los ingresos y eleva los costos de adquisición. Este proyecto soluciona:
* **Falta de Proactividad Comercial:** Reemplaza la reacción tardía ante la fuga de clientes por un enfoque predictivo que identifica usuarios en riesgo antes de que abandonen el servicio.
* **Sesgo por Datos Incompletos o Sucios:** Implementa una limpieza exhaustiva, tratamiento de valores atípicos y codificación categórica (One-Hot) para garantizar que los modelos entrenen con información de alta calidad.
* **Desbalance de Clases en el Negocio:** Resuelve analíticamente la disparidad estadística típica de los datasets comerciales (donde la mayoría de los usuarios permanecen activos), evitando predicciones sesgadas.
* **Complejidad Métrica a Estrategia:** Traduce métricas algorítmicas abstractas (Matriz de Confusión, Recall, F1-Score) en indicadores financieros y decisiones tácticas viables para el equipo directivo.

## 🚀 Tecnologías Utilizadas
* **Lenguaje:** Python 3.x.
* **Modelado Predictivo y Machine Learning:** `scikit-learn` para el entrenamiento, ajuste e implementación de clasificadores.
* **Manipulación y Ciencia de Datos:** `pandas` y `numpy` para la ingeniería de características y estructuración de los datos.
* **Visualización de Datos (EDA):** `seaborn` y `matplotlib` para la generación de gráficos de correlación y análisis de distribución.
* **Entorno de Trabajo:** Jupyter Notebook / Entorno de desarrollo interactivo de Python.

## 📊 Funcionalidades Principales
1. **Análisis Exploratorio (EDA):** Diagnóstico visual de patrones de consumo, comportamiento y variables demográficas vinculadas al abandono.
2. **Pipeline de Preprocesamiento:** Flujo automatizado de normalización, limpieza y transformación de variables crudas en vectores aptos para algoritmos.
3. **Clasificación Multialgoritmo:** Evaluación comparativa de múltiples clasificadores (Random Forest, Árboles de Decisión, KNN) para seleccionar la arquitectura más precisa.
4. **Optimización con Enfoque de Negocio:** Configuración y calibración de hiperparámetros priorizando el *Recall* para mitigar los costos de falsos negativos.

## ⚙️ ¿Qué hace el sistema?
El software funciona como un pipeline analítico secuencial que transforma datos transaccionales y de perfil en conocimiento predictivo, realizando de forma automatizada las siguientes operaciones:

* **Ingeniería de Características (Features):** Ejecuta la transformación y codificación de variables nominales a numéricas, asegurando la correcta interpretación por parte de los modelos matemáticos.
* **Tratamiento y Balanceo de Datos:** Aplica técnicas analíticas para balancear las muestras de clientes activos frente a los que se han fugado, estabilizando la base de entrenamiento.
* **Entrenamiento Adaptativo:** Ajusta de manera simultánea diferentes algoritmos de clasificación, analizando el comportamiento predictivo de cada uno bajo condiciones controladas.
* **Evaluación de Rendimiento Estratégico:** Despliega métricas de precisión técnica que evalúan el desempeño real del modelo, permitiendo conocer con exactitud el nivel de confiabilidad para campañas de retención dirigidas.
* **Análisis de Importancia de Variables:** Identifica qué factores (precio, antigüedad, tipo de contrato, etc.) tienen mayor peso en la decisión del cliente de abandonar la empresa.

## 📖 Manual de Uso
1. **Instalación:** Clone el repositorio localmente e instale las librerías necesarias mediante `pip install pandas numpy scikit-learn seaborn matplotlib`.
2. **Carga de Datos:** Coloque el dataset de perfiles en la ruta indicada dentro del script o cuaderno.
3. **Ejecución:** Inicie el script principal o el entorno de Jupyter para ejecutar secuencialmente el pipeline de datos (desde la limpieza hasta el modelado).
4. **Interpretación:** Revise los gráficos de salida y los reportes de métricas para evaluar la precisión del modelo entrenado y su relevancia con los objetivos del negocio.

## 👥 Desarrollador
Este sistema fue desarrollado por:
* **Ramirez Cardenas Luis Armando**
* **Contacto:** https://www.linkedin.com/in/luis-armando-ramirez-cardenas-53712035b/
* Todo el flujo de ciencia de datos, el análisis exploratorio, el preprocesamiento de variables, el diseño de la lógica del modelo y la optimización de los algoritmos de Machine Learning fueron construidos desde cero por mi cuenta para ofrecer una solución predictiva funcional y orientada a la toma de decisiones empresariales.
* **Carrera:** Inteligencia de Negocios.

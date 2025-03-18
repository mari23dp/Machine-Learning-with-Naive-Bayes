# Machine Learning with Naive Bayes

Este repositorio contiene un proyecto de aprendizaje automático donde se utiliza el algoritmo **Naive Bayes** para la clasificación de datos. El objetivo es aprender y aplicar este modelo en un conjunto de datos para tareas de clasificación.

## Tecnologías Utilizadas

- **Python**: Lenguaje de programación principal para el desarrollo de los modelos.
- **Scikit-learn**: Librería de Python para construir y evaluar modelos de aprendizaje automático.
- **Pandas**: Librería para manipulación y análisis de datos.
- **Matplotlib/Seaborn**: Librerías para visualización de datos.

## Descripción del Proyecto

En este proyecto, el objetivo principal es aplicar el algoritmo **Naive Bayes** a un conjunto de datos para la clasificación. Los pasos básicos incluyen:

1. **Cargar los datos**: El conjunto de datos se carga y se preprocesa usando **Pandas**.
2. **Entrenamiento del modelo**: Se entrena un clasificador **Naive Bayes** utilizando la librería **Scikit-learn**.
3. **Evaluación del modelo**: Se evalúa el rendimiento del modelo usando las siguientes métricas:
   - **Precisión (Accuracy)**
   - **Matriz de Confusión**
   - **Curva ROC (Receiver Operating Characteristic)**: Visualización para evaluar la capacidad del modelo para discriminar entre clases.
   - **AUC (Area Under the Curve)**: Métrica que calcula el área bajo la curva ROC para medir la calidad del modelo.
4. **Visualización**: Se muestran gráficos y resultados para ayudar en la interpretación de los resultados.

## Requisitos

- Python 3.x
- Scikit-learn
- Pandas
- Matplotlib/Seaborn
- Jupyter Notebook (opcional para ver los notebooks)


## Estructura del Repositorio

```plaintext
/
├── /data               # Conjuntos de datos utilizados en el proyecto.
├── /notebooks          # Notebooks de Jupyter con código, análisis y resultados.
├── /src                # Código fuente para cargar datos y entrenar el modelo.
├── /models             # Modelos entrenados guardados.

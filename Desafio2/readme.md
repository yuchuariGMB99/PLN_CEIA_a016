# Desafío 2

Este repositorio contiene la resolución del **Desafío 2** en formato Jupyter Notebook.

## Descripción del desafío
El código de este desafío está orientado a **procesar datos de texto y aplicar técnicas de clasificación automática**.  
Las principales tareas implementadas en el notebook son:

1. **Carga del dataset**: se importa el conjunto de datos de noticias para trabajar con texto real.  
2. **Preprocesamiento de datos**: se realiza limpieza de los textos (normalización, eliminación de símbolos innecesarios y tokenización).  
3. **Vectorización de documentos**: los textos se convierten en vectores numéricos mediante **TF–IDF** y/o **CountVectorizer** para que puedan ser procesados por modelos de machine learning.  
4. **Entrenamiento del modelo**: se implementa un clasificador **Naïve Bayes** para categorizar los documentos en diferentes clases.  
5. **Evaluación del rendimiento**: se obtienen métricas de desempeño como exactitud (*accuracy*), matriz de confusión y reporte de clasificación.  
6. **Pruebas de predicción**: el código incluye ejemplos de predicciones con nuevos textos, mostrando cómo el modelo generaliza sobre datos no vistos.  

Este flujo permite observar cómo un texto crudo puede convertirse en información estructurada y clasificada automáticamente.

## Contenido del Notebook
- Introducción al desafío  
- Carga de datos  
- Preprocesamiento de texto  
- Vectorización con TF–IDF / CountVectorizer  
- Entrenamiento del modelo Naïve Bayes  
- Evaluación y métricas de rendimiento  
- Predicciones de ejemplo  

## Requisitos
- **Python 3.3**  
- **Jupyter Notebook** o **JupyterLab**  
- Librerías principales:  
  - scikit-learn  
  - numpy  
  - pandas  
  - matplotlib  

## Cómo ejecutar

Clona el repositorio y abre el notebook:

```bash
git clone https://github.com/yuchuariGMB99/PLN_CEIA_a016
cd PLN_CEIA_a016
jupyter notebook Desafio2.ipynb

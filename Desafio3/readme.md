# Desafío 3

Este repositorio contiene la resolución del **Desafío 3** en formato Jupyter Notebook.

## Descripción del desafío
El objetivo de este desafío es implementar un **flujo completo de procesamiento de texto y clasificación automática**.  
El código se encarga de:

1. **Carga de datos**: se importan los textos desde el dataset proporcionado.  
2. **Preprocesamiento**: se aplican técnicas de limpieza (tokenización, normalización, eliminación de caracteres innecesarios).  
3. **Vectorización de documentos**: los textos son transformados en representaciones numéricas mediante **TF–IDF** o **CountVectorizer**.  
4. **Entrenamiento del modelo**: se entrena un clasificador **Naïve Bayes** sobre los datos vectorizados.  
5. **Evaluación del modelo**: se calculan métricas como exactitud (*accuracy*), matriz de confusión y reporte de clasificación.  
6. **Similaridad y análisis adicional**: el código explora la similitud entre documentos, utilizando distancias y comparaciones vectoriales.  

De esta forma, el notebook demuestra cómo pasar de **texto crudo** a **predicciones automáticas**, validando la utilidad de los modelos probabilísticos en problemas de clasificación de lenguaje natural.

## Contenido del Notebook
- Introducción al desafío  
- Carga y preparación de los datos  
- Vectorización de texto (TF–IDF / CountVectorizer)  
- Entrenamiento del modelo Naïve Bayes  
- Evaluación del desempeño  
- Análisis de similitud de documentos  

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
jupyter notebook Desafio3.ipynb

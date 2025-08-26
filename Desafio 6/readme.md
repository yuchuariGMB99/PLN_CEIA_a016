# Desafío 6 - Chatbot

Este repositorio contiene la resolución del **Desafío 6**, cuyo objetivo es construir un **chatbot basado en técnicas de Procesamiento de Lenguaje Natural (PLN)** utilizando Python y librerías clásicas de machine learning.

## Descripción del desafío
El código implementa un chatbot sencillo que responde a preguntas de los usuarios a partir de reglas y modelos de PLN.  
El flujo principal del notebook incluye:

1. **Definición de intenciones y respuestas**: se prepara un conjunto de pares *pregunta-respuesta* para entrenar al bot.  
2. **Preprocesamiento de texto**: tokenización, lematización y normalización del lenguaje natural.  
3. **Vectorización**: representación de las frases mediante **TF–IDF** o conteo de palabras.  
4. **Entrenamiento de un modelo de clasificación**: uso de algoritmos como **Naïve Bayes** o similares para predecir la intención de la frase.  
5. **Construcción del chatbot**: integración del modelo con la lógica que selecciona la respuesta adecuada.  
6. **Pruebas de interacción**: ejecución de ejemplos en los que el usuario envía mensajes y el chatbot responde automáticamente.  

Este desafío muestra cómo se puede diseñar un sistema conversacional básico sin necesidad de usar redes neuronales profundas.

## Contenido del Notebook
- Desafio #6

## Requisitos
- **Python 3.3**
- **Jupyter Notebook** o **JupyterLab**
- Librerías principales detectadas/estimadas:
  - ast
  - gradio
  - io
  - matplotlib
  - numpy
  - pandas
  - pathlib
  - requests
  - tensorflow
  - tqdm
  - zipfile

## Cómo ejecutar

Clona el repositorio y abre el notebook:

```bash
git clone https://github.com/yuchuariGMB99/PLN_CEIA_a016
cd PLN_CEIA_a016
jupyter notebook desafio_6_chatbot.ipynb
```


## Resultados esperados
- El chatbot responde de manera coherente a distintas entradas de texto.  
- Se observan métricas de rendimiento sobre la clasificación de intenciones.  
- Ejemplos interactivos de conversación con el modelo.  

## Autoría
Trabajo desarrollado como parte de las prácticas de aprendizaje en **PLN** y **construcción de chatbots con Python 3.3**.

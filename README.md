# Proyecto de Análisis de Quejas de Consumidores Mediante NLP

Este proyecto se centra en el análisis de quejas de consumidores utilizando técnicas de procesamiento de texto y aprendizaje automático para identificar temas y patrones en las quejas presentadas por los consumidores.

## Requisitos

Antes de comenzar, asegúrate de tener instalados los siguientes paquetes y bibliotecas:

- Python 3.x
- Pandas
- Numpy
- Scikit-Learn
- Matplotlib
- Seaborn
- NLTK
- TextBlob
- WordCloud
- NMF (Non-Negative Matrix Factorization)


## Proceso de Análisis

El proyecto se divide en varias etapas:

1. **Carga de Datos**: Comenzamos cargando los datos de las quejas desde un archivo JSON.

2. **Preprocesamiento de Texto**: Llevamos a cabo una serie de pasos de preprocesamiento de texto, que incluyen la conversión a minúsculas, eliminación de puntuación, tokenización, eliminación de stopwords, lematización y extracción de partes del discurso.

3. **Vectorización de Texto**: Utilizamos TF-IDF para convertir el texto preprocesado en una representación numérica adecuada para el aprendizaje automático.

4. **Descomposición de Matrices No Negativas (NMF)**: Aplicamos NMF para identificar temas latentes en las quejas y asignamos etiquetas de tema a cada queja.

5. **Visualización de Tópicos**: Visualizamos los temas identificados y sus palabras clave más importantes.

6. **Exploración de Datos**: Realizamos un análisis exploratorio de datos para comprender mejor la distribución de las quejas y otros patrones.

7. **Entrenamiento de Modelos de Clasificación**: Si es necesario, entrenamos modelos de clasificación para tareas adicionales, como la predicción de la categoría de una queja.

8. **Documentación y Resultados**: Documentamos los resultados y conclusiones en este archivo README.md y, si es necesario, en otros archivos de informe.

## Resultados

El análisis de quejas ha revelado varios temas latentes, lo que nos permite comprender mejor las preocupaciones y problemas más comunes de los consumidores. Los resultados se pueden encontrar en el proyecto, junto con visualizaciones y gráficos que ayudan a comunicar estos hallazgos de manera efectiva.

## Uso del Código

Puedes utilizar el código proporcionado en este proyecto como punto de partida para tu propio análisis de texto y aplicaciones de aprendizaje automático relacionadas con datos de quejas de consumidores.

## Contribuciones

Las contribuciones son bienvenidas. Si deseas contribuir o informar sobre problemas, por favor abre un problema o envía una solicitud de extracción.




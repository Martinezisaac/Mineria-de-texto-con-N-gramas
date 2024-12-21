# Análisis de Texto en Netflix con NLP
Este proyecto contiene un análisis de datos realizado sobre el conjunto de datos de Netflix, utilizando técnicas de procesamiento de lenguaje natural (NLP) para extraer información de las descripciones de películas y series del set de datos. El proyecto aborda el análisis de texto, la lematización, la eliminación de stopwords y la vectorización de datos, con el objetivo de explorar las palabras más frecuentes y los patrones dentro de dicho set de Netflix.
<br> <br>

## Descripción: 
El proyecto se centra en el procesamiento de texto extraído de las descripciones de series y películas disponibles en un conjunto de datos, se utilizan técnicas de procesamiento de lenguaje natural, se realiza un análisis que ayuda a identificar patrones lingüísticos comunes en las descripciones o cualquier información que se desee buscar, como lo pueden ser los autores, los actores de reparto, el año, la calsificación del contenido, etc.

Minería de texto con N-Gramas incluye:
- **Lematización:** Cada palabra en el conjunto de datos es reducida a su raíz o lema utilizando el modelo de lenguaje en inglés de `spaCy`.
- **Eliminación de stopwords:** Se eliminan palabras irrelevantes como preposiciones, artículos y pronombres, que no aportan información significativa al análisis.
- **Vectorización de texto:** Las descripciones de texto son convertidas en representaciones numéricas mediante el uso de `CountVectorizer` de `sklearn`, permitiendo analizar la frecuencia de las palabras.
- **Visualización de Datos:** Se generan gráficos para visualizar las 30 palabras más frecuentes y explorar el contenido textual a través de representaciones gráficas.

Este proyecto proporciona una comprensión más profunda del vocabulario utilizado en las descripciones de contenido de Netflix, esto puede ser útil para realizar análisis más complejos o para diseñar sistemas de recomendación basados en texto.

## Objetivos:
- **Explorar el vocabulario utilizado en los datos de una base de datos de Netflix**: Identificar las palabras más frecuentes y comprender los patrones lingüísticos comunes.
- **Implementar un pipeline de NLP**: Aplicar técnicas de lematización, eliminación de stopwords y vectorización de texto para transformar los datos en un formato analizable.
- **Visualización**: Representar gráficamente N cantidad de palabras más frecuentes en las descripciones para obtener una visión rápida de las palabras o metadatos más recurrentes.
- **Comparar resultados entre diferentes enfoques de procesamiento**: Evaluar los efectos de la eliminación de stopwords y la lematización sobre los resultados de la vectorización.
<br> <br>

## Requisitos: 
Para ejecutar el proyecto, es necesario tener instalado Jupyter (es posible ejecutarlo en Google Colab) y las siguientes librerías:

- **spaCy**: Para realizar la lematización de palabras.
- **nltk**: Para acceder a las stopwords en inglés y español.
- **sklearn**: Para la vectorización del texto y otras técnicas de aprendizaje automático.
- **pandas**: Para la manipulación y análisis de datos.
- **matplotlib y seaborn**: Para la visualización de los resultados.


# Multilingual News Sentiment Analysis

## Description
This project aims to analyze the sentiment of news headlines extracted directly from news websites from different countries. The default code extracts 10 headlines from Italian, French, and German news websites, but it's customizable to analyze headlines from other sources as well.

## How it Works
- **Scraping News Headlines:** The code scrapes headlines from news websites. Users can specify the websites they want to analyze.
  
- **Translation to English:** Utilizing a model from Hugging Face's Transformers library, the headlines are translated into English. This step ensures uniformity in language for sentiment analysis.

- **Sentiment Analysis:** Another model from Hugging Face's Transformers library is used to determine the sentiment of each headline. The sentiment is classified as positive or negative.

- **Presentation:** All the collected data, including original headlines, translated headlines, and sentiment analysis results, are organized in a Pandas DataFrame. 

## Usage
**1. Install the required libraries to run the program:** <br>
   These are located in the Libraries file, already prepared for execution. <br>

**2. Run the main program:** <br>
   Run the main program to initiate the sentiment analysis process. The results will be displayed automatically.

## Acknowledgments
This program uses the nllb-200-distilled-600M model and syedkhalid076/RoBERTa-Sentimental-Analysis-Model from Hugging Face to function. The program has been created only for educational purposes. <br>
Model link: https://huggingface.co/facebook/nllb-200-distilled-600M <br>
Model link: https://huggingface.co/syedkhalid076/RoBERTa-Sentimental-Analysis-Model

<br><br>

# Análisis de Sentimientos de Noticias Multilingüe

## Descripción
Este proyecto tiene como objetivo analizar el sentimiento de titulares de noticias de diferentes países. El código por defecto extrae 10 titulares de sitios web de noticias italianas, francesas y alemanas, pero es personalizable para analizar titulares de otras fuentes también.

## Cómo funciona
- **Extracción de Titulares de Noticias:** El código extrae titulares de sitios web de noticias. Los usuarios pueden especificar los sitios web que desean analizar.
  
- **Traducción al Inglés:** Utilizando un modelo de la biblioteca Transformers de Hugging Face, los titulares se traducen al inglés. Este paso garantiza uniformidad en el idioma para el análisis de sentimientos.

- **Análisis de Sentimientos:** Se utiliza otro modelo de la biblioteca Transformers de Hugging Face para determinar el sentimiento de cada titular. El sentimiento se clasifica como positivo o negativo.

- **Presentación:** Todos los datos recopilados, incluidos los titulares originales, los titulares traducidos y los resultados del análisis de sentimientos, se organizan en un DataFrame de Pandas.

## Uso
**1. Instala las librerias necesarias para ejecutar el programa:** <br>
   Estas se encuentran en el archivo Libraries, ya preparadas para ejecutar. <br>

**2. Ejecuta el programa:** <br>
  Ejecuta el programa principal para iniciar el proceso de análisis de sentimientos. Los resultados se mostrarán automáticamente.

## Reconocimiento
Este programa utiliza el modelo nllb-200-distilled-600M y el modelo syedkhalid076/RoBERTa-Sentimental-Analysis-Model de Hugging Face para funcionar. El programa ha sido creado únicamente con fines educativos. <br>
Enlace del modelo: https://huggingface.co/facebook/nllb-200-distilled-600M <br>
Enlace del modelo: https://huggingface.co/syedkhalid076/RoBERTa-Sentimental-Analysis-Model

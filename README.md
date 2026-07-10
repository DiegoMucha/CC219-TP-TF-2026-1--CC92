# Trabajo Final - Data Science

## Objetivo
El presente trabajo tiene como objetivo diseñar e implementar un modelo de clasificación capaz de predecir, a partir de un texto de entrada, el idioma en el que este fue escrito, considerando únicamente el conjunto de idiomas con los que el modelo fue previamente entrenado. Además, queremos implementar este modelo combinado con un traductor para que chatbots como ALMA UPC que solo pueden hablar en un idioma, ahora puedan comunicarse en multiples idiomas para tratar con personas de diferentes lugares.

## Integrantes
- Alexander Miranda Vivanco
- Leonardo Mathias Juscamayta Trujillo
- Diego Fabrizio Mucha Alvarez

## Breve Descripción del Dataset
El dataset utilizado fue obtenido de kaggle, una plataforma de competencias y repositorios diseñados para la ciencia de datos. El dataset se descargó mediante la API de Kaggle con un comando curl. El link se encuentra en Anexos. El archivo descargado es un archivo comprimido (.zip) que contiene el archivo CSV principal: Language Detection.csv. El dataset Language Detection está diseñado para la tarea de clasificación de texto multilingüe, cuyo objetivo es identificar automáticamente el idioma al que pertenece un fragmento de texto dado. A continuación se resumen sus características principales:

## Conclusiones
En conclusión, el presente trabajo permitió desarrollar un modelo capaz de clasificar el idioma de un texto de entrada de manera efectiva. Para ello, se aplicaron distintas técnicas de preprocesamiento, tales como la eliminación de stopwords, la tokenización, la eliminación de caracteres no alfabéticos y de signos de puntuación, procesos que resultaron fundamentales para obtener una tokenización limpia y consistente antes de entrenar los modelos. Posteriormente, se probaron tres algoritmos de clasificación: N-gramas + Naive Bayes, N-gramas + Regresión Logística y N-gramas + TF-IDF + Regresión Logística. Los tres enfoques mostraron un desempeño positivo, alcanzando niveles de accuracy altos y bastante similares entre sí, lo cual evidencia la solidez del preprocesamiento realizado. No obstante, el modelo que obtuvo el mejor rendimiento fue el de N-gramas + TF-IDF + Regresión Logística, con un accuracy de 0.96, superando ligeramente a los demás algoritmos evaluados. Finalmente, mediante una prueba rápida con oraciones nuevas, se comprobó que el modelo es capaz de clasificar el idioma de manera precisa y consistente, confirmando así su efectividad para resolver el problema planteado.

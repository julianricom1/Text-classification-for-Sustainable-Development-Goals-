# Achieving the Sustainable Development Goals: A Contribution from Machine Learning

**Note:** This project was carried out in Spanish. Code and commentaries are in spanish and a version in spanish of this file is included further down

## Description

On September 25, 2015, the United Nations (UN) adopted the 2030 Agenda for Sustainable Development, aiming to reduce poverty, ensure access to health and education, promote gender equality and opportunities, and decrease environmental impact, among other goals. To this end, it defines 17 Sustainable Development Goals (SDGs) and 169 targets derived from these different goals. 

As part of the collaboration among various entities to achieve the Sustainable Development Goals outlined in the 2030 Agenda, many organizations are tasked with monitoring and evaluating public policies and their social impact. This is the case with the United Nations Population Fund (UNFPA), which, together with public institutions and using various citizen participation tools, seeks to identify problems and assess current solutions, relating information to the different SDGs.

One of the processes requiring significant effort is the interpretation and analysis of textual information from various sources involved in participatory planning for territorial development. This task consumes a large amount of resources and requires experts to relate the texts to the SDGs. This knowledge would facilitate decision-making based on the opinions of the population and guide public policies in a more informed manner to fulfill the 2030 Agenda.

The objective of the project is to develop a solution based on natural language processing (NLP) and machine learning techniques that can automatically classify a text according to the 17 SDGs, offering a user-friendly presentation of results for the end-user.

### A. Objective

- Develop a solution based on natural language processing and machine learning techniques to facilitate the interpretation and analysis of textual information for identifying semantic relationships with the Sustainable Development Goals.

### B. Dataset

The dataset is part of the "OSDG Community Dataset" (OSDG-CD) project in its 2023 version, containing a total of 40,067 texts, of which 3,000 come from UN-related sources. It also includes public documents, article summaries, and reports. The platform gathers researchers, subject matter experts, and advocates for the SDGs from around the world to create a comprehensive and accurate source of textual information about the SDGs. Community volunteers use the platform to participate in labeling exercises to validate the relevance of each text to the SDGs based on their prior knowledge.

The texts used in this project have been translated into Spanish using tools such as Deepl. Text augmentation was also performed through the ChatGPT API.

### C. Activities to Perform

1. **Text Preparation:** Utilize the Bag of Words (BOW) schema with TF-IDF weighting. For this step, construct a pipeline that integrates the appropriate transformations.
2. **Model Development:** Develop a classification model that allows relating a text to an SDG. To manage the complexity of the input space, apply a dimensionality reduction algorithm.
3. **Model Evaluation:** Evaluate the model with texts that have not been used for training.

---

# Alcanzando los Objetivos de Desarrollo Sostenible: Un Aporte desde el Machine Learning

## Descripción

La Organización de las Naciones Unidas (ONU) adopta, el 25 de septiembre del año 2015, la Agenda 2030 para el desarrollo sostenible, cuyo fin es reducir la pobreza, garantizar acceso a la salud y educación, buscar igualdad de género y oportunidades y disminuir el impacto ambiental, entre otros propósitos. A tal efecto, define 17 objetivos de desarrollo sostenible (ODS) y 169 metas (derivadas de los diferentes ODS).

Dentro del trabajo en conjunto de diferentes entes para alcanzar el cumplimiento de los objetivos de desarrollo sostenible definidos en la Agenda 2030, muchas entidades tienen como función el seguimiento y la evaluación de las políticas públicas y su impacto a nivel social. Este es el caso del Fondo de Población de las Naciones Unidas (UNFPA, por sus siglas en inglés), que, junto con instituciones públicas y haciendo uso de diferentes herramientas de participación ciudadana, busca identificar problemas y evaluar soluciones actuales, relacionando la información con los diferentes ODS.

Uno de los procesos que requiere de un mayor esfuerzo es la interpretación y análisis de la información textual procedente de diferentes fuentes implicadas en la planeación participativa para el desarrollo a nivel territorial, ya que es una tarea que consume gran cantidad de recursos y para la cual se requiere de expertos que relacionen los textos con los ODS. Este conocimiento facilitaría la toma de decisiones con base en la opinión de la población y permitiría encaminar las políticas públicas de manera más informada para el cumplimiento de la Agenda 2030.

El objetivo del proyecto es desarrollar una solución, basada en técnicas de procesamiento del lenguaje natural y machine learning, que permita clasificar automáticamente un texto según los 17 ODS, ofreciendo una forma de presentación de resultados a través de una herramienta de fácil comprensión para el usuario final.

### A. Objetivo

- Desarrollar una solución, basada en técnicas de procesamiento de lenguaje natural y machine learning, que facilite la interpretación y análisis de información textual para la identificación de relaciones semánticas con los Objetivos de Desarrollo Sostenibles.

### B. Conjunto de Datos

El conjunto de datos forma parte del proyecto “OSDG Community Dataset” (OSDG-CD), en su versión 2023, que contiene un total de 40.067 textos, de los cuales 3000 provienen de fuentes relacionadas con las Naciones Unidas. También contiene documentos públicos, resúmenes de artículos y reportes. La plataforma reúne investigadores, expertos en la materia y defensores de los ODS de todo el mundo para crear una fuente amplia y precisa de información textual sobre los ODS. Los voluntarios de la comunidad utilizan la plataforma para participar en ejercicios de etiquetado en los que validan la relevancia de cada texto para los ODS basándose en sus conocimientos previos.

Los textos que serán utilizados en este proyecto han sido traducidos al español por herramientas como Deepl. También se realizó una aumentación de textos a través del API de ChatGPT.

### C. Actividades para Realizar

1. **Preparación de los Textos:** Utilizar el esquema de bolsa de palabras (BOW) con un pesado TF-IDF. Para este paso, construir un pipeline que integre las transformaciones que se consideren adecuadas.
2. **Desarrollo de un Modelo de Clasificación:** Que permita relacionar un texto con un ODS. Para manejar la complejidad del espacio de entrada, aplicar un algoritmo de reducción de la dimensionalidad.
3. **Evaluación del Modelo:** Evaluar el modelo con textos que no hayan sido utilizados para el aprendizaje.

---

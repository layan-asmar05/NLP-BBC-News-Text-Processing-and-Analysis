# Text Processing and Analysis of BBC News Dataset

## Introduction
This project aims to apply fundamental Natural Language Processing (NLP) techniques to real-world text data. The dataset used is a balanced subset of 120 articles from the BBC News Dataset, covering three categories: business, politics, and sport.

## Technologies Used
The project was developed using **Python** and executed on **Google Colab**. The main libraries used include:
* **NLTK (Natural Language Toolkit):** For core NLP tasks.
* **BeautifulSoup:** For HTML parsing.
* **pandas:** For data structuring.
* **matplotlib:** For data visualization.
* **ipywidgets:** To build an interactive mini-application.

## Key Features & Methodology
1. **Text Wrangling Pipeline:** Cleaned raw text by removing HTML tags, URLs, numbers, and special characters, followed by tokenization. We also compared Porter Stemmer and WordNet Lemmatizer, concluding that lemmatization produces more meaningful English words.
2. **Part-of-Speech (POS) Tagging:** Applied NLTK's averaged perceptron tagger, revealing that Singular Nouns, Adjectives, and Plural Nouns were the most frequent tags.
3. **Chunking and Chinking:** Designed regular expression grammar to extract Noun Phrases while strictly excluding verbs and prepositions.
4. **Named Entity Recognition (NER):** Extracted entities classified as PERSON, ORGANIZATION, and Geopolitical Entities (GPE), and performed manual error analysis on ambiguous entities like "Jack Straw" and "Madrid".
5. **Interactive Mini-Application:** Developed a Keyword Frequency Dashboard that allows users to select a news category (Politics, Business, or Sport) and dynamically view a bar chart of the top 10 most frequent keywords.

## Course
Natural Language Processing

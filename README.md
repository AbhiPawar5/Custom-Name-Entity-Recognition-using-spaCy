# Custom-Name-Entity-Recognition-using-spaCy
Name-Entity-Recognition or NER is probably the first step towards information extraction that seeks to locate and classify named entities in text into pre-defined categories such as the names of persons, organizations, locations, monetary values, percentages, etc using NLP. For this, we use spaCy.

## Getting started with spaCy
[spaCy](https://spacy.io/usage/spacy-101) is a free, open-source library for advanced Natural Language Processing (NLP) in Python. spaCy is designed specifically for production use and helps you build applications that process and “understand” large volumes of text. It can be used to build information extraction or natural language understanding systems, or to pre-process text for deep learning. 

## About the project
I have recently started to explore about NLP and I always like to learn with examples. This is a Jupyter Notebook which demonstrates training custome NER model to extract ORG or PROD from the text.

## Example 
```
sentence = "I was driving my Santro and visited my hometown Sangli, Maharashtra"
Entities [('Santro', 'PRODUCT'), ('Sangli', 'GPE'), ('Maharashtra', 'GPE')]
```

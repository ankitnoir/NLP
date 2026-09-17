# Natural Language Processing

This repository contains practical implementations of fundamental **Natural Language Processing (NLP)** techniques using Python. The practicals focus on basic text preprocessing and linguistic analysis methods that form the foundation of many NLP applications.

## About NLP

Natural Language Processing is a field of Artificial Intelligence that enables computers to process, analyze, and understand human language.

Human language is complex and can contain different meanings, structures, grammatical forms, and variations. NLP uses computational techniques to convert natural language into a form that can be analyzed by computers.

NLP is widely used in applications such as chatbots, search engines, sentiment analysis, machine translation, text classification, speech systems, and information extraction.

## Practicals Covered

### 1. Tokenization

Tokenization is the process of dividing a text into smaller units called **tokens**. Tokens can be individual words, sentences, or other meaningful parts of text.

For example, the sentence:

> "Natural Language Processing is interesting."

can be divided into individual words such as `Natural`, `Language`, `Processing`, and `interesting`.

The `Tokenization.ipynb` notebook demonstrates **word tokenization and sentence tokenization**.

### 2. Stemming and Lemmatization

Stemming and lemmatization are techniques used to reduce words to their base forms.

**Stemming** removes prefixes or suffixes from words to obtain a root form. The resulting word may not always be a valid dictionary word.

**Lemmatization** converts a word into its meaningful dictionary or base form while considering its linguistic properties.

For example, words such as `playing`, `played`, and `plays` can be reduced to a common base form.

The `stemming_lemmatization.ipynb` notebook demonstrates both techniques and highlights the difference between them.

### 3. Stopword Removal

Stopwords are commonly occurring words that may provide little useful information for certain NLP tasks. Examples include words such as `the`, `is`, `a`, `an`, and `and`.

Removing stopwords can reduce unnecessary information from a text and make further text analysis more efficient.

The `stopword_removal.ipynb` notebook demonstrates **stopword removal along with punctuation removal**.

### 4. Part-of-Speech Tagging

Part-of-Speech (POS) tagging is the process of assigning a grammatical category to each word in a sentence.

Common POS categories include:

* Noun
* Verb
* Adjective
* Adverb
* Pronoun
* Preposition
* Conjunction

For example, in the sentence "The student studies NLP", `student` can be identified as a noun and `studies` as a verb.

The `pos_tagging.ipynb` notebook demonstrates how POS tags can be assigned to words in text.

### 5. Parsing and Chunking

**Parsing** is the process of analyzing the grammatical structure of a sentence and identifying relationships between its words.

**Chunking** groups words into meaningful phrases, such as noun phrases and verb phrases.

These techniques help in understanding the syntactic structure of sentences and the relationships between different parts of text.

The `parsing_chunking.ipynb` notebook demonstrates basic parsing and chunking techniques for syntactic analysis.

### 6. Named Entity Recognition

Named Entity Recognition (NER) is an NLP technique used to identify and classify important entities present in a text.

Common named entities include:

* Person names
* Organizations
* Locations
* Countries
* Dates
* Products

For example, in the sentence "Apple was founded by Steve Jobs", NER can identify `Apple` as an organization and `Steve Jobs` as a person.

The `ner.ipynb` notebook demonstrates Named Entity Recognition using NLP techniques.

## Technologies Used

* Python
* NLTK
* spaCy
* Jupyter Notebook

## Learning Objectives

Through these practicals, the following fundamental NLP concepts are explored:

* Understanding the basics of Natural Language Processing
* Breaking text into words and sentences using tokenization
* Understanding the difference between stemming and lemmatization
* Removing stopwords and unnecessary punctuation
* Identifying grammatical categories using POS tagging
* Understanding sentence structure through parsing and chunking
* Identifying entities using Named Entity Recognition

These techniques provide a foundation for more advanced NLP tasks such as **sentiment analysis, text classification, machine translation, question answering, and information extraction**.

## Repository Structure

```text
NLP/
│
├── Tokenization.ipynb
├── stemming_lemmatization.ipynb
├── stopword_removal.ipynb
├── pos_tagging.ipynb
├── parsing_chunking.ipynb
├── ner.ipynb
│
└── README.md
```


# TASK 1
# Text Summarization Tool using NLP

## Overview

This project implements a **Text Summarization Tool** using Natural Language Processing (NLP) techniques in Python. The tool automatically generates a shorter version of a long text while preserving the important information and key ideas.

## Objective

To build a system that can analyze large blocks of text and produce a concise summary using NLP techniques.

## Technologies Used

* Python
* Natural Language Processing (NLP)
* NLTK (Natural Language Toolkit)
* Jupyter Notebook

## Features

* Sentence tokenization
* Stopword removal
* Word frequency analysis
* Automatic summary generation

## How It Works

1. The input text is provided by the user.
2. The text is divided into sentences using **sentence tokenization**.
3. Common words (stopwords) are removed.
4. Word frequencies are calculated to determine important words.
5. Sentences with higher scores are selected to generate the final summary.

## Example

### Input Text

```text
Artificial Intelligence is transforming industries across the world. 
It is being used in healthcare, education, finance, and transportation 
to improve efficiency and decision making.
```

### Generated Summary

```text
Artificial Intelligence is transforming industries across the world 
and improving efficiency in multiple sectors.
```

## Project Files

* `text_summarization.ipynb` – Notebook containing the implementation and examples.

## Result

The system successfully generates concise summaries from longer texts using NLP techniques.

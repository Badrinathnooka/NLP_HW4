# NLP Home Assignment 4

**Course:** CS5760 – Natural Language Processing  
**University:** University of Central Missouri  
**Student Name:** Badrinath Nooka
**Student Id :** #700782343

## Project Description

This assignment implements three NLP tasks using Python:

1. Text Preprocessing using NLTK
2. Named Entity Recognition using spaCy
3. Scaled Dot-Product Attention using NumPy

## Requirements

- Python 3
- NLTK
- spaCy
- NumPy

## Installation

Install the required libraries:

```bash
pip install nltk spacy numpy
python -m spacy download en_core_web_sm
```

## How to Run

**Q1: NLP Preprocessing**

```bash
python q1_preprocessing.py
```

Tokenizes the sentence, removes English stopwords, and applies Porter stemming.

**Q2: Named Entity Recognition**

```bash
python q2_named_entity_recognition.py
```

Uses spaCy to identify named entities and display their labels and character positions.

**Q3: Scaled Dot-Product Attention**

```bash
python q3_scaled_dot_product_attention.py
```

Calculates attention scores using Q and K, scales them, applies softmax, and multiplies the attention weights by V.

## Results

- **Q1:** Successfully performed tokenization, stopword removal, and stemming.
- **Q2:** Extracted entities such as LeBron James, NBA, United States, and 2020.
- **Q3:** Generated attention weights and the final output matrix.

## Conclusion

This assignment demonstrates fundamental NLP techniques, including text preprocessing, named entity recognition, and attention mechanisms used in Transformer models.

# NLP_Zipfs_law_of_abbreviation

This project explores **Zipf's Law of Abbreviation**, a well-established linguistic principle stating that **more frequent words tend to be shorter than less frequent words**.

Using Natural Language Processing (NLP) techniques, we analyze poetry corpora in **English** and **Spanish** to investigate the relationship between word frequency and word length. By comparing frequency distributions across both languages, we examine whether the data follows the patterns predicted by Zipf's Law of Abbreviation.


## Research Objective

The main objective of this project is to answer the following question:

> Do the most frequent words in English and Spanish poetry tend to be shorter than less frequent words?

To address this question, we:

- Collect and preprocess poetic corpora in English and Spanish.
- Extract and tokenize words.
- Calculate word frequencies.
- Measure word lengths.
- Rank words according to frequency.
- Visualize word frequency as a function of word length.

## Datasets

### English Poetry Dataset

Source:

```python
load_dataset("merve/poetry")
```

This dataset contains a collection of English poems available through the Hugging Face Datasets library.

### Spanish Poetry Dataset

Source:

```python
load_dataset("jorge-henao/disco_poetry_spanish")
```

This dataset contains Spanish poetry texts available through the Hugging Face Datasets library.

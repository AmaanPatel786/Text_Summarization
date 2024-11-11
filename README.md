# Text Summarization

This project performs text summarization by extracting key sentences from a given input text based on word frequency scoring. Using Python and the Natural Language Toolkit (nltk), the code identifies the most significant sentences, helping to reduce lengthy text while preserving essential information.

## Features

- Tokenizes the input text into words and sentences
- Removes common stopwords to focus on important words
- Calculates word frequency to evaluate the relevance of each sentence
- Extracts sentences that are most relevant based on their frequency scores

## How It Works

1. **Tokenization**: Splits the input text into words and sentences.
2. **Frequency Table**: Creates a frequency table for all non-stopwords to determine word importance.
3. **Sentence Scoring**: Assigns a score to each sentence based on the frequency of words it contains.
4. **Sentence Selection**: Sentences scoring above a certain threshold are included in the summary.

## Dependencies

- **nltk**: The Natural Language Toolkit for natural language processing.

### Install nltk

```bash
pip install nltk

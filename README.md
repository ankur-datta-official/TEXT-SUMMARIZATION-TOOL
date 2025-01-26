# Text Summarization Tool


## Description

This Python script provides a tool for summarizing lengthy articles using Natural Language Processing (NLP) techniques. It leverages the `sumy` library to extract concise summaries from input text.

## Features

- **Summarization Methods:** Supports three popular summarization algorithms:
    - **LSA (Latent Semantic Analysis):** Suitable for long, well-structured documents where thematic understanding is crucial.
    - **Luhn:** Efficient for quickly summarising short to moderately sized documents.
    - **TextRank:** A robust choice for most tasks, offering nuanced and context-aware summaries.
- **Customizable Summary Length:** Adjust the number of sentences in the summary using the `sentence_count` parameter.
- **Easy to Use:** input the text and select the desired summarization method.

## Requirements

- Python 3.x
- `sumy` library
- `nltk` library
- `spacy` library

## Installation

1. Install the required libraries using pip:
bash pip install sumy nltk spacy
2. Download NLTK resources:

python import nltk nltk.download('punkt') nltk.download('punkt_tab') nltk.download('stopwords')

## Usage

1. Run the script.
2. Enter the text you want to summarize when prompted.
3. The script will generate a concise summary and display it.

## Example

Enter the text you want to summarize: [Your input text here]
Original Text: [Your input text here]
Summary: [Generated summary]

## Note

- The script uses LSA as the default summarization method. You can change this by modifying the `method` parameter in the `summarize_text` function.
- For optimal results, ensure that the input text is well-structured and grammatically correct.

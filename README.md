# Accounting Text Processing Pipelines

This project utilizes Hugging Face Transformers to implement various natural language processing (NLP) tasks related to accounting concepts. The following pipelines are included:

## Pipelines Implemented

### 1. Zero-Shot Classification
Classifies input text into relevant accounting categories using the `facebook/bart-large-mnli` model.

### 2. Text Generation
Generates text based on an input prompt using the `openai-gpt` and `distilgpt2` models.

### 3. Fill-Mask
Predicts masked words in a sentence using the `bert-base-uncased` model.

### 4. Named Entity Recognition (NER)
Identifies named entities in text using the `dbmdz/bert-large-cased-finetuned-conll03-english` model.

### 5. Question Answering
Answers questions based on provided context using the `distilbert-base-cased-distilled-squad` model.

### 6. Sentiment Analysis
Analyzes the sentiment of input text using the `distilbert-base-uncased-finetuned-sst-2-english` model.

### 7. Summarization
Summarizes long texts using the `facebook/bart-large-cnn` model.

### 8. Translation
Translates text from Indonesian to English using the `Helsinki-NLP/opus-mt-id-en` model.

## Requirements
- `transformers`
- `torch`
- `tabulate`

## Usage
1. Clone the repository.
2. Install the required packages.
3. Run the scripts to see the NLP pipelines in action.

## Output
The results from the various pipelines are displayed in a formatted table for better readability.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Author
Budiman Zahri


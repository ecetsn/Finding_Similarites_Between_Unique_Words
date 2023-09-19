# Text Processing and Similar Word Finder
This Python script is designed for text processing and finding similar words within a given document. It utilizes various text preprocessing techniques to extract unique words and then uses Levenshtein distance to find similar words for each unique word. This README will help you understand the script, how to use it, and its key features.

## Overview
This script processes a document (in DOCX format) and performs the following tasks:

### Text Preprocessing:

Removes unnecessary punctuation and special characters from the text.
Standardizes Unicode characters and handles Turkish characters (e.g., ü, İ, ş).
Extracts valid words from the text after preprocessing.

### Finding Similar Words:

Utilizes Levenshtein distance to find the most similar words to each unique word.
Allows specifying the maximum allowed difference between words for similarity.

### Features
Text Preprocessing
Removes unnecessary punctuation and special characters.
Handles apostrophes at the beginning or end of words.
Standardizes Unicode characters and handles Turkish characters.
Extracts valid words based on length, presence of digits, and predefined exceptions.
Similar Word Finder
Finds similar words for each unique word.
Utilizes Levenshtein distance for similarity calculation.
Allows specifying the maximum allowed difference for similarity.

## Text Preprocessing

### The script preprocesses the text in the following ways:

Removes unnecessary punctuation and special characters.
Standardizes Unicode characters (e.g., ü, İ, ş) to their base forms.
Handles apostrophes at the beginning or end of words.

## Similar Word Finder
The script uses Levenshtein distance to find similar words for each unique word. It allows you to specify the maximum difference between words to consider them similar.

### Output Files
The script generates the following output files: <br />

**result_of_uniquewords.txt:** Contains the list of unique words found in the document after preprocessing. <br />
**result_of_exceptions.txt:** Contains the list of exception words encountered during preprocessing. <br />
**similar_unique_words.txt:** Contains the similar words for each unique word found in the document. <br />

### Benchmark
The script provides a benchmark that displays the elapsed time for the entire process. This helps you understand how long it took to process the document and find similar words.

<br/>

> [!NOTE]
> This project was developed as a programming assignment and serves as an educational resource for working.

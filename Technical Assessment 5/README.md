# Sentiment Analysis

This project implements two sentiment analysis programs in Python: one using the `TextBlob` library to classify 10 sentences by polarity, and another using custom word-matching lexicons to detect happy and sad tones.

## Files
- `TA5_Cruz_activity.py` - Python notebook containing the TextBlob sentiment analysis script (Section VI)
- `TA5_Cruz_challenge.py` - Python notebook containing the lexicon-based happy/sad word counter script (Section VII)
- `TA5_Cruz.pdf` - Completed laboratory exercise document with code, outputs, and screenshots
- `happy_words.txt` - Text dataset containing a list of happy words
- `sad_words.txt` - Text dataset containing a list of sad words

## Features
- **TextBlob Polarity Analysis:** Evaluates 10 user-input sentences, classifies each as `Positive`, `Neutral`, or `Negative`, and displays a final count summary.
- **Lexicon-Based Tone Counter:** Uses `number_happy()` and `number_sad()` functions to count matching words from separate text files and determine whether a sentence has a Happy, Sad, or Neutral tone.
- **Text Preprocessing:** Cleans user input by converting text to lowercase and removing punctuation for accurate word matching.

## How it Works
1. **`TA5_Cruz_activity`:** Prompts the user to enter 10 sentences one by one. For each sentence, `TextBlob` computes a polarity score between `-1` and `1`—printing `Negative` if less than `0`, `Neutral` if equal to `0`, and `Positive` if greater than `0`—before displaying the total counts at the end.
2. **`TA5_Cruz_challenge`:** Loads words from `happy_words.txt` and `sad_words.txt` into two separate lists, cleans the user's input sentence of punctuation and uppercase letters, and compares how many words match each list to classify the overall tone as Happy, Sad, or Neutral.

## How to Run
1. Install the required library (`textblob`):
   ```bash
   pip install textblob

## Author & Course Details
* **Student Name:** Krista Mari Emilia Cruz
* **Course:** CS0065 (Intelligent Systems)
* **Institution:** Far Eastern University (FEU) Alabang

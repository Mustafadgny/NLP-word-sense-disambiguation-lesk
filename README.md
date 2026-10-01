# 📖 Word Sense Disambiguation (WSD) with Lesk Algorithm

This repository demonstrates how to perform **Word Sense Disambiguation (WSD)** using the **Lesk algorithm** and **WordNet** from the `NLTK` library in Python.

## 🚀 Overview

Many words in human languages are polysemous (having multiple meanings). Word Sense Disambiguation is the task of determining which sense of a word is activated in a given sentence based on context.

The **Lesk Algorithm** resolves ambiguity by finding word overlaps between the dictionary definition (gloss) of candidate word senses in WordNet and the context words appearing in the target sentence.

## 🛠️ Tech Stack
- Python
- NLTK (Natural Language Toolkit)
- WordNet lexical database

## 💻 Installation & Setup

1. Install NLTK:
pip install nltk

2. Run the script:
python wsd_lesk.py

*(Note: The script automatically downloads the required NLTK corpora: `wordnet`, `omw-1.4`, and `punkt`.)*

## 📊 Example Demonstration

Disambiguating the target word **"bank"** across two distinct contexts:

### Case 1: Financial Context
- **Sentence:** "I go to the bank to deposit money"
- **Detected Sense:** A container (usually with a slot in the top) for keeping money at home / financial depository institution.

### Case 2: Geographical Context
- **Sentence:** "The river bank is flooded after the heavy rain"
- **Detected Sense:** Sloping land bordering a body of water or track.

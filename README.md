# Stylometric Analysis of Dante's *Inferno* and Longfellow's Translation

This repository contains a stylometric analysis comparing Dante Alighieri’s *Inferno* (Italian original) with Henry Wadsworth Longfellow’s 1867 English translation. Using Python, spaCy, NLTK, and quantitative linguistic methods, the project examines differences in sentence rhythm, word length, punctuation, part-of-speech distribution, and n-gram frequency.

## Contents
- **inferno_stylometry.ipynb** — full analysis, plots, and interpretation  
- **data/** — Italian and English text files  
- **requirements.txt** — Python dependencies  

## Summary of Findings
The analysis reveals clear structural differences between the two texts. Dante’s Italian exhibits longer, flowing sentences, richer verbal morphology, and formulaic poetic collocations. Longfellow’s English translation adapts the rhythm to Victorian English norms, producing shorter sentences, more determiners and prepositions, and a noun-heavy analytic structure. Despite these grammatical shifts, phrase-level patterns show that Longfellow preserves Dante’s imagery and rhetorical pacing.

## How to Run
Clone the repository and open the notebook in Jupyter or VS Code.

Install dependencies:
pip install -r requirements.txt

Open the notebook:
jupyter notebook inferno_stylometry.ipynb

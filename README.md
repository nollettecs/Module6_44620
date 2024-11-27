# Creator
- Cole Nollette
- 44-620

# Web Scraping and NLP with Requests, BeautifulSoup, and spaCy
This project demonstrates the use of Natural Language Processing (NLP) to analyze article content, focusing on identifying key terms, scoring sentence relevance, and visualizing word distributions. It leverages Python libraries like spaCy and BeautifulSoup to process and interpret the text effectively.

# Overview
The project covers these primary tasks:

- Text Extraction and Processing: Extracts and cleans text from an article's HTML source file.
- Tokenization and Lemmatization: Identifies frequent words (tokens) and their root forms (lemmas) while excluding stopwords, punctuation, and whitespace.
- Sentence Scoring: Calculates relevance scores for sentences based on the occurrence of "interesting" words or lemmas.
- Part-of-Speech Filtering: Focuses on specific word types (e.g., nouns) to refine the analysis.
- Visualization: Plots histograms to reveal sentence score distributions and highlight text patterns.

# Requirements
Python 3.x
Libraries:
requests: For fetching web content.
pickle: For saving and loading serialized data.
BeautifulSoup (bs4): For HTML parsing.
spaCy: For advanced NLP tasks like tokenization, lemmatization, and POS tagging.
matplotlib: For plotting histograms.
collections: For frequency counting.
spaCy Language Model:
en_core_web_sm (Install with: python -m spacy download en_core_web_sm)

# How to Use
Save the article's HTML content as a .pkl file for easy loading into the project.
Run the code in a Jupyter notebook or Python script to:
Analyze the article text.
Calculate sentence scores.
Generate visualizations.
Modify the "interesting" words list or POS filters as needed to adjust the analysis.

# Key Features
1. Token and Lemma Analysis
- Identifies the most frequent terms in the article.
- Filters out irrelevant elements (e.g., punctuation, stopwords).

2. Sentence Scoring
- Ranks sentences based on the density of "interesting" terms or lemmas.
- Useful for identifying key sections of the text.

3. Visualization
- Generates histograms to visualize sentence score distributions.
- Helps highlight the prevalence of important terms.

# Insights and Interpretation
- High-Frequency Terms
        Tokens and lemmas that appear frequently indicate the main themes or subjects of the article.

- POS-Based Filtering
        Focusing on specific parts of speech (e.g., nouns) tailors the analysis, emphasizing concepts (like entities) over actions or descriptors.

- Sentence Score Histograms
        These visualizations reveal where important terms are concentrated, offering insights into the article's structure and focus.
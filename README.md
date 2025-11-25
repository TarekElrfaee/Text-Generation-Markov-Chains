# 📰 Markov Chain Headline Generator
Description: A probabilistic text generator built with Python that creates realistic news headlines based on the "Million News Headlines" dataset. This project demonstrates the application of Markov Chains, NLTK for grammatical structuring, and NetworkX for state visualization.

Key Features:

Markovify Implementation: Utilizes state-based probability to generate text.

Ensemble Modeling: Combines multiple chain models with weighted probabilities for better coherence.

POS Tagging (NLTK): Implements Part-of-Speech tagging to ensure generated sentences follow valid grammatical structures.

Topic Filtering: Filters input data to create domain-specific models (e.g., Sports, Finance).

Graph Visualization: Uses NetworkX to plot the directed graph of word transitions.

Plagiarism Checker: Includes a utility to verify that generated text is unique and not a direct copy from the corpus.

How to Run:

Install dependencies: pip install markovify pandas nltk networkx

Load your dataset (CSV format).

Run the notebook to generate your own headlines!

Sample Output:

"Government decides against community broadcasting license." "Wall St US shares rise on buy up speculation."

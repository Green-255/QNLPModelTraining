# Quantum NLP Model Training

This repository contains the implementation for my Bachelor's thesis project on Quantum Natural Language Processing (QNLP) applied to extractive text summarization.

The goal of the project is to classify individual sentences as either summary-worthy or not summary-worthy. These predictions can then be used to create an extractive summary by selecting the most relevant sentences from a text.

The project combines concepts from Machine Learning, Natural Language Processing, and quantum circuit-based models. Sentences are parsed into grammatical diagrams, transformed into parameterized quantum circuits, and trained using a quantum-simulated model.

The repository focuses on three main stages:

1. **Dataset construction**
   Raw text data is filtered and preprocessed to obtain cleaner, simpler, and valid sentences. The dataset is also prepared with class distribution in mind, since sentence-level extractive summarization is treated as a binary classification task.

2. **Data encoding**
   Input sentences are processed, parsed, and converted into quantum circuit representations suitable for QNLP training.

3. **Model training**
   Encoded data is used to train and evaluate a quantum-simulated binary classification model for extractive summarization.

Thesis paper: [Bachelor's Thesis PDF](thesis/Bachelor_Thesis_QNLP.pdf)

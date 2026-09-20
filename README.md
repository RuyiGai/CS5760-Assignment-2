# CS5760 Natural Language Processing - Homework 2

## Student Information

- **Name:** Ruyi Gai
- **Student ID:** 700778329
- **Course:** CS5760 Natural Language Processing
- **Semester:** Fall 2026
- **University:** University of Central Missouri

---
## Files

```text
Homework 2.docx
Homework 2.ipynb
README.md
```

- `Homework 2.ipynb` — Contains the Python programming code and execution results.
- `Homework 2.docx` — Contains the answers and screenshots for the calculation and programming questions.
- `README.md` — Provides an overview of the assignment and summarizes the completed work.

---

## Assignment Overview

This homework covers several Natural Language Processing (NLP) concepts, including Document Classification, Harms of Classification, Bigram Probabilities, Zero-Probability Problems, Backoff Models, and Evaluation Metrics.

The assignment includes both theoretical questions and programming tasks. The programming work was implemented in Python, and the completed work is provided in the Jupyter Notebook and Word document.

---

## Q1: Worked Example Document Classification

This section calculates the probability scores for the document 'predictable no fun' under the positive and negative classes using the given priors and smoothed likelihoods.

The final class is determined by comparing the probability scores of the two classes.

---

## Q2: Harms of Classification

This section discusses representational harm and potential risks of text classification systems.

The topics include:

- Representational harm and the Kiritchenko & Mohammad (2018) study.
- Risks of censorship in toxicity classification.
- Performance differences across varieties of English, including African American English and Indian English.

---

## Q3: Bigram Probabilities and the Zero-Probability Problem

This section calculates sentence probabilities using Maximum Likelihood Estimation (MLE).

The tasks include:

- Calculating the probabilities of two sentences using a bigram model.
- Comparing the probabilities of the two sentences.
- Calculating the probability of an unseen bigram.
- Explaining the zero-probability problem.
- Applying Laplace (Add-1) smoothing to an unseen bigram.

---

## Q4: Backoff Model

This section demonstrates how a trigram model can back off to a lower-order bigram model when a trigram is not observed in the training corpus.

The tasks include:

- Calculating a trigram probability.
- Applying trigram-to-bigram backoff.
- Explaining why backoff is necessary.

---

## Q5: Evaluation Metrics from a Multi-Class Confusion Matrix

This section evaluates a multi-class classification system using a confusion matrix.

The implementation calculates:

- Precision and recall for Cat, Dog, and Rabbit.
- Macro-averaged precision and recall.
- Micro-averaged precision and recall.

The Python program accepts the given confusion matrix and prints all evaluation results clearly.

---

## Part II: Bigram Language Model Implementation

A Bigram Language Model was implemented in Python based on the training corpus provided in the assignment.

The program:

- Computes unigram and bigram counts.
- Estimates bigram probabilities using MLE.
- Calculates the probability of a given sentence.
- Tests the model on two sentences.
- Compares their probabilities and determines which sentence the model prefers.

The implementation uses Python's 'Counter' to count unigrams and bigrams.

---

## Technologies Used

- **Python**
- **Jupyter Notebook**
- **NumPy**
- **collections.Counter**
- **Natural Language Processing (NLP)**

---

## Conclusion

This homework provided practical experience with text classification, language modeling, smoothing, backoff models, and classification evaluation metrics.

The programming tasks demonstrated how bigram probabilities can be calculated and used to evaluate sentences, as well as how precision, recall, macro averaging, and micro averaging can be implemented for a multi-class classification problem.

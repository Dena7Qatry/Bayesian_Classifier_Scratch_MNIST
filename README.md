# Bayesian Classifier from Scratch (MNIST)

## Overview
This project implements a **Naive Bayesian Classifier from scratch** and applies it to the **MNIST handwritten digit dataset**.  
The classifier is tested and evaluated on digit recognition performance.

---

## Features
- Pure Python implementation (without relying on scikit-learn’s Naive Bayes class)
- Works directly on MNIST images
- Step-by-step probability calculations
- Performance evaluation with accuracy metrics

---

## Methodology
1. **Data Preprocessing**
   - Load MNIST dataset
   - Flatten images into feature vectors
2. **Naive Bayes Implementation**
   - Compute prior probabilities for each class
   - Estimate likelihood using pixel values
   - Apply Bayes’ theorem for classification
3. **Evaluation**
   - Measure accuracy on test set

---

## Results
- The accuracy of our model is 81.49% , which is bigger than GaussianNB of 55.58% accuracy , somehow close to The knn of 96.88%
- Demonstrates feasibility of Bayesian classification on MNIST
- Highlights computational trade-offs compared to modern deep learning methods
---

## Files in Repository
- `Bayesian_Classifier_Scratch.ipynb` – Colab notebook with implementation

---

# DocumentClustering

A simple pipeline for classifying documents from the 20 Newsgroups dataset using TF-IDF and Naive Bayes.

## Overview

This project demonstrates a complete workflow—from raw text to evaluation—structured into five main stages:

1. **Data Preparation**  
   - Load the 20 Newsgroups corpus  
   - Clean and normalize text (remove punctuation, stop words, etc.)  
   - Tokenize and lemmatize to reduce words to their base form  

2. **Feature Extraction**  
   - Transform preprocessed text into numerical feature vectors  
   - Use TF-IDF vectorization to weigh term importance within and across documents  

3. **Model Training**  
   - Fit a Multinomial Naive Bayes classifier on the TF-IDF features  
   - Optimize hyperparameters (if desired) for improved performance  

4. **Evaluation**  
   - Compute key metrics:  
     - **Accuracy**  
     - **Precision**  
     - **Recall**  
     - **F1-Score**  
   - Generate a confusion matrix to visualize classification errors  

5. **Visualization**  
   - Plot the confusion matrix for an at-a-glance view of model strengths and weaknesses  
   - Create WordClouds of top terms in each predicted category to interpret what the model “sees”  

---

## Getting Started

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/DocumentClustering.git
   cd DocumentClustering

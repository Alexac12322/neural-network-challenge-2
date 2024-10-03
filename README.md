# neural-network-challenge-2

## Employee Attrition Prediction and NLP Techniques

## Overview
This repository contains a project focused on predicting employee attrition using machine learning techniques, as well as exploring advanced Natural Language Processing (NLP) methods, including topic modeling and recurrent neural networks (RNNs).

## Project Structure
- `attrition.ipynb`: Jupyter Notebook containing the implementation of the employee attrition prediction model.
- `M20.3_-Advanced-NLP-Techniques_-Topic-Modeling-and-RNN.pdf`: A PDF document outlining advanced NLP techniques, including topic modeling with Latent Dirichlet Allocation (LDA) and text generation using LSTM networks.

## Objectives
By the end of this project, you will be able to:
1. Apply NLP preprocessing to large corpora of text.
2. Demonstrate how to classify text into topics using unsupervised learning.
3. Understand and implement LSTM RNNs for text generation.

## Model Details
### Employee Attrition Prediction
- **Input Features**: 10 features related to employee demographics and job satisfaction.
- **Output**: 
  - **Attrition**: Binary classification (leave or stay).
  - **Department**: Multi-class classification (predicting department).

### Activation Functions
- **Attrition Output**: Sigmoid activation function for binary classification.
- **Department Output**: Softmax activation function for multi-class classification.

## Installation
To run this project, ensure you have the following libraries installed:
```bash
pip install numpy pandas tensorflow scikit-learn matplotlib seaborn

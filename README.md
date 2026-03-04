# clasificacion-cancer-mlp

# Breast Cancer Classification using MLP

This project implements a machine learning model to classify breast tumors as benign or malignant using the Breast Cancer Wisconsin Dataset.

## Dataset

- 569 samples
- 30 numerical features extracted from cell nuclei images

## Models

Two models were evaluated:

- k-Nearest Neighbors (baseline)
- Multi-Layer Perceptron (MLP)

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score

## Results

Both models achieved high performance.  
The MLP reduced false positives while kNN achieved slightly higher F1-score.

## Deployment

The trained model was deployed as an interactive API using Hugging Face Spaces.

## Run locally

Install dependencies:

# End-to-End Machine Learning Pipeline (Scikit-learn)

This project demonstrates a full production-style machine learning pipeline using Scikit-learn.  
It covers preprocessing, model training, evaluation, and saving the trained pipeline for reuse.

---

## Task Overview

The goal is to build a clean and automated ML workflow using:

- ColumnTransformer for feature preprocessing
- Pipeline for chaining preprocessing and model
- Proper train-test split
- Model evaluation using standard metrics
- Saving the trained model for deployment

Dataset used: Breast Cancer Dataset from sklearn

---

## Technologies Used

- Python  
- Pandas & NumPy  
- Scikit-learn  
- Jupyter Notebook  

---

## Model Evaluation Metrics

The pipeline evaluates performance using:

- Accuracy  
- Precision  
- Recall  
- F1-score  

---

## Saved Model

The complete trained pipeline is saved as:

```bash
ml_pipeline.pkl
```

---

## What I Learned

An ML pipeline is a structured way to connect preprocessing and model training into one automated workflow so everything runs in the correct order.

Pipelines reduce data leakage because preprocessing is fitted only on training data and then consistently applied to test data, keeping evaluations fair.

ColumnTransformer allows different preprocessing steps to be applied to different feature types in a single clean process instead of handling them separately.

Pipelines make deployment easier because the entire workflow — preprocessing plus model — can be saved and reused for real predictions.

Compared to manual preprocessing, pipelines are cleaner, safer, and less error-prone since all steps are automated and standardized.



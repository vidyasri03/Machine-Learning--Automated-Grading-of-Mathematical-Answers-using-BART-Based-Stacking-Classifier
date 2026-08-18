# Automated Grading of Mathematical Answers Using BART-Based Stacking Classifier

## Project Overview

Developed an NLP-based automated grading system for evaluating student answers to mathematical questions. The system uses **BART-based sentence embeddings** combined with **stacking ensemble machine learning models** to classify student responses into three categories.

The project explores multiple transformer-based embedding approaches, hyperparameter tuning, cross-validation, and model interpretability using SHAP.

## Objectives

* Automatically evaluate student mathematical responses.
* Extract meaningful semantic representations from textual answers.
* Compare different transformer-based embedding approaches.
* Improve classification performance using ensemble learning.
* Analyze model predictions using explainable AI techniques.

## Technologies Used

* **Python**
* **BART / Transformer Models**
* **Scikit-learn**
* **Natural Language Processing (NLP)**
* **Stacking Ensemble Learning**
* **SHAP**
* **Pandas & NumPy**
* **Jupyter Notebook**

## Methodology

1. Preprocessed and prepared student response data.
2. Generated semantic embeddings using BART and other transformer models.
3. Trained multiple machine learning classifiers.
4. Combined base classifiers using a **stacking ensemble approach**.
5. Performed cross-validation and hyperparameter tuning.
6. Evaluated the final model using test data.
7. Applied **SHAP-based interpretability** to understand model predictions.

##  Results

* **Cross-Validation Accuracy:** 97.89%
* **Test Accuracy:** 91.43%
* **Classification:** Three-class student response evaluation
* **Model:** BART-based embeddings with stacking ensemble classifier

## Project Structure

```text
├── bart_embeddings.ipynb
├── bart_tuning.ipynb
├── gpt_embeddings.ipynb
├── gpt2_tuning.ipynb
├── hyperparameter_t5.ipynb
├── ML_t5.ipynb
├── Stacking_classifiers.ipynb
├── t5_embeddings.ipynb
├── testing.ipynb
├── tuning_bart.ipynb
└── README.md
```

## Key Highlights

* Transformer-based semantic representation of student answers.
* Ensemble learning for improved classification performance.
* Cross-validation and systematic hyperparameter optimization.
* SHAP-based model interpretability.
* Comparative experimentation across BART, GPT, and T5-based approaches.

## Author

**Vidya Sri K.**

B.Tech – Computer Science and Engineering | 2026 Graduate

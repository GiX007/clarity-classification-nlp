# NLP Progression on SemEval 2026 Task 6: Clarity Classification

End-to-end NLP classification experiments progressing from classical ML to deep learning, transformers, and LLMs, applied to political answer clarity classification.

## Task
Predict the clarity of politician responses to journalist questions into three categories: *Clear Reply*, *Ambivalent*, and *Clear Non-Reply*.

## Dataset
[ailsntua/QEvasion](https://huggingface.co/datasets/ailsntua/QEvasion)

## Contents
- `01_clarity_classification_classical_ml.ipynb` - EDA, preprocessing, TF-IDF and GloVe representations, Logistic Regression training and hyperparameter tuning
- ...
- ...
- ...

## Results
| Notebook | Best Model | Val F1 | Test F1 |
|---|---|---|
| Classical ML | TF-IDF + LR (v3) | 0.631 | 0.58

## Reference
Thomas et al. (2024). *"I Never Said That"*. EMNLP 2024. [arXiv](https://arxiv.org/abs/2409.13879)

## Note
This repository is educational in nature. It documents the full learning journey of NLP classification, from classical machine learning baselines to state-of-the-art deep learning approaches, with a focus on understanding each concept, methodology, 
and model before moving to the next.

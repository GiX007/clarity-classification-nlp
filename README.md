# NLP Progression on SemEval 2026 Task 6: Clarity Classification

End-to-end NLP classification experiments progressing from classical ML to deep learning, transformers, and LLMs, applied to political answer clarity classification.

## Task
Predict the clarity of politician responses to journalist questions into three categories: *Clear Reply*, *Ambivalent*, and *Clear Non-Reply*.

## Dataset
[ailsntua/QEvasion](https://huggingface.co/datasets/ailsntua/QEvasion)

## Contents
- `01_clarity_classification_classical_ml.ipynb` - EDA, TF-IDF and Word2Vec/GloVe representations, Logistic Regression
- `02_clarity_classification_bert.ipynb` - Fine-tuning BERT-base-uncased
- `03_clarity_classification_distilbert.ipynb` - Fine-tuning DistilBERT-base-uncased
- `04_clarity_classification_deberta.ipynb` - Fine-tuning DeBERTa-v3-base
- `05_clarity_classification_prompting.ipynb` - Prompting techniques on Qwen3.5 (zero-shot, few-shot, CoT, Self-Consistency), with cross-family extension (Gemma-3, Llama-3.2, Phi-4-mini)

## Reference
Thomas et al. (2024). *"I Never Said That"*. EMNLP 2024. [arXiv](https://arxiv.org/abs/2409.13879)

## Notes
This repository documents the full learning journey of NLP classification, from classical machine learning baselines to state-of-the-art transformer-based approaches, with a focus on understanding each concept, methodology, and model. 

Most of the notebooks are large and will not display on GitHub. Download the .ipynb files and open them in Google Colab to view all outputs.

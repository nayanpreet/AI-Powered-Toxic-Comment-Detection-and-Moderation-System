---

# ✅ 2) MODEL_CARD.md (copy-paste exactly)

```md
# Model Card — Toxic Comment Classification Model

## Overview
This project implements a Transformer-based NLP model for toxic comment detection. The model is designed to support content moderation workflows by classifying comments into multiple toxicity-related categories.

The repository includes the trained model artifacts, tokenizer files, dataset splits, and evaluation outputs for full reproducibility.

---

## Model Type
- Transformer-based text classification model (DistilBERT-style architecture)
- Multi-label classification setup

---

## Prediction Labels
The model predicts the following moderation categories:

- toxic  
- severe_toxic  
- obscene  
- threat  
- insult  
- identity_hate  

---

## Training Data
- Dataset: Jigsaw Toxic Comment dataset  
- Files included in this repository:
  - `train.csv`
  - `test.csv`
  - `test_labels.csv`

---

## Intended Use
This model is intended for:
- Toxicity scoring for user-generated content
- Moderation assistance pipelines
- Research and experimentation in NLP safety workflows

---

## Evaluation
Evaluation outputs are provided in the repository and include:
- Classification report
- Confusion matrix
- ROC curve
- Precision-recall curve

These artifacts can be found in the `screenshots/` folder and in the project report.

---

## Limitations
- Toxicity classification models can produce false positives, especially for identity-related text.
- Performance may degrade on slang, multilingual input, or adversarial phrasing.
- This model should not be used as the sole decision-maker in real-world moderation enforcement without human review.

---

## Artifacts Included
The following trained artifacts are included in:

- `toxicity_model/`

Key file:
- `toxicity_model/model.safetensors`

This file is tracked using **Git LFS**.

---

## Ethical Considerations
Toxicity detection is a high-impact task. In real-world deployment, best practices include:
- human-in-the-loop review
- bias testing and monitoring
- clear policy definitions and transparency
- appeal workflows for users
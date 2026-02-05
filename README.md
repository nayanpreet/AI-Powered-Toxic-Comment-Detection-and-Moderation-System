# AI-Powered Toxic Comment Detection and Moderation System

An end-to-end NLP moderation pipeline that detects toxic comments using a fine-tuned transformer model. The repository includes the dataset, trained model artifacts (via Git LFS), and a complete notebook for training/evaluation/inference.

## Key Features
- Toxic comment classification using a fine-tuned Transformer (DistilBERT-style)
- Multi-label toxicity detection (toxic, severe toxic, obscene, threat, insult, identity hate)
- Reproducible pipeline in a single Jupyter Notebook
- Dataset included (`train.csv`, `test.csv`, `test_labels.csv`)
- Trained model included (`toxicity_model/model.safetensors`) tracked using Git LFS

## Tech Stack
Python • PyTorch • HuggingFace Transformers • Pandas/NumPy • Scikit-learn • Matplotlib/Seaborn • Git LFS

## Repository Structure
- `ML_Final_Project_code_notebook.ipynb` — full training + evaluation + inference pipeline
- `train.csv`, `test.csv`, `test_labels.csv` — dataset splits
- `toxicity_model/` — trained model + tokenizer artifacts
- `ML Final Project report.pdf` — methodology and results
- `ML Final Project PPT.pptx` — presentation slides

## How to Run
1) Install dependencies:
pip install -r requirements.txt

	2.	Open and run the notebook:

	•	ML_Final_Project_code_notebook.ipynb

Notes
	•	Model weights are stored using Git LFS due to GitHub file size limits.
	•	If you use any API keys in your notebook, keep them in a local .env file (never commit). Use .env.example as a template.

Author

Nayanpreet Chhabra (Binghamton University)
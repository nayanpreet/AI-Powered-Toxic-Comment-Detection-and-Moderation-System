# Run Guide — AI-Powered Toxic Comment Detection & Moderation System

This repository contains a complete end-to-end notebook workflow for:
- Training / fine-tuning the model
- Evaluating performance
- Running inference on sample inputs

---

## 1) Clone the Repository
```bash
git clone <YOUR_REPO_URL>
cd <YOUR_REPO_FOLDER>

2) Install Dependencies

It is recommended to use Python 3.9+.

pip install -r requirements.txt

3) Run the Notebook

Open and run the notebook:
	•	ML_Final_Project_code_notebook.ipynb

Run all cells sequentially to reproduce:
	•	model training / fine-tuning
	•	evaluation metrics and plots
	•	prediction samples

⸻

4) Model Artifacts

The fine-tuned model weights and tokenizer files are stored under:
	•	toxicity_model/

The weights file:
	•	toxicity_model/model.safetensors

is tracked using Git LFS due to GitHub’s file size limits.

⸻

Notes
	•	The dataset CSV files are included in the repository for reproducibility.
	•	If optional API-based components are used, keep keys in a local .env file (never commit).
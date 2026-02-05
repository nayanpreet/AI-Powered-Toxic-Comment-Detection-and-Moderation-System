# Model Card — Toxic Comment Classifier

## Overview
Transformer-based multi-label toxicity classifier trained/fine-tuned for toxic comment detection.

## Labels
- toxic
- severe_toxic
- obscene
- threat
- insult
- identity_hate

## Data
Jigsaw Toxic Comment dataset (CSV files included in this repository).

## Intended Use
- Moderation assistance for user-generated content
- Toxicity scoring and reporting workflows

## Limitations
- Possible bias and false positives (especially identity-related text)
- May degrade on slang, multilingual, or adversarial prompts
- Human review recommended for real-world enforcement actions

## Artifacts
- Weights: `toxicity_model/model.safetensors` (Git LFS)
- Tokenizer + config: included in `toxicity_model/`
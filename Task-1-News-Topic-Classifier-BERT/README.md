# Task 1 — News Topic Classifier Using BERT

## Objective
Fine-tune a pre-trained BERT model to classify news articles into topics (e.g., Business, Sports, Tech, World).  
The notebook builds an end-to-end pipeline covering data prep, tokenization, training, evaluation, and export.

## Files in this Folder
- `Task_1_News_Topic_Classifier_Using_BERT_2.ipynb` — main notebook
- `data/` *(optional)* — small sample data if included
- `outputs/` *(optional)* — saved metrics/plots/models

## Dataset
- Expected format: a CSV with at least:
  - `text` — news article text
  - `label` — integer or string topic label  
- Example datasets that work well: **AG News**, **BBC News** (use any dataset with the columns above).  
- If the dataset is large, keep it out of the repo and add a link here.

## Environment & Dependencies
- Python 3.9+
- PyTorch
- `transformers`
- `datasets` (optional)
- `scikit-learn`, `pandas`, `numpy`, `matplotlib`

Quick install (Colab/venv):
```bash
pip install torch torchvision torchaudio
pip install transformers datasets scikit-learn pandas numpy matplotlib

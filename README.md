# Code Switching NLP

## Code Saviours Summer Internship 2026

### Project 2: Code Switching Dataset Collection

**Name:** Hadia Hameed

---

## Project Description

This project contains a Roman Urdu and English code-switching dataset created for the Code Saviours Summer Internship 2026.

The dataset is designed for language identification and code-switching NLP tasks. Each word in every sentence is annotated with its corresponding language label.

---

## Dataset Labels

- **URD** – Roman Urdu
- **ENG** – English

---

## Week 6 – Dataset Collection

During Week 6, a Roman Urdu and English code-switching dataset was collected and prepared for the language identification task.

- Collected **150 mixed-language sentences**.
- Created word-level annotations for the collected sentences.
- Labelled words as **URD** or **ENG** according to their language.
- Cleaned and prepared the dataset for model training.
- Saved the labelled dataset as `dataset.csv`.
- Created the Week 6 Google Colab notebook.

---

## Week 7 – Model Training and Deployment

During Week 7, the collected dataset was used to train a language identification model.

- Fine-tuned **XLM-RoBERTa** for token classification.
- Prepared the dataset for training and testing.
- Used GPU runtime for model training.
- Tokenized the dataset and aligned word-level labels.
- Trained the model for **5 epochs**.
- Evaluated the model using precision, recall, and F1-score.
- Saved the trained model.
- Published the trained model on Hugging Face Hub.

### Model

**Model:** XLM-RoBERTa Base (`xlm-roberta-base`)

**Task:** Token Classification

**Labels:**
- URD = 0
- ENG = 1

### Evaluation Results

- **URD F1:** 0.9951
- **ENG F1:** 0.9971
- **MIX F1:** N/A (no MIX-labeled tokens in the dataset)

### Hugging Face Model

https://huggingface.co/hadia-tech/code-switching-codesaviours-si26-hadia

---

## Technologies Used

- Python
- Pandas
- Google Colab
- GitHub
- Hugging Face
- XLM-RoBERTa
- Transformers
- PyTorch
- Scikit-learn

---

## Internship

Code Saviours Summer Internship 2026

Project 2 – Code Switching NLP

# Code Switching NLP

## Code Saviours Summer Internship 2026

### Project 2: Code Switching Dataset Collection

**Name:** Hadia Hameed

---

## Project Description

This project contains a Roman Urdu and English code-switching dataset created for the Code Saviours Summer Internship 2026.

The dataset is designed for language identification and code-switching NLP tasks. Each word in every sentence is annotated with its corresponding language label.

The project was developed further in Week 7 by training a language identification model using XLM-RoBERTa for token classification. The trained model was evaluated and published on the Hugging Face Hub.

---

## What It Does

This project identifies whether individual words in mixed Roman Urdu and English text belong to Roman Urdu or English using a fine-tuned XLM-RoBERTa token classification model.

---

## Why This Matters

Roman Urdu and English are commonly used together in everyday digital communication. Identifying the language of individual words can help NLP systems better understand mixed-language text and support future code-switching language processing applications.

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

---

## How It Works

The project starts with a dataset containing mixed Roman Urdu and English sentences. Each word is labelled as either URD or ENG and the data is divided into training and testing sets. XLM-RoBERTa is then fine-tuned to predict the language of individual words. The trained model is evaluated using F1 scores and published on Hugging Face Hub.

---

## Evaluation Results

The trained model achieved the following F1 scores on the test dataset:

- **URD F1:** 0.9951
- **ENG F1:** 0.9971

---

## Hugging Face Model

The trained model is available on Hugging Face Hub:

https://huggingface.co/hadia-tech/code-switching-codesaviours-si26-hadia

---

## Files

- `dataset.csv` – Labelled dataset
- `SI26_Week6_hadia.ipynb` – Week 6 Google Colab notebook
- `SI26_Week7_hadia.ipynb` – Week 7 model training and evaluation notebook
- `README.md` – Project documentation

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

## How to Run Locally

Install the required libraries:

pip install pandas torch transformers datasets scikit-learn seqeval accelerate

Open the `SI26_Week7_hadia.ipynb` notebook in Google Colab or Jupyter Notebook and run the cells in order.

---

## Built By

**Hadia Hameed** | **Code Saviours SI-26** | **2026**

---

## Internship

Code Saviours Summer Internship 2026

Project 2 – Code Switching NLP

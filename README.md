# Intent-Slot-Filling
Intent Detection and Slot Filling on MASSIVE Multilingual Dataset (English &amp; Persian)

# Multilingual Intent Detection and Slot Filling (MASSIVE Dataset)

This repository contains the implementation of a Natural Language Processing (NLP) assignment focusing on **Intent Detection** and **Slot Filling** using the multilingual **MASSIVE** dataset by Amazon.

---

## 📌 Project Overview
The goal of this project is to jointly predict the **Intent** of a sentence and extract **Slots** (token-level labels using BIO format: `B-Label`, `I-Label`, `O`) for both **English (en-US)** and **Persian (fa-IR)** languages.

Two distinct transformer-based model paradigms are implemented and compared:
1. **Encoder-only Models:** Built using **XLM-RoBERTa** for token classification and sequence classification tasks.
2. **Decoder-only Models:** Built using **GPT** family models via prompt engineering and generation strategies.

---

## 📂 Repository Structure

- `data/`: Contains dataset files (`en-US.jsonl` and `fa-IR.jsonl`).
- `notebooks/`: Contains Jupyter Notebooks for both encoder and decoder models in English and Persian.
- `requirements.txt`: Required Python packages.

---

## ⚙️ Installation & Requirements
To install the required dependencies, run:
```bash
pip install -r requirements.txt

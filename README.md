# 📢 Bemba ASR Evaluation Pipeline

This project provides a complete pipeline for evaluating Automatic Speech Recognition (ASR) models on **Bemba-language** datasets. It focuses on calculating key transcription performance metrics — Word Error Rate (WER) and Character Error Rate (CER) — across multiple Hugging Face-hosted models.

---

## 🎯 Key Features

- Loads and preprocesses Bemba test data (`KYAGABA/oromo_cleaned_dataset`)
- Supports multiple models via Hugging Face `pipeline()`
- Runs inference and logs predictions vs references
- Computes:
  - Word Error Rate (WER)
  - Character Error Rate (CER)
- Exports detailed CSV results for each model evaluated

---

## 🗂️ Dataset

The test set is loaded from the Hugging Face Hub:


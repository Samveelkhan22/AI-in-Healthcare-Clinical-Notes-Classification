# 🏥 AI in Healthcare: Clinical Notes Classification

![Healthcare AI](https://img.shields.io/badge/Healthcare-AI-blue) ![NLP](https://img.shields.io/badge/NLP-Clinical_Notes-green) ![Python](https://img.shields.io/badge/Python-3.7%2B-yellow)

This repository contains code for classifying clinical notes into medical specialties using machine learning and deep learning approaches.

## 📌 Overview

🔹 Two classification approaches:
1. Traditional ML with TF-IDF and Logistic Regression
2. Deep Learning with BERT-based fine-tuning

✨ Key features:
- 🏗️ Synthetic clinical notes dataset generation
- 📊 Text classification using TF-IDF + Logistic Regression
- 🤖 Fine-tuning BERT for specialty classification
- 📈 Model evaluation and deployment

## 📂 Dataset

The synthetic dataset contains 500 clinical notes across 5 specialties:
- ❤️ Cardiology
- 🦠 Oncology
- 🧠 Neurology
- 🩺 Gastroenterology
- 🫁 Pulmonology

Each note includes:
- 📝 Clinical text
- 🏷️ Specialty label
- ⚠️ Severity level
- 👶 Patient age
- ♀️♂️ Gender
- 🏥 Visit type

## ⚙️ Requirements

- Python 3.7+
- Required packages:
  ```bash
  pip install pandas scikit-learn transformers torch datasets
  ```

  ## 🤝 Contributing
Contributions are welcome! Please open an issue or submit a PR.

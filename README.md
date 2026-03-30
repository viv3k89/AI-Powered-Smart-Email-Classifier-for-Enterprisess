# AI-Powered-Smart-Email-Classifier-for-Enterprises
🚀 Overview

This project is an AI-based email classification system designed for enterprise use. It automatically categorizes incoming emails and determines their urgency using NLP and deep learning techniques such as BERT embeddings.

The system helps organizations:

Automate email sorting
Prioritize critical communications
Improve response efficiency
Reduce manual workload
🧠 Features
📂 Email Category Classification (e.g., HR, Finance, Support, etc.)
⚡ Urgency Detection (High, Medium, Low)
🤖 BERT-based Embedding Model
🧹 Data preprocessing and cleaning pipeline
📊 Training & evaluation notebooks
🌐 Deployable via a lightweight app interface

#📁 Project Structure
AI-Powered-Smart-Email-Classifier/

│
├── app.py                         # Main application file
├── requirements.txt               # Dependencies
├── README.md                      # Project documentation
│


├── data/
│   ├── Dataset_in_Excel_Format.xlsx
│   ├── Final_Preprocessed_Dataset.csv
│


├── notebooks/
│   ├── Preprocessing.ipynb
│   ├── BERT_EMBEDDING.ipynb
│   ├── Module_2_and_3.ipynb
│   ├── AI_EMAIL_CLASSIFIER.ipynb
│


├── configs/
│   ├── Category config.json
│   ├── Category tokenizer.json
│   ├── Category tokenizer_config.json
│   ├── urgency_config.json
│   ├── urgency_tokenizer.json
│   ├── urgency_tokenizer_config.json
│


├── models/
│   ├── category_encoder.pkl
│   ├── urgency_encoder.pkl
│


├── docs/
│   ├── Preprocessing documentation.docx
│   ├── Work flow document.docx
│


└── LICENSE

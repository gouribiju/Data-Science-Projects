# 📄 Text Summarization using Transformer

## 📌 Overview
This project uses BART (Bidirectional and Auto-Regressive Transformers) to generate summaries from long articles. It helps in reducing reading time and improving information digestion.

## 🔍 Problem Statement
Long articles are time-consuming to read. This project builds a model to automatically generate concise summaries using deep learning.

## 📊 Data Preprocessing & Feature Engineering
### Text Handling:
  * ✔ Loaded full articles and highlights
  * ✔ Converted to Hugging Face format
  * ✔ Tokenized using BART tokenizer

### Model Usage:
  * ✔ Used summarization pipeline
  * ✔ Generated output using BART model

## 📂 Dataset Details
  * Dataset Name: CNN/DailyMail Articles
  * Source: Kaggle Dataset
  * Columns: id, article, highlights

## 📊 Evaluation
  * ✔ Visual comparison of generated vs. original summaries
  * ✔ ROUGE Evaluation (ROUGE-1, ROUGE-2, ROUGE-L, ROUGE-Lsum)
  * ✔ Tested on multiple articles

## 🛠 Technologies Used
  * Python
  * Transformers (Hugging Face)
  * Pandas
  * Evaluate (ROUGE Score)
  * Jupyter Notebook

## 🚀 How to Use
  * 1️⃣ Navigate to the Text Summarization using BART folder
  * 2️⃣ Open the Text Summarization using BART.ipynb file in Jupyter Notebook
  * 3️⃣ Load articles, run the summarization, and check ROUGE scores

## 📌 Use Cases
  * 📈 News summarization
  * 📉 Legal or academic brief generation
  * 📚 Research paper summarization

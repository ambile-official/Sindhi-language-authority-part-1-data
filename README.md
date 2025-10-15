# 📚 Sindhi Language Authority Dataset (Phase one – Preprocessed)

### 🏛️ Source: Sindhi Language Authority  
### 📤 Uploaded by: *Abdul Majid Bhurgiri, Institute of Language Engineering*  
### 📅 Release Year: 2025  
### 🌍 Language: Sindhi (سنڌي)  

---

## 📖 Overview

The **Sindhi Language Authority Dataset** is a rich collection of authentic Sindhi text compiled and preprocessed from official Sindhi Language Authority publications.  
This dataset serves as a valuable linguistic resource for **Sindhi Natural Language Processing (NLP)**, **computational linguistics**, and **language technology research**.

It contains literary, educational, and cultural writings, including texts inspired by *Shah Abdul Latif Bhittai’s “Risalo”*, Sindhi prose, and moral lessons for children (*درس لطيف* series).

The dataset has been released to encourage open-source development for Sindhi language tools, machine learning models, and digital preservation.

---

## 📂 Dataset Structure

| File Name | Description | Format | Size |
|------------|--------------|---------|------|
| `Language Authority data phase two_211_preprocessed_final.txt` | Preprocessed Sindhi text file from Sindhi Language Authority publications | `.txt` | Variable |
| `Sindh-Language-Authority-part-1.rar` | Compressed dataset containing Sindhi text corpus (Phase 1) | `.rar` | Large |

Each file contains UTF-8 encoded Sindhi text cleaned and formatted for direct use in training or research workflows.

---

## 🧠 Purpose and Research Applications

This dataset is designed for open research, education, and technological development.  
You can use it for:

- 🗣️ **Language Modeling:** Training Sindhi text generation or completion models  
- 💬 **Chatbots & Conversational AI:** Developing Sindhi question-answer systems  
- 📊 **Text Classification:** Sentiment, intent, or topic classification  
- 🔍 **Information Retrieval:** Building Sindhi RAG (Retrieval-Augmented Generation) systems  
- 🌐 **Machine Translation:** Sindhi ↔ English or Sindhi ↔ Urdu translation models  
- 🧩 **Tokenization & Embedding:** Fine-tuning multilingual or monolingual embedding models  

---

## ⚙️ Technical Details

- **Encoding:** UTF-8  
- **Text Type:** Literary, educational, moral, cultural  
- **Data Source:** Sindhi Language Authority printed and digital texts  
- **Preprocessing:**  
  - Normalization of Sindhi Unicode characters  
  - Removal of formatting artifacts  
  - Sentence segmentation  
  - Text cleaning and whitespace correction  

Example (Python):
```python
with open("Language Authority data phase two_211_preprocessed_final.txt", "r", encoding="utf-8") as f:
    text = f.read()

print(text[:1000])  # Preview first 1000 characters

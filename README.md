# 🔍 SHL Assessment Recommendation System

A semantic search-based tool that recommends SHL assessments tailored to a given job description or role. Powered by SentenceTransformers, FAISS, and a streamlined Gradio UI, this system helps users find the most relevant SHL assessments in seconds.

---

## 📚 About the Project

This project simulates an SHL assessment recommendation engine. Users can input any job-related query, and the system returns top matching assessments based on the semantic similarity of their descriptions.

> ⚠️ **Note**: The dataset used in this project was synthetically generated using the `Faker` library. Due to JavaScript-based rendering and scraping protection on the SHL website, real-time scraping was not possible. Hence, a fake dataset was created purely for demonstration and prototyping purposes.

---

## ✨ Features

- 🔍 Semantic search using `all-MiniLM-L6-v2`
- ⚡ Fast and efficient search via FAISS
- 🧾 Neat, table-formatted results in a clean UI
- 🎛️ Adjustable number of recommendations
- 🖥️ Deployable on Hugging Face Spaces

---

## 🧠 How It Works

1. **Data Generation**: A mock dataset of SHL-like assessments is created using `Faker`, with fields such as name, duration, remote availability, and descriptions.
2. **Embedding**: Descriptions are encoded using a pre-trained sentence transformer (`all-MiniLM-L6-v2`).
3. **Indexing**: Embeddings are normalized and indexed using FAISS for fast similarity search.
4. **Recommendation**: User queries are embedded and compared to indexed data to retrieve the most semantically similar results.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Divyansh8791/shl-assessment-recommender.git
cd shl-assessment-recommender
```
### 2. Install the requirements

```bash
pip install -r requirements.txt
```

---
Thank you /.

# 📚 Mood-Based Book Recommender

## 🎯 Project Overview

An interactive chatbot that recommends books based on your mood or query. It uses the Book-Crossing dataset from Kaggle and performs semantic similarity search using sentence-transformers and FAISS.
[👉 Open the Colab Notebook](https://colab.research.google.com/drive/1ea5-7Xxove7n8hLGEetxibLZ1y94Jmjh?usp=sharing)

## 🚀 Tech Stack

- **Python**
- **Google Colab**
- **KaggleHub** (for direct dataset fetching)
- **Sentence-Transformers** (embeddings)
- **FAISS** (vector similarity search)
- **Gradio** (chatbot interface)

## 📦 Features

- Takes user input describing mood/preferences
- Embeds book metadata (title, author, publisher) into semantic space
- Finds and recommends the most relevant books using vector search
- Friendly conversational chatbot UI using Gradio

## ⚙️ How to Run

1. Install dependencies in Colab:
   ```python
   !pip install -q kagglehub sentence-transformers faiss-cpu gradio
   ```

2. Download dataset:
   ```python
   import kagglehub
   dataset_path = kagglehub.dataset_download("arashnic/book-recommendation-dataset")
   ```

3. Follow the notebook cells to build embeddings, FAISS index, and launch the Gradio app.

## 📚 Dataset

- **Book-Crossing Dataset** (Kaggle ID: arashnic/book-recommendation-dataset)

## ✅ Next Improvements

- Incorporate user ratings for better ranking
- Add genre filtering options
- Show detailed book descriptions in recommendations

---

Made with ❤️ using open-source tools.

# Intelligent Book Recommendation System

![Python](https://img.shields.io/badge/Python-3.12-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-1.14-red)
![License](https://img.shields.io/badge/License-MIT-green)
![GitHub Repo Size](https://img.shields.io/github/repo-size/leo-bsb/book-recommendation)
![Last Commit](https://img.shields.io/github/last-commit/leo-bsb/book-recommendation)
![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)

---

A hybrid **book recommendation system** that leverages **deep learning**, combining collaborative filtering and content-based approaches to deliver highly personalized and diverse book suggestions.

🔗 **[Try it Online (Hugging Face Space)](https://huggingface.co/spaces/leo-bsb/book-recomendation)**
🔗 **[Open in Google Colab](https://colab.research.google.com/drive/1ObRPGZ2z7QCmVF2sYlpw2Sudfddbfry4?usp=sharing)**

> **Note:** The interface and notebook content/documentation are in Portuguese (PT-BR).

---

## 🎯 Overview

This system harnesses the power of deep neural networks to analyze user behavior and book features, providing **accurate**, **scalable**, and **diverse** recommendations. Using PyTorch, it implements a neural collaborative filtering framework enhanced by content-based insights for optimal user experience.

---

## 📊 Dataset

**GoodBooks-10k** — one of the most comprehensive publicly available book rating datasets:

* Over 6 million ratings
* 10,000 distinct books
* 53,424 active users
* Ratings on a 1-5 star scale

---

## 🛠️ Tech Stack

* **Programming Language:** Python 3.12
* **Deep Learning:** PyTorch
* **Data Processing:** Pandas, Polars, NumPy
* **Machine Learning:** Scikit-learn
* **Deployment:** Gradio for interactive demo
* **Cloud:** Google Colab for easy experimentation

---

## ✨ Key Features

* **Hybrid Recommendation:** Fuses collaborative filtering and content-based techniques
* **Deep Neural Network:** Learns complex user-item interaction patterns
* **Personalization:** Delivers tailored suggestions for each user
* **Scalability:** Efficient handling of large-scale datasets and users
* **Interactive Demo:** Seamless web interface for exploration

---

## 🚀 Getting Started

1. Open the [Google Colab notebook](https://colab.research.google.com/drive/1ObRPGZ2z7QCmVF2sYlpw2Sudfddbfry4?usp=sharing)
2. Run all cells sequentially
3. Experiment with parameters and observe recommendation changes
4. Deploy the Gradio demo or integrate into your own system

---

## 📈 Model Architecture

* **Embedding Layers:** Learn latent factors for users and books
* **Neural Collaborative Filtering:** Multi-layer perceptron capturing nonlinear user-item relationships
* **Matrix Factorization:** Foundation for interaction modeling
* **Hybrid Scoring:** Combines collaborative and content-based scores for balanced recommendations

---

## 📖 Citation

If you use this project in your research or work, please cite accordingly.

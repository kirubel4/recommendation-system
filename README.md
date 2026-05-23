# recommendation-system
---
# 🎬 Movie Recommendation System  
*A Netflix/Amazon-style personalized recommendation engine using Collaborative Filtering, Content-Based Filtering, Embeddings, and Similarity Search.*

---

## 📌 Overview

This project builds a **movie recommendation system** similar to what platforms like Netflix and Amazon Prime Video use.  
It combines multiple recommendation approaches to generate personalized movie suggestions:

- **Collaborative Filtering**
- **Content-Based Filtering**
- **Matrix Factorization (SVD, ALS, NMF)**
- **Embedding-based Similarity Search**
- **Cosine Similarity**

The system is trained on the **MovieLens dataset** (from GroupLens), a popular benchmark dataset for recommender systems.

---

## 🚀 Features

### ✔ Collaborative Filtering
- Learns user-movie interactions  
- Detects similar users  
- Finds latent features through Matrix Factorization  

### ✔ Content-Based Filtering
- Uses genres, tags, and movie descriptions  
- TF-IDF vector representation  
- Cosine similarity for ranking similar items  

### ✔ Hybrid Recommendation Model
- Combines collaborative and content signals  
- More robust and accurate predictions  

### ✔ Movie Embeddings
- Vector representation of movies  
- Supports nearest-neighbor search  
- Enables similarity-based recommendations  

### ✔ Full ML Pipeline
- Data preprocessing  
- Feature engineering  
- Training  
- Evaluation  
- Recommendation API functionality  

---

## 📂 Dataset: MovieLens

This project uses the **MovieLens small (or 25M)** dataset provided by GroupLens.  
The dataset contains:

- Movies  
- Genres  
- User ratings  
- Tags  
- Timestamps  

Place the downloaded dataset inside:


---

## 🧰 Tech Stack

### **Languages & Tools**
- Python  
- Pandas  
- NumPy  

### **Algorithms**
- SVD / ALS / NMF  
- TF-IDF  
- Cosine similarity  
- Embeddings  

### **Libraries**
- Scikit-learn  
- Surprise or LightFM  
- Matplotlib / Seaborn  
- FAISS or Annoy (optional)

# 🎬 Movie Recommendation System (Collaborative Filtering)

**Goal:**  
Build a movie recommendation system using *unsupervised learning* (Cosine Similarity) on the [MovieLens 100k dataset](https://grouplens.org/datasets/movielens/100k/).

---

## 🧠 Project Overview
This project implements a **collaborative filtering** recommendation system that suggests movies either similar to a given title (*item-based filtering*) or personalized to a specific user (*user-based filtering*).

### Features:
- 📊 Data preprocessing using Pandas  
- 🤝 Item-based and user-based collaborative filtering  
- 🧮 Cosine similarity metric for finding similar movies/users  
- 🧠 Personalized recommendations based on similar viewers  
- 💬 Interactive console input for user selection  
- 🎨 Optional heatmap visualization of similarity matrix  

---

## 🧰 Technologies Used
- Python  
- Pandas  
- NumPy  
- scikit-learn  
- Matplotlib  
- Seaborn  

---

## ⚙️ How It Works
1. **Load dataset** (`u.data`, `u.item` from MovieLens 100k)  
2. **Build user–movie matrix** using `pivot_table()`  
3. **Compute cosine similarity**:
   - between movies (item-based)
   - between users (user-based)
4. **Generate recommendations** using:
   - `recommend(movie_title)` → similar movies  
   - `recommend_for_user(user_id)` → user-personalized films  
5. **Visualize results** with Seaborn heatmap  

---

## 🚀 Example Usage

```python
recommend("Toy Story (1995)")
recommend_for_user(25)
# 🎬 Movie Recommendation System (Collaborative Filtering)

**Goal:**  
Build a movie recommendation system using *unsupervised learning* (Cosine Similarity) on the [MovieLens 100k dataset](https://grouplens.org/datasets/movielens/100k/).

---


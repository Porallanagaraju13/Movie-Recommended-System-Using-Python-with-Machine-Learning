# 🎬 Movie Recommender System Using Python & Machine Learning

> A content-based and collaborative filtering movie recommendation engine built with Python and ML techniques.

![Python](https://img.shields.io/badge/Python-3.8+-blue?style=flat&logo=python)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange?style=flat&logo=scikit-learn)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat&logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-green?style=flat)

---

## 🧠 Overview

This project builds a **Movie Recommendation System** that suggests movies to users based on their preferences and viewing patterns. It leverages machine learning algorithms to deliver personalized recommendations from a dataset of movies and user ratings.

---

## 🚀 Features

- 🎯 Content-based filtering using movie metadata
- 👥 Collaborative filtering based on user ratings
- 📊 Exploratory Data Analysis on movie dataset
- 📁 CSV-based dataset for easy extensibility
- 🔍 Recommendations generated for any given movie title

---

## 🛠️ Tech Stack

| Category | Tools |
|----------|-------|
| Language | Python 3.8+ |
| ML Library | Scikit-learn |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Environment | Jupyter Notebook |

---

## 📂 Project Structure

```
Movie-Recommended-System-Using-Python-with-Machine-Learning/
│
├── Movie Recommender System.ipynb   # Main notebook
├── MovieRecommendations.csv         # Recommendations dataset
├── movieIdTitles.csv                # Movie ID to title mapping
└── README.md
```

---

## ⚙️ Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/Porallanagaraju13/Movie-Recommended-System-Using-Python-with-Machine-Learning.git
cd Movie-Recommended-System-Using-Python-with-Machine-Learning
```

### 2. Install Dependencies
```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

### 3. Run the Notebook
```bash
jupyter notebook "Movie Recommender System.ipynb"
```

---

## 📊 How It Works

1. **Data Loading** — Loads movie titles and user ratings from CSV files
2. **Preprocessing** — Cleans data, handles missing values, and creates a user-movie matrix
3. **Similarity Computation** — Calculates cosine similarity between movies based on ratings
4. **Recommendation Generation** — Returns top N similar movies for a given input movie
5. **Evaluation** — Measures recommendation quality using correlation metrics

---

## 🎯 Example

```python
# Get recommendations for a movie
get_recommendations("Toy Story (1995)")

# Output:
# 1. Aladdin (1992)
# 2. The Lion King (1994)
# 3. Home Alone (1990)
# ...
```

---

## 📈 Dataset

- `movieIdTitles.csv` — Maps movie IDs to movie titles
- `MovieRecommendations.csv` — Contains user ratings and recommendation data

---

## 👤 Author

**Poralla Nagaraju**
- 🎓 B.Tech CSE (AI & ML), JNTUH — 2025
- 📍 Hyderabad, India
- 🔗 [GitHub Profile](https://github.com/Porallanagaraju13)

---

## 📝 License

This project is licensed under the MIT License.

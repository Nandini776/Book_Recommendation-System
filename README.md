https://book-recommendation-system-001.onrender.com/

# 📚 Book Recommendation System

A **Book Recommendation System** built using Python and Flask that recommends books based on user-book interaction patterns using **item-based collaborative filtering**.

## 🚀 Features

- 📚 Popular books recommendation
- 🤝 Similar book recommendations
- 🔍 Dynamic book search/autocomplete
- ⭐ Rating and popularity-based information
- 🖼️ Book cover integration using Open Library
- 🌐 Flask-based web application
- ☁️ Deployment-ready with Gunicorn

## 🧠 Recommendation Approach

The system uses **item-based collaborative filtering**.

```text
User-Book Interactions
        ↓
Pivot Table
        ↓
Book Similarity Matrix
        ↓
Selected Book
        ↓
Top Similar Books
```

A separate popularity-based component displays popular books on the homepage.

## 🛠️ Tech Stack

- **Python**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Flask**
- **HTML/CSS**
- **Bootstrap**
- **Gunicorn**
- **Render**

## 📂 Project Structure

```text
Book_Recommendation-System/
│
├── templates/
│   ├── index.html
│   └── recommend.html
│
├── app.py
├── books.pkl
├── popular.pkl
├── pt.pkl
├── similarity_score.pkl
├── requirements.txt
├── Procfile
└── README.md
```

## ⚙️ How It Works

1. User searches for a book.
2. The system checks whether the book exists in the recommendation dataset.
3. The corresponding similarity vector is retrieved.
4. Similarity scores are ranked.
5. The top similar books are selected.
6. Book metadata and covers are displayed.


## 📊 Dataset

The repository currently contains the **processed recommendation artifacts** rather than the original raw dataset.

The system uses book information such as:

- Book Title
- Book Author
- ISBN
- Ratings
- Popularity information

The homepage displays the **top 50 popular books**.

## 🔮 Future Improvements

- Hybrid recommendation system
- Content-based filtering
- Fuzzy book search
- Recommendation evaluation using Precision@K and Recall@K
- Personalized user recommendations
- Recommendation explanations


[GitHub](https://github.com/Nandini776)

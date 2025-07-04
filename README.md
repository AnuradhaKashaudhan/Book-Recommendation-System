# Book-Recommendation-System
A book recommendation engine using K-Nearest Neighbors based on user-book interaction matrix.


# 📚 Book Recommendation System using KNN

This project is a content-based **Book Recommendation Engine** built using **K-Nearest Neighbors (KNN)**. It analyzes user preferences and suggests books based on similarity in reading patterns.

---

## 💡 Features

- 🔍 Recommends similar books using KNN algorithm
- 📊 Based on a **User-Book interaction matrix**
- 🧮 Utilizes cosine similarity for distance calculation
- 🛠 Built and tested using Google Colab

---

## 🔧 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn (KNN model)
- Google Colaboratory

---

## 🧠 How it Works

1. Read user-book rating data from CSV
2. Create a **pivot table** (user x book matrix)
3. Use `scipy` sparse matrix to handle memory
4. Apply `NearestNeighbors` with cosine similarity
5. Recommend books similar to the one input

---

## 🧪 Example Output

python
recommend_books("The Da Vinci Code")


📦 book-recommendation-system
├── book_recommendation_knn.ipynb   # Main Google Colab notebook
├── books.csv / users.csv / ratings.csv  # Input data (if used)
└── README.md                       # Project overview

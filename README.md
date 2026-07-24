# 📚 Book Recommendation System using NLP

A Content-Based Book Recommendation System built using Natural Language Processing (NLP), TF-IDF Vectorization, Cosine Similarity, and Streamlit.

The system recommends books similar to a selected book based on its title and description. It also provides an interactive web application where users can search books, view details, and receive recommendations.

---

## Features

- Book Search
- Content-Based Recommendation Engine
- NLP Text Preprocessing
- TF-IDF Vectorization
- Cosine Similarity Based Recommendations
- Interactive Streamlit UI
- Recommendation Network Visualization
- JSON-based Book Catalog
- Pagination Support

---

## Project Workflow

```
Books Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Text Preprocessing
(Remove punctuation,
Stopwords,
Stemming)
      │
      ▼
Feature Engineering
(Book Title + Description)
      │
      ▼
TF-IDF Vectorization
      │
      ▼
Cosine Similarity Matrix
      │
      ▼
Recommendation Engine
      │
      ▼
Streamlit Web Application
```

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- NLTK
- Streamlit
- Matplotlib
- NetworkX
- JSON

---

## Project Structure

```
Book-Recommendation-System/
│
├── app.py
├── src/
│   ├── books_db.json
│
├── recommender_systems_db/
│   ├── item_similarity_latest.csv
│   ├── vectorizer_df_latest.csv
│   ├── books_details_based_on_recommendation_matrix.csv
│   ├── top_30_books_whole_data.csv
│
├── utils/
│   ├── functions.py
│
├── notebooks/
│   └── mini_project_NLP_final_ver2.ipynb
│
├── requirements.txt
└── README.md
```

---

## Dataset

The project uses three datasets:

- Books Dataset
- Users Dataset
- Ratings Dataset

After preprocessing, a combined feature consisting of Book Title and Book Description is created for generating recommendations.

---

## Recommendation Algorithm

1. Merge Books and Ratings datasets.
2. Filter books having sufficient ratings.
3. Clean textual information.
4. Apply NLP preprocessing.
5. Generate TF-IDF vectors.
6. Compute Cosine Similarity.
7. Recommend Top-N similar books.

---

## Running the Project

### Clone Repository

```bash
git clone <repository-url>
cd Book-Recommendation-System
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Streamlit

```bash
streamlit run app.py
```

---

## Screenshots

- Home Page
- Book Details
- Recommendation Results
- Recommendation Network

(Add screenshots here)

---

## Future Improvements

- Hybrid Recommendation System
- Genre Prediction
- User-Based Collaborative Filtering
- Book Ratings Dashboard
- Book Cover OCR
- Deep Learning Embeddings
- Personalized Recommendations

---

## Author

Gautam Kumar

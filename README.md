# 📚 Book Recommender System

A Machine Learning-based Book Recommendation System that suggests books to users based on collaborative filtering techniques and user ratings. The project analyzes user-book interactions and recommends books that align with users' preferences.

---

## 🚀 Features

* Popular Books Recommendation
* Personalized Book Recommendations
* Collaborative Filtering using User Ratings
* Interactive User Interface
* Fast Recommendation Generation
* Data Preprocessing and Cleaning

---

## 📊 Dataset

The project uses the Book-Crossing Dataset containing:

* Users Information
* Books Information
* User Ratings

### Dataset Files

* `Books.csv`
* `Users.csv`
* `Ratings.csv`

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Pickle
* Streamlit
* Jupyter Notebook

---

## 📂 Project Structure

```text
book-recommender-system/
│
├── archive (2)/
│   ├── Books.csv
│   ├── Ratings.csv
│   └── Users.csv
│
├── book_recommender.ipynb
├── books.pkl
├── popular.pkl
├── pt.pkl
├── similarity_scores.pkl
├── .gitignore
└── README.md
```

### File Description

* **book_recommender.ipynb** – Jupyter Notebook containing data preprocessing, exploratory analysis, model building, and recommendation logic.
* **books.pkl** – Processed book information used during recommendation.
* **popular.pkl** – Popular books dataset generated using rating statistics.
* **pt.pkl** – User-book pivot table used for collaborative filtering.
* **similarity_scores.pkl** – Cosine similarity matrix used to find similar books.
* **archive (2)** – Contains the original Book-Crossing dataset files.
* **README.md** – Project documentation.
* **.gitignore** – Specifies files and folders ignored by Git.

```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Piyush04492/book-recommender-system.git
```

### 2. Navigate to Project Directory

```bash
cd book-recommender-system
```

### 3. Create Virtual Environment

```bash
python -m venv venv
```

### 4. Activate Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux / Mac

```bash
source venv/bin/activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🧠 Recommendation Methodology

### Popularity-Based Recommendation

Books are ranked based on:

* Average Rating
* Number of Ratings

### Collaborative Filtering

1. User-Book Matrix Creation
2. Similar User Identification
3. Cosine Similarity Computation
4. Recommendation Generation

---

## 📈 Workflow

1. Load Dataset
2. Data Cleaning
3. Merge Books and Ratings Data
4. Filter Active Users and Popular Books
5. Create Pivot Table
6. Compute Similarity Matrix
7. Generate Recommendations

---


## 🔮 Future Improvements

* Content-Based Filtering
* Hybrid Recommendation System
* User Authentication
* Book Search Functionality
* Deployment on Cloud

---

## 👨‍💻 Author

**Piyush**

Electronics and Communication Engineering (ECE) Student

GitHub: https://github.com/Piyush04492

---

## ⭐ If you found this project useful, consider giving it a star.

# 🎬 Movie Recommendation System

This is a content-based movie recommendation engine built using Python, scikit-learn, and pandas. It recommends similar movies based on your input using cosine similarity and text-based features (e.g., genres, keywords, descriptions).

## 🚀 Features

- 📽️ Search any movie and get relevant recommendations
- 📊 Uses TF-IDF Vectorization + Cosine Similarity
- 🧠 Built using pandas, NumPy, and scikit-learn
- 🎛️ Interactive UI using ipywidgets in Jupyter Notebook

## 📦 Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
```

If using Anaconda, launch the environment with:

```bash
conda install --file requirements.txt
```

## 💡 How It Works
- Movie metadata is loaded from a CSV file
- Text columns (e.g., genre, overview, keywords) are processed
- TF-IDF vectorizer transforms text into numerical features
- Cosine similarity matrix is computed
- Based on the input movie title, top-N similar movies are recommended

## 🧪 Demo
<img width="1020" height="532" alt="image" src="https://github.com/user-attachments/assets/e3961f79-d85a-4fef-bbde-7fdf54a480cf" />


## 📁 Project Structure
```
📦movie-recommender/
├── data/
│   └── movies.csv
├── recommender.ipynb
├── requirements.txt
└── README.md
```
## 🧠 Example
Type: Interstellar

Output:

1. The Martian
2. Gravity
3. Arrival
4. Inception
5. 2001: A Space Odyssey
   
## 🔗 Connect with Me
Feel free to reach out on LinkedIn or follow my AI journey.
- ✨ Star this repo if you find it useful!

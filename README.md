
# 📽️ Movie Recommendation System

This project is a **Machine Learning-based Movie Recommendation System**, built in **Jupyter Notebook** and deployed using **Render**. It provides personalized movie suggestions to users based on similarity algorithms.

The system is inspired and structured with the help of [this tutorial video](https://youtu.be/1xtrIEwY_zY?si=7hSBzAmZR-ZGiMCF), and follows a complete ML pipeline — from data loading to web deployment.

##Data set:
-Kaggle(https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
## 🚀 Features:
- Built with **Python** and **Jupyter Notebook**
- Implements **content-based filtering** using movie metadata
- Uses **cosine similarity** to calculate similarity between movies
- Trained model saved using **Pickle**
- Deployed as a web app using **Streamlit + Render**
- Clean and interactive UI for recommending movies based on user input

## 🛠️ Tools & Technologies:
- Python
- Pandas, NumPy, Scikit-learn
- Streamlit
- Jupyter Notebook
- Render (for deployment)
- TMDB API (for fetching movie posters)

## 🌐 Live Demo:
> *Link to your deployed project on Render (add here)*

## 📂 Project Structure:
```
├── app.py              # Streamlit app code
├── model.pkl           # Saved recommendation model
├── main.ipynb          # Jupyter notebook with full ML workflow
├── requirements.txt    # List of dependencies
└── README.md           # Project description and usage guide
```

## 📌 How it Works:
1. Movie metadata is preprocessed and vectorized
2. Cosine similarity matrix is generated
3. When a user enters a movie title, the system finds and recommends similar movies
4. Posters are fetched from TMDB API to enhance the UI
5. Everything is wrapped in a simple Streamlit app and deployed on Render

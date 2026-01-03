# 🎬 Movie Recommendation System

A content-based Movie Recommendation System built using **Python**, **Streamlit**, and **Machine Learning** techniques.  
The app suggests similar movies based on user selection.

---

## 🚀 Features
- Recommends movies similar to the selected movie
- Uses cosine similarity on movie features
- Fetches movie posters using TMDB API
- Simple and interactive Streamlit UI

---

## 🧠 How It Works
- Movie data is processed and converted into feature vectors
- **Cosine Similarity** is used to measure similarity between movies
- When a user selects a movie, the system recommends top similar movies

---

## 🛠️ Tech Stack
- Python
- Streamlit
- Pandas
- Scikit-learn
- TMDB API

# Project Structure
movies-recommender-system/
│
├── app.py # Main Streamlit app
├── requirements.txt # Project dependencies
├── README.md # Project documentation
├── .gitignore # Ignored files
├── .env # API keys (ignored)


---

## ⚠️ Important Note
- Large `.pkl` model files are **not uploaded to GitHub**
- They are loaded locally or from cloud storage (Google Drive)
- This is done to follow GitHub size limits and best practices

---

## ▶️ How to Run Locally

 1️⃣ Clone the repository
```bash
git clone https://github.com/USERNAME/REPO_NAME.git

2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Run the app
streamlit run app.py

🙌 Author
Shaiqua Perween
Aspiring Software Engineer 🚀

## 📂 Project Structure

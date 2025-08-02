# 🎬 IMDB Movie Analysis Project

This project explores and analyzes the **IMDB Top 1000 Movies** dataset using Python. It performs data cleaning, visualization, and predictive modeling to uncover insights about movie ratings, genres, revenue, and more.

---

## 📌 Objectives

- Clean and preprocess the IMDB dataset
- Visualize key movie trends (ratings, revenue, runtime, genres)
- Analyze top-performing directors and genres
- Predict IMDB ratings using regression models

---

## 📁 Dataset

- **File:** `IMDB-Movie-Data.csv`
- Contains metadata for 1000 top-rated movies from IMDB
- Columns include: Title, Genre, Director, Year, Runtime, Rating, Revenue, Votes, Metascore, etc.

---

## 🧼 Data Cleaning

- Removed rows with missing values
- Removed duplicate entries
- Renamed columns for clarity and consistency
- Split multi-genre entries into individual rows for genre-based analysis

---

## 📊 Visualizations

1. **Rating Distribution** – Histogram of IMDB ratings
2. **Top 10 Genres** – Bar chart of most common genres
3. **Runtime vs Rating** – Scatterplot showing correlation
4. **Yearly Trends** – Average IMDB rating per year
5. **Revenue vs Rating** – Relationship between earnings and ratings
6. **Genre-wise Rating Comparison** – Boxplot comparing ratings across genres
7. **Top 10 Highest-Grossing Movies** – Bar chart of highest revenue movies

---

## 🤖 Predictive Modeling

Used **Linear Regression** to predict a movie's IMDB rating based on:

- Year
- Runtime (Minutes)
- Number of Votes
- Revenue (Millions)
- Metascore

**Evaluation Metric:**  
- **RMSE (Root Mean Squared Error)** for model performance on test data

---

## 🛠️ Tools & Libraries

- Python 3.x
- pandas
- seaborn
- matplotlib
- numpy
- scikit-learn

---

## 📎 How to Run

1. Clone this repository or download the script
2. Ensure `IMDB-Movie-Data.csv` is in the same directory
3. Install required libraries:
   ```bash
   pip install pandas matplotlib seaborn scikit-learn

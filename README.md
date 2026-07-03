# 🎬 Netflix Movies Dataset - Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project is part of the **Prodigy InfoTech Data Science Internship - Task 2**.

The objective is to perform **Exploratory Data Analysis (EDA)** on a Netflix Movies dataset to understand movie trends, popularity, and genre distribution using Python.

---

## 📂 Dataset Information

The dataset contains the following features:

- Release Date
- Title
- Overview
- Popularity
- Vote Count
- Vote Average
- Original Language
- Genre
- Poster URL

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📊 Data Cleaning

The following preprocessing steps were performed:

- Removed duplicate rows
- Checked for missing values
- Converted Release Date to datetime format
- Split multiple genres into individual genres for visualization

---

## 📈 Visualizations

### 1️⃣ Popularity vs Release Date

- Scatter Plot
- Shows highly popular movies released after 2021.

---

### 2️⃣ Distribution of Genres

- Bar Plot
- Displays the six most common movie genres in the dataset.

---

## 📁 Project Structure

```
PRODIGY_DS_02
│
├── dataset/
│   └── netflix_movies.csv
│
├── images/
│   ├── popularity_vs_release_date.png
│   └── genre_distribution.png
│
├── task2.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

1. Clone this repository

```
git clone https://github.com/your-username/PRODIGY_DS_02.git
```

2. Install the required libraries

```
pip install -r requirements.txt
```

3. Open the notebook

```
task2.ipynb
```

---

## 📌 Results

- Action is the most common movie genre in the dataset.
- Recently released movies (after 2021) have several highly popular titles.
- Popularity varies significantly across movies.

---

## 👩‍💻 Author

**Devki Patel**

Prodigy InfoTech Data Science Internship

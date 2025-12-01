
---

# 🎮 League of Legends Match Data Analysis (NumPy Beginner Project)

This project is my first data analysis project using **NumPy** to explore my favorite game League of Legends match dataset.
The goal is to practice working with arrays, filtering, computing statistics, and extracting insights — all **without pandas**, using only NumPy fundamentals.

---

## 📂 Project Overview

Using a CSV dataset of https://www.kaggle.com/datasets/datasnaek/league-of-legends, this project explores simple, NumPy-ready questions such as:

* basic numeric summaries
* filtering values with boolean masks
* comparing winners vs. losers
* simple correlations
* grouping using manual slicing

This project is designed to be accessible for **NumPy beginners** (such as me), especially those not yet familiar with pandas.

---

## 🛠 Tools & Technologies

* **Python 3.10+**
* **NumPy**
* **Matplotlib** (just a bit)
* **VS Code**
* **Jupyter Notebook** (recommended for exploration)
* **Git & GitHub**

---

## 📁 Dataset

Placed your dataset inside a folder such as:

```
data/lol_matches.csv
```

Make sure your code loads it using **NumPy's `genfromtxt()` or `loadtxt()`** or just panda but only for loading the dataset like what i did.

---

## 🎯 Beginner-Friendly Analysis Goals

These goals are achievable using simple array operations such as slicing, masking, and `np.mean`, `np.sum`, etc.

### ✅ Match Statistics

1. Average game duration (**mean**, **median**, **std**).
2. Count how many matches are **longer than 30 minutes**
3. Find the **shortest** and **longest** match.
4. Percent of games longer than 30 minutes.
5. Side advantage — percent of games won by team1 vs team2.

### ✅ Objective-Based Insights

6. P(win) given **First Blood** (team that got First Blood → win probability).
7. P(win) given **First Dragon**.
8. P(win) given **First Baron**.
9. P(win) given **First Tower**.
10. P(win) given **First Rift Herald**.
11. P(win) given **First Inhibitor**.


### ✅ Champion / Pick / Ban Statistics

12. Top 10 most-picked champion IDs (overall pick counts).
13. Top 10 most-banned champion IDs.
14. Basic win rate for each champion (no role analysis).
15. Which champions have the highest win rate?
16. Which champions have the lowest win rate?

---

## 📂 Project Structure

A recommended folder layout:

```
lol-numpy-analysis/
│
├── data/
│   └── games.csv
│   └── champion_info_2.json
│   └── champion_info_.json
│   └── summoner_spell_info_.json
├── notebooks/
│   └── data_exploration.ipynb
│
├── src/
│
├── requirments.txt
├── README.md
└── .gitignore
```

---

## 🚀 How to Run This Project

1. Clone the repository:

```bash
git clone https://github.com/JerickJualo/LoL-Numlytics.git
```

2. Install dependencies:

```bash
pip install numpy pandas matplotlib jupyter
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook
```

4. Run the analysis inside `data_exploration.ipynb`.

---

## 📘 Skills Practiced

* Loading CSV files with NumPy
* Understanding dtypes
* Boolean masking
* Array slicing
* Computing basic statistics
* Writing clean analysis code
* Version control with Git
* Maintaining a project structure

---

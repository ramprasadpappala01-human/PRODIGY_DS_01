# 🌍 Top 10 Most Populous Countries (2024)

## 📌 Project Overview

This project analyzes global population data and visualizes the **top 10 most populous countries in 2024** using Python.

The data is processed using **Pandas** and visualized with **Matplotlib** to create a clear and informative bar chart.

---

## 📊 Features

* Loads population dataset from a CSV file
* Cleans and filters relevant data
* Extracts population data for the year **2024**
* Identifies the **top 10 most populous countries**
* Displays results using a bar chart

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas
* Matplotlib

---

## 📂 Dataset

The dataset used in this project:

* `API_SP.POP.TOTL_DS2_en_csv_v2_38144.csv`

> This dataset is typically sourced from the **World Bank Open Data** platform.

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/your-username/PRODIGY_DS_01.git
cd PRODIGY_DS_01
```

### 2. Install dependencies

```bash
pip install pandas matplotlib
```

### 3. Run the script

```bash
python your_script_name.py
```

---

## 📈 Output

The script generates a bar chart showing:

* Countries on the X-axis
* Population (in millions) on the Y-axis

---

## 🧠 Code Explanation

* `pandas.read_csv()` → Loads dataset (skipping metadata rows)
* Data filtering → Selects "Country Name" and "2024"
* Sorting → Finds top 10 countries by population
* `matplotlib.pyplot.bar()` → Creates visualization

---

## 📸 Sample Visualization

A bar chart representing the population distribution of the top 10 countries.

---

## ⚠️ Notes

* Ensure the dataset file is in the same directory as the script
* The dataset must contain the **2024 population column**
* Missing values are automatically removed using `.dropna()`

---

## 📬 Contact

For any queries or suggestions, feel free to reach out!

---

⭐ If you found this project useful, consider giving it a star!

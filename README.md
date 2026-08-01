# 📚 Books Data Analysis

<p align="center">
  <img src="images/banner.png" alt="Books Data Analysis Banner" width="100%">
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-013243?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-4C72B0?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter)

</p>

---

# 📖 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a Books dataset using Python. The primary objective is to clean the dataset, analyze important trends, and generate meaningful insights related to books, authors, publishers, ratings, languages, sales, and publication years.

The project demonstrates the complete EDA workflow followed by data analysts, including data preprocessing, statistical analysis, and visualization.

---

# 🎯 Project Objectives

- Import and inspect the dataset
- Perform data cleaning
- Handle missing values
- Remove invalid records
- Check duplicate entries
- Analyze publishing trends
- Study book genres
- Analyze author performance
- Explore publisher revenue
- Understand language distribution
- Visualize sales trends
- Generate actionable insights

---

# 📂 Dataset Information

The dataset contains information about books, including:

- Book Name
- Author
- Publishing Year
- Publisher
- Genre
- Language
- Average Rating
- Rating Count
- Gross Sales
- Sale Price
- Publisher Revenue
- Units Sold

---

# 🛠️ Tech Stack

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

# 📊 Project Workflow

```
Books Dataset
      │
      ▼
Data Import
      │
      ▼
Data Inspection
      │
      ▼
Data Cleaning
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Data Visualization
      │
      ▼
Business Insights
```

---

# 🧹 Data Cleaning

The following preprocessing steps were performed:

✔ Loaded the dataset

✔ Inspected dataset structure

✔ Generated descriptive statistics

✔ Removed invalid publishing years

✔ Checked missing values

✔ Removed rows with missing book names

✔ Checked duplicate records

✔ Examined unique values across columns

---

# 📊 Project Visualizations

## 📅 Publishing Year Distribution

Shows the distribution of books published over different years.

<p align="center">
  <img src="images/publishing_year_distribution.png" width="850">
</p>

---

## 📚 Genre Distribution

Illustrates the number of books available in each genre.

<p align="center">
  <img src="images/genre_distribution.png" width="850">
</p>

---

## ✍️ Average Rating by Author

Displays the authors with the highest average ratings.

<p align="center">
  <img src="images/average_rating_by_author.png" width="850">
</p>

---

## 📦 Book Rating Count by Genre

Compares rating counts across different genres using a box plot.

<p align="center">
  <img src="images/book_rating_count_by_genre.png" width="850">
</p>

---

## 💰 Sale Price vs Units Sold

Analyzes the relationship between sale price and units sold.

<p align="center">
  <img src="images/sale_price_vs_units_sold.png" width="850">
</p>

---

## 🌍 Language Distribution

Shows the percentage distribution of books by language.

<p align="center">
  <img src="images/language_distribution.png" width="850">
</p>

---

## 🏢 Publisher Revenue Analysis

Displays publishers generating the highest revenue.

<p align="center">
  <img src="images/publisher_revenue_analysis.png" width="850">
</p>

---

## ⭐ Author Rating Category Analysis

Compares average rating counts across author rating categories.

<p align="center">
  <img src="images/author_rating_category.png" width="850">
</p>

---

## 🌐 Language Frequency Analysis

Shows the frequency of books available in each language.

<p align="center">
  <img src="images/language_frequency.png" width="850">
</p>

---

## 📈 Average Rating vs Rating Count

Explores the relationship between average rating and rating count.

<p align="center">
  <img src="images/average_rating_vs_rating_count.png" width="850">
</p>

---

## 💵 Gross Sales by Author

Highlights the top authors based on gross sales.

<p align="center">
  <img src="images/gross_sales_by_author.png" width="850">
</p>

---

## 📈 Units Sold Over Time

Visualizes the trend of units sold across publishing years.

<p align="center">
  <img src="images/units_sold_over_time.png" width="850">
</p>

# 🔍 Key Insights

- Most books were published after the 1990s.
- Fiction dominates the dataset compared to other genres.
- English is the most common publication language.
- Certain authors consistently achieve higher average ratings.
- Publisher revenue varies significantly across publishers.
- Higher ratings do not always correspond to a higher number of ratings.
- Sales trends show noticeable growth in recent publication years.

---

# 📁 Project Structure

```
Books-Data-Analysis
│
├── data
│   └── Books_Data_Clean.csv
│
├── notebooks
│   └── Books_Data_Analysis.ipynb
│
├── images
│   ├── publishing_year_distribution.png
│   ├── genre_distribution.png
│   ├── language_distribution.png
│   ├── gross_sales_by_author.png
│   ├── publisher_revenue.png
│   └── average_rating_vs_rating_count.png
│
├── reports
│   └── Project_Report.pdf
│
├── requirements.txt
├── LICENSE
└── README.md
```

---

# 🚀 How to Run

### Clone Repository

```bash
git clone https://github.com/nsr-dev-in/Books-Data-Analysis.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
Books_Data_Analysis.ipynb
```

---

# 📌 Future Improvements

- Interactive Power BI Dashboard
- Book Recommendation System
- Machine Learning Models
- Sales Forecasting
- Interactive Streamlit Application

---

# 👨‍💻 Author

**Nitin Singh**

📧 Email: nsr2k06@example.com

🔗 GitHub: https://github.com/nsr-dev-in

🔗 LinkedIn: https://linkedin.com/in/nsr2k06

---

# ⭐ Support

If you found this project useful, consider giving it a **⭐ Star** on GitHub.

It helps support future open-source projects and encourages continuous learning.

---

## 📜 License

This project is licensed under the **MIT License**.

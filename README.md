# 🎬 Netflix Dataset Analysis

Welcome to the **Netflix Dataset Analysis** project!  
In this project, we explore and analyze Netflix’s catalog of TV shows and movies (up to 2021), using data sourced from [Flixable on Kaggle](https://www.kaggle.com/shivamb/netflix-shows).

Our goal is to extract valuable insights, uncover content trends, and visualize patterns that define Netflix’s evolving content strategy.

---

## 🚀 Project Overview

This project walks through the complete data analysis pipeline — from loading and cleaning raw data to uncovering hidden patterns through insightful visualizations.

### 🔍 Questions We Answer
- 📺 What’s the ratio of Movies vs TV Shows on Netflix?
- 🗓️ How has content production changed over the years?
- 🎭 Which genres and content types dominate the platform?
- 🌍 What countries contribute the most to Netflix's library?

---

## 📂 Dataset Details

The dataset includes metadata for every title on Netflix up to 2021, such as:

- **Title**
- **Director**
- **Cast**
- **Country**
- **Release Year**
- **Rating**
- **Duration**
- **Type**: Movie or TV Show
- **Date Added**

---

## 🛠️ Analysis Workflow

### 1. 📋 Data Inspection
Initial exploration using:
- `head()`, `tail()`, `shape`, `info()`
- `describe()` for statistical summaries

### 2. 🧹 Data Cleaning
Cleaning steps include:
- Handling missing values (`dropna`, `fillna`)
- Removing duplicates
- Standardizing column formats (e.g., trimming strings, consistent casing)

### 3. 🔄 Data Transformation
Transforming data for better insights:
- Splitting or extracting values from text (e.g., `str.split()`)
- Converting date columns using `pd.to_datetime()`
- Creating new columns (e.g., release decade, content category)

### 4. 📊 Data Visualization
Using Seaborn and Matplotlib to generate:
- **Bar Charts**: Movies vs. TV Shows distribution
- **Time Series**: Content release trends by year
- **Heatmaps**: Country-wise contributions
- **Pie Charts**: Genre breakdown

---

## 🧰 Tools & Libraries

- **Python 3.9+**
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Seaborn & Matplotlib** – Data visualization
- **Jupyter Notebook** – Interactive analysis

---

## 📈 Key Insights (Sample)

- 📌 Movies make up a larger portion of Netflix’s catalog than TV shows.
- 📌 The highest content addition occurred between 2017–2020.
- 📌 United States, India, and the UK are the top content contributors.
- 📌 Documentaries and Dramas are among the most frequent genres.

---

## 🤝 Contributing

Feel free to fork this repo, suggest new questions, or enhance visualizations. Pull requests are always welcome!

---

## 📎 License

This project is open source and available under the [MIT License](LICENSE).

---

**Created by [@iamsanyam24](https://github.com/iamsanyam24)**  
Exploring content trends, one dataset at a time. 🍿

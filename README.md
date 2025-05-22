# EDA-Google-playstore-data
EDA-Google playstore data
# 📱 Exploratory Data Analysis: Google Play Store Dataset

An in-depth exploratory data analysis (EDA) project using the Google Play Store dataset. This analysis uncovers key insights about app categories, user ratings, installs, pricing, and other metadata.

## 📘 Project Overview

This project explores a dataset containing information about Android apps published on the Google Play Store. It includes attributes like app name, category, rating, number of installs, price, type (free/paid), size, and more.

The goal of this EDA is to clean the dataset, understand relationships between different variables, and draw meaningful business and product insights.

---

## 🛠️ Tools & Technologies

- Python
- Jupyter Notebook (`.ipynb`)
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly (optional for interactive plots)

---

## 📊 Key Steps & Insights

### 1. **Data Loading & Preprocessing**
- Removed duplicate entries
- Handled missing values
- Cleaned inconsistent data (e.g., `Size`, `Installs`, `Price` columns)

### 2. **Univariate Analysis**
- Distribution of app ratings
- Most common app categories
- Price and install distributions

### 3. **Bivariate/Multivariate Analysis**
- Relationship between rating and category
- Price vs Rating vs Installs (free vs paid apps)
- Size vs Rating trends

### 4. **Data Visualization**
- Count plots for app categories
- Box plots and violin plots for rating comparisons
- Histograms for install and price distributions
- Scatter plots and heatmaps for correlation analysis

### 5. **Insights & Recommendations**
- Most popular categories by number of installs
- Impact of app size and type on user ratings
- Pricing strategies for paid apps
- Recommendations for new app developers

---

## 📁 File Structure

```
Google-PlayStore-EDA/
│
├── GooglePlayStore_EDA.ipynb    # Jupyter Notebook with complete analysis
├── dataset/
│   └── googleplaystore.csv      # Original dataset file
├── images/                      # (Optional) Exported visualizations
└── README.md                    # Project documentation
```

---

## 📌 Dataset Source

[Google Play Store Apps Dataset - Kaggle](https://www.kaggle.com/datasets/lava18/google-play-store-apps)

---

## 🧠 Skills Applied

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Statistical Interpretation
- Python Data Stack (Pandas, Matplotlib, Seaborn)

---

## 📈 Sample Visualizations

> (Include screenshots of a few visualizations like category distribution, rating vs. installs, etc. if uploading to GitHub)

---

## ✅ Conclusion

This EDA project provides a comprehensive understanding of app trends, user preferences, and category dynamics in the Google Play ecosystem. It serves as a foundational analysis for future predictive modeling or app recommendation systems.

---

## 📜 License

This project is open-source and available under the MIT License.

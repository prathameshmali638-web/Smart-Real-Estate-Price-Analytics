# 🏠 Smart Real Estate Price Analysis

A Python-based exploratory data analysis project focused on understanding housing prices, identifying influential property characteristics, and transforming raw housing data into actionable insights.

<p align="center">
  <img src="https://img.shields.io/badge/🐍_Python-3776AB?style=for-the-badge" />
  <img src="https://img.shields.io/badge/🐼_Pandas-150458?style=for-the-badge" />
  <img src="https://img.shields.io/badge/🔢_NumPy-013243?style=for-the-badge" />
  <img src="https://img.shields.io/badge/📈_Matplotlib-11557C?style=for-the-badge" />
  <img src="https://img.shields.io/badge/🎨_Seaborn-2E8B57?style=for-the-badge" />
  <img src="https://img.shields.io/badge/📓_Jupyter-F37626?style=for-the-badge" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Project-Real%20Estate%20Analysis-8A2BE2?style=flat-square" />
  <img src="https://img.shields.io/badge/Level-Beginner%20Friendly-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/Status-Completed-success?style=flat-square" />
  <img src="https://img.shields.io/badge/Data-21%2C613%20Houses-orange?style=flat-square" />
</p>

---

## 📌 Project Overview

Buying or selling a house is a big decision, and the price depends on many things like size, number of rooms, quality and location. But which of these things matter the most? 🤔

This project studies house sales data from **King County** to answer one simple question:

> 💰 **What makes a house expensive?**

The data has missing values, just like real life. So the project shows the full journey: **load → clean → explore → find insights**, using only basic Python tools.

---

## 🎯 Project Objectives

- 🧹 Clean the raw housing data
- 🩹 Fix the missing values
- 📊 Explore the data using simple charts
- 🔎 Find the factors that affect house price
- 💡 Share easy-to-understand insights

---

## 🧰 Skills & Tools Used

| 🛠️ Tools | 🧠 Skills |
|---|---|
| 🐍 Python | 🧹 Data Cleaning |
| 🐼 Pandas | 🩹 Missing Value Treatment |
| 🔢 NumPy | 📊 Exploratory Data Analysis |
| 📈 Matplotlib | 🎨 Data Visualization |
| 🎨 Seaborn | 💡 Business Insight Generation |
| 📓 Jupyter Notebook | |

---

## 📂 Dataset Information

| 📋 Detail | 📝 Info |
|---|---|
| 📄 File | `kc_house_data_NaN.csv` |
| 🏘️ Rows | 21,613 houses |
| 🧮 Columns | 22 |
| 🎯 Target | `price` |

**🔑 Key Features**

- 📐 **Size:** `sqft_living`, `sqft_lot`
- 🏗️ **Structure:** `bedrooms`, `bathrooms`, `floors`
- ⭐ **Quality:** `grade`, `condition`
- 📍 **Location:** `zipcode`, `waterfront`, `view`
- 🔨 **Construction:** `yr_built`, `yr_renovated`

---

## 🔄 Project Workflow

### 1️⃣ Load & Understand the Data 📥
- Loaded the CSV file using Pandas
- Checked the shape, data types and summary of the data
- Looked for missing values

### 2️⃣ Clean the Data 🧹
- Removed the extra `Unnamed: 0` column
- Changed the `date` column to proper date format

### 3️⃣ Fix Missing Values 🩹
- Missing values were found in `bedrooms` and `bathrooms`
- Filled them with the **average (mean)** of each column
- Checked again: no missing values left ✅

### 4️⃣ Explore with Charts 📊
- 📊 Histogram
- 🔵 Scatter plots
- 📦 Box plots
- 🔥 Correlation heatmap

---

## 🔍 Questions & Answers

❓ Question  📈 Chart  ✅ Answer 
|---|---|---|
| How are prices spread out? | Histogram | Most houses are mid-priced, very few are luxury |
| Does bigger size mean higher price? | Scatter plot | Yes, bigger houses usually cost more |
| Do more bedrooms mean higher price? | Box plot | Yes, but growth slows after about 6 bedrooms |
| Do bathrooms matter? | Scatter plot | Yes, they have a strong effect on price |
| Is a waterfront house costlier? | Box plot | Yes, much costlier |
| What is linked most with price? | Heatmap | Living area (`sqft_living`) |

---

## 💡 Key Insights

1. 📐 Living area is the biggest price factor
2. 🚿 Bathrooms matter more than bedrooms
3. ⭐ Better quality (grade) means higher price
4. 🌊 Waterfront, view and renovation make a house premium

---

## 📈 Business Recommendations

- 🏷️ **Sellers:** Show off big living space and good quality, they raise the price
- 🧑‍🤝‍🧑 **Buyers:** Look at living area first, not just the number of bedrooms
- 🌊 **Agents:** Advertise waterfront and view houses as premium homes
- 📈 **Investors:** Quality and space are good things to look for

---

## ⚠️ Limitations

- 🔍 Only basic analysis, no price prediction model
- 📍 Location is studied in a simple way
- 💸 Price changes over time (inflation) are not considered

---

## 📁 Files in this Project

```
📦 Real-Estate-Price-Analytics
 ┣ 📓 Real_Estate_Price_Analytics.ipynb
 ┣ 🌐 Real_Estate_Price_Analytics.html
 ┣ 📄 kc_house_data_NaN.csv
 ┗ 📘 README.md
```

---

## 🚀 How to Run

1. Install the libraries 📦
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```
2. Open the notebook 📓
   ```bash
   jupyter notebook Real_Estate_Price_Analytics.ipynb
   ```
3. Click **Run All** ▶️

---

## ✅ Conclusion

This project turns raw housing data with missing values into clean data and simple insights. It shows which things really affect house prices, which can help buyers, sellers and real estate companies make better decisions. 🏡

---

⭐ If you like this project, give it a star!

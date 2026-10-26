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

Buying or selling a house is a big decision, and the price of a house depends on many things like its size, number of rooms, quality and location. But which of these things matter the most? 🤔

This project looks at house sales data from **King County** and tries to answer one simple question:

> 💰 **What makes a house expensive?**

### 🎯 Aim of the Project

- 🔎 Find the main things that affect house prices
- 🧹 Clean real-world data that has missing values
- 📊 Show the results using easy charts
- 💡 Share simple insights that anyone can understand

### 🧭 What This Project Covers

- 📥 **Understanding the data** – checking what information we have about each house
- 🧹 **Cleaning the data** – fixing missing values and formats so the data is ready to use
- 📊 **Exploring with charts** – looking at prices, size, bedrooms, bathrooms and waterfront
- 💡 **Finding insights** – turning the charts into simple, useful conclusions

### 👥 Who Can Use This?

- 🧑‍🤝‍🧑 **Buyers** – to know what they are paying for
- 🏷️ **Sellers** – to set a fair price for their house
- 📈 **Investors** – to find homes with good value
- 🏢 **Real estate companies** – to understand the market better
- 🎓 **Students** – to learn basic data analysis step by step

### ✨ Why This Project?

Real data is rarely perfect. This dataset has missing values, just like real life. So this project is a good example of how to **clean data, explore it, and get useful answers** using only basic Python tools.

---

## 📊 About the Data

- 📄 **File:** `kc_house_data_NaN.csv`
- 🏘️ **Houses:** 21,613
- 🧮 **Columns:** 22
- 🎯 **What we study:** `price`

Some important columns: `bedrooms`, `bathrooms`, `sqft_living`, `grade`, `waterfront`, `view`

---

## 🛠️ Tools Used

- 🐍 Python
- 🐼 Pandas
- 📈 Matplotlib
- 🎨 Seaborn
- 📓 Jupyter Notebook

---

## 🔄 What I Did

1. 📥 **Loaded** the data and checked it
2. 🧹 **Cleaned** the data
   - Removed the extra `Unnamed: 0` column
   - Filled missing `bedrooms` and `bathrooms` values with the average
   - Changed `date` to proper date format
3. 📊 **Made charts** to understand the data
4. 💡 **Wrote insights** from the charts

---

## 🔍 Questions & Answers

| ❓ Question | ✅ Answer |
|---|---|
| How are prices spread out? | Most houses are mid-priced, very few are luxury |
| Does bigger size mean higher price? | Yes, bigger houses usually cost more |
| Do more bedrooms mean higher price? | Yes, but only up to around 6 bedrooms |
| Do bathrooms matter? | Yes, they have a strong effect on price |
| Is a waterfront house costlier? | Yes, much costlier |
| What is linked most with price? | Living area (`sqft_living`) |

---

## 💡 Key Insights

- 📐 Living area is the biggest price factor
- 🚿 Bathrooms matter more than bedrooms
- ⭐ Better quality (grade) means higher price
- 🌊 Waterfront and good views make a house premium

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
   pip install pandas matplotlib seaborn jupyter
   ```
2. Open the notebook 📓
   ```bash
   jupyter notebook Real_Estate_Price_Analytics.ipynb
   ```
3. Click **Run All** ▶️

---

## ✅ Conclusion

This project turns raw housing data into clean data and simple insights. It shows which things really affect house prices, which can help buyers, sellers and real estate companies. 🏡

---

⭐ If you like this project, give it a star!

# Smart Real Estate Price Analysis

An exploratory data analysis (EDA) project that examines the King County house-sales dataset to understand how property characteristics relate to sale prices. Using Python, Pandas, NumPy, Matplotlib, and Seaborn, the project cleans missing values and visualizes patterns in housing prices, living area, bedrooms, bathrooms, waterfront status, and property grade.

## Project Objectives

- Inspect and understand a real-world housing dataset.
- Identify and handle missing values.
- Convert the sale-date column to a proper datetime format.
- Explore relationships between house prices and selected property features.
- Communicate findings through charts and concise business insights.

## Dataset

- **File:** `kc_house_data_NaN.csv`
- **Source/name used in the notebook:** King County House Sales Dataset (with missing values)
- **Original size:** 21,613 rows × 22 columns
- **Target of analysis:** `price`
- **Sale dates represented:** May 2, 2014 – May 27, 2015
- **Missing values in the supplied file:** `bedrooms` (13) and `bathrooms` (10)

The file includes price, sale date, living and lot area, bedrooms, bathrooms, floors, waterfront, view, condition, grade, construction and renovation years, ZIP code, coordinates, and neighboring-home size fields. The original `Unnamed: 0` column is removed during cleaning.

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Workflow

1. **Load and inspect data** — read the CSV and review its dimensions, data types, and descriptive statistics.
2. **Clean the dataset** — remove the irrelevant `Unnamed: 0` column and inspect missing values.
3. **Treat missing values** — fill missing `bedrooms` and `bathrooms` values with the mean of their respective columns.
4. **Format dates** — convert `date` to a datetime data type.
5. **Perform exploratory analysis** — create visualizations to investigate price patterns and feature relationships.
6. **Summarize findings** — interpret the charts in the context of real-estate pricing.

## Analysis and Visualizations

| Question | Visualization | Purpose |
|---|---|---|
| How are house prices distributed? | Histogram | Examine the price distribution and identify its skew |
| How does living area relate to price? | Scatter plot | Explore the relationship between `sqft_living` and `price` |
| How do bedroom counts relate to price? | Box plot | Compare price distributions across bedroom counts |
| How do bathrooms relate to price? | Scatter plot | Explore price patterns across bathroom counts |
| Is waterfront status associated with price? | Box plot | Compare prices for waterfront and non-waterfront properties |
| How are selected variables related? | Correlation heatmap | Compare correlations among `price`, `sqft_living`, `bathrooms`, `bedrooms`, and `grade` |

## Main Findings

The notebook's chart interpretations report the following patterns:

- House prices are right-skewed, with fewer properties at the high-price end.
- Living area has a strong positive relationship with sale price.
- Price tends to rise with bedroom count up to a point, while the notebook notes slower growth beyond six bedrooms.
- The notebook interprets bathrooms as more influential than bedrooms for pricing.
- Waterfront properties appear at higher prices in the comparison shown.
- Among the selected variables in the correlation heatmap, the notebook identifies living area as having the strongest correlation with price.
- The notebook also highlights property grade, view, and renovation as features relevant to premium properties.

These are exploratory observations, not proof of causation. The notebook does not train or evaluate a predictive machine-learning model, and its conclusions should not be treated as a guaranteed estimate of a property's market value.

## Repository Structure

```text
.
├── kc_house_data_NaN.csv
├── Real_Estate_Price_Analytics.ipynb
├── Real_Estate_Price_Analytics.html
├── README.md
└── PROJECT_OVERVIEW.md
```

- `kc_house_data_NaN.csv` — source dataset used by the notebook.
- `Real_Estate_Price_Analytics.ipynb` — notebook containing the analysis code, charts, and written interpretations.
- `Real_Estate_Price_Analytics.html` — HTML export of the notebook for viewing in a browser.
- `PROJECT_OVERVIEW.md` — a concise description of the problem, methods, findings, and limitations.

## How to Run

1. Download or clone this repository.
2. Install Python and Jupyter Notebook, if not already installed.
3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

4. Keep `kc_house_data_NaN.csv` in the same directory as the notebook.
5. Open Jupyter Notebook and run `Real_Estate_Price_Analytics.ipynb` from top to bottom.

The notebook reads the dataset using the relative path `kc_house_data_NaN.csv`.

## Limitations

- Missing bedroom and bathroom values are filled with column means; this is a simple treatment and may not represent the original values.
- The analysis is descriptive and relies on selected visualizations and correlations.
- Correlation does not establish causation.
- The notebook does not include a trained price-prediction model, formal model evaluation, or a deployed dashboard.
- The supplied dataset represents a specific region and time period, so results may not generalize to other markets or periods.

## Possible Future Improvements

- Compare mean imputation with median or other missing-value strategies.
- Examine outliers and validate unusual property records.
- Add location-based and time-based comparisons.
- Use a train/test split to build and evaluate a house-price prediction model.
- Develop an interactive dashboard if interactive reporting is a project goal.

## Author

Add your name, GitHub profile, and contact details here.

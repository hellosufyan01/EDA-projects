# 📊 Data Analysis & EDA Portfolio

Hands-on **Exploratory Data Analysis (EDA)** projects on real-world datasets from Kaggle and UCI. Every project follows the same workflow: **load → inspect → clean → transform → engineer features → visualize → insights**.

> Journaling my journey, one commit at a time. 🚀

---

## 🗂️ Projects

| # | Project | Kaggle Dataset | Notebook / Folder | Skills Covered | Status |
|---|---------|----------------|-------------------|----------------|--------|
| 1 | **Titanic Survival Analysis** | [Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset) | `titanic/` | Missing values, categorical encoding, basic EDA | ✅ Completed |
| 2 | **Netflix Movies & TV Shows** | [Netflix Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows) | [`netflix.ipynb`](./netflix.ipynb), `netflix/` | Strings, dates, missing values, cleaning | ✅ Completed |
| 3 | **Superstore Sales Analysis** | [Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final) | `superstore/` | Business EDA, aggregation, dates | ✅ Completed |
| 4 | **Medical Appointment No-Shows** | [Medical Appointment No Shows](https://www.kaggle.com/datasets/joniarroba/noshowappointments) | `medical/` | Feature engineering, categorical analysis | ✅ Completed |
| 5 | **Airbnb NYC Listings** | [New York City Airbnb Open Data](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data) | `airbnb_nyc/` | Outliers, log transform, advanced EDA | ✅ Completed |
| 6 | **Flight Price Analysis** | [Flight Price Prediction](https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction) | [`flight_price.ipynb`](./flight_price.ipynb) | Cleaning, datetime parsing, feature engineering, IQR outliers, groupby & pivot tables, heatmap, EDA dashboard | ✅ Completed |
| 7 | **Google Play Store Apps** | [Google Play Store Apps](https://www.kaggle.com/datasets/lava18/google-play-store-apps) | [`playstore_apps_complete.ipynb`](./playstore_apps_complete.ipynb) | Cleaning, category / price / installs analysis, correlation, visualizations | ✅ Completed |
| 8 | **Red Wine Quality** | [Red Wine Quality](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009) | [`red.ipynb`](./red.ipynb) | Data quality checks, duplicates, feature engineering | ✅ Completed |
| 9 | **Sales & Marketing Customer Churn** | [Kaggle link](https://www.kaggle.com/datasets) *(add exact dataset link)* | [`smot.ipynb`](./smot.ipynb) | Missing values, outlier capping, string cleaning, SMOTE | ✅ Completed |
| 10 | **Online Retail II** | [Online Retail II (UCI)](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci) | [`retail.ipynb`](./retail.ipynb) | Excel loading, combining yearly sheets, KPI analysis | ✅ Completed |
| 11 | **COVID-19 in India** | [COVID-19 in India](https://www.kaggle.com/datasets/sudalairajkumar/covid19-in-india) | [`covid_19.ipynb`](./covid_19.ipynb) | Statewise testing data analysis | ✅ Completed |

---

## 🔍 Project Highlights

### ✈️ Flight Price Analysis
- Missing-value tables, duplicate removal, data-type fixes (`Date_of_Journey`, `Dep_Time`, `Price`)
- IQR-based outlier detection on price
- Engineered features: journey day/month/weekday, departure period, stop count, duration in hours, `Is_Weekend`, `Is_Long_Flight`, `Price_Category`, `Flight_Route`, `Price_per_Hour`, `Premium_Price`
- Average price by airline, source, destination, stops, month and departure period; pivot tables
- Histograms, boxplots, scatter plots, correlation heatmap and a 3×2 EDA dashboard
- Final cleaned dataset exported to CSV

### 📱 Google Play Store Apps
- Cleaned ratings, reviews, size, installs, price and last-updated columns
- Analyzed rating distribution, categories, price, installs, content rating and app size vs rating
- 10,841 raw rows; ~92.6% of apps are free; Family and Game are the largest categories

### 🎬 Netflix Titles
- 8,807 titles (6,131 movies, 2,676 TV shows)
- Handled missing values in `director`, `cast`, `country`, `date_added`, `rating`, `duration`
- Exported **7,965 clean rows** to `data_drop.csv`

### 🍷 Red Wine Quality
- 1,599 samples, no missing values, **240 duplicates removed** (→ 1,359 rows)
- Created `quality_category`, `Alcohol_cat`, `acidity_ratio`, `free_sulfur_ratio`

### 🛍️ Sales & Marketing Customer Dataset
- 15,000 customers × 30 features (spend, engagement, satisfaction, NPS, churn)
- Median imputation, IQR outlier capping, text standardization, SMOTE for class balancing

---

## 🧭 EDA Workflow Used in Every Project

```text
Import → Load → head/tail/shape/info/describe → Missing values → Duplicates
→ Fix data types → Outliers → Clean strings/categories → Transformation
→ Feature engineering → Univariate → Bivariate → Multivariate EDA
→ Matplotlib & Seaborn visuals → Correlation → Key insights → Final cleaned dataset
```

| Order | Dataset | Main Skills | Difficulty |
|-------|---------|-------------|------------|
| 1 | Titanic | Cleaning + missing values + basic EDA | ⭐⭐ |
| 2 | Netflix | Strings + dates + categorical data | ⭐⭐½ |
| 3 | Superstore | Business EDA + aggregation + dates | ⭐⭐⭐ |
| 4 | Medical Appointments | Feature engineering + categorical analysis | ⭐⭐⭐½ |
| 5 | Airbnb NYC | Outliers + transformation + advanced EDA | ⭐⭐⭐⭐ |

---

## 📁 Repository Structure

```text
.
├── README.md
├── titanic/
├── netflix/
├── superstore/
├── medical/
├── airbnb_nyc/
├── flight_price.ipynb
├── playstore_apps_complete.ipynb
├── red.ipynb
├── smot.ipynb
├── retail.ipynb
├── covid_19.ipynb
├── datasets (CSV files)
└── license.txt
```

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c)
![Seaborn](https://img.shields.io/badge/Seaborn-4c72b0)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

---

Open any notebook and run all cells.

---

## 🔮 Future Improvements

- Sentiment analysis using the Play Store user reviews dataset
- Baseline ML models on the cleaned datasets
- Interactive Plotly dashboards

---

## 📜 Data Sources & License

All datasets belong to their original owners (Kaggle, UCI Machine Learning Repository). See [`license.txt`](./license.txt) (Creative Commons Attribution 3.0) for the license that applies to the included data.

---

## 👤 About Me

**Sufyan**: CS student | Data & AI enthusiast

- 💼 LinkedIn: [your-linkedin-url] (www.linkedin.com/in/sksufyan01)
- 🐙 GitHub: [your-github-username](https://github.com/hello.sufyan01)

⭐ If you found this useful, consider giving the repo a star!

# 💎 Diamond Dataset - Exploratory Data Analysis (EDA)

## 📁 Project Overview
This project performs an in-depth exploratory data analysis on the popular Diamond dataset to uncover patterns and relationships between features affecting diamond prices. The goal is to gain insights that could help in building predictive models or making informed pricing decisions.

---

## 📊 Dataset Information

- **Source**: [Kaggle - Diamonds Dataset](https://www.kaggle.com/datasets/shivam2503/diamonds)
- **Size**: 53,940 rows × 10 columns
- **Features**:
  - `carat`: Weight of the diamond
  - `cut`: Quality of the cut (Fair, Good, Very Good, Premium, Ideal)
  - `color`: Diamond color, from J (worst) to D (best)
  - `clarity`: Measurement of how clear the diamond is
  - `depth`, `table`: Physical dimensions
  - `price`: Price in US dollars
  - `x`, `y`, `z`: Dimensions in mm

---

## 🔧 Technologies Used

- **Python 3.x**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 🧪 Analysis Performed

- Null value check and data cleaning
- Summary statistics and distribution plots
- Outlier detection
- Correlation matrix
- Impact of carat, cut, color, clarity on price
- Box plots, violin plots, heatmaps, and pairplots

---

## 📈 Key Insights

- Price is strongly correlated with `carat`.
- `Cut`, `color`, and `clarity` also influence price, but less significantly than `carat`.
- Certain outliers exist in the dataset that may skew models.




# 🚢 Titanic - Exploratory Data Analysis

EDA on the Titanic dataset to uncover key factors that influenced passenger survival using Python.

## 📂 Dataset
- **Source:** [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic)
- **Size:** 891 rows, 12 columns
- **Target Variable:** `Survived` (0 = No, 1 = Yes)

## 🔍 What I Did

- Loaded and inspected the dataset using `info()`, `describe()`, and `head()`
- Identified null values across all columns using `isnull().sum()`
- Analyzed survival distribution using countplot and pie chart
- Visualized relationship between Age, Fare, Sex, Pclass and Survival using scatterplot
- Compared average Age across survival status and gender using barplot
- Analyzed Age density distribution across survived vs non-survived using KDE plot
- Generated a correlation heatmap across all numeric features

## 📊 Visualizations Used

| Plot | Purpose |
|------|---------|
| `countplot` | Survival count (0 vs 1) |
| `pie chart` | Survival percentage breakdown |
| `scatterplot` | Age vs Fare colored by Survival, styled by Sex and Pclass |
| `barplot` | Average Age by Survival and Gender |
| `kdeplot` | Age density distribution by Survival |
| `heatmap` | Correlation between all numeric columns |

## 🛠️ Libraries Used

- `pandas` — data loading and manipulation
- `numpy` — numerical operations
- `matplotlib` — base plotting
- `seaborn` — statistical visualizations

## 📁 Files

| File | Description |
|------|-------------|
| `titanic_eda.ipynb` | Main analysis notebook |

1. Open `titanic_eda.ipynb` in Google Colab
2. Upload `Titanic-Dataset.csv` from Kaggle
3. Run all cells in order

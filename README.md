# Titanic Dataset - Exploratory Data Analysis

This repository contains an exploratory data analysis (EDA) of the Titanic dataset using Jupyter Notebook.

## 📁 Files Included

- `main.ipynb`: The Jupyter Notebook containing all code, plots, and observations.
- `Titanic-Dataset.csv`: The dataset used for analysis.

## 📊 What This Project Covers

1. **Summary Statistics**
   - Mean, median, standard deviation
   - Missing value analysis

2. **Visualizations**
   - Histograms for numeric features
   - Boxplots to detect outliers
   - Correlation heatmap
   - Pairplot for feature relationships

3. **Trends and Patterns**
   - Age distribution
   - Fare distribution (raw and log-scaled)
   - Survival distribution by class and family members

4. **Observations**
   - Most passengers were aged 20–35.
   - Fare is skewed with high outliers.
   - Many passengers traveled alone.
   - 'Survived' and 'Pclass' show interesting patterns for prediction.

## 📌 Tools Used

- Python
- Jupyter Notebook
- pandas, numpy, matplotlib, seaborn

## 📂 How to Run

1. Clone this repository
2. Open `main.ipynb` in Jupyter Notebook.
3. Run all cells step by step.

---
## ✅ Conclusion

This Exploratory Data Analysis (EDA) of the Titanic dataset provided key insights into the passenger demographics and survival patterns:

- **Age**: Most passengers were between 20 and 35 years old.
- **Fare**: The fare variable was highly skewed, with a small number of passengers paying very high amounts.
- **Survival**: A significant pattern was observed with survival rates and passenger class. Passengers in higher classes tended to have a higher chance of survival.
- **Family Size**: Most passengers traveled alone, indicated by low values in `SibSp` and `Parch`.
- **Correlation**: There was weak correlation between most numerical features, but visualizations revealed important trends.

Through this EDA, we identified outliers, missing data, and the overall distribution of key features. These insights are useful for building predictive models or understanding factors that influenced survival on the Titanic.

This project successfully meets the objectives of summarizing, visualizing, and interpreting the Titanic dataset using Python and Jupyter Notebook.


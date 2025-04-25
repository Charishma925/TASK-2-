# TASK-2-# Task 2: Exploratory Data Analysis (EDA) on Iris Dataset

## Objective
The objective of this task is to perform Exploratory Data Analysis (EDA) on the classic **Iris dataset** using statistical methods and visualizations to understand the data's structure, relationships, and potential insights.

---

## Dataset
The Iris dataset consists of 150 samples with the following features:
- **sepal_length**
- **sepal_width**
- **petal_length**
- **petal_width**
- **species** (Setosa, Versicolor, Virginica)

---

## Tools Used
- **Pandas** – For data manipulation and summary statistics
- **Matplotlib** – For basic plotting
- **Seaborn** – For advanced visualizations
- **Plotly** – For interactive visualizations

---

## EDA Tasks Performed

1. **Summary Statistics**
   - Used `.describe()` and `.info()` to get an overview of the dataset.
   - Checked for class distribution using `value_counts()`.

2. **Univariate Analysis**
   - Plotted **histograms** for each numeric feature.
   - Plotted **boxplots** to detect outliers and compare distributions.

3. **Multivariate Analysis**
   - Created a **correlation matrix heatmap** to analyze feature correlations.
   - Used **pairplots** to observe relationships between features grouped by species.

4. **Interactive Visualizations**
   - Generated a **scatter matrix** using Plotly for dynamic analysis.
   - Plotted interactive **boxplots** comparing features by species.

5. **Insights and Observations**
   - **Setosa** species is distinctly separable from the other two.
   - **Petal length** and **petal width** are strong indicators for class separation.
   - **Versicolor** and **Virginica** show some overlap in feature space.

---

# ApexPlanet Data Analytics Project

## Task 1: Foundational Setup & Exploratory Data Analysis (EDA)

### 📌 Objectives
- Set up Python + Jupyter/Colab environment with required libraries.
- Create GitHub repository with structured folders.
- Load the **Superstore Sales dataset**.
- Clean dataset (handle missing values, duplicates, invalid entries, spelling mistakes, negative values).
- Perform exploratory data analysis (EDA) with descriptive statistics and visualizations.

---

### 📂 Deliverables
- **Raw dataset**: `data/Superstore_Sales_Raw.xlsx`
- **Cleaned dataset**: `data/Superstore_Sales_Cleaned.xlsx`
- **Notebook**: `notebooks/Task1_Superstore_EDA.ipynb`
- **Report**: `reports/Task1_Superstore_Report.md`

---

### 🛠️ Data Cleaning Steps
- Converted `Sales` and `Profit` to numeric values.
- Handled missing values (`Customer Name` → “Unknown”, numeric → 0).
- Fixed invalid dates (`Order Date` parsed, invalid → NaT).
- Removed duplicate records.
- Corrected spelling mistakes (`Furnture` → `Furniture`, `Tech` → `Technology`).
- Converted negative values to absolute.

---

### 📊 Exploratory Data Analysis
- **Descriptive statistics**: mean, median, min, max, std.
- **Univariate analysis**: histograms for Sales.
- **Bivariate analysis**: scatterplot of Sales vs Profit.
- **Correlation analysis**: heatmap for numeric columns.
- **Categorical analysis**: bar plots for Category counts and Region sales.
- **Interactive visualization**: Plotly bar chart for Sales by Category & Region.

---

### ✅ Key Insights
- Missing values and invalid entries successfully handled.
- Sales vs Profit correlation explored.
- Regional and category-level sales visualized.
- Interactive charts created for deeper analysis.

---

### 🚀 Next Steps
- Push cleaned dataset and notebook into GitHub.
- Add Task 1 report summarizing findings.
- Prepare for Task 2 (EDA deep dive and dashboarding).

# Veda-Technology-Task-2: Exploratory Data Analysis (EDA)

**Intern:** Akshat Kumar
**Track:** Data Analytics
**Program:** VEDA Technology Internship — Level 1, Day 2

## Task

Perform exploratory data analysis on the **Sample Superstore Dataset** to identify important patterns, relationships, outliers, and trends — building the habit of questioning data visually and statistically before drawing conclusions.

# Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

# Dataset

**Sample Superstore Dataset** — 9,994 retail transaction records (2014–2017) with details on Sales, Profit, Discount, Quantity, Category, Sub-Category, Region, and Segment.

# Approach

1. Loaded the dataset and checked for missing values and data types
2. Generated summary statistics using `.describe()`
3. Built a correlation heatmap across Sales, Quantity, Discount, and Profit
4. Created 5 visualizations, each with a written observation:
   - Histogram — Sales distribution
   - Boxplot — Profit outliers by Category
   - Line chart — Monthly sales trend
   - Scatter plot — Discount vs Profit
   - Bar chart — Profit by Sub-Category
5. Summarized findings into a Top 3 Insights section

# Top 3 Insights

1. **Discounting is the biggest hidden profit killer.** Discount correlates negatively with Profit (-0.22), and orders with a discount above 30–40% almost always turn into a loss, regardless of category.

2. **A few sub-categories drag down overall profitability.** The `Tables` sub-category alone lost ~$17,725, and Furniture as a category is consistently weak, while Technology and Office Supplies drive most of the profit.

3. **Sales are highly seasonal and skewed.** Revenue peaks every November–December (holiday buying season) with an overall upward trend from 2014–2017. Most orders are small in value, while a handful of large orders drive a disproportionate share of total revenue.

# Files in this Repository

- `Superstore_EDA.ipynb` — Jupyter notebook with full analysis, code, and visualizations
- `superstore.csv` — dataset used for the analysis
- `README.md` — this file

# Outcome

Completed a full exploratory data analysis covering summary statistics, correlation analysis, and 5 different visualization types, resulting in 3 actionable business insights around discounting strategy, underperforming product lines, and seasonal sales trends.

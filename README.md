# Sales Analysis Project

## Overview
This project analyzes a sales dataset to understand trends, product performance, regional sales, and the impact of discounts. The goal is to provide actionable insights and recommendations to improve sales strategy.

---

## Data Loading and Quality Control

- Dataset: `sales_data.csv`
- Loaded using pandas in Jupyter Notebook.
- Converted `Sale_Date` to datetime format.
- Created additional features:
  - `Month` — extracted from `Sale_Date`
  - `Year` — extracted from `Sale_Date`
- Checked for missing values and duplicates; dataset is clean.

---

## Descriptive Statistics

Basic statistics for numeric columns:

| Metric | Sales_Amount | Quantity_Sold | Unit_Price |
|--------|--------------|---------------|-----------|
| Count  | 1000         | 1000          | 1000      |
| Mean   | 5,019.27     | 25.36         | 2,728.44  |
| Std    | 2,846.79     | 14.16         | 1,419.40  |
| Min    | 100.12       | 1             | 167.12    |
| 25%    | 2,550.30     | 13            | 1,509.09  |
| 50%    | 5,019.30     | 25            | 2,696.40  |
| 75%    | 7,507.45     | 38            | 3,957.97  |
| Max    | 9,989.04     | 49            | 5,442.15  |

---

## Exploratory Data Analysis (EDA)

### Sales by Product Category
- Clothing: 1,313,474  
- Electronics: 1,243,500  
- Food: 1,201,774  
- Furniture: 1,260,518  

### Sales by Region
- North: 1,369,613  
- East: 1,259,793  
- West: 1,235,609  
- South: 1,154,251  

### Monthly Sales Trend
- Total sales per month reveal seasonal trends.
- Highest sales observed in **January** and **November**.
- Visualized with a line plot showing monthly revenue.

### Impact of Discount
- Number of orders per discount level shows most sales occur at **lower discounts**.
- Total sales by discount plotted to assess revenue impact.
- Moderate discounts (10–20%) generate significant sales.

---

## Key Insights
- Clothing is the best-selling product category.
- North region has the highest total sales.
- Discounts between 10–20% drive strong revenue without excessive reduction in profit.
- Sales peak at the start of the year and late in the year, suggesting seasonal effects.

---

## Recommendations
- Focus marketing and promotions on **high-performing regions** (North) and categories (Clothing).  
- Use **moderate discounts** (10–20%) to increase revenue efficiently.  
- Plan promotions around **seasonal peaks** (January, November).  

---

## Visualizations
Include these plots from the notebook:  
1. **Monthly Sales Trend** — shows revenue variation by month.  
2. **Impact of Discount on Sales** — shows total sales per discount level.  

---

## How to Run
1. Open `analysis.ipynb` in Jupyter Notebook or Google Colab.
2. Ensure `sales_data.csv` is in the same folder.
3. Run all cells to reproduce the analysis, descriptive statistics, and visualizations.

---

## Files
- `analysis.ipynb` — Jupyter notebook with full code, cleaning, EDA, and visualizations.  
- `sales_data.csv` — the original sales dataset.

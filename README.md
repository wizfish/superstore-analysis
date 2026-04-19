# Superstore Sales Analysis

## Project Overview
This project analyzes the **Sample - Superstore** dataset using **Pandas** in Python.  
The goal is to perform data cleaning, feature engineering, aggregation, pivot tables, data merging, and visualization to extract business insights.

## Dataset
- Source: [Superstore Dataset on Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- Contains sales, profit, customer, product, and order information for a retail superstore.

## Tasks Performed

### 1. Load & Explore Data
- Loaded CSV into Pandas DataFrame.
- Displayed first rows, data types, summary statistics.

### 2. Data Cleaning
- Checked for missing values (none found).
- Converted `Order Date` to datetime.

### 3. Feature Engineering
- Extracted `Month` and `Year` from order date.
- Created `Profit Margin` column (Profit / Sales).

### 4. GroupBy & Aggregation
- Total sales by category.
- Total profit by region.
- Top 5 customers by sales.
- Monthly sales trend.

### 5. Pivot Tables
- Sales by Category and Region.
- Sales trend by Segment over time.
- Profit by Sub‑Category.

### 6. Data Splitting & Merging
- Split data into two DataFrames (sales‑only and profit‑only).
- Merged them back on common keys.

### 7. Visualizations
- Line chart: monthly sales trend.
- Bar chart: sales by category.
- Bar chart: profit by region.
- Pie chart: segment distribution.

### 8. Business Insights
- **Most profitable category**: Technology.
- **Least performing region**: Central (lowest profit).
- **Sales vs Profit**: Not perfectly correlated – high sales do not guarantee high profit (discounts, costs).
- **Trends**: Profit peaks in Q4 (holiday season); overall sales grow over years.

## How to Run
1. Clone this repository.
2. Install required libraries:
   ```bash
   pip install pandas matplotlib numpy

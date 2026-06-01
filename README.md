# Superstore Sales Analytics & Business Intelligence Project

## Project Overview

This project presents a complete end-to-end analysis of the Superstore retail dataset using Python. The objective is to transform raw sales data into actionable business insights through data cleaning, exploratory data analysis (EDA), customer analytics, profitability analysis, forecasting, and strategic recommendations.

The project follows a real-world analytics workflow used by data analysts to identify growth opportunities, optimize profitability, and support data-driven decision-making.

---

## Business Objectives

* Analyze overall sales and profit performance
* Identify high-performing products and categories
* Discover loss-making products and regions
* Understand customer purchasing behavior
* Measure the impact of discounts on profitability
* Perform customer segmentation using RFM analysis
* Forecast future sales trends
* Generate business recommendations based on findings

---

## Project Structure

```text
├── main.ipynb
├── superstore analysis.csv
├── cleaned_superstore.csv
├── screenshots/
├── README.md
```

### Files

| File                    | Description                                  |
| ----------------------- | -------------------------------------------- |
| main.ipynb              | Complete analysis notebook                   |
| superstore analysis.csv | Final processed dataset                      |
| cleaned_superstore.csv  | Cleaned dataset exported after preprocessing |
| screenshots/            | Visualizations and dashboard screenshots     |
| README.md               | Project documentation                        |

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Statsmodels
* Jupyter Notebook

---

## Installation

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels openpyxl
```

---

## How to Run

1. Clone the repository

```bash
git clone <repository-url>
```

2. Navigate to the project folder

```bash
cd superstore-sales-analytics
```

3. Launch Jupyter Notebook

```bash
jupyter notebook
```

4. Open:

```text
main.ipynb
```

5. Run all cells sequentially.

---

## Analysis Performed

### 1. Data Cleaning

* Missing value detection
* Duplicate record detection
* Data type verification
* Postal code correction
* Dataset validation

### 2. Sales Analysis

* Total Sales
* Total Orders
* Average Order Value
* Monthly Sales Trends
* Category Performance
* Sub-Category Performance

#### Key Metrics

* Total Revenue
* Total Orders
* Total Quantity Sold
* Average Order Value
* Sales Growth

### 3. Profitability Analysis

* Profit by Category
* Profit by Sub-Category
* Profit by Product
* Regional Profitability
* Loss-Making Product Identification

### 4. Customer Analytics

#### Customer Segment Analysis

* Consumer
* Corporate
* Home Office

#### Customer Value Analysis

* Top Customers
* Average Revenue per Customer
* Customer Contribution Analysis

#### Pareto Analysis (80/20 Rule)

Identifies the percentage of customers responsible for approximately 80% of total sales.

### 5. RFM Customer Segmentation

Customers are segmented based on:

* Recency
* Frequency
* Monetary Value

RFM helps identify:

* High-value customers
* Loyal customers
* At-risk customers
* Low-value customers

### 6. Product Analysis

* Best-Selling Products
* Most Profitable Products
* Least Profitable Products
* Quantity Sold by Category

### 7. Regional Analysis

Analysis performed at:

* Region Level
* State Level

Metrics:

* Sales
* Profit
* Profit Margin

### 8. Correlation Analysis

Relationships between:

* Sales
* Profit
* Quantity
* Discount

Visualizations:

* Correlation Heatmap
* Scatter Plots

Key Finding:

A strong negative correlation exists between discounts and profitability.

### 9. Time Series Analysis

Monthly and yearly trends for:

* Sales
* Profit
* Orders
* Quantity

Includes:

* Monthly Trend Analysis
* Year-over-Year Growth Analysis

### 10. Sales Forecasting

Implemented forecasting using:

* Exponential Smoothing (Holt-Winters Method)

Forecast Horizon:

* Next 6 Months Sales Prediction

Library Used:

```python
from statsmodels.tsa.holtwinters import ExponentialSmoothing
```

---

## Key Business Insights

### Sales Performance

* Technology generated the highest revenue.
* Consumer segment contributed the largest share of sales.
* West region achieved the highest sales performance.

### Profitability

* Technology was the most profitable category.
* Several products generated negative profit.
* Higher discounts significantly reduced profitability.

### Customer Behavior

* A small percentage of customers generated the majority of revenue.
* High-value customers contributed disproportionately to sales.

### Operations

* Sales exhibited clear seasonal patterns.
* Certain states consistently outperformed others.

---

## Business Recommendations

### 1. Optimize Discount Strategy

* Reduce excessive discounting.
* Monitor promotion profitability.
* Use bundled offers instead of direct discounts.

### 2. Improve Customer Retention

* Implement loyalty programs.
* Offer personalized promotions.
* Focus on high-value customers.

### 3. Expand High-Performing Regions

* Increase investment in profitable markets.
* Replicate successful regional strategies.

### 4. Product Portfolio Optimization

* Promote profitable products.
* Reevaluate loss-making products.
* Improve inventory allocation.

### 5. Demand Forecasting

* Use forecasting for inventory planning.
* Prepare for seasonal demand fluctuations.

---

## Sample Visualizations

* Sales by Category
* Sales by Region
* Monthly Sales Trends
* Profit by Category
* Customer Segment Analysis
* Correlation Heatmap
* Top Customers Analysis
* Product Profitability Analysis
* Sales Forecasting Charts

---

## Output

The project exports:

```text
cleaned_superstore.csv
```

and

```text
superstore analysis.csv
```

---

## Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Business Analytics
* Data Visualization
* Customer Segmentation
* Statistical Analysis
* Time Series Forecasting
* Business Intelligence
* Python Programming
* Data Storytelling

---

## Author

Jaiv Patel

Aspiring Data Analyst | Python | SQL | Power BI | Machine Learning

This project was created to demonstrate practical business analytics skills using a real-world retail dataset.

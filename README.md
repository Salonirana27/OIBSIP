# Retail Sales EDA

## Project Overview

This project performs Exploratory Data Analysis (EDA) on retail sales data to identify sales trends, product performance, category-wise revenue, regional performance, and actionable business insights.

The project was completed as part of the Oasis Infobyte Data Analytics Internship.

## Objective

The objective of this project is to analyze retail sales data and uncover:

- Sales trends over time
- Best-selling products
- Revenue contribution by product category
- Relationships between numerical variables
- Regional sales performance
- Actionable business insights for decision-making

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

The project uses a retail sales dataset containing information about:

- Order ID
- Order Date
- Ship Date
- Ship Mode
- Customer ID
- Customer Name
- Segment
- Country
- City
- State
- Postal Code
- Region
- Product ID
- Category
- Sub-Category
- Product Name
- Sales

## Analysis Performed

### 1. Initial Data Inspection

- Dataset shape
- Column data types
- Missing value check
- Duplicate record check
- Basic dataset structure

### 2. Descriptive Statistics

Calculated:

- Mean
- Median
- Mode
- Standard deviation

for the available numerical variables.

### 3. Time Series Analysis

Analyzed sales trends using:

- Monthly sales trend
- Quarterly sales trend

Line charts were used to visualize changes in sales over time.

### 4. Customer Demographics

The dataset does not contain customer age or gender information. Therefore, age-group distribution and gender breakdown could not be performed.

This limitation was documented in the notebook.

### 5. Product Analysis

Performed:

- Top 10 best-selling products analysis
- Revenue by product category

Bar charts were used to compare product and category performance.

### 6. Correlation Analysis

Created a correlation matrix and heatmap to identify relationships between numerical variables.

### 7. Additional Analysis

Analyzed total sales by region to identify regional differences in sales performance.

## Key Insights

- Sales performance was analyzed across monthly and quarterly periods.
- Quarter 4 showed stronger sales performance.
- A small group of products contributed significantly to overall sales.
- Technology was the highest-revenue product category.
- Sales performance varied across different regions.
- Numerical variables showed limited correlation with Sales.

## Business Recommendations

1. **Prepare for higher demand in Quarter 4:** Increase inventory and marketing activities before Quarter 4 to take advantage of higher customer demand.

2. **Focus on top-selling products:** Maintain sufficient stock of best-selling products and use targeted promotional strategies to maximize their revenue contribution.

3. **Improve lower-performing regions:** Develop region-specific marketing campaigns and promotional offers to improve sales performance in comparatively weaker regions.

## Project Structure


DataAnalytics-L1-EDARetailSales/
│
├── dataset/
│   └── train.xlsx
│
├── output/
│   └── screenshots/
│
├──Notebook
|   └── Retail_Sales_EDA.ipynb
│
└── README.md

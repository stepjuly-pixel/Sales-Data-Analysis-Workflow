# Full Data Analysis Workflow on a Sales Dataset

## Project Overview

This project demonstrates a complete data analysis workflow using a real-world sales dataset.
The objective is to transform raw transactional data into structured insights through data cleaning, preprocessing, exploratory analysis, and visualization.

The project follows a structured analytical pipeline:

- Data inspection

- Data cleaning and validation

- Feature engineering

- Exploratory Data Analysis (EDA)

- Business insight extraction

This notebook reflects a real-world data analyst approach rather than isolated visualizations.

## Tools & Libraries

- Python

- Pandas

- NumPy

- Matplotlib

- Seaborn

## Dataset

The dataset contains transactional sales records with the following key attributes:

- ```order_id``` – unique order identifier

- ```order_date``` – date of purchase

- ```ship_date``` – shipping date

- ```order_priority``` – order priority level

- ```country_code``` – country of sale

- ```product_id``` – product identifier

- ```sales_channel``` – sales channel (Online / Offline)

- ```units_sold``` – number of units sold

- ```unit_price``` – price per unit

- ```unit_cost``` – cost per unit

## Data Preparation

The following preprocessing steps were performed:

- Data structure inspection

- Data type corrections (date conversion)

- Missing value validation

- Duplicate check

- Numerical consistency checks

- Creation of calculated metrics:

  - Revenue

  - Total Cost

  - Profit

  - Profit Margin

These steps ensure analytical accuracy and business-ready metrics.

## Exploratory Data Analysis

### Revenue & Profit Distribution

- Analysis of revenue and profit distributions

- Identification of skewness and high-value transactions

- Detection of outliers

### Sales Channel Performance

- Comparison between Online and Offline channels

- Differences in sales volume and profitability structure

### Geographic Performance

- Revenue comparison across countries

- Profitability differences between regions

### Order Priority Analysis

- Evaluation of how operational priority relates to financial outcomes

### Time-Based Trends

- Monthly revenue and profit trends

- Detection of growth patterns and seasonality

## Key Insights

- Revenue growth does not always translate into proportional profit growth.

- Online and Offline channels demonstrate structural differences in sales volume and margin performance.

- Geographic segmentation reveals uneven profitability across countries.

- Order priority and delivery timing show no strong correlation with profitability, indicating that operational urgency does not necessarily increase financial return.

- Seasonality patterns suggest opportunities for forecasting optimization.

<img width="1163" height="808" alt="plots" src="https://github.com/user-attachments/assets/9f5c3912-4c43-4292-af42-f64a84f48f94" />


## How to Run

1. Clone this repository

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open data-analysis-workflow.ipynb in Jupyter Notebook or Google Colab

## Project Structure

full-data-analysis-workflow/
- data-analysis-workflow.ipynb
- requirements.txt
- README.md

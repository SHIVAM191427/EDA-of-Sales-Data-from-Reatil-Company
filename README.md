# EDA-of-Sales-Data-from-Reatil-Company
This repository contains an Exploratory Data Analysis (EDA) project using the Retail Sales Dataset. The dataset contains sales data for a retail company, with transaction details such as item price, quantity sold, shop ID, and item ID. 
# Exploratory Data Analysis (EDA) on Retail Sales Dataset

## Project Overview

This repository contains an **Exploratory Data Analysis (EDA)** project using the **Retail Sales Dataset**. The dataset contains sales data for a retail company, with transaction details such as item price, quantity sold, shop ID, and item ID. The goal of this project is to clean, analyze, and visualize the dataset to gain insights into sales trends, item distribution, and shop performance.

### Dataset

The dataset used in this project is from the **[Competitive Data Science: Predict Future Sales](https://www.kaggle.com/c/competitive-data-science-predict-future-sales/data)** competition on Kaggle.

#### Files:
- **sales_train.csv**: The main dataset containing sales transactions.
- **item_categories.csv**: Information on item categories.
- **items.csv**: Information on individual items.
- **shops.csv**: Information on shops.
- **sample_submission.csv**: Sample submission for predictions.
- **test.csv**: Test dataset for future predictions.

## Requirements

Before running the project, make sure to install the following dependencies:

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scipy

You can install the required libraries using:

```bash
pip install -r requirements.txt


## Project Structure

## Steps

### Data Loading and Overview:
- The dataset is loaded from the `sales_train.csv` file.
- Basic information, missing values, and duplicates are checked.

### Data Cleaning:
- Negative values in **item_price** are replaced with `NaN`.
- Rows with negative **item_cnt_day** (returns or erroneous data) are removed.

### Exploratory Data Analysis (EDA):
- **Sales Distribution**: Visualizing the distribution of items sold per day.
- **Outliers Detection**: Boxplot to detect sales outliers.
- **Correlation Analysis**: Visualizing the relationships between numerical columns.
- **Sales by Month**: Aggregating sales per month and plotting a bar chart.
- **Sales by Shop**: Aggregating sales per shop and visualizing the results.
- **Price Distribution**: Visualizing the distribution of item prices.

### Outlier Detection:
- Outliers are detected using the **Z-Score** method and removed.

## Visualizations

### 1. Sales Distribution per Day:
- A histogram of the distribution of items sold per day.

### 2. Boxplot for Sales (Outliers):
- A boxplot to detect any outliers in the sales data.

### 3. Correlation Heatmap:
- A heatmap visualizing the correlation between numerical variables.

### 4. Total Sales by Month:
- A bar chart showing total items sold per month.

### 5. Total Sales by Shop:
- A bar chart showing total items sold per shop.

## Conclusion

This EDA provides a comprehensive analysis of the retail sales data, focusing on sales distribution, item performance, shop performance, and outliers. It serves as a foundation for further predictive modeling or deeper insights into sales trends.

## How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/retail-sales-eda.git


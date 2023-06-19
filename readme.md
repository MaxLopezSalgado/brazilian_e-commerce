# Customer Geolocation Analysis

*An analysis of customer geolocation data to visualize customer distribution and generate insights.*

## Description

This project focuses on analyzing customer geolocation data from a Kaggle dataset provided by Olist. The mean goal of this Analysis is to gain insights into customer distribution and generate visualizations for better understanding of the information of this Brasilian E-commerce Company. This venture involves cleaning and merging customer data with geolocation data, performing data wrangling tasks, conducting exploratory data analysis (EDA), plotting customer locations on a map, and creating a heatmap based on customer counts. In the future we could also perform some ML predictions, but for now this exceed the aim of the analysis.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Data Sources](#data-sources)
- [Technologies Used](#technologies-used)
- [Contributors](#contributors)

## Installation

1. Clone the repository: 
    ```bash   
    git clone https://github.com/your-username/customer-geolocation-analysis.git

2. Install the required dependencies:
    ```python
    pip install pandas folium
    pip install folium
    pip install matplotlib

3. Open the Jupyter Notebook or Python script to run the project.

## Usage

1. Run the Jupyter Notebook or Python script.
2. Follow the provided code examples and comments to understand the process.
3. Explore the generated visualizations to gain insights into customer geolocation data.

## Data Wrangling and Exploratory Data Analysis (EDA)

The project involved data wrangling and exploratory data analysis on the following datasets:

**DataFrame 1: Customer Data**
```python
# DataFrame 1 Info
print(customer_df.info())
# DataFrame 2 Info
print(order_df.info())
# DataFrame 3 Info
print(payment_df.info())
# DataFrame 4 Info
print(review_df.info())
# DataFrame 5 Info
print(order_details_df.info())
# DataFrame 6 Info
print(product_df.info())
# DataFrame 7 Info
print(seller_df.info())
# DataFrame 8 Info
print(product_category_df.info())
# DataFrame 9 Info
print(geolocation_df.info())

## Data Sources

The data used in this project consists of several datasets. Here are the links to the sample datasets:

- [Customer Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- [Order Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- [Payment Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- [Review Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- [Order Details Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- [Product Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- [Seller Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- [Product Category Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- [Geolocation Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

## Technologies Used
- Python
- Pandas
- Matplotlib
- Folium

## Contributors
Maximiliano López Salgado



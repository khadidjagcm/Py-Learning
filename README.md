# VEGO GLOBAL Sales Data Analysis

## Project Description

This project focuses on the analysis of VEGO GLOBAL's e-commerce sales data using Python and Pandas.

The objective is to integrate data from different sources, clean and transform the datasets, and analyze sales, customers, products, currencies, and sales territories.

## Datasets

The project uses four datasets:

- InternetSales.xlsx: sales transaction data
- customers.json: customer information
- Products.csv: product information
- SalesTerritory.parquet: sales territory information

## Data Preparation

The following steps were performed:

1. Loading the datasets using Pandas.
2. Inspecting the structure and data types.
3. Cleaning and converting data types.
4. Transforming the six currency columns using unpivoting.
5. Creating the `CurrencyKey` and `SalesAmount` columns.
6. Integrating the datasets using merge operations.

## Data Analysis

The analysis includes:

- Sales by year
- Sales by currency
- Sales by country
- Sales by gender
- Monthly sales

## Data Visualization

Different charts were created to visualize the main results and identify important trends in the data.

## Conclusion

The project demonstrates how Python can be used to clean, integrate, analyze, and visualize e-commerce data in order to obtain useful business insights.
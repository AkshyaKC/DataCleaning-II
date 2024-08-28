# Data Cleaning Project -EV Vehicle Sales

This project focuses on cleaning a messy and unstructured dataset generated using the `faker` library. The dataset simulates sales data from an electric vehicle (EV) company, containing various imperfections to practice data cleaning techniques using Python.

## Project Overview

In this project, we will clean and prepare a raw dataset for analysis. The dataset includes multiple common data quality issues such as:

- Missing values
- Duplicates
- Incorrect data formats (e.g., date formats)
- Invalid entries
- Mixed data types
- Incorrect data labels

By the end of the project, the dataset will be ready for further analysis, allowing us to gain insights into EV sales trends and customer behavior.

## Dataset Description

The dataset contains the following columns:

- **Sale_ID:** Unique identifier for each sale (contains some duplicates).
- **Date_of_Sale:** Date of sale in various formats, including some incorrect formats.
- **Customer_Name:** Name of the customer.
- **Customer_Email:** Email address of the customer (some missing).
- **Vehicle_Model:** Model of the vehicle sold.
- **Vehicle_Year:** Manufacturing year of the vehicle (some invalid entries).
- **Price:** Sale price of the vehicle (some missing).
- **Color:** Color of the vehicle (some missing).
- **Payment_Method:** Method of payment used by the customer.
- **Discount_Applied:** Discount applied to the sale (if any).
- **Salesperson:** Name of the salesperson handling the sale.
- **Region:** Geographic region of the sale (some missing).
- **Warranty_Years:** Number of warranty years provided (some invalid entries).
- **Mileage_at_Sale:** Mileage of the vehicle at the time of sale (some missing).
- **Previous_Owner:** Name of the previous owner (if applicable, some missing).

# Online-Retail-Largescale-Data-Analysis

## Overview

This project focuses on performing exploratory data analysis (EDA) on a dataset of approximately half a million sales transactions from a UK-based online retailer. The analysis includes trend analysis, customer segmentation using RFM analysis, and customer churn analysis. Additionally, the project demonstrates large-scale data analysis on 32 million records using the Fireducks library within Google Colab, leveraging its AI assistant features.

## Objective

The primary goals of this project are:

*   To gain hands-on experience in exploratory data analysis.
*   To develop skills in data cleaning, feature engineering, and data visualization.
*   To learn how to perform customer segmentation and churn analysis.
*   To understand how to work with large datasets using libraries like Fireducks.
*   To utilize AI-assisted coding in Google Colab for improved productivity.
*   To gain domain knowledge in the retail industry.
*   **To demonstrate the performance benefits of using Fireducks for faster data analysis.**

## Dataset

The dataset used in this project is the "Online Retail" dataset, which can be found on the UCI Machine Learning Repository. It contains approximately 500,000 records with the following columns:

*   **InvoiceNo:** Invoice number (string).
*   **StockCode:** Product ID (string).
*   **Description:** Product description (string).
*   **Quantity:** Quantity of items purchased (integer).
*   **InvoiceDate:** Date of the invoice.
*   **UnitPrice:** Unit price of the item.
*   **CustomerID:** Customer ID (string).
*   **Country:** Country where the purchase was made.

## Tools and Libraries

*   **Google Colab:** Cloud-based Jupyter notebook environment.
*   **Pandas:** Data manipulation and analysis library.
*   **Matplotlib:** Data visualization library.
*   **Fireducks:** A Pandas-compatible API for large-scale data analysis.

## Key Insights

*   Identification of top-selling products.
*   Understanding customer purchasing behavior.
*   Segmentation of customers based on their purchasing patterns.
*   Insights into factors affecting customer churn.
*   Total sales started rising up in August having a peek in November. This is likely due to the holiday season at the end of the year.
*   UK has the highest sales (around 9 million)
*   Netherlands, EIRE, Germany and France are the next 4 countries each having a sales of more than 2 million.

## Conclusion

This project provides a comprehensive guide to performing exploratory data analysis on online retail data.

## Performance Improvement with Fireducks

*   **Fireducks accelerates Pandas operations, reducing execution time by almost 50%.**
*   This allows for faster iteration and analysis, especially on large datasets.

***

# Raw Data README

## Overview

This folder contains the original, unprocessed transaction dataset for customer segmentation and retention analysis.

***

## Dataset Description

Each row represents an individual purchase transaction made by a customer.

***

## Columns

- **InvoiceNo**: Unique identifier for each invoice (transaction/order).
- **StockCode**: Unique code assigned to each distinct product.
- **Description**: Text description of the item purchased.
- **Quantity**: Number of units of the product purchased in the transaction.
- **InvoiceDate**: Date and time when the transaction took place (format: MM/DD/YYYY HH:MM).
- **UnitPrice**: Unit price of the product at the time of transaction.
- **CustomerID**: Unique identifier assigned to each customer.
- **Country**: Name of the country where the customer resides.

***

## Usage Notes

- Raw data may include missing values or duplicates—please use analysis notebooks to clean the data.
- Make sure your code points to the correct file if you move or rename it.

***

# Delivery Scheduling with Pandas and OR-Tools

## Project Goal

This project prepares food delivery order data for a future scheduling optimization model.

## Current Work

- Read CSV data
- Inspect dataset
- Check missing values
- Filter cancelled orders
- Filter by distance
- Filter by order value
- Add delivery cost column
- Analyze orders by zone using groupby
- Save cleaned dataset
## Driver Data Cleaning

The driver dataset was cleaned by:

- checking missing values
- removing incomplete records
- filtering unavailable drivers
- filtering drivers with zero capacity
- organizing drivers by delivery zone

The cleaned dataset was saved as:

clean_drivers.csv
## Tools

- Python
- Pandas
- Google Colab
- OR-Tools
- Matplotlib

## Future Work


- Match drivers with orders
- Build OR-Tools scheduling model
- Visualize results

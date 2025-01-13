# E-Commerce Data Analysis Project

## Overview

- This project is designed to analyze e-commerce transaction data, including orders, payment methods, and customer demographics. The analysis includes data cleaning, filtering, and visualization to uncover insights such as order statuses, payment trends, and customer behaviors. The results are exported to a structured Excel file with multiple sheets, each containing a specific aspect of the analysis.

## Features

- **Data Cleaning**:
Handle missing values in orders, payments, and customer data.
Remove duplicates from the datasets.

- **Data Analysis**:
Filter orders by status (e.g., invoiced, canceled).
Analyze payment values by month, year, and payment type.
Group and summarize data based on customer IDs and transaction details.

- **Data Visualization**:
Heatmaps for missing data.
Pie charts for order distribution by status.
Line plots for payment trends by month and year.
Scatter plots for customer payments and installments.
Bar plots and box plots for payment distributions by type.

## Export Results:
Save analysis outputs to a multi-sheet Excel file, which includes the merged data, canceled orders, invoiced orders, and specific customer and payment insights.

## Technologies Used
- Python: Main programming language for data analysis.
- Pandas: For data manipulation and cleaning.
- NumPy: For numerical computations.
- Matplotlib: For creating static visualizations such as plots and charts.
- Seaborn: For enhanced data visualizations and aesthetics.
- XlsxWriter: To export analysis results into an Excel file.

## File Structure
**E-Commerce Data Analysis/**
├── orders.xlsx              # Order data
├── order_payment.xlsx       # Payment details
├── customers.xlsx           # Customer data
├── E_Commerce_analysis_results.xlsx  # Exported analysis results
└── analysis_notebook.ipynb  # Jupyter notebook containing the full analysis

## How to Use

- Install Dependencies: Ensure you have the necessary Python libraries installed:

- pip install pandas numpy matplotlib seaborn xlsxwriter

Prepare Data: Place the required Excel files (orders.xlsx, order_payment.xlsx, and customers.xlsx) in the same directory as the project.

Run the Analysis: Execute the analysis script or Jupyter notebook to clean, analyze, and visualize the data.

Export Results: The results will be saved to an Excel file E_Commerce_analysis_results.xlsx, which contains detailed insights in multiple sheets.

Conclusion
This analysis provides a detailed understanding of e-commerce transactions, including trends in orders, payment methods, and customer demographics. The visualizations offer an intuitive way to explore the data, while the exported Excel file allows for further examination and decision-making.



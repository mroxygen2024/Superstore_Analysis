# Superstore Sales and Profit Analysis

## Project Overview

This project involves a comprehensive exploratory data analysis (EDA) of the `Sample - Superstore.csv` dataset. The primary goal is to uncover key sales and profit trends, identify the most and least performing aspects of the business (e.g., categories, regions, customer segments), and derive actionable insights. The analysis covers data cleaning, feature engineering, aggregation, pivot table creation, and data visualization.

## Dataset

The dataset used for this analysis is `Sample - Superstore.csv`. It contains detailed information about sales transactions, including:
- Order details (Order ID, Order Date, Ship Date, Ship Mode)
- Customer information (Customer ID, Customer Name, Segment)
- Product information (Category, Sub-Category, Product Name)
- Geographical data (Country, City, State, Postal Code, Region)
- Sales metrics (Sales, Quantity, Discount, Profit)

## Analysis Highlights

Key areas explored in this notebook include:
- **Data Loading and Exploration**: Initial inspection of data types, missing values, and descriptive statistics.
- **Data Cleaning**: Handling missing values and converting data types to ensure data quality.
- **Feature Engineering**: Creation of new features such as 'Order Month', 'Order Year', and 'Sales After Discount' to enrich the dataset.
- **GroupBy & Aggregation**: Calculating total sales by category, total profit by region, identifying top customers, and analyzing monthly sales trends.
- **Pivot Tables**: Generating pivot tables to understand sales by category and region, and sales trends by segment over time.
- **Data Splitting & Merging**: Demonstrating data manipulation techniques by splitting and merging subsets of the data.
- **Data Visualization**: Creating various charts (line plots, bar plots, pie charts) to visually represent trends and distributions.

## Key Findings

Based on the analysis:

*   **Most Profitable Category**: `Technology` is the most profitable category, generating a total profit of `145454.95`.
*   **Least Performing Region (by Profit)**: The `Central` region is the least profitable, with a total profit of `39706.36`.
*   **Sales and Profit Patterns**: It was observed that not all high-sales sub-categories translate to high profits. Some sub-categories like 'Tables' and 'Bookcases' show significant sales but incur losses, indicating potential pricing or cost issues. Conversely, 'Copiers' and 'Phones' are highly profitable. The 'Profit Ratio' calculation highlighted variations in profitability across sub-categories, providing a clearer picture than just raw sales or profit figures.
*   **Important Trends Over Time**: Monthly sales and profit trends show fluctuations, with distinct seasonal peaks (e.g., end-of-year periods), generally indicating an upward trend over the years of data.

## How to View and Run the Notebook

This project is presented as a Jupyter Notebook (`.ipynb`) file, which can be viewed directly on GitHub with all outputs visible. To run and interact with the code:

1.  **Download the Notebook**: Download the `Superstore_Analysis.ipynb` file to your local machine.
2.  **Open with Jupyter/Colab**: You can open this notebook using Jupyter Notebook, JupyterLab, or Google Colab.
    *   **Google Colab**: Upload the `.ipynb` file to Google Colab directly via `File > Upload notebook`.
    *   **Jupyter**: Ensure you have Jupyter installed (`pip install jupyterlab`) and then run `jupyter lab` in your terminal, navigate to the notebook file, and open it.
3.  **Execute Cells**: All code cells have been executed, and their outputs are saved within the `.ipynb` file. You can re-run all cells by selecting `Runtime > Run all` in Colab or `Kernel > Restart & Run All` in Jupyter to reproduce the analysis.

## Requirements

To run this notebook locally, you will need the following Python libraries, which can be installed via pip:

```bash
pip install pandas matplotlib seaborn

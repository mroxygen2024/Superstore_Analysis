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

## Key Findings (Examples - you can update with your specific findings)

*   **Most Profitable Category**: `Technology` emerged as the most profitable category.
*   **Least Performing Region**: The `Central` region showed the lowest profit.
*   **Sales and Profit Patterns**: Visualizations indicate varying profit margins across sub-categories, with some high-sales sub-categories yielding negative profits.
*   **Important Trends Over Time**: Monthly sales and profit trends show seasonality and growth over the analyzed period.

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

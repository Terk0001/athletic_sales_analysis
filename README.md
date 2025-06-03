This project was done in google colab, a lot of the code is generated, suggested, autocompleted by colab
Athletic Sales Analysis
This project performs an in-depth analysis of athletic sales data from 2020 and 2021 to identify key trends and insights. It leverages Python's Pandas library for data manipulation, cleaning, and aggregation, providing a clear understanding of sales performance across different regions, retailers, and product categories, with a specific focus on women's athletic footwear.

Features
Data Combination and Cleaning: Merges sales data from 2020 and 2021 CSV files, checks for null values, and converts invoice_date to a datetime format for accurate time-series analysis.

Regional Sales Analysis: Determines regions, states, and cities with the highest product sales and total sales using both groupby and pivot_table methods.

Retailer Performance Analysis: Identifies top-performing retailers based on total sales.

Women's Athletic Footwear Deep Dive: Filters sales data specifically for women's athletic footwear to analyze:

Retailers with the most units sold.

The day with the highest sales.

The week with the highest sales.

Flexible Aggregation: Demonstrates the use of both groupby() and pivot_table() for various aggregation tasks, showcasing different approaches to data summarization.

Technologies Used
Python

Pandas

Setup and Usage
To run this analysis, you will need to have Python and Pandas installed.

Clone the repository (or download the script):

git clone <repository_url>
cd athletic-sales-analysis

(Note: Replace <repository_url> with the actual URL if this project is hosted on a platform like GitHub.)

Ensure you have the data files:
This script expects two CSV files named 2020.csv and 2021.csv to be present in the /content/ directory (as indicated by the pd.read_csv("/content/2020.csv") paths). You will need to place your sales data files in this location or update the paths in the script.

Run the script:
You can run the script using a Python interpreter or in a Jupyter/Colab environment.

If running locally:

python athletic_sales_analysis.py

If using Google Colab, ensure you mount your Google Drive as shown in the script:

from google.colab import drive
drive.mount('/content/drive')

And then upload your 2020.csv and 2021.csv files to the /content/ directory in your Colab environment.

The script will output various dataframes and series to the console, showing the results of each analysis step.

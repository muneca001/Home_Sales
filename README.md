# Home Sales Data Analysis

## Overview
This project processes home sales data using PySpark. It includes calculating average home prices based on various criteria, caching data for performance, and analyzing query runtimes. Key findings include insights on home prices by bedroom count, square footage, view ratings, and more.

## How to Run
1. Ensure PySpark and necessary libraries installed.
2. Download the `home_sales_revised.csv` file from the provided AWS S3 location.
3. Run the script in a PySpark environment.
```bash
# To install PySpark if needed
pip install pyspark

```
4. Download home_sales_revised.csv from the provided AWS S3 bucket.
5. Open the Jupyter Notebook (Home_Sales.ipynb) and run cells sequentially.

## Key Insights
- Average prices for 4-bedroom homes per year.
- Price analysis for homes with specific features, such as 3-bed, 3-bath, and 2-floor homes.
- Impact of "view" ratings on home prices for properties with prices ≥ $350,000.
- Performance improvements using cached and partitioned data.

References - edX for data 




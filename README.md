# README: E-commerce Furniture Sales Data Analysis

## Overview
This repository contains an analysis of the e-commerce furniture sales dataset for the year 2024. The analysis aims to derive insights into sales performance, customer preferences, and the impact of pricing and shipping strategies on sales.

## Dataset
- **File Name:** `ecommerce_furniture_dataset_2024.csv`
- **Description:** The dataset includes various attributes related to furniture sales, including product titles, original prices, sale prices, units sold, and shipping information.

## Key Objectives
- To preprocess the data for analysis.
- To visualize and analyze key metrics related to sales performance.
- To identify trends in pricing, discounts, and shipping options.
- To provide actionable insights and recommendations based on the analysis.

## Data Preprocessing
- **Handling Missing Values:** Null values were filled with 0.
- **Removing Duplicates:** A total of 94 duplicate rows were identified and removed.
- **Data Type Conversion:** Price and original price columns were converted to numeric values for analysis.

## Key Findings
1. **Total Sales Performance:**
   - Total number of products sold: **46,987**
   - Total revenue generated: **$2,110,806.88**

2. **Price Distribution:**
   - The price distribution is skewed to the right, indicating that most furniture items are priced lower.

3. **Impact of Free Shipping:**
   - Products with free shipping tend to sell more units, especially at lower price points.

4. **Discount Analysis:**
   - Average discount percentage across products is approximately **16.67%**.

5. **Top Selling Products:**
   - The top-selling product is the portable round folding table, with **10,000 units sold**.

## Visualizations
- **Price Distribution Histogram:** Displays the distribution of furniture item prices.
- **Price vs. Units Sold Scatter Plot:** Illustrates the relationship between price and units sold, highlighting the effect of free shipping.
- **Shipping Analysis Pie Chart:** Shows the proportion of free vs. paid shipping options.
- **Top Selling Products Bar Chart:** Highlights the top 10 products based on units sold.

## Recommendations
- Focus on offering free shipping to enhance sales.
- Analyze pricing strategies to optimize sales performance.
- Consider promotional discounts to attract more customers.

## Usage
To replicate the analysis:
1. Ensure you have the required libraries installed:
   - `pandas`
   - `matplotlib`
   - `seaborn`
   - `plotly`
2. Load the dataset using `pandas` and follow the analysis steps outlined in the provided Jupyter Notebook or Python script.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Thank you to the contributors and data providers for making this analysis possible.

---

For any questions or further information, please contact Garima Shukla at shuklagarima447@gmail.com.

# Diwali Sales Data Analysis

## Project Overview

This project focuses on analyzing sales data during the Diwali festival. Through Exploratory Data Analysis (EDA), we explore customer demographics, purchasing patterns, and key product categories. The aim is to gain actionable insights that can guide marketing strategies and improve customer targeting.

## Dataset

- **Name**: Diwali Sales Data
- **Rows**: 11,251
- **Columns**: 15
- **Key Attributes**:
  - `User_ID`: Unique ID of the customer
  - `Gender`: Gender of the customer
  - `Age Group`: Age group of the customer
  - `Marital_Status`: Marital status of the customer (0: Unmarried, 1: Married)
  - `State`: State of residence
  - `Occupation`: Profession of the customer
  - `Product_Category`: Category of product purchased
  - `Orders`: Number of products ordered
  - `Amount`: Total amount spent by the customer

## Libraries Used

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`

## EDA Steps

1. **Data Cleaning**:
   - Removed irrelevant columns like `Status` and `unnamed1`.
   - Handled missing values in the `Amount` column by filling them with the average amount.

2. **Demographic Analysis**:
   - Analyzed the distribution of sales across gender, age group, and marital status.
   - Visualized sales distribution by different states and zones.

3. **Sales Insights**:
   - Explored total sales across various product categories.
   - Identified the top 10 most sold products.
   
4. **Key Findings**:
   - The majority of customers who purchased products during Diwali were married women aged 26-35.
   - The highest sales came from the states of Uttar Pradesh, Maharashtra, and Karnataka.
   - Customers working in IT, Healthcare, and Aviation were more likely to purchase products from the Food, Clothing, and Electronics categories.

## Conclusion

**Married women aged 26-35 from Uttar Pradesh, Maharashtra, and Karnataka, working in IT, Healthcare, and Aviation, are more likely to buy products from the Food, Clothing, and Electronics categories.** This insight can help businesses tailor their marketing strategies towards this key demographic during the Diwali festival.

## Visualizations

Several visualizations were created to highlight key insights, including:
- Sales distribution by gender, age group, and state.
- Top-selling products.
- Distribution of sales across different product categories.

## Future Work

- Further refine marketing strategies to target key customer segments identified in this analysis.
- Use predictive modeling to forecast future sales trends during the Diwali season.

---

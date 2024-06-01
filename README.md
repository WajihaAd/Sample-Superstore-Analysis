# Superstore Analysis

## Project Overview

This project involves an analysis of sales and profit data across different regions, segments, and product categories. The goal is to identify key insights and trends that can help in strategic decision-making.

## Dataset

The dataset includes the following columns:
- `Ship Mode`
- `Segment`
- `Country`
- `City`
- `State`
- `Postal Code`
- `Region`
- `Category`
- `Sub-Category`
- `Sales`
- `Quantity`
- `Discount`
- `Profit`

## Analysis Performed

### Correlation Analysis
- **Discounts and Performance**: Found a moderate negative correlation between discounts and both sales (-0.57) and profit (-0.47).
- **Sales and Quantity**: Discovered a weak positive correlation (r ≈ 0.20) between sales and the quantity sold.

### Sub-Category Performance
- **Profitability**: Copiers and Machines are the most profitable sub-categories, while Fasteners and Art are the least profitable.
- **Sales**: Copiers and Machines lead in sales, indicating high demand.

### Category Insights
- **Technology**: Highest mean sales and profit.
- **Office Supplies**: Lowest mean sales and profit.
- **Furniture**: Moderate mean sales and profit.

### Regional Performance
- **Total Sales and Profit**: East region has the highest profit, while the West region has the highest total sales.
- **Average Sales and Profit**: Despite high total sales and profit, regions with more transactions can have lower averages.

### Segment and Shipping Mode
- **Segments**: Consumer segment leads in both sales and profit.
- **Shipping Mode**: Standard Class is the most popular and profitable.

### Discount Impact
- Discounts above 0.6 negatively affect average profit.

### Top Products
- **Technology**: Phones have the highest sales.
- **Office Supplies**: Binders contribute the most to total profit.

## Visualizations

- Correlation heatmaps
- Bar charts for average sales and profit by region
- Sub-category performance graphs
- Category performance comparisons
- Top states and cities by sales and profit
- Segment and shipping mode analysis

## Conclusion

The analysis provides valuable insights into how different factors like discounts, product categories, regions, and customer segments affect sales and profitability. These insights can help in making informed decisions to optimize sales strategies and improve overall profitability.


## Repository Structure

- `sales_profit_analysis.ipynb`: Jupyter notebook containing the analysis.
- `README.md`: Project documentation.

# MADE BY WAJIHA ADNAN

# Milwaukee Property Sales Analysis | 2025

## Project Overview

This project analyzes Milwaukee property sales data from 2025 to identify real estate market trends, neighborhood pricing differences, and relationships between property characteristics and sale prices.

Using Python and Jupyter Notebook, I performed data cleaning, exploratory data analysis (EDA), statistical analysis, and data visualization to transform raw property transaction data into actionable business insights.

## Business Objectives

- Analyze residential property sale prices across Milwaukee neighborhoods.
- Identify trends in monthly property sales activity.
- Compare property values using price per square foot.
- Examine relationships between property characteristics and sale prices.
- Communicate findings through visualizations and business recommendations.

## Tools & Technologies

- **Python:** Data analysis and processing
- **Pandas:** Data cleaning, manipulation, and aggregation
- **Matplotlib & Seaborn:** Data visualization
- **Jupyter Notebook:** Analysis and documentation
- **VS Code:** Development environment

## Dataset

The original dataset contained 5,685 records and 21 columns.

During data cleaning, I identified and removed 105 completely empty records, resulting in 5,580 usable property transaction records.

Of those, 4,530 were classified as residential properties.

The analysis included validation of missing values, duplicate transaction checks, and segmentation by property type.

## Key Findings

### 1. Residential Property Prices

The median residential sale price was $235,000, compared with an average of approximately $245,267.

### 2. Neighborhood Pricing Differences

Neighborhood code 3060 had the highest median residential sale price among neighborhoods with at least 10 transactions, at approximately $800,000.

Neighborhood code 4560 had the highest median price per square foot, at approximately $315.

### 3. Monthly Sales Trends

Residential sales activity peaked in May 2025 with 485 recorded transactions.

Median residential sale prices reached their highest monthly level in June at $246,000.

### 4. Property Characteristics

Finished square footage showed the strongest individual linear correlation with sale price among the characteristics examined (r = 0.355).

Full bathroom count also showed a positive correlation with sale price (r = 0.289).

Square footage and full bathroom count were correlated with each other (r = 0.65).

## Business Recommendations

1. Use neighborhood-level median prices and transaction counts when comparing local housing markets.
2. Consider price per square foot alongside total sale price to account for differences in property size.
3. Examine monthly transaction patterns when planning real estate marketing and sales activities.
4. Incorporate property characteristics and geographic information into future pricing models.

## Project Limitations

- The analysis covers one year of transactions and cannot establish long-term market trends.
- Neighborhoods are currently represented by numeric codes.
- Correlation does not establish causation.
- The analysis is descriptive and does not constitute a predictive valuation model.

## Future Improvements

- Map neighborhood codes to official geographic names.
- Incorporate multiple years of property sales data.
- Explore SQL-based analysis.
- Develop a multivariable regression model.
- Build an interactive real estate analytics dashboard.

## Project Files

- `property_sales_analysis.ipynb` — Python analysis and visualizations
- `README.md` — Project documentation
- Generated PNG files — Data visualizations

## Skills Demonstrated

Data Cleaning | Exploratory Data Analysis | Data Visualization | Statistical Analysis | Data Aggregation | Business Insights | Python | Pandas
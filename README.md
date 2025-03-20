# House Sales Analysis

## Overview

This project involves a comprehensive analysis of house sales data to uncover key factors influencing property prices, identify market trends, and provide actionable insights for stakeholders in the real estate industry.

## Objectives

- **Price Determinants:** Identify factors influencing property prices, such as location, property type, and the number of bedrooms.
- **Market Trends:** Analyze trends in property sales over time to understand how the market has evolved.
- **Geographic Variation:** Explore geographic variation in property prices by analyzing data across different postcodes.
- **Bedroom Analysis:** Investigate how the number of bedrooms affects property prices and demand.
- **Market Performance:** Evaluate the overall performance of the real estate market based on property sales data.

## Dataset

The dataset utilized in this analysis comprises the following columns:

- **Datesold:** The date when a property was sold.
- **Postcode:** 4-digit postcode of the suburb where the property is located.
- **PropertyType:** The type of property, either a house or unit.
- **Price:** The sale price of the property.
- **Bedrooms:** Number of bedrooms in the property.

*Note: The dataset is sourced from publicly available real estate transaction records.*

## Key Questions Addressed

1. What are the main factors contributing to variations in property prices?
2. Does the number of bedrooms have a noticeable impact on property prices, and if so, what is the relationship?
3. How has the average property price changed over time? Are there any seasonal patterns or long-term trends?
4. Is there any correlation between property prices and property type?
5. Are there significant differences in property prices between different postcodes?
6. Which are the top six postcodes by yearly average price?
7. Are there specific neighborhoods or postcodes that have shown consistent growth in property prices?
8. Which date corresponds to the highest number of sales?
9. Which year witnessed the lowest number of sales?
10. Which postcode has the highest average price per sale?
11. Are there any patterns or trends in the dates of property sales?

## Methodology

1. **Data Cleaning:** Handled missing values, corrected data types, and ensured data consistency.
2. **Exploratory Data Analysis (EDA):** Conducted statistical analyses and visualizations to understand data distributions and relationships.
3. **Feature Engineering:** Created new features to enhance model performance and insight generation.
4. **Data Visualization:** Utilized visualization tools to present findings in an accessible manner.

## Tools and Technologies

- **Python:** Data manipulation and analysis using libraries such as Pandas and NumPy.
- **Data Visualization:** Employed Matplotlib and Seaborn for creating insightful visualizations.
- **Jupyter Notebook:** Used as the interactive environment for developing and presenting the analysis.

## Findings

- **Price Influencers:** Identified that location (postcode) and property type significantly influence property prices.
- **Bedroom Impact:** Observed a positive correlation between the number of bedrooms and property prices, with diminishing returns beyond a certain point.
- **Market Trends:** Detected seasonal patterns in property sales, with certain months exhibiting higher sales volumes.
- **Geographic Insights:** Highlighted specific postcodes with consistently high or low property prices, aiding targeted market strategies.

## Conclusion

This analysis provides valuable insights into the factors affecting property prices and market dynamics. Real estate professionals, investors, and policymakers can leverage these findings to make informed decisions and strategize effectively in the housing market.

## Repository Contents

- `House_Sales_Analysis.ipynb`: Jupyter Notebook containing the complete analysis.
- `data/`: Directory containing the dataset used for the analysis.
- `README.md`: This file, providing an overview of the project.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

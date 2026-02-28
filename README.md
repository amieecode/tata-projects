# Tata Data Analytics Project Documentation

##Project Overview
The Tata online retail store engaged me as a data consultant to analyze their sales data and provide actionable insights. The goal of the project was to:
- Review business performance and revenue trends
- Identify top-performing customers and countries
- Explore opportunities for international expansion
- Provide insights to support operational and marketing strategies
This project focused on data cleaning, analysis, and visualization, ensuring that the insights are reliable for executive decision-making.

## Data Cleaning & Preparation
Before analysis, the dataset required several cleaning steps:
- Removed negative quantities to exclude product returns from revenue and demand analysis.
- Validated unit price values, removing any zero or negative prices.
- Standardized Invoice Date to a proper Date/Time format.
- Created a new “InvoiceDateOnly” column in Power Query to remove the time component for accurate monthly aggregation.
- Created a Date Table (2010–2012) to enable time-series analysis.
- Established relationships:
  - DateTable[Date] → Sales[InvoiceDateOnly] (One-to-Many)
- Formatted country field as Country/Region for accurate mapping.
These steps ensured all subsequent analysis was accurate and reliable.

## Tools Used
- Power BI – Data cleaning, modeling, and visualization
- Power Query – Invoice date transformation, invalid value removal
- DAX – Revenue and quantity calculations, filtering, and aggregation

## Business Recommendations
- **Seasonal Planning:** Focus on Q4 for inventory, staffing, and marketing campaigns.
- **Customer Retention:** Implement loyalty programs for top 10 revenue-generating customers.
- **International Expansion:** Prioritize Netherlands, EIRE, Germany, France, and Australia for growth.

## Conclusion
This project demonstrates the ability to clean, transform, and analyze transactional retail data to deliver actionable business insights. The analysis provides a clear roadmap for marketing, operations, and expansion strategies, supporting executive decision-making for Tata’s online retail business.

Data-Driven Strategy: Use monthly revenue trends and product demand insights to forecast and plan effectively.

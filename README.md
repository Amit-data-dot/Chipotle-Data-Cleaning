# Chipotle-Data-Cleaning

## Project Description
This project showcases a complete data cleaning workflow on the Chipotle Orders dataset. It involves importing raw data, correcting inconsistencies,converting price values to numeric and filtering relevant fields to ensure the dataset is accurate, consistent, and ready for analysis.

## Resources
**File Used:**
- chipotle.tsv
**Source:**
- [Chipotle Dataset](https://www.kaggle.com/datasets/andyxie/chipotle)

## About the Data
The dataset contains restaurant order records from Chipotle.
- Rows = 4622
- Columns = 5

## Data Information
- order_id- unique identifier of each rows
- quantity- Quantity of items ordered
- item_name - Name of the menu items
- choice_description - Additional choice
- item_price - Price of the items.(sign $)

## Cleaning Steps performed
- Converted item_price from string to numeric.
- Using filtering, slicing and indexing to select the relevent subset for analysis.

## Impurities Removed
- Filtered out unwanted rows.
- Converted inconsistent format.

## Insights
**Business Overview**
  - It helps us to analysis which items where mostly ordered.
  - Chipotle operates over 3900 restuarants in US, Canada, UK, France, Germany and Kuwait with plans to expand in Mexico.
  - Digital Sales Account for 35.1% of chipotles food and beverage revenue in 2024.
**Customer Insights**
  - Company has strong brand presence among young consumers with 88% brand awareness.
  - Chipotle target audience includes college educated Gen Z and Millennials who prioritize social and environmental issues.
       

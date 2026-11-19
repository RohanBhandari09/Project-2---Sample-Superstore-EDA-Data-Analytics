# Sample Superstore — Sales Data Analysis

## Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on the Sample Superstore dataset using ONLYOFFICE Spreadsheet Editor.

The objective was to understand sales and profitability patterns, identify underperforming areas, and derive meaningful business insights through data cleaning, spreadsheet analysis, calculations, and visualisations.

## Dataset Overview

- **Dataset:** Sample Superstore
- **Source:** Kaggle
- **Original Records:** 9,994
- **Records After Cleaning:** 9,977
- **Duplicate Records Removed:** 17
- **Number of Columns:** 13

## Tools Used

- ONLYOFFICE Spreadsheet Editor
- Spreadsheet formulas and functions
- Data cleaning and exploratory analysis
- Charts and visualisations

## Data Preparation

The original dataset was examined and cleaned before analysis.

Key preparation steps included:
- Checking the dataset structure and columns.
- Identifying and removing 17 duplicate records.
- Verifying missing values.
- Creating a separate cleaned dataset.
- Checking the consistency of calculated results.

## Analysis Performed

The analysis covered the following dimensions:

1. Category-wise performance
2. Sub-category-wise performance
3. Regional performance
4. Discount analysis
5. Customer segment analysis
6. Shipping mode analysis

### Key Performance Indicators

- Total Sales: 2,296,195.59
- Total Profit: 286,241.42
- Total Quantity Sold: 37,820
- Average Discount: 15.63%
- Overall Profit Margin: 12.47%

## Visualisations

The project includes four charts:

1. Sales by Category
2. Profit by Category
3. Profit by Sub-Category
4. Sales and Profit by Region

The chart screenshots are available in the `screenshots/` folder.

## Key Findings

- Technology generated the highest category-wise sales and profit margin, while Furniture had a comparatively low profit margin of 2.49%.
- Tables recorded the largest sub-category loss, while Copiers generated the highest sub-category profit.
- The West region recorded the highest sales and profit, whereas the Central region had the lowest profit margin.
- Certain higher-discount groups showed negative profit margins. However, this association alone does not establish that discounts caused the losses.
- The overall business profit margin was approximately 12.47%.

## Recommendations

- Investigate the profitability of Furniture, particularly its sub-categories.
- Examine the pricing, discount patterns, and costs associated with loss-making sub-categories.
- Study regional differences to identify opportunities for improving profitability.
- Evaluate discount strategies using additional business context before making changes.

## Repository Structure

sample-superstore-eda/
│
├── README.md
│
├── data/
│   ├── Sample_Superstore_Original.csv
│   └── Sample_Superstore_EDA_Project.xlsx
│
└── screenshots/
    ├── sales_by_category.png
    ├── profit_by_category.png
    ├── profit_by_subcategory.png
    └── sales_profit_by_region.png

## Project Outcomes

Through this project, I practised:

- Spreadsheet-based data cleaning.
- Identifying and removing duplicate records.
- Using formulas for aggregation and calculations.
- Performing exploratory data analysis.
- Calculating and interpreting profit margins.
- Creating charts to communicate findings.
- Drawing business insights and recommendations.
- Documenting and organising an analytical project.

*Note: This project is exploratory in nature. Observed relationships between discounts and profitability should not be interpreted as proof of causation.*

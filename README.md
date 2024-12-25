# Evaluating the Effect of Proximity to Rail Trails on House Prices 🏠

## Overview
This project evaluates the effect of proximity to rail trails on house prices using a dataset of homes sold in Northampton, Massachusetts. The goal is to assess whether living near a rail trail affects house prices, considering various predictor variables such as square footage, number of bedrooms, and proximity to rail trails.

## Objective
- **Primary Goal**: Determine how proximity to rail trails influences house prices.
- **Additional Insights**: Identify the impact of other variables like square footage, number of bedrooms, and garage spaces on house prices.

## Dataset
The dataset consists of homes sold in 2007 in Northampton, MA, with the following key variables:
- **price2014**: Estimated value of the home in 2014 (in thousands of dollars).
- **distance**: Distance (in thousands of feet) to the nearest entry of the rail trail.
- **acre**: Number of acres of property.
- **bedrooms**: Number of bedrooms in the home.
- **bikescore**: Bike friendliness of the area (0-100 scale).
- **walkscore**: Walkability of the area (0-100 scale).
- **garage_spaces**: Number of garage parking spaces.
- **squarefeet**: Square footage of the interior finished space of the home.
- **zip**: Zip code of the house.

## Methodology
1. **Exploratory Data Analysis (EDA)**: Examined distributions and relationships between variables to understand patterns.
2. **Modeling**: Built a linear regression model to estimate the effect of rail trail proximity on house prices.
3. **Diagnostics**: Checked for linear regression assumptions like linearity, normality, and homoscedasticity.

## Key Findings
- **Effect of Distance**: For every additional 1,000 feet away from the rail trail, house prices decrease by approximately $390.
- **Significance**: The proximity to the rail trail is statistically significant, but the effect on price is modest compared to other factors like square footage.
- **Other Factors**: Square footage and number of bedrooms were found to have a much more significant impact on price.

## Limitations
- The dataset only includes homes sold in 2007 in Northampton, MA, which limits its generalizability.
- The dataset does not include other factors that could influence house prices, such as school quality or local economic conditions.

## Future Work
- Expanding the dataset to include homes in different regions and years to improve the generalizability of the findings.
- Exploring non-linear models and interactions between predictors to better capture the complexity of the housing market.

## Files Included
- **midterm-report.pdf**: The final report documenting the methodology, results, and analysis.
- **scripts/**: Contains R scripts for data analysis, modeling, and diagnostics.

## How to Run
1. Clone this repository.
2. Install the necessary R packages (ggplot2, dplyr, etc.).
3. Load the dataset and run the R scripts to reproduce the analysis.

# Data-analysis-of-chocolate-companies
# Chocolate Data Preprocessing and Analysis

This repository contains code for preprocessing and analyzing chocolate data using Python libraries such as NumPy, pandas, and seaborn.

## Preprocessing Steps
1. Read the raw chocolate data from 'chocolate.csv'.
2. Clean column names by removing newline characters.
3. Convert specific columns to string data type.
4. Remove '
5. Save the preprocessed data to 'chocolate_preprocessed.csv'.

## Analysis Steps
1. Normalize the 'Rating' column by multiplying it with a scaling factor.
2. Calculate the price per 100g based on 'Rating' and 'Cocoa Percent'.
3. Filter dark chocolates with a cocoa percentage greater than 70%.
4. Increase the price of chocolates with 'Trinitario' bean type by 10%.
5. Sum up the prices of selected dark chocolates.

## Further Analysis
1. Read the processed data from 'chocolate_price.csv'.
2. Filter out chocolates with a cocoa percentage less than or equal to 70%.
3. Calculate the mean ratings of companies over the last 6 review years.
4. Identify the top 10 companies with the best average ratings.
5. Filter chocolates from these top companies for potential selling.
6. Sum up the prices of selected chocolates for selling.

The final output includes the top-rated chocolates from selected companies and the total price of these chocolates for potential selling.

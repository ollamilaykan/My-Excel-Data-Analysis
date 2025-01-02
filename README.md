# My-Excel-Data-Analysis
## Overview
-This report examines a real life sales records of a supermarket for 3 month across 3 different branch using Microsoft Excel.
## Data Source
The data used for this analysis was obtained from - <a href="https://kaggle.com/datasets/aungpyaeap/supermarket-sales?resource=download">KaggleDataset</a>
You can read the full analysis report on - <a href="https://medium.com/@yussuf.olamilekan.u/aung-pyae-supermarket-analysis-from-jan-mar-2019-ab27a6eb2974">Medium</a>

## Questions answered with the analysis are:

-Which of the product line has most sales?
-What is the percentage of male and female customers?
-Which mode of payment is best preferred by the customers?
-Which branch has the highest sales and customer type?
-Which month recorded the highest revenue?

## Data preparation and processing

- ### Cleaning of Data:
- Data cleaning is an important aspect of data preparation. Data cleaning helps purify our dataset by removing blank cells, duplicate data and removing unwanted rows and columns in the dataset concerning this project
- ### Standardising Data :
-  I changed the data type for unit price, cost of goods sold, gross income and total sales from the numeric data type into currency in usd$.
-  I also renamed some header to be more easy and relatable eg; COGS to Cost of goods sold, Total to Total Sales and Payment to Payment Methods.
-  I created a new column and formatted the date column to month in a new column using the (=TEXT) function.
-  I also used the rating column to create a new column (Feedback) to categorize the rating using the (=IF) function.

## Analysis Outcome and Visualization 
- I created my pivot table from the cleaned dataset.
- 1. Food and Beverages has the highest sales of over $56,000 in the product category while sports and travel is the closest with over $55,000.
- 2. Female customers has patronized the supermarket more than the male gender with the difference of 4%.
- 3. Cash is the most preferred mode of payment with a slight difference over the usage of E-wallet across all branch.
- 4. Naypyitaw branch recorded the highest sales with the difference of $4,161 from the next branch which is the Yangon branch which has almost the same value with the Mandalay branch
- 5. The month of January has the most revenue across the 3 month. This increase might be due to the holidays in january has its the beginning of the year.
- 6. According to the analysis food and beverages and health and beauty has more great reviews while food and beverages and sports and travel also has more bad reviews.

## Recommendations and Conclusions

- 1. Aung Pyae supermarket should always stack up the food and beverages has it is the most purchased category.
- 2. Product feedbacks are used to measure customer satisfaction about products, based on the analysis there are more of good reviews but there are also bad reviews. Aung Pyae supermarket need to conduct a survey   to know the reason why the customers are giving bad review.
- 3. The highest sales and revenue was from january due to holidays and festive period, i would recommend that the store should always have all product in stock during this period to maximize profit.
- 4. E-wallet is best preferred in Yangon branch because they have more member customers patronizing them compared to Mandalay and Naypytaw branch where the preferred mode of payment is cash.

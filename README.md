# Myntra-Data-Cleaning
This project focuses on cleaning, analyzing, and retrieving data from a Myntra product dataset. The dataset contains product details such as discount offers, sizes, and pricing. The main goals are:

Data Cleaning: Remove duplicates, standardize discount formats, and handle missing values.
Data Analysis: Compute product statistics like average prices, discount distributions, and size availability.
Data Retrieval: Use Excel functions like VLOOKUP, XLOOKUP, INDEX, and MATCH for lookup operations.
📊 Tasks and Solutions
A. Data Cleaning and Preparation
Remove duplicate values in the dataset.
Standardize the "DiscountOffer" column to ensure all values follow a uniform format.
Fill missing values in "DiscountPrice" where both "DiscountPrice" and "DiscountOffer" are null, using the average discount price of the respective category.
Replace all null values in "SizeOption" with "Not Available".
B. Data Analysis
Calculate the overall average original price for products with ratings greater than 4.
Count the number of products with a discount offer greater than 50% OFF.
Count the number of products available in size "M".
Create a new column to classify products as:
"High Discount" if the discount offer is greater than 50% OFF.
"Low Discount" otherwise.
C. Data Retrieval and Lookup
Use VLOOKUP/XLOOKUP to find brand, price, and rating of the product with Product_id = 11226634.
Use INDEX and MATCH to find the DiscountPrice for Product_id = 6744434.
Utilize nested XLOOKUP to find details of a product using its Product_id.

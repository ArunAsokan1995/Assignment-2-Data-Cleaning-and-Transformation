# Assignment-2-Data-Cleaning-and-TransformationAssignment 2 Data Cleaning and Transformation
## Handling Missing Values
1.First the Product Name has been aligned in Proper
2.Then correct the spelling of Category and fill up the missing category based on product name manually
3.Replace Electroni with Electronics IF(F3="Electroni","Electronics",F3)
4.Manually Replace the Blank Category based on the Product Type
5.Then We can fill out the missing Prices
6.Headphones and Sunglasses can be arrived based on Average price of that product and Camping Tent Price can be arrived bases to the average price of Category it is mapped.
## Correcting Inconsistent Data
1.First the Product Name has been aligned in Proper
2.Then correct the spelling of Category and fill up the missing category based on product name manually
3.Replace Electroni with Electronics IF(F3="Electroni","Electronics",F3)
4.Removing Duplicates
5.3 Duplications removed by selecting all the columns in Data -> Remove Duplicates
## Splitting and Merging Data
1.Splited Product ID to Manufacturing Date and Country code
2.Either you can use MID Function or you can use Text to Column in the Data ribbon and can split with separator "-"
3.Using Concatenate Function the Brand Name and Product Name can be Merged CONCATENATE(E2&" "&D2)
## Number Formatting
1.Formatted Price Column in currency by selecting Currency type in Home - Section Number - Different Type
2.Replace the last 2 words in the product ID to year 2026, LEFT(A2,LEN(A2)-2)&"2026" and created a new column Manufacturing date. Then in Home -> Number Section -> advance Menu -> Selected Date in DD-MM-YYYY format
## Conditional Formatting
1.Price highlighted with Data bars - high to low
2.Category - Electronics highlighted with Colour formatting with specific logic

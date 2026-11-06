# Power-BI-Assignment-1-Data-Transformation-Data-Modeling
This assignment focuses on exploring and analyzing e-commerce sales data using Power BI, it covers Data transformation and Data modeling.
  
  What I did,
- Limited the "List of Orders " into first 500 rows.
- Checked and updated the data types of Order Date to Date and Amount and target to Decimal Number.
- Changed the customer Name column to proper case for ensuring consistent capitalization for each word.
- Checked and removed the duplicates and empty rows to keep data clean.
- Merged the City and State column into one column named Location.
- Created a custom column named Profit Margin by dividing the Profit by Amount formatted the result to percentage.
- Added conditional Column named Profit Status to categorize the profit as 'Loss', 'Break-Even' or 'Profit' based on profit amount.
- Merged the "Order details" and "List of Orders" tables using the Order ID column to create a new table named "Order Data".
- Sorted the orders by order date in descending order to view the latest order trends.
- Duplicated the Order Data table and applied filters to focus on a specific state for regional analysis.
- Duplicated the "Order Details" table and used Groupby to calculate the count of each Order ID, average profit by Category and total amount by Sub-Category.
- Duplicated the "Sales Target" table and calculated the total target amount by Month of Order Date using Groupby.
- Established a relationship between the “List of Orders” and “Order Details” tables using the ‘Order ID’ column and relationship between the “Order Details” and
  “Sales Target” tables based on the ‘Category’ column and ensured the relationship is active.

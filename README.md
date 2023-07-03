1a. Data Source: 

Brazilian E-Commerce Public Dataset by Olist, Kaggle. 

1b. Data Collection: 

The dataset was provided by Olist, the largest department store in Brazilian marketplaces. The dataset has information of 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil. 

1c. Data Contents: 

The dataset includes order status, price, payment and freight performance to customer location, product attributes, geolocation, and reviews written by customers. 

1d. Data Profile:

The dataset is split by product category name, sellers, products, orders, reviews, payments, items, geolocation, and customers. 


Data Cleaning: 

•	In the payments column I changed ‘boletos’ to ‘voucher’ for consistency. 
•	Deleted the ‘not defined’ payment types in the payments tabs (3 rows deleted). 
•	Changed ‘s√£o paulo’ to ‘sao paulo’ for consistency.
•	Changed ‘*cidade’ to Curitiba (based on the lat and long). 
•	Changed ‘¬¥teresopolis’ to Teresopolis. 
•	Replaced √© with E. 

Limitations and Ethics: 

Since the data was provided by Olist (the owner) there are no ethical issues in terms of use. Some limitations might be that an order might have multiple items, each item might be fulfilled by a distinct seller, and all the identifying stores and partners were replaced with codenames. 

Questions to Explore: 

1)	What are the overall sales trends between 2016 and 2018?  
-	The year of 2017 had the highest revenue. 
 
2)	Which products or product categories have the highest sales volume or revenue? 
-	Housewares have the highest revenue. 

 
3)	Are there any seasonal or cyclical patterns in the sales data? 
-	I was expecting the holiday season to have an increase in revenue to the numbers show otherwise. 
 
4)	What is the average order values? 
5)	How does sales performance vary across different states and cities in Brazil? 
 


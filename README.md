Objective:
Real Canadian  store wants to create an annual sales report for 2022. So that,this store can understand their customers and grow more sales in 2023.

Sample Data Analytics Questions: 
1.	Compare the sales and orders using a single chart.
2.	Which month got the highest sales and orders?
3.	Who purchased more men or women in 2022?
4.	What are different order status in 2022.
5.	List top 05 states contributing to the sales?
6.	Relation between age and gender based on number of orders
7.	Which channel is contributing to maximum sales?
Data Cleaning:
Check each column for null values and duplicate values,blanks
In the column of Gender we can see duplicate values for Men as M and for women as W so we need clean this column by replacing  M with Men and W with Women
So, I am replacing One with 1 and Two with numeric 2.
Data Processing:
Now I am creating a age group(teenage, adult and Senior)
Formula 
If(E2>=50,”Senior”,If(E2>=30,”Adult”,”Teenage”))
Data Analysis:
Now I am creating a pivot table

1.	Compare the sales and orders using a single chart.
In the below chart two business problems are solved.
Sales means amount and order id (drag them into values)
1.Which month got the highest sales and orders?
2. Compare the sales and orders using a single chart.
2.	Who purchased more men or women in 2022?
3.	What are different order status in 2022.

4.	List top 5 states contributing to the sales?

1.	Relation between age and gender based on number of orders

Adding of slicers

Month, channel and category


Insights:
We can see that in the orders vs sales, march months has highest sales of 1.90M with the lowest sales in nov 1.60M
In Sales: men vs women: women are contributing more sales then men
Order status: So, most of the items are delivered with 92%
Top 5 states with more sales 
Order vs Gender: We can see the primary contributors for orders are adults 34.59%
Channels: People are buying products more from Amazon channel 35%





My sample insights.

Women are more likely to buy compared to men(~64%)
Maharastra,Karnataka, Uttar Pradesh are the top 3 states(~35%)
Adult age group(30-49 years) is max contributing ~50%)
Amazon,Flipkart and myntra channels are max contributing (~80%)
Final Conclusion of Real Canadian Store sales:
Target women customers of age group (30-49yrs) living in maharastra,Karnataka,Uttarpradesh by showing ads/offers/coupons available on Amazon,Flipkart and Myntra.


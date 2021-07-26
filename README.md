# Business Analytics Report

###### Running an analysis on Tableau Superstore Dataset to find key insights to make better business decision for managers 

## Summary 
We will be looking at the overall data, before deep diving into the components which have interesting trends to help us understand what we can improve on to increase profits.
Looking at the overall profits and sales by clustering the countries into 3 clusters: high, medium, low allow us to better understand which region is doing well. It will also help us better look at which country is driving the most profits and apply their best practices to the other clusters.
With our best performing and worst performing country, we will investigate them to see the most profitable category. This allows us to study the trends that States of the countries are making. From there, we can make decisions if certain areas are worth investing on.
Understanding that the Furniture Category is not doing so well based on data shown in States of countries, we further investigate on it. Looking at the trend of category profits based on ship date, there is a trend that caused a negative loss of furniture during January 2012. The data across the years showed that the sub-category, Tables, profitability decrease every year. Therefore, in the long run, the production for tables should decrease.
We will analyse Customer trends and their spending behaviours. Over the years, the highest spending category is Technology from customer in different years. With that, we should focus on selling other products in the same category as it would likely appeal to them as to increase sales. 2012 saw the lowest sales, mostly contributed by the loss in Q1 (as seen from the breakdown of category). Looking at the quarters of each year, there is a fixed trend of customers’ spending habit. Q1 sales will be low, and sales gradually increases towards Q4. Discounts follow this trend as well. We are therefore assuming here that cost prices have been decreased since profits increase this way as well.
Finally, we will be looking at the forecast of each sub-category, as well as the sales and how discounts affect the sales. The forecast would also project the segment of customer to focus on, hence helping the business focus and make better business decisions.
This would then help us better understand where to increase our investments in, therefore increasing overall profits.

# Introduction 
Given the dataset from 2011 Q1 to 2015 Q1, we will be looking into the key insights which would help the management make better decisions on where to invest their money in. 

## Overview by Profitability 
![image](https://user-images.githubusercontent.com/58731312/126946594-7edfa54b-2acc-4014-8c01-aea1bb6732f2.png)
###### Figure 1. Map of Countries in Clusters, sorted by Profits and Sales

This is an overall view of countries that are clustered by profit and sales. There are 3 clusters: high, medium and low. Each cluster will compromise of countries whose sales and profits are close to each other. The high cluster has an average profit of 286,397 while the low cluster has an average profit of 2,635 which shows huge disparity.  As seen on figure 1, it Is largely compromised by ‘Low’ clusters.  
In the following figures, clusters will be used to highlight the proportion of countries. 

![image](https://user-images.githubusercontent.com/58731312/126946797-e9edd290-eae4-47e6-8d8c-4f21ea8daa20.png)
###### Figure 2. Profits and Sales sorted by Clusters

We can see that the highest profiting country is United States (286,397). On the other hand, the lowest country is Turkey, with a negative profit of -98,447. The huge difference between these countries greatly affect the firm’s overall average. The sales average across all countries is 84,849 and the profit average is 9,849. The average sales are only 3% of U.S. Sales. 
It would suggest that U.S.  share their best practices with the rest of the clusters so that company can raise their average sales and profits.

![image](https://user-images.githubusercontent.com/58731312/126946844-ef933244-8d48-419d-a0bd-88b7dcac1f35.png)
###### Figure 3. Category sorted by Clusters. The longer the bar, the higher the profits. 

Technology has the highest profits (663,779), followed by Office Supplies (518,474) then Furniture (285,205). The data shows that the profits made by furniture is not even 50% of technology profits. Therefore, it suggests that the sub-category are not doing well and needs to be looked into details. 

## Breakdown by Countries
Figure 2 shows that the highest performing country is U.S. and the lowest performing is Turkey. In figure 4, we will look at their profits in the respective categories. 
![image](https://user-images.githubusercontent.com/58731312/126946965-bd9032fc-32da-4c4d-ab07-f7e67d8ccf0a.png)
###### Figure 4. Country Outliers as shown on fig 2 - Breakdown of U.S. and turkey

While U.S. is making high profits, Turkey has been constantly making losses. The data also shows that the Furniture category have an average of -2,375 which is mostly due the low profits from U.S. This suggest that U.S. have been doing Turkey sales. 
There is an increase in profits as each year pass for Office Supplies and Technology  which suggest they are more worth investing in to increase our profits. 

Figure 5 and 6 breaks down the top or bottom 4 states of their respective country. 

![image](https://user-images.githubusercontent.com/58731312/126947044-aecbed42-a40d-48b5-8fa4-e59f7a764f27.png) 
###### Figure 5. U.S. Top 4 State Profits                 
![image](https://user-images.githubusercontent.com/58731312/126947055-0d4e7806-e63b-435d-9ed9-81db5d5c63ac.png)
###### Figure 6. Turkey Bottom 4 State Profits 

In figure 5, it is notable that there is a huge disparity between New York (42,187) and Washington (15,019).  There could be a lack of brand awareness or consumer preference in the products we are offering in the office supplies and technology items as well as the lack of demand for furniture items.
As Istanbul is the capital of Turkey which saw the most losses, we suggest lessening in investment for Turkey. It would not be profitable in the long run. 

## Breakdown by Category
We analyse the profits of all the categories over the years and there is a huge drop in profits for Furniture in January 2012. It is the only point in the diagram that gives a negative profit of -1340.

![image](https://user-images.githubusercontent.com/58731312/126947199-6430642c-3034-4c7b-8617-2f8ad9467436.png)
###### Figure 7. Profit of Categories over the years, 2011 – 2015 Q1

![image](https://user-images.githubusercontent.com/58731312/126947228-9c83f681-786d-47fa-93a4-009aafd0aa74.png)
###### Figure 8. January 2012 Furniture Sub-Category Countries by Profits.

![image](https://user-images.githubusercontent.com/58731312/126947280-a076fdc0-ac31-4adb-898c-a72640730c6d.png)
###### Figure 9. Filter of figure 8 by Tables

Further investigation shows that the sub-category Tables is the item that contributed most to the drop in profits. 
There are only five countries purchasing tables as seen on figure 9. U.S. contributed most to the losses, therefore it suggest that tables are not in demand. 

![image](https://user-images.githubusercontent.com/58731312/126947340-c9b9b549-1b42-47cb-a4fc-d9590001507f.png)
###### Figure 10. Total Profits of each category from 2011 to 2015 Q1. 

Comparing the total profits over the years to sub-categories, we see that Tables has been constantly making a loss. 
The data shows that Technology category is flourishing which suggest investing more to increase profits. 
As for Office Supplies category, the data shows that there is slow growth for Envelopes, Supplies, Labels and Fasteners. We suggest that supply increase in tandem with the growth. 

## Customer Behaviour Analysis
![image](https://user-images.githubusercontent.com/58731312/126947413-9c7ff2b0-035b-468a-8929-f25d5e3a90e8.png)
###### Figure 11. Customer Behaviour through Sales, 2011 – 2015

We will analyse customer behaviour in order to help us make more customer-centric decisions.  
There is an increase in average of sales over the years.  In the case of customer - Sean Miller,  the sale of technology product has reached its high at 26K, and therefore, we should continue to market more technological products to him; whereas in the case of customer Sanjit Chand’s, the recommend focus should be in office supplies at 12K. 

![image](https://user-images.githubusercontent.com/58731312/126947455-e837cd5d-3420-4870-9e00-8e6ed92df277.png)
###### Figure 12. Sales and Discount Trend from 2011 – 2015, categorised by Category

![image](https://user-images.githubusercontent.com/58731312/126947490-54014c41-4fd9-462b-9baa-d8dd13016acb.png)
###### Figure 13. Filter by Office Supplies from figure 12

Figure 12 shows that there is a trend of more discounts leading to higher sales as each quarter of the year pass. There is a trend that shows sales starting in Q1 will progressively increase until Q4 as the peak. This tells us that the Sales is affected by seasonality. We should promote our products more during Q1 so that sales can be increased. 

A trend that stands out most is the high discounts of office supplies have increased the sales of office supplies. To clear out the existing stockpile, we could offer them as bundles to further attract customers. 
Customers have a variety of choices of their shipping mode. We are analysing if there is a relation between shipping mode and sales. 

![image](https://user-images.githubusercontent.com/58731312/126947598-d1690140-6c66-4792-986c-d54ab976a96c.png)
###### Figure 14. Shipping Cost of each Segment, coloured by Ship Mode from 2011 -2015 

Most of them do not opt for Same Day shipping, which shows no urgency.  The data set suggest that there is no need to place emphasis on the mode of shipping as most customers prefer Standard Class mode.  

## Forecasting Profits in Long Run
We will forecast by profits of sub-categories, profits in relation to discount, and the segmentation of customers. 

![image](https://user-images.githubusercontent.com/58731312/126947684-f07dbe0e-8645-494d-b68a-62fecb92aff2.png)
###### Figure 15. Forecast of Profits for Furniture Category

In the long run, the data suggest that there is no demand for the sub-category Tables, hence decreasing production would allow us to invest in other places. Bookcases shows a trend of increasing profitability; hence we should focus on producing and marketing bookcases.

![image](https://user-images.githubusercontent.com/58731312/126947752-5bf05b53-04e7-45f3-abc9-6d5bf2f53cc1.png)
###### Figure 16. Forecast of Profits for Office Supplies Category

In today’s context, every information is being digitize. Hence, the demand of envelopes, fasteners, labels, supplies and binders will potentially decrease. There is not much profit being made in the long run as well. Hence, we should scale back on these items as to avoid excess stocks. 
Looking at figure 16, it tells us that we should be focusing on storage and appliances as that would help us increase profits. 

![image](https://user-images.githubusercontent.com/58731312/126947814-9a22264a-d76a-4d76-b3db-0bfd7298c88b.png)
###### Figure 16. Forecast of Profits for Technology Category

We should place more emphasis on this category by investing more in copiers and accessories. Profits on machine seems to suggest that there is far less to make, hence we should scale back on it.  

![image](https://user-images.githubusercontent.com/58731312/126947878-a5a8d575-b609-4e41-b3f9-0cc4160f7d79.png)
###### Figure 17. Forecast of Profits and Discounts by Quarter

Assuming the sale price of products has gone up, or the company brought in a bigger bulk, we see that the profits have been increasing stealthy along with the discounts. It suggests that customers are over reliant on discounts to decide if they should buy. Hence, we should market the products such that even without discounts, they are willing to purchase it. 

![image](https://user-images.githubusercontent.com/58731312/126947944-08125d47-4328-4700-bba0-5e934555c977.png)
###### Figure 18. Forecast of Profits of Segmentation by Quarter

We should place more emphasis on Consumer and Corporate rather than Home Office customers. This would allow more sales in those segments and therefore increasing overall profits. 

## Conclusion
The overall profits and sales of countries suggest that we should focus most on U.S. However, Turkey should be less emphasised on as it is a loss-making country and more likely to close eventually.
The data have shown that the category furniture makes the least profits. Hence, there should be scaling back on the production of items in it. Especially for the sub-category tables, where we saw a loss in the long run. Hence, we should consider ceasing production for Tables. 
The sales of customer are segregated by category, which suggest that we should focus our marketing scheme appropriately to the category they are interested in and giving them the appropriate discounts. This would allow excess stocks to be cleared, as well as increasing sales at the same time. 
In the long run, we might want to implement a system to help us manage our customers, in terms of service for technology or product recommendations. It is also more beneficial to understand the demographics of our consumers and corporate customers, and which countries they are purchasing from. This way, our focus on the top countries and customers will be able to drive up more profits, hence increasing overall profits. 

# StockX sneakers market Project (SQL)
A comprehensive analysis of sales trends, prices, and buyer preferences in the stockX sneaker market, comparing Nike x Off-White sneakers and Yeezy sneakers. Leveraging a rich dataset, I identified marketing and sales strategies as well as regional variations

# About StockX
StockX is an online marketplace that specializes in buying and selling of sneakers, including limited-edition sneakers from popular brands like Nike and Adidas, electronics, collectibles, and other high-demand consumer goods. Since its launch in 2015, StockX has become wildly popular for its distinctive approach to e-commerce.

# About the dataset
This dataset comprises a single file of sales data sourced from StockX. It contains information such as Order Date, Brand, Sneaker Name, Sale Price, Retail Price (cost), Release Date, Shoe Size, and Buyer Region for two prominent brands: Nike x Off-White and Yeezy. There are 99,956 total sales in the data set. The sample consists of U.S. sales only.

# Objective
The objective of this analysis is to gain insights into the sales trends and buyer preferences for Yeezy sneakers and off-white sneakers during the specified time period. By examining factors such as order date, sale price, retail price(cost), release date, shoe size, and buyer region, we aim to identify key patterns, pricing strategies, and regional variations that can inform marketing and sales strategies for Yeezy and Off-White sneakers in the future.

# Total sales 

![image](https://github.com/Ananyad7/SQL_StockXsneakersmarket_Project/assets/164981636/434ea9c6-af77-4208-8393-dc5a5bbb985e)

72,162 Yeezy sales
27,794 Off-White sales

# Average sale price

![image](https://github.com/Ananyad7/SQL_StockXsneakersmarket_Project/assets/164981636/134809dc-5178-49bd-bd30-d3ca4b55a9a3)

Average sale price of Off-White is  $671.48
Average sale price of Yeezy  is  $360.03

# Maximum and Minimum sale prices

[image](https://github.com/Ananyad7/SQL_StockXsneakersmarket_Project/assets/164981636/b5fd981b-8e98-4b39-9934-6e29f1fae908)

The maximum and minimum sale prices for Yeezy are $2300 and $186, respectively.

![image](https://github.com/Ananyad7/SQL_StockXsneakersmarket_Project/assets/164981636/7c05a802-e4cd-48e1-a6fb-998a23c1daf0)

The maximum and minimum sale prices for Off-White are $4050 and $203, respectively.

# Top 3 sneakers

![image](https://github.com/Ananyad7/SQL_StockXsneakersmarket_Project/assets/164981636/0f4ea1ff-bb9f-445a-ab4b-ed3da81ddac4)

Yeezy’s highest-selling sneaker is the Adidas Yeezy-Boost-350-V2-Butter (11423).

![image](https://github.com/Ananyad7/SQL_StockXsneakersmarket_Project/assets/164981636/17b24c8a-a193-452b-b1ff-020b4f2c20ce)

Off-White’s highest-selling sneaker is Air-Jordan-1-Retro-High-Off-White-University-Blue (4635).


# Top 5 popular shoe sizes

![image](https://github.com/Ananyad7/SQL_StockXsneakersmarket_Project/assets/164981636/bebc5084-69a4-4b7b-9b80-bb4b00d88deb)


![image](https://github.com/Ananyad7/SQL_StockXsneakersmarket_Project/assets/164981636/763a2d87-2bc7-420c-aee3-2dead0025a51)


# Release date Analysis



![image](https://github.com/Ananyad7/SQL_StockXsneakersmarket_Project/assets/164981636/b66cb614-3475-4922-b7e2-cd78a9efbce0)

Yeezy launched the most products overall in 2017 (44722), and the least products overall in 2015 (333).
![image](https://github.com/Ananyad7/SQL_StockXsneakersmarket_Project/assets/164981636/6ffff983-20c9-46f7-a82f-63686b957640)

Off-White launched the most products overall in 2018 (21449), and the least products overall in 2019 (1371).

#  Annual Order Analysis
 ![image](https://github.com/Ananyad7/SQL_StockXsneakersmarket_Project/assets/164981636/0b1e9f54-3577-437a-85f6-05257f2cf8af)

Yeezy got the highest order in 2018 (49349) and the lowest in 2017 (10731).
Off-White got the highest order in 2018 (21121) and lowest in 2017 (2562).

# Profit Margin Analysis

![image](https://github.com/Ananyad7/SQL_StockXsneakersmarket_Project/assets/164981636/59d3d93b-492c-4a37-aaff-e46e0627bd52)
Yeezy’s Profit Margin is 39% 
Off-White’s Profit Margin is 74%

# Top 5 regions with highest order

![image](https://github.com/Ananyad7/SQL_StockXsneakersmarket_Project/assets/164981636/1303638b-0d44-4cd3-880a-57f6e86ce34e)

![image](https://github.com/Ananyad7/SQL_StockXsneakersmarket_Project/assets/164981636/d51753e8-8485-47e0-9ef4-21eb59d4fded)

# Average sale price across different time periods


![image](https://github.com/Ananyad7/SQL_StockXsneakersmarket_Project/assets/164981636/35090a4f-eb2f-4341-888f-fa04ea0937ae)


![image](https://github.com/Ananyad7/SQL_StockXsneakersmarket_Project/assets/164981636/3c2b9a76-ad3c-4989-8a11-8776fff1afe4)



 Off-White consistently has higher average sale prices compared to Yeezy throughout the year. Prices tend to be lower in the first few months of the year (January to March) and then rise during the middle months before potentially declining again towards the end of the year for both brand.


# Total profit margin for last quarter of the year 2017 Vs 2018

![image](https://github.com/Ananyad7/SQL_StockXsneakersmarket_Project/assets/164981636/def0d4f2-3416-46f9-b277-b8fff1e1dd2b)

Yeezy : In 2017, Yeezy's profit margin declined from 67.76% in October to 56.51% in November and 45.88% in December. In 2018, it averaged 27.69% in October, decreased to 24.95% in November, and improved to 26.79% in December, but remained lower than in 2017.
![image](https://github.com/Ananyad7/SQL_StockXsneakersmarket_Project/assets/164981636/2157c78a-5f9b-4795-b2b3-e4cbb747e18d)




Off-white : In 2017, Off-White consistently had strong profit margins in the last quarter of the year, with October at 84.83%, November at 74.27%, and December at 72.99%. In 2018, they maintained relatively high profit margins, starting at 76.82% in October, decreasing to 71.90% in November, and 62.04% in December, still outperforming Yeezy.

# Observations

 
> Yeezy has higher total sales than Off-White; however, Off-White products typically have a higher average sale price than Yeezy products, suggesting that Off-White items are generally more expensive in the market.
> Yeezy product releases have experienced significant growth from 2015 to 2017, followed by a decrease in 2018. Off-White experienced a notable fluctuation in its product release strategy over the three-year period.
> In 2018, there was a significant uptick in orders for both Yeezy and Off-White items. However, in the following year, 2019, orders for both brands decreased. Notably, in 2017, Yeezy received 10,731 orders, a substantially higher number than Off-White's 2,562 orders.
> To maximize sales and inventory management, the brands should focus on popular sizes such as size 10, and consider targeted marketing and stocking strategies for these sizes.
> Off-White has a higher profit margin than Yeezy, possibly because of higher prices, lower production costs, or better cost management. Conversely, Yeezy might have lower profit margins due to higher production or operational costs.
> California and New York seem to be the top regions for both brands, with California having the highest total orders for both Yeezy and Off-White products, and the brands should continue to focus their marketing and distribution efforts in this area. 
> Yeezy and Off-White both show seasonal price trends. Off-White consistently having higher average sale prices indicating its premium image. Yeezy's lowest prices occur in July, suggesting a chance for promotions to boost sales then.
> Off-White had a more favorable profit margin performance compared to Yeezy during the specified time frame. Off-White also saw fluctuations in profit margin, its decline from 2017 to 2018 was less pronounced compared to Yeezy.









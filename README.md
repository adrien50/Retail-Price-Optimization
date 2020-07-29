# Machine Learning project for Retail Price Optimization
## Problem Statement

Pricing a product is a crucial aspect in any business. A lot of thought process is put into it. There are different strategies to price different kinds of products. There are products whose sales are quite sensitive to their prices and as such a small change in their price can lead to noticeable change in their sales. While there are products whose sales are not much affected by their price - these tend to be either luxury items or necessities (like certain medicines). This machine learning retail price optimization project will focus on the former type of products.

Price elasticity of demand (Epd), or elasticity, is the degree to which the effective desire for something changes as its price changes. In general, people desire things less as those things become more expensive. However, for some products, the customers desire could drop sharply even with a little price increase, and for other products, it could stay almost the same even with a big price increase. Economists use the term elasticity to denote this sensitivity to price increases. More precisely, price elasticity gives the percentage change in quantity demanded when there is a one percent increase in price, holding everything else constant.

In this machine learning pricing optimization case study, we will take the data of a cafe and based on their past sales, identify the optimal prices for their items based on the price elasticity of the items. For each item, first the price elasticity will be calculated and then the optimal price will be figured. While this is taking a particular cafe data, this work can be extended to price any product.

## Project Flow
* Understanding the retail price optimization machine learning problem
* Importing Libraries
* Importing datasets and initial understanding with the help of visualizations
* Making inferences from plots
* Implementing model to identify price elasticity of items
* Walkthrough of price optimization for one product and visualizing the outputs
* Creating generic code to identify price elasticity of all items
* Generic code for price optimization for all products
## Conclusion 

we have calculated the price the cafe should set on it's item to earn maximum profit based on it's previous sales data. It is important to note that this is on a normal day. On 'other' days such as a holiday, or an event taking place have a different impact on customer buying behaviours and pattern. Usually an increase in consumption is seen on such days. These must be treated separately. Similarly, it is important to remove any external effects other than price that will affect the purchase behaviours of customers including the datapoints when the item was on discount. Once, the new prices are put up, it is important to continuously monitor the sales and profit. If this method of pricing is a part of a rpoduct, a dashboard can be created for the purpose of monitoring these items and calculating the lift in the profit.

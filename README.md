# Moving from Complexity to Clarity in Supply Chain

This is a supply chain analytics project. In which conducted an analysis of supply chain inefficiencies, and developed informative dashboards to inform business stakeholders of potential issues, along with proposing strategic business enhancements.

## Project Description :
The project provides a real-world dataset focusing on supply chain analytics. As the main data analyst for Just In Time, you will help solve key shipment and inventory management challenges, analyze supply chain inefficiencies, and create insightful dashboards to inform business stakeholders about potential problems and propose structural business improvements.

## Objective 
In this project, my primary focus is on addressing key challenges related to shipment and inventory management within the supply chain. To achieve this goal efficiently, the project has been divided into few objectives:

## METHODOLOGY

Business demand analysis

Requirements: Create dashboard to analyze the business problem and improve the supply chain’s efficiency

Method: descriptive and exploratory analysis

Tool used: Python (Data preprocessing, data cleaning, EDA, inventory segmentation); Tableau (Dashboard)

Business Performance : 

=> Dashboard of overall business performance including Profit & Cost of Products, total profit, best products etc 

Inventory Management :

=> Dashboard of inventory management including warehouse inventory, Supply/Demand by Product Department, Inventory Storage Cost, Most Overstock products, Most understock products etc

Shipment Invenstigation :

=> Dashboard of shipping management including delay shipping like % of delapy orders, overall delay evolution, shupping delay by location, Most deplayed products etc 

Order Fullfillment : 

=> Dashboard of average warehouse inventory fullfilment by Product Category

Overall story of Create an interactive dashboard to summarize the research of the problem of the supply chain and suggest the solution

## Data Pre-Processing & Data Cleaning 

The data pre-procesing and Data cleaning is done using Python. 

## Data Overview 
The dataset provides three data tables including order_and_shipment, inventory and fulfillment. After examining the data fields, I noticed that the dataset generally represents the following key information

Customer: General information about customers including identifiers and addresses

Order: Information about the order including date of order, product and quantity ordered, order value

Shipment: Shipping information including shipping date, shipping mode

Product: Specific information about the ordered item including product name, product category, product department

Warehouse Inventory: Information on inventory management for each product name including monthly inventory, warehouse location, storage costs, order fulfillment

## Key Insights 
**1 Profit & Costs :**
The monthly profit typically ranges from 104,000 to 135,000 dollars. However, there was a noticeable decline in profit from October to December 2017, which requires further investigation due to potential data limitations.

**Most Profitable Product Department :**

Fan Shop : generating approximately $50,000 in monthly profit.
Other top-profit product departments include Apparel, Golf, and Footwear, which also incur the highest inventory expenses.
Most Profitable Products :

Perfect Fitness Perfect Rip Deck
Field & Stream Sportsman 16 Gun Fire Safe
Nike Men’s Free 5.0+
Goods with Highest Profit Margin :

Hirzl Women’s Soffft Flex Golf Glove
Under Armour Women’s Ignite PIP VI Slide
O’Brien Men’s Neoprene Life Vest
Highest Inventory Storage Cost :

Highest Storage Cost Spends in Apparel department
Other top-cost product departments include Golf and Fan Shop
2. Inventory Analysis :
There are some overstock products which basically increasing the storage cost and its demand is less.

**Supply vs Demand :**

Highest demanding product department is Fan Shop, but its supply(inventory) is compared to less.

Below are overstock and overstock products.

**Overstock Product Category :**

Cleats
Shop By Sport
Toys
**Under stock Product Category :**

Indoor/ Outdoor Games
Water Sports
Fishing
**3. Shipment Delay Analysis:**
The average 61% of shipment delay across all orders. Notably, highest delay experiences are USA, France and Mexico.

The period between January 2015 and May 2016 witnessed the greatest number of orders with delays.

Interestingly, one of most profit margin products, Under Armour Women’s Ignite PIP VI Slide, is also products with the highest average Shipment delay.

**4. Order Fulfillment Days:**
Product categories Video Games, Crafts, and Women’s Clothing take 8.8, 7.1, and 6.9 (average) days, respectively, to fulfill their stock into the warehouse.


## Sugesstions 

**Optimize Product Inventory :**
To improve profits and save on storage costs, we need to optimize our inventory, especially for most profitable and popular products worldwide. It is important to study demand patterns and adjust stock levels to avoid running out during peak periods and reduce excess inventory during slower times. Maintaining a reasonable buffer above expected demand during busy seasons can prevent shortages and optimize inventory expenses.

**Reorganize Inventory Distribution :**
The Fan Shop department’s inventory is insufficient compared to its demand, which may result in missed the sales opportunities. The company should take steps to increase inventory
Consider reorganizing inventory distribution between warehouses to reduce shipment delays. Minimizing delays in highly demand products can improve customer satisfaction.

**Marketing Strategies :**
Focus on promoting products with the highest profit margins to increase overall revenue. Consider advertising the top products with the highest profit margins and offer targeted discounts during peak seasons to boost sales and customer engagement.

**Monitor Shipment Delays :**
A further analysis is needed to identify the reasons for shipment delays and implement corrective measures to reduce them. Analyzing shipment processes and addressing potential bottlenecks can lead to improved fulfillment efficiency and customer satisfaction.

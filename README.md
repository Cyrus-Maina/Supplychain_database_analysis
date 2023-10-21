# Supplychain_database_analysis_and_insights

This analysis deduces day to day insights of Herman Traders' supply chain operations, insights meant to streamline the operations to improve efficiency, increase profits and cut costs. 

The dataset consists of supply chain operation entries of Herman Traders, sourced from Kaggle.

The company tasked us to analyze this data and provide meaningful insights   that will help them streamline operations in a measure to reduce costs, maximize profits, improve on time efficiency and enroll more customers.

By the end of the analysis we will provide all these insights and Herman’s will have a new outlook on their day to day operations.

On top of the original fields we added more that expose underlying patterns/statistics such as:

Profits- how much of it each sales channel, team and warehouse generated

Revenues- total income generated by all mediums

Delivery_time- number of days between order and delivery date.This metric tells how long it takes to process and deliver an ordered product.

Inventory_turnover_time- number of days between procure and order date. It tells how many days it took for the product to be bought,an important metric to plot demand of goods to understand the market.

Fulfillment_time- the metric shows how long it takes to process an order in the warehouse i.e., between order and ship date. A warehouse with high Fulfillment_time may require more staff or machinery.

Trucking_time- shows the number of days on the road.

Several fields were dropped e.g., CurrencyCode as it’s uniform across the dataset thus has no significant meaning and _StoreID as well.

We changed all time and money related fields like  ProcuredDate and Unit price from data type string to datetime/numeric format to allow easy manipulation.


**DATA INSIGHTS**

In-Store channel has the highest profits generating $12M and wholesale the least generating $3M, a quarter of In-Store.
This reflects that it is cheaper to do business with the In-store model and Herman’s should strategize on how they would maximize on that and channel as many customers that way.
Warehouse NMK1003 generated the highest profits, $9.7M while WH NBV1002 generated the least at $2.6M. 
This may reflect factors like numbers of customers, delivery time convenience to customers and sales team abilities.

Team 26 generated the most revenues at $3.3M followed by Team 1 at $3.2M. Teams 28 and 27 generated the least at $2.5M and $2.53M  respectively. They are the only teams below the $2.6M mark.

There are only seven teams below the $2.8M mark. Herman’s could enroll the teams on sales training and give incentives to improve morale. It could also roll out a target of $2.8M per team and help the teams get there.

Product ID 23 is the most profitable item to sell generating $908K with only two products generating lower than $530K that is products 44 and 42, a worrying statistic compared to the rest.
Is it that they are low in demand, have high costs of production and what are the costs of selling products 44 and 42 are questions Herman’s should ask to decide on the future of the two products.

In-Store has the least Fulfillment time while Distributor has the highest. 
This helps reflect the inner operations. Herman’s should figure out why Distributor related products take that long to be processed. Most likely, it would be because Distributors may suggest compiling goods till they are enough and supply them at once, cutting costs.

Wholesale has the lowest turnover time (143 days), we could attribute this to the low prices associated with it and the fact that consumers buy in bulk hence the short shelf time.
In-store has the highest turnover at (150 days).
The time difference is so big that it is possible logistical costs increase due to the turnover inconsistency. A solution would be stocking the goods in a manner that anticipates this time difference.

WARE MKL1006 and UHY1004 have the shortest fulfillment time whereas PUJ1005 and XYS1001 have the longest.
 We could ask some questions that will aid in digging deeper like; is there a labor power difference between the wares or does MKL1006 have some warehouse machinery that PUJ1005 lacks or is it better time management?

WARE MKL1006 had the shortest turn over time but the longest Fulfillment time, it can be attributed to the high number of orders to process thus it would be economical to add its labor force or machinery.

PUJ1005 and NMK1003 perform poorly in Turnover and Fulfillment time, it would be worthy to investigate why and assist them accordingly. 

Distributor channels have the shortest delivery time at 85 days whereas online has the highest at 90 days. 
Obviously, distributors perform well due to their large logistical network, if Herman’s could employ such logistical networks for the Online channel, it’s likely revenues will increase due to the customer convenience.
Apparently the two channels with the highest revenues have the longest delivery time count.

In-store has the highest number of customers (83,778) followed by Online(62,253) with Distributor (34,775) and Wholesale (22,621) lagging behind. This insight demands resources to be allocated to each channel to enhance their abilities.
We could attribute In-Store’s  success to customer experience.
Despite this, remember In-store has the highest Inventory turnover  time.


**GROWTH INSIGHTS**

Profits and Revenues have continued to increase (a positive sign) but at a lower pace from 2019-2020 compared to 2018-2019.
Profit rate surged from 66% growth to 1.2% and revenues from 63% to 1.04%.
Herman’s should assess why this dip happened.

We grouped teams into Best (26, 1, 13) and Worst (6, 7, 8) performing to plot their growth so that we can compare them. We deduced Team B  had steady constant growth in 2020 while Team W had dipping sales in 2020.
This insight gives us an opportunity to find means to assist the poor performing teams and assess why they perform so.
Another insight we deduced is the numbers of customers per sales team. We deduced there is a correlation between sales and number of customers. We noted Team B had high numbers of customers compared to Team W.

Products 44 and 42 sales  (worst performing) have been dropping back to back. Herman’s should reassess the value of these products to the market as the declining sales reflect low demand.

With these insights, Herman’s will surely face its supply  chain operations from a different perspective as they know where to exactly fix to cause change.

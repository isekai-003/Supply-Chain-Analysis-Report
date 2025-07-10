# AtliQ Mart Supply Chain Analysis

## Problem statement

AtliQ Mart is a growing FMCG manufacturer headquartered in Gujarat, India. It is currently operational in three cities Surat, Ahmedabad and Vadodra. They want to expand to other metro/tier1 cities in the next 2 years.

AtliQ Mart is currently facing a problem where a few key customers did not extend the annual contract due to service issues. It is speculated that some of the essential products were either not delivered on time or not delivered in full over a continued period, which could have resulted in bad customer service. Management wants to fix this issue before expanding to other cities and requested their supply chain analytics team to track the ’On time’ and ‘In Full’ delivery service level for all the customers on a daily basis so that they can respond swiftly to these issues.

The Supply Chain team decided to use a standard approach to measure the service level in which they will measure ‘on-time delivery (OT) %’, ‘In-full delivery (IF) %’ and OnTime in full (OTIF) % of the customer orders on a daily basis against the target service level set for each customer.


## Data Model 

<p align="center">
  <img src="https://github.com/isekai-003/Supply-Chain-Analysis-Report/blob/0acb0937aac46fd3bfbf91d9491d050607818091/Data%20Modelling.png">
</p>

## Dashboard 

<p align="center">
  <img src="https://github.com/Naveen-S6/AtliQ_Mart_Supply_Chain_Analysis/blob/main/resources/Dashboard.jpg" width="300">
</p>

## Major Insights 

- All the Key Metrics (OT%, IF%, OTIF%) are far behind the target
- On an average, orders are delayed 0.42 days from the agreed date of delivery
- Lotus Mart, Coolblue, Acclaimed stores have the highest orders as well as delayed the most to deliver the products on time 
  - Is it because we are not estimating the right delivery date?
  - Is it because we are receiving more orders than expected?
- Ghee, curd and butter products are most delayed to deliver. 
- There is no noticeable improvements in any of the key metrics in the last few months
- There is a huge gap in IF% for most of the customers. Is it because of less production?

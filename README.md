# FMCG Supply Chain OTIF Analysis

## What is this project about?
I analysed over 180,000 supply chain shipment records to measure OTIF performance, which stands for On Time In Full. This is one of the most important delivery metrics used by FMCG companies like Nestle, Unilever and PepsiCo. The goal was to find out why so many orders are failing and where the biggest problems are.

## The Problem
After analysing the data, I found that only 21% of orders were delivered on time and in full. That means 79% of orders failed. This causes serious problems for any business including retailer penalties, lost sales and damaged relationships with customers.

## Tools I Used
- Microsoft Excel for data cleaning, analysis and dashboard
- Functions used: COUNTIF, COUNTIFS, IF and AND formulas
- Data source: DataCo Supply Chain Dataset from Kaggle (180,000+ records)

## What I Found
- Only 21% of all orders met OTIF criteria
- Standard Class shipping had the most orders at 107,752 but poor OTIF performance
- Second Class shipping performed best across all shipping modes
- South Asia and Eastern Asia were the strongest performing regions
- Central America and South America had 0% OTIF which means every single order failed
- Men's Footwear had the best OTIF rate across all product categories
- Water Sports and Indoor/Outdoor Games had 0% OTIF

## My Recommendations
1. Urgently investigate Central America and South America as both regions show complete delivery failure
2. Review First Class shipping since it costs more but delivered 0 successful OTIF orders
3. Use Men's Footwear fulfilment process as a model for other categories
4. Set a minimum OTIF target of 85% for every region and review it every month
5. Find out what is causing Water Sports and Indoor/Outdoor Games to fail completely

## How the Excel File is Structured
- RAW DATA tab: original dataset untouched
- WORKING DATA tab: cleaned data with OTIF Status and Delivery Gap columns added
- ANALYSIS tab: summary tables showing OTIF by Shipping Mode, Region and Category
- DASHBOARD tabs: bar charts showing performance visually

## About Me
Built by Mahnoor Jabeen, aspiring Supply Chain and Logistics Analyst 
LinkedIn: https://www.linkedin.com/in/mahnoor-jabeen/ 

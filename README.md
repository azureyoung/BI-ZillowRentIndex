BI-ZillowRentIndex

This project is to provide a business intelligence solution to present and analyze Zillow rent data.

BI tools in this project :SQL server 2016, SSIS and SSRS.

The original dataset was downloaded from Zillow research data

The original data were exported, combined, transformed, cleaned and loaded into respective staging tables in SQL server by SSIS. The data warehouse/marts were constructed by dimensional model.

The analyzed data were reported by SSRS using stored procedures wrote in SQL server.

With this BI solution, the rent data can be checked and analyzed basing on price, year and location. The rent data can be presented in formats such map, chart and table. It can help to answer questions such as what city has the highest and lowest rental prices in the country? which metropolitan area is the most expensive to live in? Where have rental prices increased in the past five years and where have they remained the same? What city or state has the lowest cost per square foot? The examples were presented in the powerpoint document named BI-ZillowRentIndex.

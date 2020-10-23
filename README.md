# kickstarter-analysis
Performing data analysis on Theater and Play outcomes

## Overview of Project
This project provides launch outcomes for Theater based on launch month, as well as launch outcomes for Plays based on goals.

### Purpose
The project provides two purposes. First, it allows users to analyze the successful rate, failed rate and cancelled rate for Theater launch based on month across years. Second, it provides insight to one of the theater subcategories Plays based on different goal ranges.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The analysis is performed using Pivot table, Pivot Line Charts, as well as utilizing filter function in Pivot table. And Microsoft Paint is used to save the image. 

### Analysis of Outcomes Based on Goals
The analysis is performed using Pivot table, Pivot Line Charts, combined with formulas including COUNTIFS and SUM. And Microsoft Paint is used to save the image.

### Challenges and Difficulties Encountered
The challenge is when editing the COUNTIFS function, I need to pay close attention to ensure all the manual inputs are correct for all cells. 

## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
  - May is the month with highest successful amount; In general, the launch tends to be more successful in summer from May to August; 
  - It’s not recommended to launch theater in December as the total of failed and cancelled theater is over the successful ones. 

- What can you conclude about the Outcomes based on Goals?
  <br /> When the price is set below 4999, the successful rate is the highest; we do not recommend going over 45000.

- What are some limitations of this dataset?
  - Theater outcome can also be impacted by the theater environment and actors’ quality in each country;
  - by only showing months for Theater outcome, it didn't distinguish between the year that had financial difficulties

- What are some other possible tables and/or graphs that we could create?
  - We can conduct analysis on theater outcomes based on countries and identify the countries with top 10 successful launch rate. 
  - We can also build a table based on staff pick so that we can verify if the ones that got a “staff pick” will indeed have a higher successful rate.

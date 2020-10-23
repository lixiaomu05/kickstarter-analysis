# kickstarter-analysis
Performing data analysis on Theater and Play outcomes

## Overview of Project
This project provides launch outcomes for Theater based on launch month. It also provides launch outcomes for Plays based on different goal ranges.

### Purpose
The project provides two purposes. First, it allows users to analyze the successful, failed and cancelled numbers of Theater launch based on month across years. Second, it provides analysis on the launch outcome on one of the theater subcategories, Plays, based on different goal ranges.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The analysis is performed using Pivot table, Pivot Line Charts, as well as utilizing filter and sort function in Pivot table. And Microsoft Paint is used to save the image. The Pivot Table shows a breakdown on the successful, failed and canceled event in numbers and provides a comparision across 12 months.

### Analysis of Outcomes Based on Goals
The analysis is performed using Pivot Line Charts, combined with formulas including COUNTIFS and SUM. And Microsoft Paint is used to save the image. The Pivot Chart is constructed on a data table by breaking down the goal into 12 ranges and comparing the percentage of successful and failed among the ranges.

### Challenges and Difficulties Encountered
The challenge I encountered when editing the COUNTIFS function is that I had to pay close attention to ensure all the manual inputs are correct for all cells. 

## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
  - May is the month with highest successful event in number; In general, the launch tends to have more successful number in summer from May to August; 
  - It’s not recommended to launch theater in December as the total of failed and cancelled theater is over the successful ones. 

- What can you conclude about the Outcomes based on Goals?
  <br /> When the price is set below 1000, the successful rate is the highest at 76%; it is not recommended to go over 45000 or go between 25000 to 34999, where the successful rates are below 30%. 

- What are some limitations of this dataset?
  - Thearter outcome based on launch date only shows numbers of successful, failed and canceled outcome, it doesn't show the percentage of outcomes, making it hard to compare in relative term;
  - Theater outcome can also be impacted by the theater environment and actors’ quality in each country, month is not the single factor that determines the successful rate

- What are some other possible tables and/or graphs that we could create?
  - We can conduct analysis on theater outcomes based on countries and identify the countries with top 10 successful launch rate; 
  - We can also build a table based on staff pick so that we can verify if the ones that got a “staff pick” will indeed have a higher successful rate.

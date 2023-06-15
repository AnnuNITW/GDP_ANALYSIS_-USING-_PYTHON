# GDP_Analysis_-using-_Python 
Gross Domestic Product (GDP) is a measure of the size and health of an economy. It represents the total value of all goods and services produced within a country over a specific period of time, usually a year. GDP is considered a key indicator of a country's economic performance and is used to compare the economic output of different countries.This project focuses on analyzing growth rate of different Countries.


Table of Contents:
> Importing Dependencies ,
> Data Description ,
> Data Cleaning ,
> EDA Steps ,
> Conclusion 

Importing Dependencies:
we have imported following python libraries Pandas,Plotly,Seaborn,Matplotlib.

Data Description :
The dataset used for this analysis contains GDP data for a specific period.The data is provided in CSV format and includes the following columns:
> Country Name ,
> Country Code  ,
> Year  ,
> Value

Data Cleaning:
In our dataset no null values is present .

EDA steps:

Dataset walkthrough: 
In this section we analyzing columns of data using describe() , min() ,max() functions.

Now we create line graph  between Year and Value by using plotly library of 'Arab World' and analysing 'Arab World' GDP growth.

GDP Growth on whole Dataset:

GDP growth refers to the percentage change in GDP from one period to another. For example, if a country's GDP in one year was 100 and the next year it was 105, the GDP growth rate would be 5%.
It is not clear what you mean by a "whole dataset" in this context. If you have data on GDP for a particular country or region and want to calculate the GDP growth rate, you can do so by using the formula:
GDP growth rate = (GDP in current period - GDP in previous period) / GDP in previous period * 100

For example, if a country's GDP in 2020 was 100 and in 2021 it was 105, the GDP growth rate would be calculated as follows:
GDP growth rate = (105 - 100) / 100 * 100 = 5%

Now we can plot a line graph using plotly library between GDP Value and Year of
> World ,
> India ,
>  India | China ,
>  India| USA | ITA |China  ,
>  All countries  ,
and  plot GDP growth between 1960-2016  so after analyzing these we get some conclusions.

Conclusion: 
 At last we can see by comparing GDP across countries in our Dataset ,GDP of 'World' Country growing higher than all countries. when we compare GDP of 'China' and 'India' we can see GDP of China grew much faster than the India.
 




 





# Data-Analysis-Using-Pandas
This project aims at analysing covid data and Indian gross domestic price data by using Pandas. Covid data and Indian gross domestic price data were analyzed. Chart analysis was performed and insights were provided

## Why Pandas?
Pandas provides tools for reading and writing data to data structures and files. It also provides powerful aggregation functions for data manipulation. Pandas provide advanced data structures to store different types of labeled and relational data. This makes Python very flexible and extremely useful for data cleansing and manipulation.

## Requirements
- pandas

## Following steps are involved:

1. Read the excel file using read_excel() method and fill the NA(not available)data  with 0.

2. Select the rows and coloum data that needs to be compared by usig loc or iloc attribute

3. Plot the graph for selected columns using Dataframe.plot.(graph_name)

##  Data analysis for Covid data
1. Below bar graph compares the types of Covid cases in top 10 countries of the world.

 ![covidbar](https://user-images.githubusercontent.com/115713117/222389906-a66c3b34-7d5b-4566-ac03-d5c560782a62.PNG)

 Insights:
 Among top 10 countries, USA has highest number of cases and Russia has lowest number of cases. Japan has highest number of active cases. 

2. Below stacked bar represents the comparision of total death and recovered cases in top 10 countries of the world.

![image](https://user-images.githubusercontent.com/115713117/222391777-23da2320-3cc8-49b6-8036-5f1537c3ed22.png)

Insights:
Total recovery and death cases  are highest in USA whereas the japan has lowest number of deaths.

3. Below pie chart represents the covid impact rate in  top 10 countries of the world.

![image](https://user-images.githubusercontent.com/115713117/222392677-67763081-4fcf-4b5a-838b-06b796e45839.png)

Insights:
USA have high covid impact rate when compared to other countries with 26.2%. Russia have less covid impact rate with 5.5%.

## Data analysis for Indian gross domestic price data
1. The graph represents comparision of Indian GDP and per capita over the 10 years

![image](https://user-images.githubusercontent.com/115713117/222395996-a3745553-8c67-487c-9812-1030a97f7567.png)

Insights:
Over the the years Indian gross domestic product price and per capita have increased significantly.

2. The following graph represents annual growth rate over the years

![image](https://user-images.githubusercontent.com/115713117/222397317-741e099d-a7b4-490b-ba6c-b3429a2a786e.png)
 
 Insights:
 Annual growth rate was highest in the year 2021 and lowest during the year 2020.
 





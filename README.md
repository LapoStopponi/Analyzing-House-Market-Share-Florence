# Analyzing-House-Market-Share-Florence

## Introduction
Everyone who has ever approached the Real Estate market knows that finding the right house to buy is no easy job. A friend of mine was struggling to find the right solution for him, so I jumped in and helped him out. He was interested in a house with 4 bedrooms, 
and he also didn't want to overpay it. To help him, I conducted an analysis and shared the results with him. Below, you can find how I did it.


## Background
There were multiple questions I wanted to answer in order to help my friend. He wanted to know:
1. What is the Neighborhood with the lowest Price per square root?
2. What's the median price we should expect to buy a house in Florence for?
3. Which House types are on the market, and how many of each type are available?
4. What's the median price per square meter for each house type?
5. In which neighborhood is the biggest pool of houses available?
6. Is there a correlation between the Median Price and the Median Area?

## Tools I used
For my deep dive into the Real Estate market, I harnessed the power of several key tools:
-**RowsX**: I used this Chrome extension to data scrape the data that I needed from the Real Estate portal, Idealista.
-**Excel**: I then loaded the data into Excel's Power Query, to clean the data and transform it to my needs. The Main cleaning jobs were: removing duplicates, creating new columns to specify metrics, and transforming data types.
-**Power BI**: The chosen data visualization tool, ideal for showcasing my discoveries

## The Analysis
1. To answer the first question, "What is the Neighborhood with the lowest Price per square meter?", I created a chart in Power BI.
 ![Neighborhood price Analysis](https://github.com/user-attachments/assets/b4e201d9-b1b3-47b6-9ff9-bafe55230ddf)
It came out that the Neighborhood with the lowest price per square meter is Peretola, with a Price per square meter of  €2864,08.
But my friend is looking for a 3 bedroom, and things change, in that case, as you can see from this graph.
![Median Price per square meter by neighborhood 3 bedrooms](https://github.com/user-attachments/assets/4e644eb7-6768-4b42-85e2-1ba133bf25e6)

3. What's the median price we should expect to buy a house in Florence for?


![median price per house in Florence](https://github.com/user-attachments/assets/e5d92391-5567-412d-9f9c-739d5ae45fe6)


The median price we should expect to buy a house in Florence is €390000.

3. Which House types are on the market, and how many of each type are available?

![Number of houses per house type](https://github.com/user-attachments/assets/132f24be-32da-4cf4-b2a2-03ee0e37041a)

There are 12 house types on the Market, the most available type in terms of quantity is "Appartamento" (Apartment), which is 27,53% of the total. 

4. What's the median price per square meter for each house type?

![Median price per m2 by house type](https://github.com/user-attachments/assets/73e37278-b28c-4f3f-b04b-cf7b284254f2)

The house type with the highest Median Price per square meter is Attico, with €5.000 as the median price per square meter. The lowest median price per square meter goes to Casale/Cascina.

5. In which neighborhood is the biggest pool of houses available?

![Number of houses per Neighborhood](https://github.com/user-attachments/assets/ec7794fc-52a9-414f-b3ed-36865a632ccf)

Novoli Baracca is the Neighborhood with the highest number of houses available on the market.

6. Is there a correlation between the Median Price and the Median Area in different Neighborhoods?

![relationship median price and median area](https://github.com/user-attachments/assets/f8d3cb7e-5dc8-4e4b-ba1a-79882ba5d47a)

![Median price per 3 bedrooms by neighborhood](https://github.com/user-attachments/assets/fe433bf3-78d6-4a0c-b45a-9b01d42e4e31)


To determine if there is a correlation between the Median Price and the Median Area of the houses in different Neighborhoods, I carefully analyzed the graph. There is a general trend when neighborhoods with higher prices tend to have larger median areas, and vice versa. Neighborhoods on the left side of the graph, show both high prices and high median areas. Neighborhoods on the right side of the graph, tend to have both lower prices and lower median areas. There are some exceptions to this general trend, where the relationship between Price and Area doesn't perfectly follow the pattern. Based on this observation, I can conclude that there is a positive correlation between the median price and the median area of properties across different neighborhoods. However, the correlation is not perfect, suggesting that factors other than size influence property prices in various Neighborhoods. To quantitatively confirm this correlation, it would be necessary to calculate a correlation coefficient using precise numerical data. In the neighborhood where the Median Area is relatively higher than the Median price, the houses might be more convenient in space/price terms. Some examples would be Due Strade - Ponte all'Asse, San Jacopino, Isolotto. In these Neighborhoods, you could theoretically get more space for your money rather than in other neighborhoods, with a higher price/area rate. But we should also consider that this analysis is based only on the median data, it doesn't necessarily apply to all the properties in the Neighborhoods. And also the value of the house doesn't depend solely on the dimensions, but on other factors too. 


## What I learned
Through this project, I've enhanced my Excel And Power BI toolkit:
 - **Power Query Measures**, Mastered Power Query Measures, creating the necessary ones to complete my project.
 - **Data Cleaning**, Improved my data cleaning skills.
 - **Data Visualization**, Improved my data visualization skills, and my knowledge of Power BI.
# Conclusion
From the analysis, several insights that could help my friend emerged: 
First of all, we have to consider that the Median price per square meter in Florence is 3900 euros, but he was looking for a 4 bedroom, and the Median price per square meter per a 4 bedroom in Florence is  €3750. The Neighborhood with the lowest price per square meter is Peretola, with a price of  €2864,08. He was looking for a 4 bedrooms. If we apply this filter we can see that the lowest price per square meter for a 4-bedroom is actually not in Peretola but in Novoli-Parco di San Donato. This could be a good solution for him, but we also have to consider other factors. Of all the Houses on the Real Estate Market in Florence, only 21 are in the area in question, and of these, only 5 have 4 bedrooms. So, there isn't much choice. I then made a comparison between the Median Price of the Houses and the Median Area to look for some hidden gems, where the Median Area is relatively higher than the Median price. To this graph, I applied a filter to show me these values for 4-bedroom houses. I noticed that it wouldn't be very convenient for him, since the Median Area is almost way lower than the Median price. I try to decrease one by one and increase by one, and I've noticed that there are great deals for 3 bedrooms, in almost all the neighborhoods. With some of these houses having a bigger Median Area despite having a room less. In conclusion, if my friend really needs a 4 bedroom and is looking for the cheapest option he should go for one of the 4 bedrooms in Novoli-Parco di San Donato, if instead, he can make a 3 bedroom work, space-wise, he will probably get a better deal for the Median Area. This said, there are many other factors that we didn't take into consideration in this project, in order to choose the best house for you. 
## Closing thoughts
This project enhanced my Excel,Power Query, and Power BI skills and provided valuable insight into the Real Estate Market in Florence. 

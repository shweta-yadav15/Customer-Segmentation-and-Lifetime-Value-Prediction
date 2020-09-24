## Background

E Commerce industry is forecasted to double in size within the next two years and grow from 3.53 trillion US dollars in retail ecommerce sales in 2019, up to 6.54 trillion US dollars in 2022. The key drivers of success over the next decade will be centered on building a deep understanding of and connection to the empowered consumer, and the only way to understand consumer behavior is to measure and analyze. 

## Motivation

This project deals with many real-world challenges faced by e-commerce websites that includes predicting customer lifetime value using RFM score and k-means clustering, customer segmentation to find out best valued customers. Also, predicting review score that customers will give to their order experience depending on their location, order cost and other factors. I have also done a detailed analysis of how geolocation can affect user's experience and their purchase and much more.

## Dataset

Brazilian ecommerce public dataset of orders made at Olist Store. The dataset has information of 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil. Its features allows viewing an order from multiple dimensions: from order status, price, payment and freight performance to customer location, product attributes and finally reviews written by customers. Also included is a geolocation dataset that relates Brazilian zip codes to lat/lng coordinates.

This dataset have nine tables which are connected with few common attributes. [Dataset Link](https://www.kaggle.com/olistbr/brazilian-ecommerce)

## Project Overview
The project is divided into two parts:
1. Analysis and Visualizations- Detailed anaysis, understanding metrics and graph plotting
2. Predictions- Customer lifetime value prediction, predicting customer satisfaction and segmentation

# Part 1: Analysis
Few instances of the analysis performed are as follows:

![Overall_Study](https://user-images.githubusercontent.com/33171500/93948439-b14fa880-fcfb-11ea-84af-6e86ebf28120.png)


![Overall_Study](https://user-images.githubusercontent.com/33171500/93949050-32f40600-fcfd-11ea-8a44-2dbbab31dec0.png)


* There is an upward trend in orders purchased between January 2017 and July 2018.

![Overall_Study](https://user-images.githubusercontent.com/33171500/94201775-b470a300-fe79-11ea-9a28-f1ce486a3e37.png)

* Unfortunately, customers who live in the north and northeast of Brazil has to bear with higher freight costs and has to wait longer to receive their purchase.

![Overall_Study](https://user-images.githubusercontent.com/33171500/94201805-bcc8de00-fe79-11ea-8ce8-b1f2765baa78.png)

* The consequence of late delivery is that the customers in north side are likely to give lower reviews.

![Overall_Study](https://user-images.githubusercontent.com/33171500/94201827-c4888280-fe79-11ea-9f82-d89287ebe4ae.png)

* Most of the revenue is coming from the Southeast and South regions of Brazil. Also, large cities and capitals, where population is bigger, have larger participation on revenue.

![Overall_Study](https://user-images.githubusercontent.com/33171500/94201844-ca7e6380-fe79-11ea-9c92-f567882fd6c9.png)

* Monthly retention rate shows whether customers continue to buy products from the website r not. There is an upward linear trend here but with few major exceptions.

![Overall_Study](https://user-images.githubusercontent.com/33171500/93948977-0809b200-fcfd-11ea-9fc3-f4d1d4260d97.png)

* Even here monday blues are showing effects. Customers seem to most likely buy on Monday then any other day of the week.

![Overall_Study](https://user-images.githubusercontent.com/33171500/93948981-093adf00-fcfd-11ea-8c33-4bfd19192380.png)

* Afternoon boredom is making customers buy items mostly in afternoons.

![Overall_Study](https://user-images.githubusercontent.com/33171500/94202035-20eba200-fe7a-11ea-8aeb-63dca33cc5c0.png)

* Company seems to be doing well in terms of delivery time since most of the orders are getting delivered way before they are expected.

![Overall_Study](https://user-images.githubusercontent.com/33171500/93949045-31c2d900-fcfd-11ea-85a9-14a4ee60614b.png)



























```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).


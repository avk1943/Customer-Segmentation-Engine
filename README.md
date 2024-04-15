# Customer-Segmentation-Engine

Data Science Project for Marketing Analytics

This project aims to segregate customers into different groups for further identification and analysis of spending behaviors. These behaviors can serve different marketing strategies for different groups of customers.


## Getting Started

Make sure you have the following libraries installed for local run of project

* pandas
* numpy
* seaborn
* scikit
* dabl

### Exploratory Data Analysis

The Customer Dataset was analyzed in the following ways to gain better understanding:-

* Distribution of Annual Income and Age - There are few people who earn more than 100K US Dollars. Most of the people have an earning of around 50K-75K US Dollars. Also, most regular customers for the Mall are around 30-35 years of age. 
* Gender Distribution of the Customers - Females are in the lead with a share of 56% whereas the Males have a share of 44%, which is a huge gap considering that the population of Males is comparatively higher than Females.
* Age Distribution of Customers - People of age 55, 56, 69, 64 are very less frequent in the malls. People at age 32 are the most frequent visitors in the Mall.
* Distribution of Annual Income - There are customers in the mall with a very much comparable frequency with their Annual Income ranging from 15K US Dollars to 137K US Dollars.
* Distribution of Spending Score - Most of the customers have their Spending Score in the range of 35-60
* Spending Score for Each Gender - Most of the males have a Spending Score of around 25K US Dollars to 70K US Dollars whereas the Females have a spending score of around 35K US Dollars to 75K US Dollars
* Annual Income for Each Gender - There are more number of males who get paid more than females. But, the number of males and females are equal in number when it comes to low annual income.

### Clustering Analysis

Clusters of Customers who share similar similar behavior are created for specialized marketing campaigns. For this purpose, the K-Means algorithm is utilized. 

#### Clustering between Annual Income and Spending Score

![image](https://github.com/avk1943/Customer-Segmentation-Engine/assets/47321440/a0be5d07-0ada-46b9-b1b4-85d829d6ca75)

The Clustering Analysis gives us a very clear insight about the different segments of the customers in the Mall. There are clearly Five segments of Customers namely Miser, General, Target, Spendthrift, Careful based on their Annual Income and Spending Score which are reportedly the best factors/attributes to determine the segments of a customer in a Mall.

#### Clustering between Age and Spending Score

![image](https://github.com/avk1943/Customer-Segmentation-Engine/assets/47321440/c3a03a54-20d0-45d3-8ca1-b14cd606d550)

By looking at the above clustering plot between the age of the customers and their corresponding spending scores, we have aggregated them into 4 different categories namely Usual Customers, Priority Customers, Senior Citizen Target Customers, Young Target Customers for various marketing strategies.


### Conclusion

Since sustomers have different needs, it’s not wise to serve all customers with the same product model, email, text message campaign, or ad.. A one-size-for-all approach to business will generally result in less engagement, lower-click through rates, and ultimately fewer sales. Customer segmentation is the cure for this problem.

Customer segmentation improves customer experience and boosts company revenue. Finding an optimal number of unique customer groups will help you understand how your customers differ, and help you give them exactly what they want. 

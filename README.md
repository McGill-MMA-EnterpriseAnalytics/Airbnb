# Overview

Airbnb operates an online marketplace for lodging, primarily homestays for vacation rentals, and tourism activities. It allows people (hosts) to list their propoerties for short-term rentals and earns money through the commission for each booking. The business model is based on the idea that these rentals are cheaper than hotels, making the company a threat to hotel industry. The value proposition to hosts is side income, while for the guests it is cheaper accomodation.

The market of these short-term rentals in cities such as New York is highly competitive because renters are presented with a broad range of selection of listings for their specific criteria. Since Airbnb is a marketplace, the dynamics of marketplace have a huge influence on the the amount a host can charge on a nightly basis. This is in fact one of the biggest challenges for the hosts: deciding the prices for their listing. If they charge above the market place, they will lose out on revenue as the renters will most liklely find another affordable alternatives. If the price is set too low, then they again lose out on profits. Additionally, renters may lose out on the opprtunity to live at a great place.

For this project, our goal is build a regression model that can accurately predict the price of the listing, which will:
1) Help existing hosts adjusts their prices
2) New hosts decide on a price

Additionally, the machine learning algorithms will provide insight into what factors influence the pricing of these rentals. If they are something that can be controlled by the hosts, then they can use the insights from this analysis to improve those factors and provide better accomodation to guests. For the scope of this project, we will only be looking at properties in New York considering that New York is a highly competitive marketplace for Airbnb. We will also be seeking to answer the following hypotheses by performing Causal ML:
1) Does the 'Starbucks Effect' affect the price of Airbnb listings?
2) Does the distance to the nearest metro station affect the price of Airbnb listings?

We used the following techniques for this project: 
1) Advanced Imputation Techniques
2) Feature Engineering 
3) Auto ML 
4) Used ML flow (on Databricks) for hyper parameter tuning. 
5) Semi Supervised learning - for practice purpose (Not in final notebook file as it wasn't used in the analysis)
6) Unsupervised learning: A and autoencoder - for practice purpose
7) Making a user-interface on Python 
8) Using Docker to containerize the model 
9) Use of Gitflow functions - pull requests, merging branches etc

The Airbnb dataset that we have used is from: http://insideairbnb.com/get-the-data.html

Starbucks Data was obtained from: https://www.starbucks.com/store-locator?place=New%20York%2C%20NY%2010001%2C%20USA

Metro Data was obtained from https://catalog.data.gov/en/dataset/nyc-transit-subway-entrance-and-exit-data

The team consists of:  
Eunice Worifah - Data Scientist  
Fandi Yi - Data Scientist  
Pascal Nguyen Tang - Product Manager  
Shivangi Soni - Data Analyst  
Vivek Saahil - Business Analyst  

In this branch you can find the following files: 
1) Final Netbook File - This file consists of all the pre-processing, data exploration, AUTO ML, feature engineering, regression models, ML flow and UI interface code.  
2) Gifs for UI - to show prototype of our UI
3) Docker File - A docker file has been created and deposited in the repository. A requirements file (called requirements.txt) containing all the packages and adequate versions to run the models has been created. These documents are needed to run the Docker image on which instances of the model will be run.

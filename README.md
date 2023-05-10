# Steam-Price-Predictor
Steam Price predictor using ml.

A project based on python and machine learning to predict future price for items available on steam(gaming platform) community market.

Objective- To help the gamers who used to invest in virtual items of popular games like Counter-Strike..With the help of this machine learning model we will know which item price will increase or decrease with time. This will help the people who are willing to invest in these virtual in-game items which has aesthetic value.

In this version, the development of code is done using google colab notebook, hence it will be compatible in colaboratory notebook. 30 items(Cases and sticker capsules) added till now. First, the item price history data is scraped from the steam community market website using python script. Then the two machine learning models namely, linear and polynoial regression are implemented over the dataset scraped from the website. After running the model, on giving a future date to the model it can predict the price of the selected item for future and we can know whether it price will grow or decrease in future. Hence, it help us to gain profit by helping us to invest in right item.

Version 1
A college project for final year. Steam Price predictor using ml. This is first version of the project. This project has a scrapper that do web scraping of nearly 30 items available on steam community market. Takes their price history dataset and stores it in a csv file. Then we use the data set to perform regression and predict the price of the item using linear regression.

Version 2

I have added one more model using same date varaiable as x value but this time using polynomial function.
Also shown why quantity sold can't be taken as an attribute for price prediction.
Created two prediction function one which predicts on linear model using date as x and price as y.
Other uses polynomial model using date as an attribute and price as y value.

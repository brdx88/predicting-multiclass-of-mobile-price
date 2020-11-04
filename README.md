# Predicting Mobile Phone Price Range
A man named Bob has started his own mobile company. He wants to give tough fight to big companies like Apple, Samsung, etc. 
He does not know how to estimate price of mobiles his company creates. In this competitive mobile phone market you cannot simply assume things. To solve this problem he collects sales data of mobile phones of various companies.
Dataset from [Kaggle](https://www.kaggle.com/iabhishekofficial/mobile-price-classification?select=train.csv).


## Problems
1. What is the relation between features of a mobile phone and its selling price range?
2. Is it possible to make Machine Learning model to predict mobile phone price range?

## Goals
1. Find out what's the relation between features of a mobile phone and its selling price range.
2. Make a Machine Learning model to predict price range for the mobile phone to assist Bob sell his phones.

# Conclusion
1.  Higher the RAM, higher its price.
2. RAM has the highest coefficient to the price range. Means that mobile phone's RAM is affecting in predicting price range. Besides RAM, there are battery power, pixels resolution and internal memory that affect mobile phone's price.
3. The average of RAM of phone which sold is about 2 GB of RAM with its internal memory 32 GB and clock speed about 1,5 GHz quad-core. And also with battery power about 1200 mAh.
4. The best Machine Learning model's accuracy is 0.98 of 1.00 with Support Vector Machine Classifier algorithm.

# Recommendation
1. Mr. Bob can actually can build and sell his phones with the minimum specification like 2 GB of RAM, 32 GB of internal memory, quad-core 1,5 GHz, and the battery power minimum 1200 mAh.
2. If Mr. Bob hesitated by the price range, he does not have to worry because he can use Machine Learning model to predict whether his phone could have a price range level 0, 1, 2, or 3.

# MLProject4

## 1: Business Case

Question: Given stock market data from previous days, is it possible to predict what it will look like tomorrow evening?

We believe that it is an interesting question because naturally, while you can see what the stock prices are when you wake up, if you're able to predict what they will look like later on in the day, it's possible to game the system in a sense. From our standpoint, if we're able to do so, we could potentially play the stockmarket. It's a pipe dream but it's also an interesting experiment.



## 2: Data
What we use as a datasource is the website Quandl, which has a ton of stock market data that we can make use of to predict the stockmarket in terms of price.

Specifically, we're using the End of Day stock prices that quandl have available to us.

The method used to download the data is as follows:

quandl.ApiConfig.api_key = 'ssEweszzyQvwu_nC-yuv'

quandl.get('EOD/HD')

## 3: Data content and Format

The data that we use come from the end of previous days in Quandl's database. This means that we have data matching previous evenings, where the stock prices have "stabilized". Because of this, we should be able to reliably predict what the price will end up tomorrow evening, and so on and so forth.

The models that we want to attempt to use are as follows:

Logistic Regression

Support Vector Machine Classifier

Decision Tree classifier

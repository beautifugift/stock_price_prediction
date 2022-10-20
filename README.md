# stock_price_prediction
The project is for predicting SP 500 tomorrow price given historical data
The model has been back tested on 20 plus years of historical data in order to be confident with the prediction that it is making

We want to buy stock when the price is down. an algorithm is created to know when the price will go up or down tomoorrow,
based on the data today.

We will be looking at working with minimum risk, This is to make sure that when the algorithm predicts the price will go up it eventually 
goes up. We will maximize Our true positive rate, These are days when the stock price goes up.

to achieve this, we need to minimize the false positive rate when the algorithm says the price will go up however, it actually
goes down. We will be using this as the error metric

Presition is the true positive rate divided by false positive rate plus true contant rate.

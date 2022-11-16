# Cryptocurrency-Prediction-using-LSTM

The most rapidly developing market in the modern world is cryptocurrency, which is regarded as the financial industry's next big thing. Cryptocurrencies are a great study topic because of the vast quantity of data available and the complex architecture that supports them, making it simple to share and straightforward to gain a thorough understanding of their worth. machine learning for predicting.
Deep learning has recently advanced, and it has become clear that employing deep learning is one of the greatest methods for forecasting cryptocurrency values. In this study, it has been demonstrated how LSTM networks are an improvement over the prior approaches (regression, conventional neural networks, and basic recurrent neural networks) and how they can be used to forecast the price of any cryptocurrency.


OVERVIEW OF DATA
The data being used for this project is historical data of everyday, we use an api call in our model to get the data from the server.


The dataset contains of five major headings and they are as follows:
Open Price - This price is the day's commencing price for the market.
Close Price - It is the currency market's closing price on that given day.
High Price - The currency value is at its peak of the day.
Low Price - It is the day's cheapest rate for currencies.
Volume - The amount of currency traded on that particular 



LSTM ALGORITHM
LSTM stands for long short term memory, due to problem that the recurrent neural networks had was that they didn't have a long memory to remember things.
For example there are two sentences,


Today, due to family and job status, I need to take a loan.
Last year,  due to family and job status, I had to take a loan.
In the above two statements to predict the word need in the first sentence  the algorithm needs to remember the word “Today”, which in traditional RNN is not possible due to the layers that are formed with time. 

LSTM helps us solve this problem as it is the advanced version of RNN, the traditional RNN having the short term memory and additional to it we add a long term memory in which we store only the keywords that we need to remember inorder to make the prediction.
In order to judge whether to discard the long term memory keywords or to keep and add more long term memory keywords we need to do this during the training of our model.

Each LSTM layer may access the data from both the layer below it and the one above it using specific gates. The data is sent through the LSTM cells after passing through a number of gates (such as the forget gate, input gate, etc.) and different activation functions (such as the tanh function, relu function). The key benefit of this is that it gives each LSTM cell the ability to retain patterns for a limited period of time. It should be highlighted that the LSTM may recall crucial information while simultaneously forgetting unimportant information.

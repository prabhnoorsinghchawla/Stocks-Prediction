<h2>STOCK CLOSING PRICE PREDICTOR</h2>
This project predicts the closing stock price for different companies (like Google, Facebook, Microsoft) using Machine Learning. The application is developed in Jupyter Notebook using an artificial recurrent neural network called Long Short Term Memory (LSTM). The application uses key libraries such as Keras (Tensorflow), sklearn, numpy and pandas. Feel free to check out the Stock Predictions.ipynb file to see how the application works. I have used the stocks of Google as an example to demonstrate and have included the results in the form of visualization as well.

<h2>LONG SHORT TERM MEMORY(LSTM)</h2>
The main learning from the project came from the Machine Learning tools and how effective it is in predicting stocks. For the project U used a Recurrent Neural Network(RNN) called Long Short Term Memory (LSTM).LSTM is a really powerful RNN while predicting sequence problems as they store the past information to predict outcomes. This is important in this project as the previous price of a stock is crucial in predicting its future price.For the project I used the past 100 days stock values to determine the 101th day stock price.

<h2>RESULTS FROM THE PREDICTIONS</h2>
After running the test data on the LSTM model, the predictions were pretty close to the actual readings. As you can see in the graph here, the predicted and the actual values are going hand in hand.

![This is a graph of the predictions made on the test data](https://github.com/prabhnoorsinghchawla/Stocks-Prediction/blob/master/graph.png)

After developing the whole model, I predicted the stocks from today and compared them with the actual value. Here is the result from that.

![This is a graph of the predictions for today and the actual value](https://github.com/prabhnoorsinghchawla/Stocks-Prediction/blob/master/present_day.png)
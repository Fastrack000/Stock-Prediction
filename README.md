# <p align = 'center'>Stock Price Prediction Using RNN </p>
### Overview Of Project:
<p align = 'center'>
    <b>
        <i>Stock Price Prediction using machine learning helps to discover the future value
of company stock on stock market. The benefit of predicting the value of stock
is to gain more profit from the market. For the closing price prediction of Tata
Motors, the model is built using Long Short Term Memory Network (LSTM).
The model is trained using the past records of the Company from Yahoo
Finance.
        </i>
    </b>   
</p>
    

### Libraries/Frameworks used:
<ul>
    <li> <b> pandas_datareader: </b> It is used to extract the dataset of stock prices. </li>
<li> <b> numpy: </b> It is used to handle the arrays. </li>
<li> <b> pandas: </b> It is used to handle data frames. </li>
<li> <b> MinMaxScaler: </b> Is used to scale the data. </li>
<li> <b> Sequential: </b> To build the ML model </li>
<li> <b> Dense: </b> It is a layer for the model, in which each neuron receives input from all the neurons of
the previous layer. </li>
<li> <b> LSTM: </b> It is a layer for the model, in which each neuron receiver input from all the past
previous layers. </li>
<li> <b> Dropout: </b> It is a layer for the model, it helps to randomly select the neurons and helps to
reduce the overfitting of the model. </li>
<li> <b> matplotlib.pylot: </b> Is used for plotting the graphs for values. </li>
</ul>


### ML Model Details:
> LSTM (Long short-term memory)
<ul>
    <li> Root Mean Square Error: 0.9894429065605955</li>
    <li>Activation Functions: Nadam</li>
    <li>Input Size of images: (60, 1)</li>
</ul>

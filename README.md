# Time Series Analysis on Adj. Close from ^BVSP using Matlab 

Time Series forecast the values of future time steps of a sequence, that trains a sequence-to-sequence regression LSTM network. The responses are the training sequences with values shifted by one time step. At each time step of the input sequence, the LSTM network learns to predict the value of the next time step.

The dataset can be found from Yahoo Finance:

https://finance.yahoo.com/quote/%5EBVSP/history?period1=749102400&period2=1569556800&interval=1d&filter=history&frequency=1d

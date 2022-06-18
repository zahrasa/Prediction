# Prediction
Simple RNN

Two time series are provided in train.csv and test.csv files. The train.csv file contains information about 1000 days and the test.csv file contains information about 460 days later.

Using simpleRNN layers, one networks was implemented, which predicts the value of the 21st day by receiving information for previous 20 consecutive days.

The data in train.csv was used for network training and the test.csv data was used for network evaluation. Finally, for the evaluation dataset (for all 440 possible days) the predicted values and the actual values were shown in a graph.

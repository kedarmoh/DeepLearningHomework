# LSTM Stock Predictor

Ad part of tweaking the model, I observed the results by tweaking the following paramaters
1. Epoch: I tried with epcoh size of 50, 100, 200. I saw better results with higher epochs though there wasnt a big difference between 100 and 200. 
2. Number_units: I did some tests with numberof units upto 20
3. Window size: I also tried window sizes upto 25 

For Window size 10, number_units 20 and epochs 200
 FNG based model had a loss of 0.0930
 Closing price based model had a loss of 0.0115

 FNG Predictions where way off. 
 FNG Model Predictions (FNG-Model-WindowSize10.jpg)
 CLosingPrice Model Predictions (ClosingPrice-Model-WindowSize10.jpg)

 For Window size 25, number_units 20 and epochs 200
 FNG based model had a loss of 0.1058
 Closing price based model had a loss of 0.0051

 FNG Predictions where way off. 
 FNG Model Predictions (FNG-Model-WindowSize25.jpg)
 CLosingPrice Model Predictions (ClosingPrice-Model-WindowSize25.jpg)

 For Window size 8, number_units 10 and epochs 75
 FNG based model had a loss of 0.0900
 Closing price based model had a loss of 0.0123

 FNG Predictions where way off. 
 FNG Model Predictions (FNG-Model-WindowSize8.jpg)
 CLosingPrice Model Predictions (ClosingPrice-Model-WindowSize85.jpg)

> Which model has a lower loss?
The closing price model had a lower loss
>
> Which model tracks the actual values better over time?
The closing price model tracks actual values better over time.
>
> Which window size works best for the model?
The window size of 8 worked best for my case. I tried with a window size of  10 and 25 and the predicted values were off as compared to the actual values



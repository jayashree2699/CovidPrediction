# Covid Prediction Using Stacked Ensemble
This project has two key functionalities. Firstly, we are going to make an analysis of the geographical spread of covid among different states of India. We present an ensembling model combining the results of the base models such as LSTM, ARIMA and GRU for the case prediction. The Meta model is trained using four different regression algorithms and a comparison is made to identify the best model for the time series prediction. Experimental results indicate that the ensemble model outperforms the individual models in terms of r2_score and accuracy. Finally, based on the symptoms of persons who’ve already taken a covid test and have tested either positive or negative, a covid test recommendation will be provided by the system trained using the machine learning algorithm. 
# Flow Diagram 
![PredSrchi](https://user-images.githubusercontent.com/56253957/202853389-4d18ddbf-45d3-4dc6-afd3-575408cc9eb9.PNG)
# Machine Learning Models used for Time-Series Prediction
<h3>LEVEL 1 <br /></h3>
* Gated Recurrent Unit (GRU) <br />
* Long short-term memory (LSTM) <br />
* AutoRegressive Integrated Moving Average (ARIMA) <br />
<h3>LEVEL 2 <br /></h3>
* Linear Regression <br/>
* Polynomial Regression <br/>
* Lasso Regression <br/>
* Ridge Regression <br/>
<h1>Steps to Run the Code</h1>
Step 1: Download the datasets from Dataset folder <br />
Step 2: Run the Covid_19_Case_Prediction.ipynb file

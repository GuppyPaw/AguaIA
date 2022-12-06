# AguaIA

Find a way to predict the state of water (stage and discharge) at any time in the future using ML, sensor data and photographs of water bodies.

<img src="img/lake.png">


## Corrections
Rodrigo: at first, I tried to build ML models predicting the two dependent variables at once, but the results weren't so promising so with the feedback, I just focus in one dependent variable that was stage. I analyzed it very carefully and came up with a great performance by the regression models. Because we only predicted one dependent variable, my team and I decided to come up with two approaches two predict the stage, one by splitting the data randomly and other splitting the data with the train set from year 2012 to 2017 and the test set from 2018 to 2019. Also, we decided to do a time series model analysis in order to have a different approach from the regressio models made. The ARIMA model was not enough for us so we added the Prophet model.

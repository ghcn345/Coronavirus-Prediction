<p>
<img src="images/Coronavirus.jpg" width="900" height="585">
</p>

# Coronavirus Prediction

**Authors**: Ning Chen, Elliot Macy

## Overview
The goal of this project is to investigate Coronavirus and make related predictions in regard to time series modeling. The data is accessed by public APIs. Machine learning and deep learning methods such as ARMA, ARIMA, SARIMAX, Facebook PROPHET, Recurrent Neural Network and Long short-term memory (LSTM) Networks are implemented and evaluated.


## Business Understanding

The prediction problem of Coronavirus comes with a significant degree of ambiguity, which is difficult to predict considering the complex circumstances in the real world. While one important task in this project is understanding time series modeling and forecasting related rates for the decision makers to layout some strategies in dealing with covid-19.




## Data Understanding
The Coronavirus data is accessed by open public APIs without authentication. It provides updated information associated with COVID-19. The public data [API](https://github.com/ghcn345/Coronavirus-Research) provides access to all of the data at a national and state level. The death cases, positive cases and mortality are studied to make further predictions. 


## Data Preparation
![graph](/images/acf.jpeg)




## Modeling
![graph](/images/death.jpeg)

## Evaluation
SARIMAX with opitmized hyperparameters by Gridsearch and LSTM Networks show better RMSE and MAE results. 


## Deployment
Web app can be furtherly tested and released.


## For More Information

Please review our full analysis in [our Jupyter Notebook](https://github.com/ghcn345/Coronavirus-Research) or our [presentation]().

For any additional questions, please contact **Ning Chen—chen.ning345@gmail.com, Elliot Macy—elimacy@gmail.com**.

## Repository Structure

Description of the structure of the repository and its contents:

```
├── README.md                           <- The top-level README for reviewers of this project
├── project_coronavirus                 <- Narrative documentation of analysis in Jupyter notebook
├── Project_Presentation.pdf            <- PDF version of project presentation
├── data                                <- Both sourced externally and generated from code
└── images                              <- Both sourced externally and generated from code

```

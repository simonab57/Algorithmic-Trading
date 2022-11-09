## Overview of the Analysis: Algorithmic-Trading
The purpose of this analysis is to create an algorithmic trading bot that learns and adapts to new data evolving markets using financial python programming and machine learning. 

The first step of this analysis is to establish a baseline performance to generate a trading strategy, Single Moving Average,  using short and long-window SMA value, splitting training and testing data, use a SVC classifier machine learning algorithm to model, fit, and predict testing data, and finally generate a classification report to present accuracy. Next is to tune the baseline trading algorithm, by adjusting parameters that will give us the best trading outcomes by adjusting the training data. Last but not least, is to evaluate a new machine learning classifier that allows for better predictions. The algorithm that was chosen, was an AdaBoost Classifier, which has its own import requirements, but still follows the same procedures of a using a model, that is to model, fit, and predict. We then will present the final evaluation report. 


## Technology 
Pandas, Numpy, HvPlot, MatPlotlib, SKlearn, StandardScaler, DateOffset, Classification Reports


## Evaluation Report: Results and Summary

SVC Model Results: 

SVC Model seems to get on the right foot with its predictions, as both actual and strategy returns seem to follow each other till 2017. Later in that same year, the actual returns and the strategy returns tend to show difference. However, it tends to move in the same direction. Around the later months of 2018, we tend to see increased gaps between the two results, yet still moving in the same direction, and this trend seems to continue towards the end of the plot. 

![returns_svc_model](https://user-images.githubusercontent.com/109967916/199276714-ccd1a77d-dcb0-48fd-b668-c8c9841ee738.png)


AdaBoost Model Results: 

AdaBoost Model is a model that corrects the weak classifiers in the SVC Model, and improves it for better accuracy results. The model seems to predict actual and strategy returns almost in perfection as not evidence of blue (actual returns) is seen in the plot, as the strategy returns excactly predicts the actual returns. 

![returns_adaboost_model](https://user-images.githubusercontent.com/109967916/199277576-f68da78b-b090-469a-8c9c-19304c8047d3.png)

## Contributor
Simon Abennet





# Module 21 Report

## Overview
The purpose of this analysis is to determine which of the applicants are most likely to succeed, in order to choose the best candidates for funding.

## Results: Using bulleted lists and images to support your answers, address the following questions:
Data Preprocessing:
* What variable(s) are the target(s) for your model?
  * I chose to use all of the variables provided, except for EIN and NAME.
* What variable(s) are the features for your model?
  * 
* What variable(s) should be removed from the input data because they are neither targets nor features?
  * The EIN and NAME columns.

Compiling, Training, and Evaluating the Model:
* How many neurons, layers, and activation functions did you select for your neural network model, and why?
  * I had two layers in my original version of the model. I used 80 neurons in the first layer, and 30 in the second layer. I used the activation code "relu". 
* Were you able to achieve the target model performance?
  * I was very close, my final accuracy after the third model was 73%.
* What steps did you take in your attempts to increase model performance?
  * The most effective thing I did was switch from using relu to using leaky_relu, which improved the accuracy from 44% to 72%. I also tried adding layers and switching up the number of neurons, however this didn't seem to make much of a difference.

## Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

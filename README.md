# Neural_Network_Charity_Analysis

## Overview 
This analysis was conducted to determine what charity applications would be successful.We cleaned the initial data and then set up test and train data to work with the model.

##Results

### Data Processing
The variable specification for the model are seen below:

- Target Variable: IS_SUCCESSFUL
- Features: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT
- Neither features nor targets: EIN, NAME

### Compiling, Training, and Evaluating the Model

I seleceted a total of 14 neurons becasue it did not seem like it would overfeed the mode. Based on the density shown i used the relu and sigmoid functions due to how they keep values positive. Unfortunately i was unable to achieve target performance.

Based on my initial attempt i had an accuracy of .5768.

![image](https://user-images.githubusercontent.com/91395269/163304062-3fd94101-daf9-4042-a14e-abc3f1c15a89.png)


I initially tried to add in the name feature but that got a lower accuracy of .48. I then tried to increase the epochs and add another hidden layer. These changes were to no avail and did not result in the sought out .75 accuracy.

![image](https://user-images.githubusercontent.com/91395269/163305000-fb64460e-0167-497a-a57f-4acc195cfc2e.png)




## Summary

Overall the model is working to fit the data but is not quite at a functional level yet. A regression model on the application that were successful might be a better indicator of what features needed to be in order to get funding. Further work could be done on this machine learning model as well by adding further hidden layers and evaluating the best function for the inputs.



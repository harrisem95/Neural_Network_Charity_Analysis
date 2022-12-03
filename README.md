# Neural_Network_Charity_Analysis

## Overview of the Loan Prediction Analysis

### Purpose
The purpose of this project is to use machine learning and neural networks to create a binary classifier to help predict if Alphabet Soup, a charitable orginzation, will be successful in their funding of an applicant. Using a dataset of 34,000 organization we preprocessed data, compiled, trained and evaluated the model. Finally, we optimized the model.


## Results

### Data Preprocessing

#### What variable(s) are considered the target(s) for your model?
The variable that was the taget for my model is IS_SUCCESSFUL column.

#### What variable(s) are considered to be the features for your model?
Every column with the exception of IS_SUCCESSLFUL are the features for my model.

#### What variable(s) are neither targets nor features, and should be removed from the input data?
EIN and NAME columns were removed from the input data.

### Compiling, Training, and Evaluating the Model

#### How many neurons, layers, and activation functions did you select for your neural network model, and why?
For my neural network model, I had 80 neurons in my first hidden layer and 20 in my second hidden layer, and I included an output layer with an activation function of sigmoid. My first hidden layer has the tanh activation function and my second hidden layer has the relu output layer. I wanted more neurons in my first hidden layer than my second. I also chose a couple different activation functions to attempt to optimize the output.

#### Were you able to achieve the target model performance?
I was not able to achieve the target model performance.

#### What steps did you take to try and increase model performance?
I changed the neurons in my model, I added a hidden layer, and I doubled the amount of epochs. This did not significantly change my output and I still did not reach the target.

#### Original Accuracy
![Original_Results](/Resources/original_accuracy.png)


#### Optimized Accuracy
![Optimized_Results](/Resources/optimized_accuracy.png)


## Summary
Overall, we were not able to optimize the results of the deep learning model. I recommend running a model with hyperparameters options to find the ideal parameters to have in the model. I also recommend increasing the amount of data and reducing the noise of the data.I think this could solve the classificaiton problem. 





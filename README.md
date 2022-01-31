
# Neural_Network_Charity_Analysis

## Overview
The purpose of this analysis is to use machine learning and neural networks to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results
Using bulleted lists and images to support your answers, address the following questions.

### Data Preprocessing

 - What variable(s) are considered the target(s) for your model?
	 - **IS_SUCCESSFUL:** Determining if the money was used successfully
- What variable(s) are considered to be the features for your model?
	-  **APPLICATION_TYPE:** Alphabet Soup application type
	-   **AFFILIATION:** Affiliated sector of industry
	-   **CLASSIFICATION:** Government organization classification
	-   **USE_CASE:** Use case for funding
	-   **ORGANIZATION:** Organization type
	-   **STATUS:** Active status
	-   **INCOME_AMT:** Income classification
	-   **SPECIAL_CONSIDERATIONS:** Special consideration for application
	-   **ASK_AMT:** Funding amount requested
- What variable(s) are neither targets nor features, and should be removed from the input data?
	-  **EIN** & **NAME:** Identification columns

### Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?
	- Neurons: 80, 50, 30
	- Layers: 3
	- Activation Functions: 2 (Relus & Sigmoid)
- Were you able to achieve the target model performance?
	- No
- What steps did you take to try and increase model performance?
	- Increasing the number of hidden layers
	- Adjusting the number of neurons in each layer
	- Changing the activation function
	- Binning the Ask Amount column to ease classification

## Summary
In the end, I was not able to achieve above 75% accuracy despite the steps taken to refine the model. I think there are a few outliers in the dataset that could be removed to help improve the model's accuracy. Since this is a classification model, I think a Random Forest could also be useful in determining whether a company will be successful if funded by Alphabet Soup.

> Written with [StackEdit](https://stackedit.io/).

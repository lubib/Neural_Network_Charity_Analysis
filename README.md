# Neural_Network_Charity_Analysis

Overview of the analysis: 

The purpose of this analysis is the to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

Results: 

Using bulleted lists and images to support your answers, address the following questions.

    Data Preprocessing
1. We considered IS_SUCCESSFUL as a target variable in our model. 
2. The Features variables for the model are APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT, STATUS.
3. The EIN and NAME variables have been dropped because they are neither targets nor features.

    Compiling, Training, and Evaluating the Model

4. The following neurons and activation functions were chosen to optimize the neural network model.
Layer	Neurons	Activation function
First hidden	80	relu
Second hidden	30	relu
Output		Sigmoid

5. We were not able to achive the target model performance of 75%. However, we were pretty close with the highest accuracy for the model of 72%. 

6. Following steps were taken to try and increase model performance:

Adjusting the input data by dropping more variables.
Added more neurons to a hidden layer.
Added more hidden layer.
Used different activation functions for the hidden layers.
Reduced the number of epochs to the training regimen.


Summary: 
Even thought we were not able to achive the 75% accuracy we wanted we were able to increase the accuracy from 55% to 72%.  
I would suggest to use the Random forest classifiers model to solve the classification problem. It has been a staple in machine learning algorithms for many years due to their robustness and scalability and could be a good solution to our problem. 



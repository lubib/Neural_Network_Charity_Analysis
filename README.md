# Neural_Network_Charity_Analysis

#### Overview of the analysis: 

The purpose of this analysis is the to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

#### Results: 

Data Preprocessing
  
1. We considered IS_SUCCESSFUL as a target variable in our model. 
2. The Features variables for the model are APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT, STATUS.
3. The EIN and NAME variables have been dropped because they are neither targets nor features.

Compiling, Training, and Evaluating the Model

4. The following neurons and activation functions were chosen to optimize the neural network model.
Layer	Neurons	Activation function

<img width="406" alt="Screen Shot 2020-11-02 at 11 08 16 PM" src="https://user-images.githubusercontent.com/67556541/97949089-862b9080-1d60-11eb-81e2-e2aad1fdc1c4.png">

  Hiden laye activation="relu"
  
  Output layer activation="sigmoid"

5. We were not able to achive the target model performance of 75%. However, we were pretty close with the highest accuracy for the model of 72%. 

6. Following steps were taken to try and increase model performance:

- Adjusting the input data by dropping more variables.
- Adding more neurons to a hidden layer.
- Adding more hidden layer.
- Using different activation functions for the hidden layers.
- Reducing the number of epochs to the training regimen.

#### Summary: 
Even thought we were not able to achive the 75% accuracy we wanted we were able to increase the accuracy from 55% to 72%.  
I would suggest to use the Random forest classifiers model to solve the classification problem. It has been a staple in machine learning algorithms for many years due to their robustness and scalability and could be a good solution to our problem. 

<img width="651" alt="Screen Shot 2020-11-02 at 1 02 24 AM" src="https://user-images.githubusercontent.com/67556541/97948204-dfde8b80-1d5d-11eb-8e71-f4a7c894416c.png">

<img width="661" alt="Screen Shot 2020-11-02 at 1 01 06 AM" src="https://user-images.githubusercontent.com/67556541/97948198-d8b77d80-1d5d-11eb-89c3-015d417e327e.png">




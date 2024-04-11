# deep-learning-challenge

Module 21 Report										04/11

Overview: 
The objective of this assignment is to assist Alphabet Soup select applicants for funding with the best chance of success in their ventures.  By employing machine learning and neural networks, features are used to create a binary classier that can predict whether applicants will be successful if funded by Alphabet Soup.

Data Processing:

•	The target variable for my model is IS_SUCCESSFUL
•	The features for my model is APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT.
•	Variable EIN and NAME was removed from the input data as they are neither targets nor features.

Compiling, Training, and Evaluating the Model:
•	I selected 3-4 hidden nodes layers: First, second, third and fourth hidden layers with various values.
•	Experimented with activation functions Sigmoid and Relu
•	Despite 3 attempts, target performance of 75% accuracy was not achieved. The highest accuracy obtained was 73.17%
•	To increase model performance, I adjusted epochs, number of layers and neuron’s value.

Summary:
Overall results were good around 73% accurate in predicting the classification problem but the desired 75% performance target was not met. To enhance model performance, additional layers and dropping more columns could be considered.  Further experimentation and optimization may lead to improved results.
![image](https://github.com/NesAtar/deep-learning-challenge/assets/148135912/8278f135-6a4a-4e4c-9262-19c6e8d2574a)

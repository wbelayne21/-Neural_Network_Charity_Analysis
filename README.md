# Neural_Network_Charity_Analysis
## Overview of the analysis: 


### Results: Using bulleted lists and images to support your answers, address the following questions.

Data Preprocessing
- 'Is Successful' will be the target feature
- APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT are the features for our model. 
- 'EIN', 'NAME' are non-beneficial columns that were dropped.
                          
Compiling, Training, and Evaluating the Model
- We have 3-4 layers, 3 activation functions (tanh, sigmoid, relu). Number of neurons were 80, 50, 20 and 10 for hidden layers 1-4 respectively. 
- We added more neurons and layers as well as changed activation functions to increase optimization. We also increased epochs to the training regimen. 
- The target model perfomance of 75% was not achieved however the accuracy increased during 3 attempts at increasing optimization. 
- Attempt 1 - 43.7%
- Attempt 2 - 46.6%
- Attempt 3 - 46.7%
#### Summary: 

Altough the desired performance level was not achieved, we learned that changing activation functions, adding more neurons and layers as well as epochs improves optimization. A recommendation would be to try optimizers other than 'adam' and see if that makes a significant difference. 
**Addionally, we could use RandomForest Classifier as it is faster, more robust and scalable than deep learning and achievs similar performace. Another suggestion is to use SVM model which would yield similar predictive yield.

Attempt 1
![1](https://user-images.githubusercontent.com/92958091/161800911-271c108c-b4be-4823-b053-2108c84ebbb8.png)

Attempt 2
![2](https://user-images.githubusercontent.com/92958091/161800915-9fd964fa-d312-4e54-9e3c-ce2ababcea5d.png)

Attempt 3
![3](https://user-images.githubusercontent.com/92958091/161800916-76ce6bfe-2b53-446b-9222-4359426d9cef.png)

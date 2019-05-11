# KBSProject

 - ### Detailed plan including Data source, potential audience, plan, domain is contained in "DetailedPlan.pdf"
 - ### Processing notebook with principle component analysis is included in "PCA_KBS.ipynb"
 - ### Citations with the abstract are contained in "Citations.pdf" 
 - ### Screenshots of dashboard is contained in "Dashboard.pdf"
 - ### Data is uploaded to BigQuery
 -	### Neural Network Model is built in "NNModel_KBS.ipnb"
    Neural Network model to predict whether whether customers are going to churn or not has been built based on Tensorflow. Stratified random sample based on gender is used to sperate the train data and test data. Features of "Senior Citizen", "Tenure", "Monthly Charges" and "Total Charges" are taken into the model.

    For this model, we take four variables as inputs of train data and wether the customers will churn(yes/no) as the outputs. One hidden layer is used which has 30 neurons. ReLU is used as activation function of the hidden layer and Softmax for the output layer. Dropout is used for avoiding outfitting. The model is trained for 5000 epochs. The batch size is set as 32. Cross-Entropy is used as the cost function. Adam, which is one kind of gradient descent algorithm is used for optimization. 
    
    After building the model, the accuracy of the model is proved to be 70.9% based on the test data.


  


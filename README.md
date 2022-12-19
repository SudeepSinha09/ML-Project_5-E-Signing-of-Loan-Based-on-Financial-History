# ML-Project_5-E-Signing-of-Loan-Based-on-Financial-History
### Data Details 
  
   Kaggle - https://www.kaggle.com/datasets/aniruddhachoudhury/esigning-of-loan-based-on-financial-history?select=financial_data.csv  
   Colab Notebook - https://colab.research.google.com/drive/1wRf9RP3_3VA_DCBQkx5HzDwchzrEJ55P?usp=sharing
   
#### Please use the Ipynb file in the repository for a detailed explanation of this project. This is because the project has been completed and the steps have been written in the notebook referenced in the repository.
Link - https://github.com/SudeepSinha09/ML-Project_5-E-Signing-of-Loan-Based-on-Financial-History/blob/main/E-Signing%20of%20Loan%20Based%20on%20Financial%20History.ipynb

## An Overview of EDA

![image](https://user-images.githubusercontent.com/93086122/208379948-dfc9d1ec-d0c2-4006-92e6-018a23d7a1d4.png)

![image](https://user-images.githubusercontent.com/93086122/208380021-ede76a19-b8ca-43a7-81a6-735a2b581cd9.png)

## Project Brief

As part of this project, I cleaned the data, after which I train-tested the data, and then I made models using the train data

In order to determine the accuracy of each model, I made predictions based on the train data before making the models, i.e. predicting the models with the train data.

Using these parameters, we found that the accuracy, recall, precision, and f1 scores

Compairinng accuracy values for all the above models we can conclude that best model is XGBoost as it's accuracy in classifying the output is approximately 64% which is higest of all

##### Model selected - XGBoost

Ater finally seleting the model we will perform hyperparameter tuning further to get the best or the most accurate result from the selected model by chainging its parameters

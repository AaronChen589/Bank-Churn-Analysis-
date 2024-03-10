# Bank-Churn-Analysis-

# Background
How do you predict whether a customer will churn (leave a bank)?
Today, I will be trying to answer this quesiton by create an Artificial Netural Network through Tensorflow.

## Getting Started

### Introduction to the files
* Churn_Modelling.csv - the original/ unclean dataset
  
* Preprocessing_Bank_Churn_Dataset.ipynb - notebook where the dataset is preprocessed and clean

Example of Preprocessing  
![image](https://github.com/AaronChen589/Bank-Churn-Analysis-/assets/80292924/6de97a3b-4ade-44d7-8484-9749336feec8)
![image](https://github.com/AaronChen589/Bank-Churn-Analysis-/assets/80292924/111ffc95-5f37-45c0-a6f1-ed538f47ed1f)

Pyspark is used to query and visualize tenure vs churn
![image](https://github.com/AaronChen589/Bank-Churn-Analysis-/assets/80292924/77bc79cb-9ace-40d5-a692-8d54a12b1d05)
* Test_Bank_Churn_Dataset.csv (Output of the preprocesing Bank Chun Dataset)
* Train_Bank_Churn_Dataset.csv (Output of the preprocesing Bank Chun Dataset)
* Machine_Learning_Bank_Churn.ipynb - notebook where the ANN is trained and tested

Summary of the ANN models


![image](https://github.com/AaronChen589/Bank-Churn-Analysis-/assets/80292924/80cb7c1f-ba7b-4442-8db6-2a5e8110b9fe)
![image](https://github.com/AaronChen589/Bank-Churn-Analysis-/assets/80292924/f3e6912f-e954-4eaa-a635-858c7513e239)
![image](https://github.com/AaronChen589/Bank-Churn-Analysis-/assets/80292924/fabf0df8-36a1-4adc-a766-1ccd78cdc987)


### Dependencies
* Necessary libraries/frameworks: tensorflow, pandas, matplotlib, seaborn, scikit-learn, pyspark
* Vscode or any other IDE with notebook capabilities
  
### Executing the Program
* First, import Churn_Modelling.csv and run Preprocessing_Bank_Churn_Dataset.ipynb first ===> (Output) Test_Bank_Churn_Dataset.csv, Train_Bank_Churn_Dataset.csv
* Then import Test_Bank_Churn_Dataset.csv and Train_Bank_Churn_Dataset.csv, and run Machine_Learning_Bank_Churn.ipynb

### Author:Aaron Chen
https://www.linkedin.com/in/aaronchenstony/
https://public.tableau.com/app/profile/aaron.chen3368/vizzes 

### Acknowledgment
The dataset was taken from...
https://www.kaggle.com/datasets/radheshyamkollipara/bank-customer-churn

# SYSC5809F--Adversarial Machine Learning for IoT Cybersecurity
## Overview 
This project demonstrate the effects of adversarial machine learning for IoT IDS.
In this project we compared the effectivenes for our IDS built with different ML algorithms:
- Random Forest (RF)
- Linear Regression (LR)
- Deep Neural Network (DNN)
  
We choose to compare our models under different conditions:
- Clean Dataset
- Adversarial Dataset
    - Fast Gradient Sign Method (FGSM) implementtion
    - Project Gradient Descent (PGD) implementation

- Mitigation: Adversarial retraining of our DNN model with PGD generated data.
---

## Dataset
We are using the CICIDS2017 Dataset to simulate network traffic in a smart home system. We are going to create an intrusion detection system using baseline machine learning models. And then we will use the same models to intoduce an adversarial attack and visualize the new results. With the adversarial attacks we will retrain the model as defense mechanism. 
<b>Dataset link:</b> https://www.unb.ca/cic/datasets/ids-2017.html
<b> Please use the friday-afternnon working hours to test the code.</b>
---
## HOW TO RUN 

Run on local environment: 
1- Add a cell and execute "! pip install pandas numpy matplotlib seaborn sklearn tensorflow " (please add any other missing librairies)
2- Install the csv of friday-afternoon-working hours from the dataset link
3- Replace the second code cell with your path from the dataset
4- Run the Code ;)

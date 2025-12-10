# SYSC5809F--Adversarial Machine Learning for IoT Cybersecurity
Fall 2025

## Overview 
This project demonstrates the impact of adversarial machine learning on an Intrusion Detection System (IDS) for IoT cybersecurity.
We build an IDS using multiple machine learning algorithms and evaluate how adversarial attacks affect their performance.

In this project we compared the effectivenes for our IDS built with different ML algorithms:
- Random Forest (RF)
- Linear Regression (LR)
- Deep Neural Network (DNN)
  
We chose to compare our models under these different conditions:
- Clean Dataset
- Adversarial Dataset
    - Fast Gradient Sign Method (FGSM) implementtion
    - Project Gradient Descent (PGD) implementation

- Mitigation: Adversarial retraining of our DNN model with PGD generated data.
---

## Repository Structure
│
├── notebook/                 # notebook (main project code)
│   └── IDS.ipynb
        └── Results
│
└── README.md                 # Project documentation

---

## Dataset

We used the CICIDS2017 Dataset to simulate network traffic in a smart home system. We created an intrusion detection system using baseline machine learning models, and used the same models to intoduce an adversarial attack and visualized the new results. With the adversarial attacks we retrained the model as defense mechanism. <br>
<b>Dataset link:</b> https://www.unb.ca/cic/datasets/ids-2017.html  <br>
<b> Please use the friday-afternnon working hours to test the code.</b>
---


## Tools Used
Python Libraries - Program implementation and test execution
Git and Github - Version control and repository hosting
Google Colab - Code Running
Google Docs - Final Report Writing
Google Slides - Project Presentation

## Requirements 
If running locally, install the following Python libraries:
pandas
numpy
matplotlib
seaborn
scikit-learn
tensorflow
keras

You can install them using:<br>
!pip install pandas numpy matplotlib seaborn scikit-learn tensorflow keras


## HOW TO RUN 

Run on local environment: <br>
1- Add a cell and execute "! pip install pandas numpy matplotlib seaborn sklearn tensorflow " (please add any other missing librairies) <br>
2- Install the csv of friday-afternoon-working hours from the dataset link <br>
3- Replace the second code cell with your path from the dataset <br>
4- Run the Code <br>

## Authors
Diana Addae 
Carleton University 
Student ID - 101363765

Karamoko Soumare 
University of Ottawa (uOttawa ID - 300203291)
Carleton University ID - 101396604 

## Key References

These references are included to support the implementation of the adversarial attacks and dataset used in this project:

CICIDS2017 Dataset — Canadian Institute for Cybersecurity
https://www.unb.ca/cic/datasets/ids-2017.html

Goodfellow, I., Shlens, J., & Szegedy, C. (2014).
Explaining and Harnessing Adversarial Examples. (FGSM)

Madry, A., Makelov, A., Schmidt, L., Tsipras, D., & Vladu, A. (2017).
Towards Deep Learning Models Resistant to Adversarial Attacks. (PGD)

#GDM Prediction using Visceral Fat

## Background
This project aims to develop a machine learning model for predicting Gestational Diabetes Mellitus (GDM) based on maternal visceral adipose tissue 
(VAT) measurement by ultrasound during the first half of pregnancy. The model can contribute to early GDM screening and metabolic control, 
reducing maternal and fetal risk associated with the condition.

## Data
The dataset used for this project was obtained from [https://physionet.org/content/maternal-visceral-adipose/1.0.0/ ], containing 133 
instances of pregnant women who underwent ultrasound measurements of VAT during their first half of pregnancy, and later developed or did not 
develop GDM during the third trimester.

## Methodology
The project uses Python programming language and machine learning libraries, including numpy, pandas, matplotlib, seaborn and sci-kit learn. 
The data was preprocessed, and feature engineering techniques were applied to extract relevant features for the model.
We developed several machine learning models, including Logistic Regression, Decision Tree and Random Forest, and compared their
performance using metrics such as accuracy and F1-score. Since, the classes were imbalanced a 

## Results
The best-performing model was Random Forest, achieving an accuracy of 0.96, F1 score of 0.88.The model was able to accurately predict 96% of 
GDM cases in the test dataset. However, more training data is definitely required to imporve the model performance, as the classes are imbalanced.


References
[1] Rocha, A. da, Bernardi, J. R., Matos, S., Kretzer, D. C., Schöffel, A. C., Goldani, M. Z., &amp; de Azevedo Magalhães, J. A. (2020). 
Maternal visceral adipose tissue during the first half of pregnancy predicts gestational diabetes at the time of delivery – A cohort study. 
PLOS ONE, 15(4). https://doi.org/10.1371/journal.pone.0232155 


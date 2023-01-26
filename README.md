# Credit_Risk_Analysis

## Overview

The following Machine-Learning example uses a variety of credit-related risk factors to predict a potential client's credit risk. The models include; Logistic Regression, Balanced Random Forest and EasyEnsemble, and a variety of re-sampling techniques are used (Oversampling/SMOTE, Undersampling/Cluster Centroids, and SMOTEENN). Evaluation metrics like the accuracy score, classification report and confusion matrix are generated to compare models and determine which suits this particular set of data best.

## Results

The following are the results observed.
![image](https://user-images.githubusercontent.com/111898553/214760038-5357f5d0-c5cd-4455-ba0a-ae51f72bf04a.png)


![image](https://user-images.githubusercontent.com/111898553/214760095-537cb66e-7560-44f9-b79c-c3902353b37f.png)



Of the 4 models, the Logistic Regression model using the SMOTEENN Combination Re-Sampler had the best balanced accuracy score at 79.8%.
Of the 4 models, the Logistic Regression model using the Smote Oversampler had the best recall score at 88%.
Of the 4 models, both the Logistic Regression model using the SMOTEENN Combination Re-Sampler and the model using the Smote Oversampler had the best geometric mean scores at 79%.





- The Easy Ensemble classifier had the best balanced accuracy score at 93%.
- The Easy Ensemble classifier had the best recall score at 94%.
- The Easy Ensemble classifier had the best geometric mean score at 93%.
The top three features are total_rec_prncp (8.3%), total_pymnt_inv (6.9%) and last_pymnt_amnt (6.1%).

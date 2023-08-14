# Team-3-Loan-Predictions

### Authors

Tara Dehdari, Sowmiya Kanmani Maruthavanan, Landon Padgett

## Data Source  

The data set was used from Kaggle and can be accessed at: https://www.kaggle.com/datasets/architsharma01/loan-approval-prediction-dataset

## Exploratory Data Analysis 

There were no missing values or outliers that needed to be handled. There were no significant trends in the data set

## Data Preprocessing

All asset columns (residential_assets_value, commercial_assets_value, luxury_assets_value, and bank_assets_value) were aggregated into one column called total_assets. Transformation techniques were not needed because after the aggregation of the assets columns the dataset was normal. The fields including loan id, loan term, number of dependents, and self-employed, were excluded because it wouldn't help find our target variable (loan_status). The data set was partitioned into training and test subsets, 67% for training, and 33% for testing. 

## Model Building

Five models were created as well as a basline model. The models used were logistic regression, K-neaerest neighbor, decision tree, random forest, neural network modeling, and then majority class classifier for our baseline model.

## Evaluation Metrics

The models were compared to the baseline model to ensure they performed better than the baseline model and than an AUC-ROC curve was created to see which model was the best.

## Results

All the models compared to the baseline model had a higher accuracy, and their accuracies were all similar, but according to our AUC-ROC curve the Neural Network modeling was the best model because the curve is closer to 1 than the others.  

## Usage

Using your IDE of your choice run the codes one by one in order. Ensure you have keras, tensorflow, scikit-learn, and seaborne downloaded. 

## Contact information

For questions or conerns email us at tdehdari@sandiego.edu, lpadgett@sandiego.edu, and/or smaruthavanan@sandiego.edu

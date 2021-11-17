![vcrtmdijhgqr1rz2yd8u](https://user-images.githubusercontent.com/9140821/142194686-012af438-4724-4dc9-82de-33699c2f05ff.jpg)

    
# Salary Prediction on Hitters Dataset: 154.9561 RMSE

### Salary Prediction for Hitters Dataset with Linear and Non-Linear Models ###

In this project, we will build several linear and non-linear models on the Hitters dataset. After creating base models, some of them will be tuned to minimize prediction errors in terms of the RMSE metric. To split the dataset for training and test purposes, K-fold Cross-Validation will be used. Linear models used in this project are Linear Regression, Ridge, Lasso, ElasticNet. Non-linear models used in this project are regression implementations of K-Nearest Neighbors (KNN), Classification and Regression Trees (CART), Random Forest (RF), Support Vector Machine (SVM), Gradient Boosting Machine (GBM), eXtreme Gradient Boosting (XGB), and Light-GBM (LGBM). 


## FAQ

#### Can I download the dataset?

You can download from https://www.kaggle.com/ceyhunkapucu/salary-prediction-on-hitters-data-154-9561-rmse/data

You can also see my Kaggle notebook from https://www.kaggle.com/ceyhunkapucu/salary-prediction-on-hitters-data-154-9561-rmse/

#### What is the description of the dataset?

* InvoiceNo: Invoice number. Nominal. A 6-digit integral number uniquely assigned to each transaction. If this code starts with the letter 'c', it indicates a cancellation.

* AtBat: Number of times at bat in 1986
* Hits: Number of hits in 1986
* HmRun: Number of home runs in 1986
* Runs: Number of runs in 1986
* RBI: Number of runs batted in in 1986
* Walks: Number of walks in 1986
* PutOuts: Number of put outs in 1986
* Assists: Number of assists in 1986
* Errors: Number of errors in 1986
* CAtBat: Number of times at bat during his career
* CHits: Number of hits during his career
* CHmRun: Number of home runs during his career
* CRuns: Number of runs during his career
* CRBI: Number of runs batted in during his career
* CWalks: Number of walks during his career
* Years:Number of years in the major leagues
* League: A factor with levels A and N indicating player's league at the end of 1986
* Division: A factor with levels E and W indicating player's division at the end of 1986
* NewLeague: A factor with levels A and N indicating player's league at the beginning of 1987
* Salary: 1987 annual salary on opening day in thousands of dollars


  
## Authors

- [@ckapucu](https://www.github.com/ckapucu)

  
## Requirements

To run this python code, you will need to add the following modules to your environment.

`xgboost` `lightgbm` 

You can install these modules with `pip install xgboost` `pip install lightgbm`

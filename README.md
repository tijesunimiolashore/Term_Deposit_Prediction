## Term Deposit Predictive Model

### About
---
A machine learning model to predict whether or not future clients of the bank of portugal would subscribe to their term deposit.

### Business need
---
I successfully finished up to my rigorous job interview process with Bank of Portugal as a machine learning researcher. The investment and portfolio department would want to be able to identify their customers who potentially would subscribe to their term deposits. As there has been heightened interest of marketing managers to carefully tune their directed campaigns to the rigorous selection of contacts, the goal of my employer is to find a model that can predict which future clients who would subscribe to their term deposit. Having such an effective predictive model can help increase their campaign efficiency as they would be able to identify customers who would subscribe to their term deposit and thereby direct their marketing efforts to them. 

This would help them better manage their resources (e.g human effort, phone calls, time)
The Bank of Portugal, therefore, collected a huge amount of data that includes customers profiles of those who have to subscribe to term deposits and the ones who did not subscribe to a term deposit. As their newly employed machine learning researcher, they want you to come up with a robust predictive model that would help them identify customers who would or would not subscribe to their term deposit in the future.

My main goal as a machine learning researcher is to carry out data exploration, data cleaning, feature extraction, and developing robust machine learning algorithms that would aid them in the department.

### Dataset
---
Download the data from the [UCI ML](http://archive.ics.uci.edu/ml/datasets/Bank+Marketing) website. It's a zip file called bank-additional.zip

### Tasks I did in carrying out this Project
---
**Task 1 - I did an Exploratory Data Analysis on the data by carrying out data visualization on the data**

**Task 2 - Preprocessing**
* I encoded all categorical variables using one-hot encoding to transform them into numerical columns.  
* I handled all outliers using z-score. 
* I used StandardScaler() to rescale all numerical columns.
* I explored TSNE, autoencoders, and PCA dimensionality reductions techniques.

**Task 3 - I used Logistic Regression, Decision Tree Classifier, XGBoost Model and Random Forest for Modelling and Predicton.**

# Installation
* Download the data from the [UCI ML](http://archive.ics.uci.edu/ml/datasets/Bank+Marketing) website. It's a zip file called bank-additional.zip
* Clone this repo to your computer.
* Get into the folder using cd Term_Deposit_Prediction.
* Run mkdir data.
* Switch into the data directory using cd data.
* Download the data files from UCI ML into the data directory.
* Install the requirements
* Install the requirements using pip install -r requirements.txt.
* Make sure you use Python 3.

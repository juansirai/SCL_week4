# 📊🧪🧬DATA SCIENCE CHALLENGE SCL WEEK 4 📊🧪🧬
## *Predicting card fraud*
---------------------
![alt text](https://www.paymentsjournal.com/wp-content/uploads/2019/02/hack-3671982_1920-1.jpg)

# ✨ BACKGROUND ✨
The datasets contains transactions made by credit cards in September 2013 by european cardholders. It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, ... V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise. The dataset has been collected and analysed during a research collaboration of Worldline and the Machine Learning Group (mlg.ulb.ac.be) of ULB (Université Libre de Bruxelles) on big data mining and fraud detection.

# ✨ DATASET ✨
Columns:
* 0 -> Time, numeric variable
* 1-28 -> Predictive numeric features
* 29 -> Amount, numeric variable
* 30 -> Class, this is the target. It is a nominal variable with just 2 unique values (0 and 1)

# ✨🏆 TASK 🏆✨
Create a predictive algorithm (Machine Learning, NOT ANN) to predict if a transaction is fraud (class 1) or not (class 2).

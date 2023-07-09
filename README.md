
# Credit Card Fraud Detection - Readme

The credit card fraud detection project aims to develop a robust and accurate system to identify and prevent fraudulent transactions in credit card transactions.
By leveraging advanced machine learning algorithms and data analysis techniques, the project seeks to analyze various transaction features.
The system will continuously learn from historical data, adapt to new fraud patterns, and improve its detection capabilities over time.
The ultimate goal is to protect customers from financial losses, minimize false positives, and enhance the overall security and trustworthiness of credit card transactions.

## Dataset

 - [Credit Card Transactions Data](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

The project utilizes a dataset containing credit card transactions, which includes various features such as transaction amount, location, time, and other numerical input variables which are the result of a PCA transformation. The dataset is provided in CSV format and is split into a training set and a test set.

Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. Features V1, V2, … V28 are the principal components obtained with PCA.The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.
## Required Dependencies


| Dependencies | Version     | Description                |
| :-------- | :------- | :------------------------- |
| `Numpy` | 1.24.3 | **Optional**. For working with arrays |
| `Pandas` | 1.5.3 | **Required**. For dataframes and required process |
| `Matplotlib` | 3.7.1 | **Optional**. Data Visualization Techniques |
| `Seaborn` | 0.12.2 | **Optional**. Advanced Data Visualization Techniques |
| `Sklearn` | 1.2.2 | **Required**. Model preprocessing, creation and evaluation |




## Workflow

**1. Data Retrieval** Using 

**2. Data Preprocessing** Checking for missing values and removing if found. Dealing with the unbalanced data through under sampling.

**3. Data Analysis** Identifying relationships between independant and dependant features.

**4. Train Test Split** Splitting the data into training dataset and testing dataset to train the machine learning model and evaluation.

**5. Model Creation and Training** Creating the appropriate machine learning model on the basis of type of data present.

**6. Evaluation** Evaluating the data on the basis of different metrics paramaters.


## Conclusion

The credit card fraud detection project provides a framework for building an effective fraud detection system. By leveraging machine learning algorithms and analyzing transaction data, the project aims to minimize financial losses and ensure the security of credit card users.

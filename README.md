# TelcoCustomerChurnPrediction (InterpretML)

## About project

This project represents an example of the "*Telco Customer Churn Prediction System*" that predicts whether the customer churned or not. Also, it has been used an *InterpretML* library to show relations between atributes and their importance for the target value.

## :mortar_board: Autor
- [Milica Galjak, 1071/2020](https://github.com/milicagaljak)

## Run project

-Installation of rarely used ML libraries and packages:

***InterpretML:***

***pip install interpret***<br />
or<br />
***conda install -c interpretml interpret***

-Other important libraries and packages:

*pandas, numpy, sklearn, matplotlib etc.*

Installation of these packages goes the same like previous example.

The project was built in Jupyter notebook environment.


## Data
Dataset used in this project was downloaded from
[Kaggle - Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) and than processed.

Each row represents a customer, each column contains customer’s attributes described in the file *"./dataset/DatasetDescription.docx"*.
The raw data contains 7043 rows (customers) and 21 columns (features).
The “Churn” column is our target value.


## Related work
[**"InterpretML - Alpha Release"**][1], *InterpretML - Alpha Release*

[**Official website: https://interpret.ml/**][2]

[1]: https://github.com/interpretml/interpret

[2]: https://interpret.ml/

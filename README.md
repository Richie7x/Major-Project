# COVID-19 Pandemic Analysis
COVID-19 Pandemic Analysis using DS

This project is created using python and it's powerful set of libraries. It uses pandas to establish the Dataframe model and FbProphet for forecasting on the basis of data patterns
existing in a dataset.

Librares and tools used:
1. Pandas  -----------------------Working with datasets
2. matplotlib  ------------------Plotting datapoints
3. FbProphet  -----------------------------Forecasting data on a dataframe

NOTICE:
1. The current project reads a csv file from the local directory which holds the data until July 11 2021. The Pandas function *read_csv()* can also take urls of datasets as argument. Likewise, a line of code consisting the url as an argument exists in the project; but, it is commented out as it was observed that the updated datasets contain more NULLS and invalid data sequences. However, the model will still read the dataset from the url but aggregation used to answer analytical questions from the data might not work. 

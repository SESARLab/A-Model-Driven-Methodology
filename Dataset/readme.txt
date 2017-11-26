Datasets

We used a log data set containing around 6 weeks of activity collected from SAP systems deployed in a test environment. We considered three features, namely Executed Transaction, Data Sent, and Data Received, extracted from the log files and aggregated per user. For testing purpose, we artificially generated a data set with multi-variate Gaussian distribution having the same average and covariance matrix as the original data points.

All information has been anonymized for privacy reasons.
- combined-simplified.csv contains data about users' transactions including "time, user, transaction, data sent, data received"
- preprocessed_data.csv contains data about users' transactions including "id, user, transaction, data sent, Scale_Data_Transfer"

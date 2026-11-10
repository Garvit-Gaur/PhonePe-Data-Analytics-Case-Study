# Data Dictionary

Descriptions reflect the column names and contents observed in the supplied CSVs. Confirm official metric definitions with the dataset publisher.

- **State_Txn_and_Users.csv:** `State`, `Year`, `Quarter`, `Transactions`, `Amount (INR)`, `ATV (INR)`, `Registered Users`, `App Opens`.
- **State_TxnSplit.csv:** `State`, `Year`, `Quarter`, `Transaction Type`, `Transactions`, `Amount (INR)`, `ATV (INR)`.
- **State_DeviceData.csv:** `State`, `Year`, `Quarter`, `Brand`, `Registered Users`, `Percentage`. A fully blank `Unnamed: 6` column is removed during cleaning.
- **District_Txn_and_Users.csv:** `State`, `Year`, `Quarter`, `District`, `Code`, `Transactions`, `Amount (INR)`, `ATV (INR)`, `Registered Users`, `App Opens`.
- **District_Demographics.csv:** `State`, `District`, `Headquarters`, `Population`, `Area (sq km)`, `Density`, `Code`, `Alternate Name`.

Numeric fields are converted to numeric types in the notebook. Malformed values are coerced to null for analysis.

# Credit card fraud detection using machine learning
The objective of credit card theft is clear. You can remove a large sum of money without the owner's awareness in a short period of time without danger. Scammers are always attempting to carry out genuine fraudulent transactions. This identifies fraud and tough labour, as well as detecting challenging jobs. The simplest approach to identify this sort of fraud is to examine each card's spending habits and look for any deviations from the "normal" spending trends. Machine learning algorithms are employed to analyse all the authorized transactions and report the suspicious ones
## Dependency
* Pandas
* Numpy 
* Matplotlib
* Sklearn
## Dataset
The data is broken into two files identity and transaction, which are joined by TransactionID. Not all transactions have corresponding identity information.
### Categorical Features - Transaction
* ProductCD
* card1 - card6
* addr1, addr2
* P_emaildomain
* R_emaildomain
* M1 - M9
### Categorical Features - Identity
* DeviceType
* DeviceInfo
* id_12 - id_38
The TransactionDT feature is a timedelta from a given reference datetime (not an actual timestamp).
## Project Flow
- Import the data 
- Pre-process Data
- Extract the important features
- Train models using processed data
- Predict using test data and analyze models
## Instruction to implement
- Download the python Notbook
- Download and install the required library
- Download data set
- Run the cells in Notebook one by one to obtain results

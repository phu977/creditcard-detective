# creditcard-detective
<h1>DATASET ATTRIBUTES</h1>
<p1>Dataset contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.</p1>
<col>
    <li>Id- A unique id for each row</li>
    <li>Time - Number of seconds elapsed between this transaction and the first transaction in the dataset </li>
    <li>V1-V28 - Features after dimensionality reduction to protect user identities and sensitive features</li>
    <li>Amount - Transaction amount</li>
    <li>Class - Target Class (1 for fraudulent transactions, 0 genuine)</li>
</col>

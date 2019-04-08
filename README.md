# Analysis of Lending Club data

Lending Club is a peer-to-peer lending platform: https://www.lendingclub.com/. 
They make their data publically available. This data is also availble on kaggle at: https://www.kaggle.com/wordsforthewise/lending-club

This repository contains a number of notebooks that examine this data and do some analysis on loan default prediction.
This is a classification task with the aim of predicting which loans will default.

The first notebook showcases some data exploration, viualization and feature engineering.

The second notebook assess the performance of a set of standard classification algorithms against this dataset.
3 classification algorithms were fitted against a datast of c. 80,000 loans with a c. 28% default rate.
For risk-adverse investors/lenders the classification probability threshold was adjusted to reduce the numbers of False Negatives.

Time permitting a third notebook will provide a more advanced analysis with PCA analysis and classification using a selected subset of features. The dataset as-is contains many credit-history features that are subsumed into the Fico scores and which could be removed. The existing dataset is also imbalanced. Finally these notebooks use a secondary source of Lending Club data. I have not compared the dataset with the original to ensure consistency. The secondary dataset contained some important fields that the public primary datset does not contain, hence the decision to use the secondary dataset provided on kaggle.

The repository also contains the input data used in CSV format.
To reporoduce these notebook it should be enough to clone the repo, ensure the libraries are installed and execute the notebooks.

The classification results are similiar to others I have seen that provide reproducible code.
Time permitting, the next approach will be to evaluate multicollinearity among input feature sets and use sampling methds more robust to imbalanced datasets such as SMOTE  - https://jair.org/index.php/jair/article/view/10302





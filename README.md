# Analysis of Lending Club data

Lending Club is a peer-to-peer lending platform: https://www.lendingclub.com/. 
They make their data publically available. This data is also availble on kaggle at: https://www.kaggle.com/wordsforthewise/lending-club

This repository contains a number of notebooks that examine this data and do some analysis on loan default prediction.
This is a classification task with the aim of predicting which loans will default.

The first notebook showcases some data exploration, viualization and feature engineering.

The second notebook assess the performance of a set of standard classification algorithms against this dataset.
3 classification algorithms were fitted against a datast of c. 80,000 loans with a c. 28% default rate.
For risk-adverse investors/lenders the classification probability threshold was adjusted to reduce the numbers of False Negatives.

Time permitting a third notebook will provide a more advanced analysis. The existing dataset is imbalanced. These notebooks use a secondary source of Lending Club data. I have not compared the dataset with the original to ensure consistency. The secondary dataset contained some important fields that the public primary datset does not contain. 




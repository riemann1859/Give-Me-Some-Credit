Banks play crucial role in market economies. They decide who can get finance and on what terms and can make or break investment decisions. For markets and society to function, individuals and companies need access to credit.

Credit scoring algorithms, which make a guess at the probability of default, are the method banks use to determine whether or not a loan should be granted. This project requires us to improve on the state of the art in credit scoring, by predicting the probability that somebody will experience financial distress in the next two years.

In this project, historical data on 150,000 borrowers id analyzed. We implemented various classification algorithms for predicting whether somebody will experience financial distress in the next two years by looking on various parameters like monthly income, age, number of open credit lines and loans etc.

It is commonly desired for banks to accurately assess the probability of default for their customers so that they can manage their loan risk better. With a better model, they can take calculated risk in lending out to customers thus improving the certainty of their profit. They can tailor make interest rate to cover for the level of risk they are exposed from the loan.

This project is a Kaggle competition issued seven years ago. We sent our predictions in late submission. Our random forest and gradient boosting models give the AUC scores 0.86508 and 0.86864 respectively. In this competition the first rank's score is 0.86955. 

The above results are related to overall accuracy score. However, in such imbalanced datasets, in general costs of false negatives and false positives are not the same. Here to make data more balanced we appeal to over-sampling techniques. By this way, with very small loss in accuracy score, we gain much more recall scores, which compensate the first loss sufficiently in terms of cost. (recall_score=TP/(TP+FN)) 



Jupyter notebook files can be read in https://nbviewer.jupyter.org if there is any need.

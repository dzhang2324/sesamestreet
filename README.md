# sesamestreet
Replication Code/Paper for Kearney and Levine (2019): Early Childhood Education by Television: Lessons from Sesame Street. Link to the original paper: https://www.aeaweb.org/articles?id=10.1257/app.20170300

This replication is my share of the work for a final project in STAT156/256 - Causal Inference (UC Berkeley), done with one other person. I replcate the results in the paper, which are the estimations of two fixed effects regressions, and reanalyze the data in the paper utilizing AIPW/Doubly Robust estimators to estimate the causal effect of interest. All replications are done in R. 

The original paper implements a bootstrapping procedure that is too computationally intensive: I develop an alternative bootstrapping procedure that is discussed more thoroughly in the paper. The code corresponding to the original bootstrapping procedure is labeled as the failed attempt. 

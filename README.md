# sesamestreet

Replication Code/Paper for Kearney and Levine (2019): Early Childhood Education by Television: Lessons from Sesame Street. Link to the original paper: https://www.aeaweb.org/articles?id=10.1257/app.20170300

This repository represents my share of the work for a final project in STAT156/256 - Causal Inference (UC Berkeley), done with one other person. I replcate the results in the paper, which are the estimations of two fixed effects regressions, and reanalyze the data in the paper utilizing AIPW/Doubly Robust estimators to estimate the causal effect of interest. All replications are done in R. The write-up is written entirely by me. 

This paper utilizes census data. It is too large to upload onto GitHub, so the data can be found here: https://drive.google.com/drive/folders/1eYZjPuEdySHfdMZuUBPZeJT6htCw87t-?usp=sharing. Use read.table in R to read the data. 

The paper aims to quantify the causal effect of Sesame Street exposure on school outcomes for those who start preschool coinciding with the initial airing of Sesame Street, and for cohorts who start preschool shortly after. Since the authors do not use data on specific amounts of Sesame Street exposure, they estimate an intent-to-treat effect. The authors also look at the effect of Sesame Street exposure on later life outcomes, specifically around employment and socioeconomic status.

The original paper implements a bootstrapping procedure that is too computationally intensive: I develop an alternative bootstrapping procedure that is discussed more thoroughly in the paper. The code corresponding to the original bootstrapping procedure is labeled as the failed attempt. 

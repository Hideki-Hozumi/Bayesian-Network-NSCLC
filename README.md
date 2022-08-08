# Prediction-with-bayesian-network.  
   This is a supplementary material of an article, "Constructing simple and interpretable network models to predict 
response of Immunotherapy against Non-Small-Cell Lung Cancer" by Hozumi et al.   
   Here, we provide Naive Bayes (NB) and Tree augmented naive bayes (TAN) model to predict durable clinical benefit of patients treated with immunotherapy

# Description.
  NB is a probabilistic model based on Bayes' theorem and the assumption that all covariates are equally important without distinction and are conditionally independent given a class value.   
  TAN is based on Naïve Bayes model. Unlike NB, TAN alleviates conditional independence between features while keeping the directed acyclic graph simple

# Requirement
・The available code works on R, so if you want to try our models, you have to install R to you computer. The dataset is available on cBioPortal (http://www.cbioportal.org).  
・If you want to use the same data as ours, go to (https://www.cbioportal.org/study/summary?id=nsclc_pd1_msk_2018) for Rivizi cohort, and to  (https://www.cbioportal.org/study/summary?id=nsclc_mskcc_2018) for Hellmann cohort.  
・These codes are based on bnlearn package, so for further information, access to (https://www.bnlearn.com).

# Author   
   Hideki Hozumi (Keio University School of Medicine)

# Reference.  
   Hideki H, Hideyuki Shimizu. Constructing simple and interpretable network models to predict 
response of Immunotherapy against Non-Small-Cell Lung Cancer. -----------

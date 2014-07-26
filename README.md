=======
kdd2014
=======
This is the best solution for team "Chaotic Experiments" led by Kiran R who is also the "sole team member"


#######Software Requirements###########
1) R version 3.02 or above
2) Ubuntu 14.04 Trusty Operating System
3) Python 2.7

#######Data Mining Packages###########
1) Vowpal Wabbit (any version) must be installed and the command vw must be runnable from command line meaning vw must be in the PATH variable:
https://github.com/JohnLangford/vowpal_wabbit
2) XGBoost must be installed from Tianqui Chen's repository: https://github.com/tqchen/xgboost
3) 1) The development version of scikit Learn installed  because we use GBMs with early stopping to prevent overfitting + we want to randomly choose the number of trees at each split
4) The following libraries must be installed in R
#  data.table
#  Matrix
#  glmnet
#  doMC
#  foreach
#  rbenchmark
#  Metrics
#  gbm
#  RRF
#  lme4

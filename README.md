# Intelligent-Data-Analysis-Project

The final project for the course 'Intelligent Data Analysis &amp; Machine Learning I' at the University of Potsdam. The given task was to predict the income (under or over 50k) based on interview answers from 30k individuals. The income is known for 5k of the 30k people. The income needs to be predicted for the other 25k people. 

As methods to solve the task, I chose Support Vector Machine (SVM), decision trees and random forest. I did hyperparameter tuning for each method. The different models showed similiar results based on the checked metrics (F-Measure and ROC AUC). The random forest slightly outperforms the other models.

For the future:

* Balance the data set for target variable (e.g. with downsampling)
* Test binning or removing of heavily skewed/imbalanced variables (e.g. gains, losses, country of birth)
* Extent hyperparameter search trying out more combinations (e.g. with RandomizedSearchCV)
* Check if decision trees / random forest perform better without one-hot encoding

## Dataset

Kohavi, R. (1996). Census Income [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5GP7S.

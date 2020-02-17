# Prediction of High Cost Patients

Predicting the likely future healthcare costs of individuals across different social groups is an important and stimulating
computing challenge. To address the problem of controlling healthcare costs, we retrieved data from the MEPS dataset,
which contains general and medical information about 2000 patients collected during 2003 in the United States. After having
conducted a preliminary descriptive analysis, the Pre – Processing phase involved the conversion of data types, the
discretization of continuous attributes of the original dataset and the engineering of a binary feature that will serve as the class
attribute for the classification model. We modeled the task of predicting high cost patients as a binary classification problem.
Once eliminated the redundant attributes, the Naïve Bayes Classifier and the Multilayer Perceptron set up with 1 hidden layer
and 8 artificial neurons emerged as the two best models in terms of Mean Error Rate and F-Measure. We validated the
results through a process of 10-fold Cross – Validation. 

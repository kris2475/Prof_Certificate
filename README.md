# Prof_Certificate
Portfolio project on optimising ML models for real-life data

# Human Activity Recognition


## EXPLANATION 

The project uses a Human Activity Recognition dataset from Universit`a degli Studi di Genova. It is uses accelerometer and gyropscope sensor data from a smart phone to predict the following human activities: 'Walking', 'Walking Upstairs', 'Walking Downstairs', 'Sitting', 'Standing', 'Laying'. 

## DATA
The dataset that I used was produced by Davide Anguita et al of the Universit`a degli Studi di Genova. 
It consists of two datasets (train dataset and test dataset), split 70:30, respectively. Each dataset has 562 input feaures (too many to list here) and six predictors or outputs.

## MODEL 
The models used in this project are 

(1) Decision Tree classifier 

(2) Random Forest classifier 

(3) Logisitcal Regression 

(4) Support Vector Machines 

(5) kNN.

I also tried an ensemble of some of the models, using 'hard' voting. But the accuracy did not improve.


## HYPERPARAMETER OPTIMSATION
Hyperparameter optimisation using grid search was used on the Decision Tree classifier, Random Forest classifier and Logisitc Regression classifier. 
Bayesian Optimisation was used to tune the Support Vector Machine model's hyperparameters.



## RESULTS

All models were tested with a test datsset.

The best performances accuracies as summarised below:

Decision Tree (default hyperparameters):                                  73 %

Decision Tree (criterion='entropy', max_depth=7, min_samples_leaf=20,):   75 %

Random Forest (default hyperparameters):                                  83 %

Logistic Regression (default hyperparameters):                            85 %

Support Vector Machine (default hyperparameters):                         85 %

KNN (k=6):                                                                89 %

Ensemble (soft voting): KNN, LogReg:                                      88.63 %



## CONTACT DETAILS
krishna.seunarine@swansea.ac.uk

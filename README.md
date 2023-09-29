# News Article Classification

the dataset contains five categories (sport, business, politics, entertainment, tech). The task is to classify documents into one of these five categories:

Raw training data with labels:
●  	The dataset contains the raw text of 1063 news articles and the article category. Each row is a document.
●  	The raw file is a .csv with three columns: ArticleId, Text, Category 
●  	The “Category” column are the labels you will use for training

Raw test data without labels
●  	This dataset contains the raw text of 735 news articles. Each row is a document.
●  	The raw file is a .csv with two columns: ArticleId,Text. 
●  	The labels are not provided

Firstly, Evaluate random forests model on pre-processed training data. Use 5-fold cross-validation to evaluate the performance w.r.t. the number of trees (n_estimators) and Report the average training and validation accuracy, and their standard deviation for different parameter values (organize the results in a table).Draw a line figure showing the training and validation result, x-axis should be the parameter values, y-axis should be the training and validation accuracy. 

Secondly,Use 5-fold cross-validation to evaluate the performance w.r.t. the minimum number of samples required to be at a leaf node (min_samples_leaf).Report the average training and validation accuracy, and their standard deviation for different parameter values (organize the results in a table).Draw a line figure showing the training and validation result, x-axis should be the parameter values, y-axis should be the training and validation accuracy. 

Finally,Predict the labels for the testing data (using raw training data and raw testing data). The final classification models used on test data are limited to decision trees, random forests, and boosting trees (AdaBoost, or GradientBoostingTree). It is OK to use other models/methods to do feature engineering (e.g., using word embeddings)



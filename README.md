# Ad-Click-Prediction-on-internet-accessing-users

* Predicting whether or not a user will click on an ad, based on his/her features. As this is a binary classification problem, a logistic regression model is well suited here.

### Dataset:
* 'Daily Time Spent on Site': consumer time on site in minutes
* 'Age': cutomer age in years
* 'Area Income': Avg. Income of geographical area of consumer
* 'Daily Internet Usage': Avg. minutes a day consumer is on the internet
* 'Ad Topic Line': Headline of the advertisement
* 'City': City of consumer
* 'Male': Whether or not consumer was male
* 'Country': Country of consumer
* 'Timestamp': Time at which consumer clicked on Ad or closed window
* 'Clicked on Ad': 0 or 1 indicated clicking on Ad

### Exploratory Data Analysis:
* Used seaborn jointplot and pairplot for analysing data.

### Data splitting for training and testing:
* Used "train_test_split" from scikit-learn library for splitting the dataset into training and testing data.
* Data split is in the fraction of 0.3 for testing and 0.7 for training.

###  Model Training:
* Model is trained over the Logistic Regression Model.

### Evaluations:
* "classification_report" is generated which gives the values of precision, recall, f1-score and support

### Final Result:
* Precision = 92%
* Recall = 92%
* F1-score = 92%

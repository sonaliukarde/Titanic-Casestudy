<H2><B><U>Preprocessing and Training </B></U></H2>

Reading the Titanic data

Finding the Null values in the Dataset

Combined the Test and Train data set to impute the Null values of the entire Dataset

Imputed Null values of the columns Age, Fare, Cabin, Embarked.

Studied the relationship between the Dependent and Independent Variable using the Seaborn library.

Dropped the columns Name, Ticket.

Created the dummies for categorical data

Splitting the Dataset into Train Set (dropped the target variable and added In the Test set) and Test Set in 70% and 30% respectively.

Trained the dataset using the LogisticRegression model

Predicting the final decision associated with an application using this model

And saving the predicted value as LogSub1.csv and uploaded to Kaggle which gate the prediction score 0.76555.

Applied the Feature Engineering to the dataset to get better prediction score.

Again created dummies, spliting data into Train and Test and training the model using the new train dataset, saving the predicted value as LogSub2.csv and uploaded to Kaggle which gave the prediction score 0.78.
test_data_set should be in .csv format

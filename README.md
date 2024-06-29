Titanic Survival Prediction 🚢🔍
Description
English:
This project preprocesses the Titanic dataset to prepare it for machine learning models, aiming to predict passenger survival based on various features.

Español:
Este proyecto preprocesa el conjunto de datos del Titanic para prepararlo para modelos de machine learning, con el objetivo de predecir la supervivencia de los pasajeros en función de varias características.

Conclusion
English:
Hello everyone! 😃

I have completed an interesting data preprocessing exercise using the famous Titanic dataset. 🎉 The objective was to prepare this data for use in machine learning models that can predict whether a person could have survived the sinking of the Titanic. 🚢

Step-by-Step of the Exercise:
Describe the missing values:
First, we identified how many missing values there are in each of the dataset's columns. This helped us understand which variables needed special attention. 📊

Complete missing values in the Pclass column:
Missing values in the Pclass column were completed by assigning class 2 to those individuals. ✌️

Impute data in the Sex column:
We ensured that the Sex column only contained the values "male" and "female". For the missing values, we used the forward fill technique to impute the data. 🚹🚺

Fill missing values in the Age column:
We calculated the average age of the passengers and used this value to fill the missing data in the Age column. 🎂

Assign the value "S" to missing data in the Embarked column:
We completed the missing values in the Embarked column by assigning "S" (Southampton), which was the most common port of embarkation. 🛳️

Details of the Task Performed:
Data preprocessing is a crucial step in any machine learning project. 🧠🔧 In this exercise, we ensured that the dataset was clean and complete, allowing the models to be trained effectively without issues due to missing or inconsistent data.

Throughout this project, I learned the importance of each step in data preprocessing and how it can influence the final performance of the models. 💡

Uploading the Project to GitHub
I will upload the project to a GitHub repository so everyone can access and review the code. Here are the repository details:

Repository Name: titanic-survival-prediction
Repository Description: 🚢🔍 Titanic Survival Prediction: Machine Learning Data Preprocessing Project. This project preprocesses the Titanic dataset to prepare it for machine learning models, aiming to predict passenger survival based on various features.
I hope this project is useful and educational for everyone interested in data preprocessing and machine learning. Thank you for your attention! 🙌

Project Details
Titanic Survival Prediction
This project uses Machine Learning techniques to predict the survival of Titanic passengers based on their characteristics. A logistic regression model is implemented and its accuracy is evaluated.

Project Files
train.csv: Training dataset containing information about the passengers and whether they survived.
test.csv: Test dataset containing information about the passengers without the survival label.
titanic_predictions.csv: Output file with survival predictions for the test dataset.
Requirements
Python 3.7+
Pandas
Scikit-learn (pip install pandas scikit-learn)

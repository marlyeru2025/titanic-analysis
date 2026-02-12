# titanic-analysis

Project Goal: Predict whether a Titanic passenger survived or not (binary classification).

Dataset: Passenger information such as Age, Sex, Pclass, Family size, Ticket, etc.

Data Cleaning:

Fill missing values (Age, Embarked).

Convert categorical features to numeric (Sex, Embarked).


Feature Engineering:

FamilySize = SibSp + Parch

IsAlone = 1 if traveling alone


Model: Random Forest Classifier

Evaluation: Accuracy on validation set

Final Prediction: Apply the model to test data and save results in CSV.

Libraries Used: pandas, numpy, scikit-learn, matplotlib/seaborn (optional)

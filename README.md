# Ensemble_Learning_Bagging
# First i load "diabetes.csv" and check if there is any missing value """df.isnull().sum()"""
# I also look at descripiton of my "df" "mean" "std" itd. """df.describe()""" and use method "value_counts" on my "Outcome" column """df.Outcome.value_counts()"""
# Now i need to create my "X" and "y" as column "Outcome" """X = df.drop('Outcome', axis = 'columns')""" """y = df.Outcome"""
# Then i make "feature scaling", so I import "StandardScaler" from "sklearn.preprocessing" and "scale" my "X" """X_scaled = scaler.fit_transform(X)"""
# Next I can import "train_test_split" and get "train" and "test" set, my "X" is "X_scaled" and I use parameter "stratify" on "y" its "labels array"
# I check shape of my "X_train" and "X_test" and I use method "value_counts" on my "y_train"
# Then I import "classifier" from "sklearn.tree" I import "DecisionTreeClassifier" and from "sklearn.model_selection" I import "cross_val_score"

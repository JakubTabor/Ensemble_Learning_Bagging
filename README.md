# Ensemble_Learning_Bagging
# First i load "diabetes.csv" and check if there is any missing value """df.isnull().sum()"""
# I also look at descripiton of my "df" "mean" "std" itd. """df.describe()""" and use method "value_counts" on my "Outcome" column """df.Outcome.value_counts()"""
# Now i need to create my "X" and "y" as column "Outcome" """X = df.drop('Outcome', axis = 'columns')""" """y = df.Outcome"""

<!DOCTYPE html> <html> <head> <title>FIFA Rankings Data Analysis</title> </head> <body> <h1>FIFA Rankings Analysis</h1> <h2>Project Description</h2> <p>Classification Algorithms Project
This notebook contains code to analyze and compare different classification algorithms on a student admissions dataset.

Data
The dataset used is 'Admission_Predict_Classification.csv', which contains several attributes about students along with their admission status (yes/no).

Algorithms
The following classification algorithms are implemented and their performance compared:

Random Forest
Support Vector Machine (SVM)
Logistic Regression
Decision Tree
Analysis
The dataset is first loaded and cleaned. It is then split into training and test sets.

Each algorithm is trained on the training set and then used to make predictions on the test set. The model performance is evaluated using metrics like accuracy, precision, recall and F1 score.

A bar plot is also generated to visually compare the F1 scores of the different algorithms.

Future Improvements
Some potential ways to improve the analysis:

Try additional/different algorithms
Perform parameter tuning
Add data preprocessing/feature engineering
Implement cross-validation.</p> <h2>Data</h2> <p>The dataset used is 'Admission_Predict_Classification.csv', which contains several attributes about students along with their admission status (yes/no)..</p> <h2>Data Processing</h2> <p>The data is loaded into a pandas DataFrame and preprocessed/cleaned. Invalid or duplicate records are dropped.</p> <h2>Exploratory Analysis</h2> <p>Basic descriptive statistics and aggregations are performed to understand trends in rankings, points etc over time.</p> <h2>Visualization</h2> <p>Various plots like line plots, histograms are created using matplotlib to better visualize patterns and relationships in the data.</p> <h2>Conclusion</h2> <p>Key insights from the analysis are summarized. Potential areas for future extensions discussed.</p> </body> </html>

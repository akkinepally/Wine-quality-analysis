# Wine-Quality-Analysis

The wine dataset has 1600 rows and 12 features and I have decided to analyse which wine was best using dependent variables 
'quality' based on the independent variables:'fixed acidity', 'volatile acidity', 'residual sugar', 'chlorides', 'free sulfur dioxide',
'total sulfur dioxide', 'density', 'sulphates','alcohol','pH','Citric acid'.
step 1)I have imported all the required libraries
step 2)Read the data using data_csv
step 3)Checked for Null values
step 4)Plotted a correlation matrix and removed the variable that were highly correlated.
step 5)Binned the target variables into 2 bins ans labeled them as 0 and 1 ( 0 as bad & 1 as good)
step 6)Split the data
step 7)Scaled the data 
step 8)Built an svm model and got an accuracy of 91
step 9)Used Gridsearch inorder to get an optimal values for the hyper parameters and know if the data is linear or non-linear
step 10)As the data was non linear applied Naive Bayes, Decision tree, Random Forest and KNN
step 11) Random forest had the highest accuracy and f1 score among all the models.

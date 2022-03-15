# Predicting-Heart-Disease
Using Machine Learning techniques to predict the incidence of heart disease in patients, given clinical parameters.

### Data Cleaning 

The data was collected from the University of California Irvine ML database. Before building a model I converted the 'object' variables that included 'Sex'	'ChestPainType'	'RestingECG'	'ExerciseAngina'	and 'ST_Slope' into integer variables - categorical. 

### EDA 

The EDA gave some interesting insights - I found the distribution of heart disease incidents across the genders of particular interest, though I was not surprised! 

![Screenshot 2022-03-15 at 19 24 03](https://user-images.githubusercontent.com/93582626/158456051-5413dce3-34b4-4823-83aa-0cc621eda44b.png)
![Screenshot 2022-03-15 at 19 24 29](https://user-images.githubusercontent.com/93582626/158456059-0d717f44-f161-46a1-b563-2f9af3c0de74.png)

# Model Construction 

The pre-processing segment consisted of Extracting Independent and Target Variables, Splitting Data into Test and Train Split and Dimensionality Reduction.

I then generated a classifier model to predict the incidence of heart disease in patients based on several clinical parameters. Applied Support Vector Machine Classifier and K-Nearest Neighbours to compare model performance. 
Then I optimised the model with Grid Search technique. Linear SVM (C = 1) was selected as the best model, which obtained a best accuracy of 92.4%.

![Screenshot 2022-03-15 at 19 31 08](https://user-images.githubusercontent.com/93582626/158456758-e3edde82-2ab3-4301-8a22-c431d70f4a05.png)

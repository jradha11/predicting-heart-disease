# heart disease dataset
Classification models on Heart Disease Dataset along with exploratory data analysis.

## DATASET OVERVIEW
This dataset has been taken from kaggle and our aim is to predict what sorts of people are likely to have a heart disease.
1. age
2. sex(1-male 0-female)
3. cp( Chest pain) | 0: asymptotic, 1: atypical angina, 2: non-anginal pain, 3: typical angina
4. trestbps(resting blood pressure | (in mm Hg on admission to the hospital))
5. chol(serum cholestoral in mg/dl)
6. fbs(fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
7. restecg(resting electrocardiographic results | 0: showing probable or definite left ventricular hypertrophy by Estes' criteria , 1: normal, 2: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
8. thalach(maximum heart rate achieved)
9. exang(exercise induced angina (1 = yes; 0 = no))
10. oldpeak = ST depression induced by exercise relative to rest
11. slope: the slope of the peak exercise ST segment(0: downsloping; 1: flat; 2: upsloping)
12. ca: number of major vessels (0-3) colored by flourosopy
13. thal: | 1 = fixed defect; 2 = normal; 3 = reversable defect
14. target (yes = 1(>50% chance of having the disease), no=0(<50% chance of having disease))

## Exploratory data analysis
In order to get an insight into the dataset, I have used matplotlib and seaborn libraries to create scatterplots,boxplots etc. 
This helped me in visualising the relationship between the predictors and the target variable and also correlation between the predictor variables and I was able to draw some significant insights.

## Classification models
I used Random Forest and Logistic Regression Machine and obtained the following accuracies on test-set data:
1. Logistic regression: 93.44%
2. Random Forest: 96.72%

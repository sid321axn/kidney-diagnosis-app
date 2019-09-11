# Chronic Kidney Disease Diagnosis Web App

# Overview

In this project I have developed a web app for automated diagnosis of chronic kidney disease cases based on 11 input variables. I have used python and flask for making the web app and hosted it on heroku cloud. The web app is live at (https://kidney-diagnosis-app.herokuapp.com/)

## About Dataset

The dataset used for this project is taken from UCI Mchine Learning Repository at [chronic kidney disease](https://archive.ics.uci.edu/ml/datasets/chronic_kidney_disease).This dataset can be used to predict the chronic kidney disease and it is collected from the Apollo hospital at Tamil Nadu in nearly 2 months of period. 


This dataset contains 24 attributes and 1 Target class variable

## Attribute Information:
------------------------
          
      -- 1. Age(numerical)
      -- 2. Blood Pressure(numerical) - bp in mm/Hg
      -- 3. Specific Gravity(nominal) sg - (1.005,1.010,1.015,1.020,1.025)
      -- 4. Albumin(nominal) al - (0,1,2,3,4,5)
      -- 5. Sugar(nominal) su - (0,1,2,3,4,5)
      -- 6. Red Blood Cells(nominal) rbc - (normal,abnormal)
      -- 7. Pus Cell (nominal) pc - (normal,abnormal)
      -- 8. Pus Cell clumps(nominal) pcc - (present,notpresent)
      -- 9. Bacteria(nominal) ba - (present,notpresent)
      -- 10. Blood Glucose Random(numerical) bgr in mgs/dl
      -- 11. Blood Urea(numerical) bu in mgs/dl
      -- 12. Serum Creatinine(numerical) sc in mgs/dl
      -- 13. Sodium(numerical) sod in mEq/L
      -- 14. Potassium(numerical) pot in mEq/L
      -- 15. Hemoglobin(numerical) hemo in gms
      -- 16. Packed Cell Volume(numerical)
      -- 17. White Blood Cell Count(numerical) wc in cells/cumm
      -- 18. Red Blood Cell Count(numerical) rc in millions/cmm
      -- 19. Hypertension(nominal) htn - (yes,no)
      -- 20. Diabetes Mellitus(nominal) dm - (yes,no)
      -- 21. Coronary Artery Disease(nominal) cad - (yes,no)
      -- 22. Appetite(nominal) appet - (good,poor)
      -- 23. Pedal Edema(nominal) pe - (yes,no)
      -- 24. Anemia(nominal) ane - (yes,no)     

## Attributes types
-----------------

Numerical: 1,2,10,11,12,13,14,15,16,17,18
Nominal: 3,4,5,6,7,8,9,19,20,21,23,24


## Variable to be predicted
------------------------
Class - nominal - (ckd, notckd)

400 observations

# Dependencies
This project requires Python 3.x and the following Python libraries installed:
- [Numpy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](https://matplotlib.org/)
- [scikit-learn](https://scikit-learn.org/stable/)
- [scipy](https://www.scipy.org/)
- [mlextend] (https://pypi.org/project/mlxtend/)
- [lime] (https://pypi.org/project/lime/)
- [flask 1.1.1](https://pypi.org/project/Flask/)

Use **pip** to install any missing dependencies.
I also reccommend to install Anaconda, a pre-packaged Python distribution that contains all of the necessary libraries and software for this project which also include jupyter notebook to run and execute [IPython Notebook](http://ipython.org/notebook.html).

## Run :

In a terminal or command window, navigate to the top-level project repo kidney-diagnosis-app/(that contains this README) and run one of the following commands:

```ipython notebook Chronic_kidney_Classification.ipynb```
or

```jupyter notebook Chronic_kidney_Classification.ipynb```

This will open the iPython Notebook software and project file in your browser.

# Model Evaluation :
I have done model evaluation based on following sklearn metric.
- Confusion Matrix
- Sklearn classification report
- Mcnemar Test

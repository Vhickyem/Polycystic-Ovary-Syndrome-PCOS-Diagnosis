# Polycystic-Ovary-Syndrome-PCOS-Diagnosis
The aim of this project was to build a model that diagnoses if a patient has the PCOS or not.
## Data
Dataset was gotten from Kaggle https://www.kaggle.com/datasets/prasoonkottarathil/polycystic-ovary-syndrome-pcos
It was cleaned and manipulated using Python Programming Language.
* All useless columns were removed 

![Screenshot_20230320-080523](https://user-images.githubusercontent.com/99379120/226311389-c4eef987-2649-4139-acab-a57eb670ba5f.png)

* Duplicate values were checked for

![Screenshot_20230320-080701](https://user-images.githubusercontent.com/99379120/226311892-61ed33b4-86a8-4479-9569-3618dfa10be1.png)

* Whitespaces in column names were removed and columns were changed to appropriate data types.

![Screenshot_20230320-080856](https://user-images.githubusercontent.com/99379120/226312303-3cf9b2cc-29ab-4c97-9b27-ef90846efd91.png)

* Missing BMI data was calculated using weight and height provided in the dataset and other null values were dropped.

![Screenshot_20230320-081054](https://user-images.githubusercontent.com/99379120/226312843-a1f0d1e7-7269-4a86-bc79-ed5c311a6bc0.png)

## Python Packages

## Methodology
Visualizations were done to explore the dataset and to check relationship between variables. A Classification model was used to diagnose the patients. The model's performance was also checked.
### Visualizations
* An heatmap was used to check for correlation between variables
* A countplot was used to show how many of the patients had PCOS
* Relationship between all numerical variables and target variable were shown using box plot
* Relationship between all categorical variables and the target variable were shown with bar plot.

### Classification / Diagnosis
* A logistic Regression model was used.
* The model was trained using 70% of the Dataset and tested using 30% of the same dataset.
* Model Accuracy score was checked to be 0.83
* Model Performance was checked using a confusion mateix

![Screenshot_20230320-082107](https://user-images.githubusercontent.com/99379120/226315980-2fc78004-b5bc-47b0-ac24-0a1af58162f6.png)

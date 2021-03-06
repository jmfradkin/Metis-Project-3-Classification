# Metis-Project-3-Classification

*Project 3 of Metis Data Science Bootcamp.* Problem statement below:  

Use supervised learning and classification methods to predict a discrete response variable in a data set.
___
I am using a [data set](https://archive.ics.uci.edu/ml/datasets/Heart+Disease) detailing various elements of patients' medical records in order to predict whether or not they will be diagnosed with coronary artery disease. My goal is to find a model that accurately predicts heart disease diagnosis for both men and women so that I can compare the weight of features in both models.  

The features are:  
1. ECG Reading during Exercise (slope)  
2. ECG Reading during Rest (restecg)  
3. Chest Pain Type (value 1-4)  
4. Exercise induced angina (exang--boolean)  
5. Hypertension (htn--boolean)
6. Age  
7. Cholesterol (chol)  
8. Resting Heart Rate (thalrest)  
9. Peak Heart Rate during exercise (thalach)  
10. Resting BP (trestbp--Sys. + Dias.)
11. Peak BP (tpeakbp--Sys. + Dias.)  

Response variable (num) = 1 for positive diagnosis, 0 for negative diagnosis. 
___

###Files
 
-`male5.csv` and `fem5.csv` are the cleaned data sets I used for the project.  
-`mcnulty_models-final.ipynb` shows the modeling analysis on this data.

The project **blog post** can be found [here](https://jamiefradkin.wordpress.com/2016/02/20/metis-project-3-predicting-heart-disease-diagnosis-with-classification-methods/). The project presentation can be found [here] (http://www.slideshare.net/JamieFradkin/metis-project-3-predicting-heart-disease-diagnosis).

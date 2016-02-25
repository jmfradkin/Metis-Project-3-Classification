# Metis-Project-2-Classification

*Project 3 of Metis Data Science Bootcamp.* Problem statement below:  

Use supervised learning and classification methods to model a discrete response variable in a data set.

I am using a data set detailing various elements of patients' medical records in order to predict whether or not they will be diagnosed with coronary artery disease. My goal is to find a model that accurately preducts heart disease diagnosis for both men and women so that I can compare the weight of features in both models.  

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

This repo contains an iPython notebook showing the modeling analysis on this data.

Here is a link to the [project presentation](https://docs.google.com/presentation/d/1pvAz2v6ZQMDWX4bKPi-zoZJtcTENkDBmq24u9sly6ZY/edit#slide=id.p4).
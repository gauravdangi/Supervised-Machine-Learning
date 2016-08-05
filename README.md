# Supervised-Machine-Learning

I have implemented two supervised classification problem (Heart disease prediction and Springleaf Marketing Response) using 
machine learning algorithms. In heart disease prediction, we need to predict the status of heart disease which can be 0, 1, 2, 3 
and 4. These 5 classes are not cleared by data dictionary but 0 means diameter narrowing is less than 50%.


In Springleaf marketing response, we have a large anonymous dataset (with 1933 features) to predict whether the customers likely 
to respond and be good candidates for their services.


# 1] Heart Disease Diagnosis Prediction:-  
Heart disease dataset contains 4 dataset concerning heart disease diagnosis. Dataset contains 74 attributed from which only 14 are used and this was further reduced to 10. In this we need to predict whether a patient’s heart status which have 5 possible values and it’s unclear from the data dictionary what these 5 status means.
I have implemented lot of machine learning algorithms (Generalized boosted regression, linear discriminant analysis, random forest, logistic regression, support vector machine, etc.) and cross validate all results. The data is collected from 4 different location:-
- Cleveland Clinic foundation
- Hungarian Institute of cardiology
- V.A Medical Centre, Long Beach 
- University Hospital
I have used Cleveland Clinic foundation dataset. We need to predict the diagnosis of heart disease which is either 0, 1, 2, 3 or 4(5 Classes)
    0: <50% diameter narrowing 
    1: >50% diameter narrowing 
But it contains value 0, 1, 2, 3, 4 which is 5 factors. It is unclear what these                                             status means.
Number of attributes are 76 but I have used 14 main attributes that are:
 -Age, sex(0:female & 1:male),
 cp(Chest pain type):
   1: for typical angina
   2: for atypical angina
   3: for non-anginal pain
   4: for Asymptomatic 
Trestbps(Resting blood pressure), chol, fbs, restecg, thalach(max heart rate achieved), exang, oldpeak, slop, ca, thal(3 = normal; 6 = fixed defect; 7 = reversible defect)  and num (the predicted attribute)  


# 2] Springleaf Marketing Response:-
Springleaf offers their customers personal and auto loans that helps their customers to take control of their lives and finances. Springleaf’s team connect with their customers through direct mail whom may be in need of a loan.
Direct mails provides huge value to customers who is in need of loan and it’s a fundamental part of Springleaf’s marketing strategy. Now here in order to improve their targeted efforts, our job is to predict the customers who are likely to respond and a good candidate for their services. Data provided is anonymous and large.
Using a large anonymised data-set, I predicted which customer will respond to a direct mail. A different approach is required to work with such a large dauntingly dataset.

-> Mail me If you want code (Layers function Script will not be provided). I have implemented this in R.


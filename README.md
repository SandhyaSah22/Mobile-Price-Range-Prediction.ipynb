# Mobile-Price-Range-Prediction.ipynb

Problem Statement:
In the competitive mobile phone market companies want to understand sales data of mobile phones and factors which drive the prices. The objective is to find out some relation between features of a mobile phone(eg:- RAM, Internal Memory, etc) and its selling price. In this problem, we do not have to predict the actual price but a price range indicating how high the price is.

#Data Description -

Battery_power - Total energy a battery can store in one time measured in mAh

Blue - Has bluetooth or not

Clock_speed - speed at which microprocessor executes instructions

Dual_sim - Has dual sim support or not

Fc - Front Camera mega pixels

Four_g - Has 4G or not

Int_memory - Internal Memory in Gigabytes

M_dep - Mobile Depth in cm

Mobile_wt - Weight of mobile phone

N_cores - Number of cores of processor

Pc - Primary Camera mega pixels

Px_height - Pixel Resolution Height

Px_width - Pixel Resolution Width

Ram - Random Access Memory in Mega Bytes

Sc_h - Screen Height of mobile in cm

Sc_w - Screen Width of mobile in cm

Talk_time - longest time that a single battery charge will last when you are

Three_g - Has 3G or not

Touch_screen - Has touch screen or not

Wifi - Has wifi or not

Price_range - This is the target variable with value of
0(low cost),
1(medium cost),
2(high cost) and
3(very high cost).

Thus our target variable has 4 categories so basically it is a Multiclass classification problem.

#EDA on given Data set:

Digging into data we understand that

1. There is no null and missing value in the data set.
2. There are mainly 21 Features.
3. Dependent variable should be considered as Price Range.
4. There are Factors affecting the dependent variable such as RAM, Battery Power,
camera, etc .
5. The heatmap gives a good correlation between the given Feature.

#Models used :

∙ KNN

∙ Random Forest

∙ Gradient Boosting Classifier

∙ XGBClassifier

∙ Logistic Regression

∙ Decision Tree Classifier

∙ Support Vector Machine

∙ Gridsearch CV

#Conclusion:

∙ RAM in mobile phones is a very important feature for the price range prediction of mobile . as the
ram and battery power increase the price range increases.

∙ According to the user specifications the camera plays the role of attracting the
customer. ∙ Customer prefers the longer Battery backup for long-lasting.

∙ kneighbors classifier is giving the best results for this dataset.

∙ We build a predictive model, which could help companies estimate the price of mobiles effectively.

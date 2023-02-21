# Linear-Regression_Mobile-Price-Prediction
## Term project done on linear regression analysis on Mobile Price Prediction data set

# Problem Statement

- Renowned mobile company facing huge competion in the exisiting mobile product categories
- They wanted to conquer the competiton by re catrgorization of the some of the products.
- As a data scientist we have to analyze Mobile Price basis the Mobile Features so that competitive prodcut can be launched with the Best Price
- Objective is to find which features have more impact on mobile price and provide information on it.

>Distribution of the target feature

![image](https://user-images.githubusercontent.com/106458239/216774422-19ff4932-0406-43d4-b3ab-5ff5f4189a33.png)

>Screen Rosolution distribution in Mobile Price

![image](https://user-images.githubusercontent.com/106458239/216774455-a7fd459a-0c39-44e4-bc99-8737421e194d.png)

>Coefficients of independent variables

![image](https://user-images.githubusercontent.com/106458239/216774471-ff16d2a5-0b5e-4972-ae8e-49cb9947cb69.png)

>Regression Plot

![image](https://user-images.githubusercontent.com/106458239/216774534-5bc46232-8159-41be-97dd-74377b1a9323.png)

** Conclusion **

- We have analyzed and understood the different features that can influence price of the mobile.

- PPI, CPU Core, CPU Freq, Internal Memory, Rear_Cam & Front Cam is an important role in determining the price of the mobile.

- We have also built a predictor to estimate the mobile price based on those influential features.

- The model performs decently as shown by our evaluation metrics.

- This can help the mobile company to predict best price and cut the competition.

- Since the data is less, getting more records can improve the model's performance.

** Scores achieved from the analysis **

Mae for the training is 136.11983095593305
Mae for the test is 142.33353538715346

MSE for the training is27192.36926698868
MSE for the test is27575.599815168986

RMSE for the training is 164.90108934445726
RMSE for the test is 166.05902509399778

R2 score for training is 0.9536945242083958
R2 score for test is 0.9520086347128638

Adjusted R2 for training is 0.9488626484736198
Adjusted R2 for test is 0.923213815540582

## Have created model using  Decision Tree Regressor  & Random Forest Regressor to check for model accuracy.

** Scores achieved from the analysis **

>By using Descion Tree Regressor we are getting below scores:


RMSE for the training is 0.0

RMSE for the test is 114.97377830170537

R2 score for the training is 1.0

R2 score for the test is 0.9769942845233095

AdjR2 score for the training is 1.0

AdjR2 score for the test is 0.9631908552372952


>By using Random Forest Regressor we are getting below scores:


RMSE for the training is 61.88997763799282

RMSE for the test is 121.1840081208838

R2 for the training is 0.9935773217943683

R2 for the test is 0.9701418883846334

AdjR2 for the training is 0.9929966945033458

AdjR2 for the test is 0.96322070214154135


**By Decision Tree Regressor method we have noticed R2 & AdjR2 score for the training is 1, and test score difference less than 5% hence we are not facing any issue of over fillitng here**

**By Random Forest Regressor Method R2 & AdjR2 score for the training & test score difference less than 5% hence we are not facing any issue of over fillitng here**



# credit-risk-classification
Module 20
Code in stater_code folder within credit_risk_classification.ipynb
Analysis

The purpose of this analysis is to test our models that try to assess which factors will lead to a high risk loan. The variable this analysis is trying to predict is whether the loan will be high rish or low risk. To accomplish this first the variable were split into two data frames one that is the variable we are trying to predict and the rest that determine what the loan status will be. To do this a Logistic Regression model was used below are the results.

             
              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.84      0.94      0.89       619
  
         accuracy                      0.99     19384
         macro avg 0.92      0.97      0.94     19384
      weighted avg 0.99      0.99      0.99     19384


 This analysis is attemtpting to figure out whether or not we can predict what will be a high risk versus a low risk loan. For 0 which represents non high risk loans high precison and recall are achieved as shown by the extremely high f score. Precsion means the model is able to not mislabel a negative as a postive. In this case whether the loan is low risk. Recall means the abilty to locate all the postive instances. The combination of no mislabels indicated by the precision being 1 and high recall being .99 indciates this is a great model for identifying low risk loans. Therefore for low risk loans the company absolutely should use this model.

For 1 which is high risk loans the recall is good but more mistakes in the model then low risk. Precison is not working as well with the model with the score being at .84. My recommedation would be to increase the support which is the actual number of instances in this case of high risk loans. Increase the data on high risk see if the model gets better and if it does not make the decison from there. The difference of support or instances of occurences between the two models is just too much to suggest that the high risk model would not get better as it gets closer to the support or instances of low risk. The company should use the logistic regression model to figure out low risk loans. For high risk loans more data should be added to the model before making a decsion on whether or not to use it for high risk loans.


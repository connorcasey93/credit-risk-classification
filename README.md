# credit-risk-classification
Module 20
Code in stater_code folder within credit_risk_classification.ipynb
Analysis
The purpose of this analysis is to test our models that try to assess which factors will lead to a high risk loan.
             
              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.84      0.94      0.89       619

    accuracy                           0.99     19384
   macro avg       0.92      0.97      0.94     19384
weighted avg       0.99      0.99      0.99     19384

For 0 which represents non high risk loans high precison and recall are achieved as shown by the extremely high f score. Precsion means the model is able to not mislabel a negative as a postive. In this case whether the loan is low risk. Recall means the abilty to locate all tje postive instances. The combination of no mislabels indicated by the precision being 1 and high recall being .99 indciates this is a great model for identifying low risk loans. Therefore for low risk loans the company absolutely should use this model.
For 1 which is high risk loans the recall is good but more mistakes in the model then low risk. Precison is not working as well with the model with the score being at .84. My recommedation would be to increase the support which is the actual number of instances in this case of high risk loans. Increase the data on high risk see if the model gets better and if it does not make the decison from there. The difference of support or instances of occurences between the two models is just too much to suggest that the high risk model would not get better as it gets closer to the support or instances of low risk.


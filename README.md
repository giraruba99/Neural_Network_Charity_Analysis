# Neural_Network_Charity_Analysis
## Purpose of the analysis
- The main purpose of this analysis is to use deep learning (neural network) to study how success of charitable donation, that way we can correctly predict trens for future. 

## Result and Analysis
  * Deliverable 1

  - In the data processing step, we were able to succesfully remove the NAME and EIN colums as they are not needed for the analysis.
  - When looking for target model, we found the Is-Successful column as out target model.
  - We were able to consolidate a dataframe by merging encoded features and drop the originals, and got the column names are: NAME, APPLICATION, TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT,SPECIAL_CONSIDERATIONS, STATUS, and ASK_AMT.

  * Deliverable 2

  - In this step we were able to succesfuly add two layers, with 30 and 80 Neurons .
  - For the activation function, we used relu for both hidden layers.
  - For the output layet, we used Sigmoid activation function.
  
  * Deliverable 3 

  - In this step we created 5 hidden layers, out of which the 1st layers was with 60 Neurons and the rest 4 layers were with 70 neurons each.


## Summary and Conclusion

- Finally it can be concluded that, our deep learning model does not reach our target of 75% accuracy. But over all, it proved the deep learning system to be effective and realiable method of machine learning that can help a lot of business decisions based on trained models.


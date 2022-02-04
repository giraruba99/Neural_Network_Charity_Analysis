# Neural_Network_Charity_Analysis
## Purpose of the analysis
- The main purpose of this analysis is to use deep learning (neural network) to study how success of charitable donation, that way we can correctly predict trens for future. 

## Result and Analysis
  ### Deliverable 1

  - In the data processing step, we were able to succesfully remove the NAME and EIN colums as they are not needed for the analysis.

![df](https://user-images.githubusercontent.com/89214854/152468813-82cf65c1-f0d4-438e-aba8-a627600ae2b5.png)


  - When looking for target model, we found the Is-Successful column as out target model.
  - We were able to consolidate a dataframe by merging encoded features and drop the originals, and got the column names are: NAME, APPLICATION, TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT,SPECIAL_CONSIDERATIONS, STATUS, and ASK_AMT.

  ### Deliverable 2

  - In this step we were able to succesfuly add two layers, with 30 and 80 Neurons .
  - For the activation function, we used relu for both hidden layers.
  - For the output layet, we used Sigmoid activation function.
  
  ![hidden layers D2](https://user-images.githubusercontent.com/89214854/152468830-db9a8090-dce1-422a-9591-26e51b72ebd1.png)

  
  ### Deliverable 3 

  - In this step we created 5 hidden layers, out of which the 1st layers was with 60 Neurons and the rest 4 layers were with 70 neurons each.

![hidden layers D3](https://user-images.githubusercontent.com/89214854/152468856-a50f858b-5d56-4425-b1c9-15e3f999b1e4.png)



## Summary and Conclusion

- Finally it can be concluded that, our deep learning model does not reach our target of 75% accuracy. But over all, it proved the deep learning system to be effective and realiable method of machine learning that can help a lot of business decisions based on trained models.


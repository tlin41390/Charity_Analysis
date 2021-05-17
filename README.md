# Charity_Analysis
Overview
  The purpose of this analysis is to beable to process data, extract the data and fit a model so that a neural network can attempt to interpret the data and make predictions
  
## Results
  * Preorcessing the Data
    * Data Preprocessing: The target variables that we wanted to use was the "IS_SUCCESSFUL" feature, which is what we wanted to predict for the success rate of the charity data
    * The features for my neural network model is the APPLICATION_TYPE and CLASSIFICATION in order to determine the integrity of the charity organization
    * During the processing, I had to remove STATUS, INCOME_AMOUNT, as well as  SPECIAL_CONSIDERATIONS because they did not assist us in the assessment. 
  * Constructing Model
    * When creating the model 1 used 2 hidden layers because it seemed like it would help in improving the accuracy score of the model we are trying to use.
  [hidden_nodes](https://github.com/tlin41390/Charity_Analysis/blob/main/images/plot.png)
    * Unfortunately I was not able to get above 75% accuracy for the machine learning model.
   **Initial Test**
  [accuracy score](https://github.com/tlin41390/Charity_Analysis/blob/main/images/accScore.png)
  **Mod 1**
  [accuracy score 2](https://github.com/tlin41390/Charity_Analysis/blob/main/images/accScore2.png)
  **Mod 2**
  [accuracy score 3](https://github.com/tlin41390/Charity_Analysis/blob/main/images/accScore2.0.png)
  **Mod 3**
  [accuracy score 4](https://github.com/tlin41390/Charity_Analysis/blob/main/images/accScore3.png)
    * The modifications I tried to do is increase the number of hidden nodes, I also increased the epochs of the machine learning model. Finally I tried to combine both of the    modifications into one run   

  

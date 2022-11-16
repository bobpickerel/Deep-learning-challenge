# Deep-learning-challenge
1 - Purpose of the analysis - This dataset provided data regarding different fund raising campaigns and marked each as being successful or not in meeting their income goal.  The neural network build is used to predict if the campaign is succesful based on the data criteria provided.

2 - Results
- Data Preprocessing

  a. The target of the model is the is_successful data point.  This indicates if the campaign was successful or not.
  
  b. Variables - Application_type, affiliation, classification, use_case, organization, status, income_amt, special_considerations, ask_amt
  
  c. Variables removed - EIN and Name
  
- Compiling, Training, and Evaluating the Model

  a. through optimization - 22 nodes and 5 layers was determined to be the best setup for the optimization
  
  b. model performance was 73.22% which is on the low side of acceptability
  
  c. in order to increase the model performance different numbers of neaurons and layers were used to determine performance.
 
 3 - Summary
 Overall results do not support using this model going forward.  Retesting the model with a Supervised learning technique such as Random Forest may provide better results.

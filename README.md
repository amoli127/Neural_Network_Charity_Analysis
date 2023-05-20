# Neural_Network_Charity_Analysis
## overview of Project
The purpose of this analysis is to create a predictive model using deep learning neural network. The model aims to accurately determine the success of organizations that receive funding from Alphabet Soup. By analyzing various features in the dataset, we can gain valuable insights and make informed predictions about the outcomes of these organizations.

## Results

### Data Preprocessing:

  - **What variable(s) are considered the target(s) for your model?**
     - The target variable for the model is "IS_SUCCESSFUL," which indicates the success of the funded organization.

  - **What variable(s) are considered to be the features for your model?**
     - The features for the model include various variables such as "APPLICATION_TYPE," "AFFILIATION," "CLASSIFICATION,"  "USE_CASE," "ORGANIZATION," "INCOME_AMT," and "SPECIAL_CONSIDERATIONS." These features provide information about the organization's characteristics, application type, affiliation, classification, use case, income amount, and special considerations.
   - **What variable(s) are neither targets nor features, and should be removed from the input data?**
      - The variables "EIN" and "NAME" are neither targets nor features and should be removed from the input data. These variables do not contribute to the prediction of the organization's success and can be considered irrelevant for the model.

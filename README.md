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

### Compiling, Training, and Evaluating the Model:

  - **How many neurons, layers, and activation functions did you select for your neural network model, and why?**
     -  The model contains two hidden layers, the first with 80 nodes and the second with 30. The choice of the ReLU activation function in these layers helps detect and represent various patterns and features in the input data. For the output layer, the sigmoid activation function was selected to generate binary classification probabilities, allowing us to assess the likelihood of success for Alphabet Soup-funded organizations.
  - **Were you able to achieve the target model performance?**
     -  The initial model performance did not achieve the target accuracy of 75%. The accuracy levels obtained in the first and second attempts were 0.68 and 0.54, respectively, indicating that the model could not accurately predict the success of Alphabet Soup-funded organizations.
  - **What steps did you take to try and increase model performance?**
     -  I tried out different arrangements of hidden layers, varying the number of neurons and activation functions, to discover the best combination that could effectively capture the intricate relationships in the data.

## Summary

Overall, the deep learning model achieved a moderate level of accuracy but fell short of the target performance of 75%. Despite several attempts to optimize the model, the highest accuracy obtained was below the desired threshold.

Additionally, exploring feature engineering techniques could be beneficial. This involves creating new relevant features or applying dimensionality reduction methods to improve the quality and representation of the input data. By carefully selecting and transforming features, we can extract more meaningful information and enhance the model's performance.

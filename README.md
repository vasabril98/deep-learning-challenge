# Alphabet Soup Charity Funding Predictor

## Overview of the analysis: 
The purpose of this project is to develop a binary classifier using neural network models for the fictional nonprofit foundation Alphabet Soup who wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With the dataset provided, a binary classifier was created that can predict whether applicants will be successful if funded by Alphabet Soup.

The dataset received is a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

<img width="646" alt="image" src="https://github.com/vasabril98/deep-learning-challenge/assets/120423945/afdfc559-e609-40bf-a67d-830669b5868e">


## Results: Using bulleted lists and images to support your answers, address the following questions:

### Data Preprocessing

* After running the model with different combination of features, the features that hold majority of the signal required for the model to achieve the target model performance are:
    * ```APPLICATION_TYPE```
    * ```AFFILIATION```
    * ```CLASSIFICATION```
    *```USE_CASE```
    * ```ORGANIZATION```
    * ```INCOME_AMT```
    * ```ASK_AMT```
* On the other hand, the feature that hold little to no significance for the model to performace are:
    * ```EIN ```
    * ```STATUS```
    * ```SPECIAL_CONSIDERATIONS```  
* For the purporse of this project the target variable that is being predicted is  ``` IS_SUCCESSFUL```

### Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
Were you able to achieve the target model performance?
What steps did you take in your attempts to increase model performance?

## Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

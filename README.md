## Annette Donald Blackburn

# Module 19: Neural Network Model Challenge
### Overview and Purpose of Analysis
A company, Alphabet Soup, wants to predict where they should invest. Using machine learning models and deep neural networks, the goal is to create a binary classifier that is capable of predicting whether applicants will be successful if they are funded by Alphabet Soup. 

The methods for the analysis are:
- preprocessing the data for the neural network model
- compline, train, and evaluate the model
- optimize the model 

### Results

#### Data Preprocessing
1. What variable(s) are considered the target(s) for your model?
The target for the model is the variable that indicate success.
2. What variable(s) are considered to be the features for your model?
The IS_SUCCESSFUL column is the feature for this model.
3. What variable(s) are neither targets nor features, and should be removed from the input data?
The EIN and NAME columns are neither targets nor features and should be removed from the input data.

#### Compiling, Training, and Evaluating the Model
4. How many neurons, layers, and activation functions did you select for your neural network model, and why?
5. Were you able to achieve the target model performance?
The target of the model was 75% and considering that I could not get tensorflow to work on my M1 Mac, I was not able to achieve the target model performance.
6. What steps did you take to try and increase model performance?
The steps I took to try and increase model performance was to troubleshoot tensorflow issues. I created new Anaconda environments with different Python versions (3.5, 3.6, 3.7, etc.) and installed tensorflow different ways.

### Summary
#### Summary of Results
The deep learning neural network did not reach the target of 75% accuracy since I could not get tensorflow to run on my M1 Mac.
#### Recommendation on using a different model to solve the classification problem and justification
Since creating a binary classifier was the goal, a supervised machine learning model, like a Random Forest Classifier, could be better since it wouldn't be as impacted by outliers. Another possibly model could be a Support Vector Machine because they are less prone to overfitting.
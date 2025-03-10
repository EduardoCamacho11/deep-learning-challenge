# deep-learning-challenge

1.	Overview of the analysis: Explain the purpose of this analysis.
o	The purpose of this analysis is to develop a deep learning model to help select the applicants for funding with the best chance of success. The goal was to preprocess the data, build a neural network, and evaluate its performance to predict certain target variables based on a set of features. The analysis aimed to identify the appropriate variables for the model, optimize the neural network architecture, and evaluate its ability to meet predefined performance targets.
2.	Results: Using bulleted lists and images to support your answers, address the following questions:
o	Data Preprocessing
	What variable(s) are the target(s) for your model?
1.	The variablle targeted for this model was ‘Application_type’.
	What variable(s) are the features for your model?
1.	The  variable that were the features for this model were ‘classification'’ 
	What variable(s) should be removed from the input data because they are neither targets nor features? 
1.	The variables that were removed were ‘EIN’ and ‘NAME’. 
o	Compiling, Training, and Evaluating the Model
	How many neurons, layers, and activation functions did you select for your neural network model, and why?
1.	I used 80 neurons in the first hidden layer and 30 neurons in the second hidden layer. The activation function I used was ReLu in my first layer and sigmoid in the second layer. 
	Were you able to achieve the target model performance?
1.	The target was not met. The achieved accuracy was 73% and the target accuracy was 75%.
	What steps did you take in your attempts to increase model performance?
1.	The steps taken to increase model performance were removal of columns and adjusting the number of neurons.
3.	Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
o	Overall the deep learning model achieved good performance in predicting the target variable, with accurace reaching approximately 73%. However, with further tuning I was not able to reach the target accuracy of 75%. Several step were taken such as replacing cutoffs in my data and changing the number of neurons used. 

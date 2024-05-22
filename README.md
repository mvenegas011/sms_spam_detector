# sms_spam_detector
Module 21 Challenge

Create the SMS Classification Function
Using the code in the sms_text_classification_solution.ipynb file, create the sms_classification function in the gradio_sms_text_classification.ipynb by doing the following:

Set the features variable to the text message column of the DataFrame.

Set the target variable to the "label" column of the DataFrame.

Split data into training and testing and set the test_size to 33%.

Build a pipeline to transform the test set to compare to the training set.

Fit the model to the transformed training data and return model.

Load the SMSSpamCollection.csv into a DataFrame and call the sms_classification function with the DataFrame, and set the result to the "text_clf" variable.

Create the SMS Prediction Function
Use the sms_prediction function to predict the classification of a new text by doing the following:

Create a variable that will hold the prediction of a new text.

Use a conditional statement that determines if the text message is "ham" or “spam”.

If the message is “ham”, the function should return the following message: f'The text message: "{text}", is not spam.'

If the message is spam, the function should return the following message: f'The text message: "{text}", is spam.'

Create the Gradio Interface Application
Create a Gradio Interface application that takes a textbox for the inputs and has a textbox for the output. 

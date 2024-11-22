# Week 21 Kala SMS Spam Detector Challenge

### Step 1: Create the SMS Classification function
* Read the input CSV file.
* Set features to 'text_message' and target to 'label' columns.
* Split input data into train and test, where test size = 33%.
* Built a pipeline with the TfidVectorizer and LinearSVC model.
* Train and test the model.
* Accuracy score is 98.9% on the test data.

### Step 2: Create the SMS Prediction function
* Create a function to predict if a message is Ham or Spam.
* Return a conditional message based on prediction.

### Step 3 Create a Gradio app
* Create a Gradio app that accepts as input an SMS text message and return prediction of Ham or Spam.
 
### Sources of code
* Most of my code is based on code provided in starter code files and in exercises by the AI Bootcamp.
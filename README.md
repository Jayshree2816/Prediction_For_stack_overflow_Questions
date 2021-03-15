# Prediction_For_stack_overflow_Questions
Download dataset from https://www.dropbox.com/s/5721wcs2guuykzl/stacksample.zip?dl=0

# Goal : Given text for Questions , predict tags associated with them 

Suggested Guidelines : 

1. Pick top 10 most occurring tags and filter data for them and build your model for them 

2. You can expand your model later on 

3. Since there is no performance threshold and associated data given to you , you'll need to separate data in train/validation yourself 

4. Before directly jumping in with LSTM ( or any other model of your choice ) , explore this text data and see if any basic data cleaning is required .

# Solution :

1. Data cleaning using regex

2. Plot the top 10 tags 

3. Split the data set shared into trainig and validation data.

4. Update question and respective tags in question_clean file

5. Using RNN build the model and predict the f1_score: 0.83 with a 0.89 Validation accuracy




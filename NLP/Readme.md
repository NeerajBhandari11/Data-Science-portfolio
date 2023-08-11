# Twitter Sentiment Analysis

Twitter Sentiment Analysis will classify the Twitter data provided for each user and predict the Gender of the user ID provided in the test dataset. To perform this task following steps are followed:

Twitter data for each user is fetched from the XML file provided for each user.
Text processing and the feature extraction process are done for tweets once we extract data for all users from the unstructured data file and convert the extracted data into a suitable format.
After preprocessing, we split user data into train and test based on the user ID provided in Train and Test datasets respectively.
Using the preprocessed data and extracted feature the classifier model is built to predict the gender of the user.

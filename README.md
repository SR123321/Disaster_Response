# Disaster_Response
Disaster Response Udacity Project: A machine learning pipeline implemented through a web app that classifies messages to assist with disaster emergency response.

Instructions:

Run the following commands in the project's root directory to set up your database and model.

To run ETL pipeline that cleans data and stores in database python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db
To run ML pipeline that trains classifier and saves python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl
Run the following command in the app's directory to run the web app. python run.py

Go to http://0.0.0.0:3001/

Files:

• app/templates/* : templates/html files for web app.

• data/process_data.py: Extract Train Load (ETL) pipeline used for data cleaning, feature extraction, and storing data in a SQLite database.

• models/train_classifier.py : A machine learning pipeline that loads data, trains a model, and saves the trained model as a .pkl file for later use.

• run.py : The file used to launch the Flask web app used to classify disaster messages.

Acknowledgements:

Thanks to Figure Eight for the data.

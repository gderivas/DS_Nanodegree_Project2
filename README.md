# Disaster Response Pipeline Project

### Motivation

Udacity Data Science Nanodegree - Second Project

The aim is to build a Data Science pipeline to classify disaster response messages and comunicate results through a web app.

### Files Structure

The data folder includes:
- Raw Data without preprocessing (dissaster_messages.csv & dissaster_categories.csv)
- Preprocessing Script
- Database with cleaned data

The models folder includes:
- ML pipeline script to tokenize and train the data 
- Saved Model

The app folder includes:
- Flask Web App Script
- Html Templates folder


### Instructions:
1. Run the following commands in the project's root directory to set up your database and model.

    - To run ETL pipeline that cleans data and stores in database
        `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db`
    - To run ML pipeline that trains classifier and saves
        `python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl`

2. Run the following command in the app's directory to run your web app.
    `python run.py`

3. Go to http://0.0.0.0:3001/

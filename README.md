# Classify medical diagnosis with ICD-10 code
This application was built to demonstrate IBM's Watson Natural Language Classifier (NLC). The data set we will be using, ICD-10-GT-AA.csv, contains a subset of ICD-10 entries. ICD-10 is the 10th revision of the International Statistical Classification of Diseases and Related Health Problems. In short, it is a medical classification list by the World Health Organization (WHO) that contains codes for: diseases, signs and symptoms, abnormal findings, complaints, social circumstances, and external causes of injury or diseases. Hospitals and insurance companies alike could save time and money by leveraging Watson to properly tag the most accurate ICD-10 codes.

This application is a Python web application based on the Flask microframework, and based on earlier work done by Ryan Anderson. It uses the Watson Python SDK to create the classifier, list classifiers, and classify the input text. We also make use of the freely available ICD-10 API which, given an ICD-10 code, returns a name and description.

When the reader has completed this pattern, they will understand how to:

Create a Natural Language Classifier (NLC) service and use it in a Python application.
Train a NLC model using csv data.
Deploy a web app with Flask to allow the NLC model to be queried.
Quickly get a classification of a disease or health issue using the Natural Language Classifier trained model.
architecture

Flow
CSV files are sent to the Natural Language Classifier service to train the model.
The user interacts with the web app UI running either locally or in the cloud.
The application sends the user's input to the Natural Language Classifier model to be classified.
The information containing the classification is returned to the web app.
Included Components
Watson Natural Language Classifier: An IBM Cloud service to interpret and classify natural language with confidence.
Featured Technologies
Artificial Intelligence: Artificial intelligence can be applied to disparate solution spaces to deliver disruptive technologies.
Cloud: Accessing computer and information technology resources through the Internet.
Python: Python is a programming language that lets you work more quickly and integrate your systems more effectively.

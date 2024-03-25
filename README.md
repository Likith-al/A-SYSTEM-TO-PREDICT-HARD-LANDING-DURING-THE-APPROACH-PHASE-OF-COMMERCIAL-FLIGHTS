# A-SYSTEM-TO-PREDICT-HARD-LANDING-DURING-THE-APPROACH-PHASE-OF-COMMERCIAL-FLIGHTS
Support Vector Machine (SVM) - Implemented in the runSVM() function. Logistic Regression - Implemented in the runLR() function.

E-Pilot: A System to Predict Hard Landing During the Approach Phase of Commercial Flights

Introduction:

E-Pilot is a predictive system designed to forecast hard landings during the approach phase of commercial flights. This system utilizes machine learning algorithms to analyze various features extracted from flight data, aiming to identify potential instances of hard landings in advance. Hard landings, also known as firm landings, pose safety risks and can lead to aircraft damage, passenger discomfort, and crew injuries. By detecting such events early, E-Pilot helps improve flight safety and operational efficiency.

Features:

E-Pilot integrates multiple algorithms, including Support Vector Machine (SVM), Logistic Regression, and Hybrid LSTM models. These algorithms analyze different sets of features derived from pilot actions, actuator responses, and physical parameters of the aircraft. By processing and normalizing the dataset, E-Pilot prepares the data for training and testing, ensuring optimal performance of the prediction models.

Usage:

To use E-Pilot, users can upload flight landing datasets containing relevant features such as pilot inputs, actuator behaviors, and physical measurements. The system preprocesses the dataset, performs feature normalization, and splits the data into training and testing sets. Users can then execute specific algorithms to train prediction models and evaluate their performance in terms of sensitivity and specificity.

Implementation:

The system's implementation involves graphical user interface (GUI) development using the Tkinter library in Python. Users interact with the system through buttons and text displays, facilitating dataset upload, preprocessing, algorithm execution, and result visualization. E-Pilot provides a user-friendly interface for aviation professionals to analyze flight data and make informed decisions regarding landing safety.


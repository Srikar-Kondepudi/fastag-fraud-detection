# fastag-fraud-detection
This is a Machine learning project that involves folium that helps us to find the mapping points of the fraud location in HTML Form that you can see after implementing the code

This repository contains the materials for our Data Mining Final Project, which focuses on detecting fraudulent transactions in FASTag data. Our project applies various data mining techniques to identify patterns and anomalies that indicate fraudulent activities.

Project Overview

The goal of this project is to effectively detect and predict fraudulent transactions using a dataset of FASTag transactions. The dataset includes various features related to the transactions, each potentially indicative of normal or fraudulent activities.

Repository Structure

Project_data_Mining.ipynb: Jupyter notebook containing all the preprocessing, analysis, and modeling steps.
FastagFraudDetection.csv: Dataset used for training and testing the fraud detection models.
fraud_locations.html & enhanced_fraud_locations.html: Interactive maps displaying the geographical distribution of fraudulent transactions.
README.md: This file, providing an overview and instructions for the project.
Data

The FastagFraudDetection.csv file is the primary dataset for this project. It includes transaction details such as transaction time, amount, location, and whether the transaction was flagged as fraudulent.

Technologies Used

Python: For all data processing and analysis.
Pandas & NumPy: For data manipulation.
Scikit-Learn: For implementing machine learning models.
Folium: For generating interactive maps to visualize geographical data.
Jupyter Notebook: For documenting the project workflow.
Setup and Installation

Clone this repository to your local machine using git clone.
Ensure you have Python installed, preferably through Anaconda to manage packages easily.
Install the required packages: pip install -r requirements.txt (if available) or manually install packages like pandas, numpy, sklearn, folium, etc.
Run the Jupyter notebooks to view the analysis and models.
How to Use

Open the Project_data_Mining.ipynb notebook to see the data processing, exploratory data analysis, and modeling steps.
The maps in fraud_locations.html and enhanced_fraud_locations.html can be opened in any web browser to interact with the data visually.
Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your suggested changes.

License

This project is licensed under the terms of the MIT License.

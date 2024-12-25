# Datamining-Assingment-and-Midterm (Group 9)
Abdulkadir Efe Buğday 210408033
Ali Uğur Gümüşlü 210408007

CICIoT2023 Dataset Examination and Machine Learning Model Implementation

This repository contains an analysis of the CICIoT2023 dataset and the implementation of a Random Forest Classifier for detecting various IoT-related cyber threats. The project combines data preprocessing, feature engineering, and machine learning to build an effective intrusion detection system (IDS) tailored for IoT environments.

About the Dataset
The CICIoT2023 Dataset was created to support IoT security research. It includes traffic data from a network of 105 interconnected IoT devices and contains 33 distinct types of attacks categorized into seven groups:

DDoS
DoS
Recon
Web-based attacks
Brute force attacks
Spoofing
Mirai botnet
The dataset also provides detailed features, such as packet-level statistics and flow-level metrics, enabling the development of robust security analytics tools.

Key Features of the Project
Data Preprocessing
Label Encoding: Transforms categorical target labels into numerical values for supervised learning.

Train-Test Split: Divides data into training (80%) and testing (20%) sets, maintaining class distribution.

Standardization: Normalizes feature values to improve the performance and stability of the machine learning model.

Model Training and Evaluation

Random Forest Classifier: Trains a robust model to classify network traffic as benign or one of the attack types.

Performance Metrics: Evaluates the model using accuracy, precision, recall, F1-score, and confusion matrices.

Visualization: Includes a heatmap for the confusion matrix to interpret prediction performance visually.

Challenges and Limitations
Class Imbalance: Certain attack classes (e.g., SQL Injection) are underrepresented, impacting the detection performance for these minority classes.
Proposed Solutions: Techniques like SMOTE or class-weighted loss functions are suggested to address imbalance issues.

Dependencies
Python
Pandas
Scikit-learn
Seaborn
Matplotlib
Workflow

Load and preprocess the dataset - it is only a part of the whole 13gb dataset (part-00000-363d1ba3-8ab5-4f96-bc25-4d5862db7cb9-c000.csv). 
You can find the relevant dataset here: https://www.kaggle.com/datasets/akashdogra/cic-iot-2023?resource=download

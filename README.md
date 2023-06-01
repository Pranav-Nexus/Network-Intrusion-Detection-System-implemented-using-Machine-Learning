# Network-Intrusion-Detection-System-using-Machine-Learning
Desigining an ML Based Network Intrustion Detection System

Introduction :

Intrusion Detection Systems are essential for ensuring the safety and the protection of the any computer network. These systems were primarily designed to identify particular patterns, signatures, and rule violations. Machine Learning and Deep Learning approaches have been used in recent years in the field of network intrusion detection to provide promising alternatives. 
Here we implement a system that ensures network safety and detects unauthorised intrusions into the network using the concepts of  Support Vector Machine(SVM), Decision Tree, Random Forest, Multi-Level Perceptron(MLP), K-Nearest Neighbour, Linear and Logistic Regression.
According to Cisco, there will be 29.3 billion internet-connected gadgets by 2023, Intruders and nefarious actors are able to easily defeat the firewall and its variants, for example, by exploiting a bogus source address. The current security systems have also failed to detect many DoS (Denial of Service) and DDoS (Distributed Denial of Service) attacks, making them very vulnerable to Cyber – Security threats of today. We are presenting a solution to these in the form of a Network Intrusion Detection System utilizing machine learning techniques. A thorough evaluation on the performance of the proposed detection system using multiple machine learning algorithms on the NSL - KDD dataset. The NSL-KDD dataset suffers from several issues, such as imbalanced classes and some else .

![image](https://github.com/Pranav-Nexus/Network-Intrusion-Detection-System-using-Machine-Learning/assets/65056700/5b847a33-eed5-4b02-ba87-e06dfbaf7288)
Fig. System Model Diagram

The Dataset and the csv file containing the features are imported and the imported information is classified as Binary or Multi – Class data models.
On these Classified Datasets Pre – Processing of data is done using Normalisation and Min – Max Scalar function.
This data is then split as a Test dataset and a Train Dataset and on the train dataset is used to train the ML models using various Methods as follows:
a) Support Vector Machine (SVM): SVM chooses the extreme points/vectors that help in creating the hyperplane. These extreme cases are called as support vectors, and hence algorithm is termed as Support Vector Machine. 
b) Decision Tree: Decision tree is a flowchart-like tree structure, where each internal node denotes a test on an attribute, each branch represents an outcome of the test, and each leaf node (terminal node) holds a class label. 
c) Multi Level Perceptron (MLP): The Multilayer Perceptron (MLP) procedure produces a predictive model for one or more dependent (target) variables based on values of the predictor variables.
d) K-Nearest Neighbour (KNN) : a non-parametric, supervised learning classifier, which uses proximity to make classifications or predictions about the grouping of an individual data point.
e) Logistic Regression: supervised machine learning algorithm that accomplishes binary classification tasks by predicting the probability of an outcome, event, or observation. 
f) Random Forest: Random forests or random decision forests is an ensemble learning method for classification, regression and other tasks that operates by constructing a multitude of decision trees at training time.

# Supervised Learning Classifiers Project

### Running the program
To run the code, you can use the Jupyter Notebook, with the Anaconda Python Interpreter.

## Contributors
- Maria Rabelo up202000130
- Máximo Brandão 202108887
- Edoardo Tonet 202311494

## Project Overview
The classifiers implemented were Decision Trees, Random Forests, SGDClassifier, K-Nearest Neighbors (KNN), and Neural Networks. 

**Decision Trees**: A decision support tool that uses a tree-like model of decisions and their possible consequences. It's a non-parametric supervised learning method used for classification and regression.

**Random Forests**: An ensemble learning method that operates by constructing multiple decision trees during training and outputting the class that is the mode of the classes (classification) or mean prediction (regression) of the individual trees.

**SGDClassifier**: Stochastic Gradient Descent is an iterative method for optimizing an objective function with suitable smoothness properties. It's used for large-scale machine learning problems.

**K-Nearest Neighbors (KNN)**: A instance-based learning algorithm that classifies new cases based on a similarity measure (e.g., distance functions). The new case is assigned to the class most common among its k nearest neighbors.

**Neural Networks**: A series of algorithms that attempt to recognize underlying relationships in a set of data through a process that mimics the way the human brain operates. They are used in a variety of applications such as pattern recognition and classification.

## Cyber-Security Dataset: BCCC-CIRA-CIC-DoHBrw-2020 -- DoH
### Dataset Summary
The dataset was quite large - about 500 thousands entries. 
Domain over HTTPS (DoH) is a security protocol for the internet that encrypts DNS (Domain Name System) traffic using the HTTPS protocol, enhancing user privacy and security. The dataset includes:

**Traffic Classification**: Classifies traffic as DoH or non-DoH using statistical features and further characterizes DoH traffic as benign or malicious using time-series classification.
**Tools and Browsers**: Includes data from Google Chrome, Mozilla Firefox, dns2tcp, DNSCat2, and Iodine.
**DoH Servers**: AdGuard, Cloudflare, Google DNS, and Quad9.

# Bank-Loan-Approval
Artificial Intelligence
CMP SCI 5300
Professor: Sambriddhi Mainali
University of Missouri - St Louis

This course project focuses on applying Tensorflow/Keras to build, train, and evaluate feed-forward neural networks for binary classification tasks using a standard tabular dataset. The chosen dataset is sourced from Kaggle, specifically the ”Bank Approval Dataset.” The project aims to solve the problem of predicting whether a bank loan application will be approved (binary  classification: 0 or 1). The dataset is carefully selected to meet specific criteria, including a minimum of 1000 rows, at least 3 features, and no sequence/time-series, image, or text inputs. The project is divided into three main phases.

In the initial phase, the dataset is loaded into a Python Notebook, and exploratory data analysis is performed, visualizing feature distributions and normalizing the data. The distribution of output labels is analyzed to check for imbalance. 

The second phase involves experimenting with network size to overfit the entire dataset, starting with a logistic regression model and progressively growing into multi-layered architectures. The objective is to determine the optimal architecture that achieves close to 100.

 In the third phase, the dataset is split into training and validation sets, and various neural network architectures are explored, comparing their performance on the validation set. Model checkpointing is employed, and a detailed table summarizes key metrics such as accuracy, loss, epochs, neurons, and parameters. Different metrics, including precision, recall, and F1 score, are considered for model evaluation. The best-performing model is selected based on validation accuracy.

The final phase focuses on feature importance, where models are trained iteratively by removing one feature at a time. Bar diagrams illustrate the relative importance of each feature, and a stepwise process is employed to identify and remove non-informative features. The feature-reduced model is compared with the original model to assess differences in accuracy. The project provides a comprehensive learning experience in building, training, and optimizing neural networks for tabular data classification.
# Email_Classification_ML
A model that classifies emails as spam or not spam using the Decision Tree algorithm and evaluating the model under different conditions to understand its performance

Email Classification Using Decision Tree Model
Machine Learning Project Group 3
1. Introduction
The goal of this study is to build a model that classifies emails as spam or not spam using the Decision Tree algorithm.

We evaluate the model under different conditions to understand its performance:

With and without normalization
With and without overfitting control
With and without dataset balancing
For each case, performance is measured using the confusion matrix and classification report.

2. Decision Tree Algorithm
In this study, the Decision Tree algorithm is used to classify emails as spam or not spam based on their features.

The model works by recursively splitting the dataset using the most informative features, selecting splits based on metrics such as Information Gain. Each split creates branches that lead to a final decision at the leaf nodes (Spam or Not Spam).

Given that the dataset contains numerical features representing email content, the Decision Tree can effectively identify patterns that distinguish spam emails from legitimate ones.

If the tree becomes too complex, it may lead to overfitting. Thus, the model complexity is controlled by limiting the tree depth (pruning) to improve generalization.

3. Dataset Details
The dataset used is the Spambase dataset for email classification.

4,601 email instances
57 numerical features representing email content (word frequencies, symbols)
Binary class label: Spam (1) and Not Spam (0)
The features help the Decision Tree model identify patterns that distinguish spam from non-spam emails.

Spam: 39.4%
Not Spam: 60.6%
The dataset is slightly imbalanced, which may affect the model’s performance and is considered during the analysis.

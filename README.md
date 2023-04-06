# Mobile-price-range-prediction-Classification

*Built a Multi-Class classification model to find the relation between features of a mobile phone(RAM, Internal Memory etc) and its selling price. Model will predict the price range indicating how high the price is.

💾 Project Files Description

*This Project includes 2 executable files, 1 text files ,1 h5 file as well as 1 directories as follows:

Executable Files:

*mobile_price_range_prediction_- Includes all functions required for classification operations and generates the model.h5 file after execution.

Output Files:

*model.h5 - Model contains information about the predictions of the train set, such as 0(low),high(1),very high(2).

confusion_matrix.txt - Contains information about the classified emotions of the test set.

Source Directories:

*Dataset - Includes all dataset for the training phase and testing phase of the model in the csv format.

📖 Random Forest Classification

*Random forest classifier creates a set of decision trees from randomly selected subset of training set. It then aggregates the votes from different decision trees to decide the final class of the test object.Ensembled algorithms are those which combines more than one algorithms of same or different kind for classifying objects. For example, running prediction over Naive Bayes, SVM and Decision Tree and then taking vote for final consideration of class for test object.Basic parameters to Random Forest Classifier can be total number of trees to be generated and decision tree related parameters like minimum split, split criteria etc.

![vz1f8191 Ensemble-of-decision-trees](https://user-images.githubusercontent.com/120657228/230440242-0a3a06d7-c39b-4a39-b158-e21bc6d37702.png)

📖 XG-Boost

*XGBoost stands for “Extreme Gradient Boosting”. XGBoost is an optimized distributed gradient boosting library designed to be highly efficient, flexible and portable. It implements Machine Learning algorithms under the Gradient Boosting framework. It provides a parallel tree boosting to solve many data science problems in a fast and accurate way.

📖 Decision Tree

![maxresdefault](https://user-images.githubusercontent.com/120657228/230441582-e14a6e5f-f988-4f00-9d09-5510057db3d0.jpg)

A decision tree is a non-parametric supervised learning algorithm, which is utilized for both classification and regression tasks. It has a hierarchical, tree structure, which consists of a root node, branches, internal nodes and leaf nodes.

📖 K Nearest Neighbour KNN

K-Nearest Neighbors Algorithm. The k-nearest neighbors algorithm, also known as KNN or k-NN, is a non-parametric, supervised learning classifier, which uses proximity to make classifications or predictions about the grouping of an individual data point.

![k-nearest-neighbor-algorithm-for-machine-learning2](https://user-images.githubusercontent.com/120657228/230441931-60d025a4-dd15-4afa-a95d-8be1912e857f.png)





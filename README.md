# Iris_DataAnalysis

The following repository contains the analysis of the vary famous Iris dataset. The Iris flower data set or Fisher's Iris data set is a multivariate data set introduced by the British statistician and biologist Ronald Fisher in his 1936 paper. The use of multiple measurements in taxonomic problems as an example of linear discriminant analysis. The Iris data set contains 3 classes of 50 instances each, where each class refers to a type of iris plant. Four features were measured from each sample: the length and the width of the sepals and petals, in centimetres. The central goal here is to design a model which makes good classifications for new data, in other words one which exhibits good generalization.

We start by importing the dataset and then reading it. Data preprocessing was not required. We then created a model by applying logistic regression which performed quite well on the dataset. We also plotted the Decision Boundaries in 2-D using the two most coorelated features with the target variable. We observed that one class is linearly separable from the other two; the latter are not linearly separable from each other. We also implemented K-means clustering and visualised the results in 3-D. Further KNN and different SVM classifiers were also implemented. Out of all, SVM performed the best. All the different SVM Classifiers were compared and visualised using decision boundaries in 2-D. We observed that linear SVM generalised well whereas polynomial SVM and gaussian SVM seemed to overfit. We used accuracy as the performance metric.

Python language is used, we first download our datasets locally, and then we will load them into data frames in python. In python, we use pd.read_csv to read CSV files into pandas data frame variables. 
Libraries used:

1)library(pandas) #to read .csv file.

2)library(numpy) #for preprocessing and data manipulation.

3)library(sklearn.preprocessing) #for LabelEncoder().

4)library(sklearn.metrics) #for evaluating the performance.

5)library(sklearn.model_selection) #for train_test_split and fine-tuning the model parameters.

6)library(matplotlib) #for data visualisation.

7)library(mpl_toolkits) #for 3-D visualisation.

8)library(sklearn) #for applying SVM, KNN, K-means and Logistic Regression.

## Introduction

In today’s world, we are on the express train to a cashless society.  It’s expected that in future years there will be a steady growth of non-cash transactions.

Now, while this might be exciting, but on the flip-side fraudulent transactions are on the rise as well. Even with EMV smart chips being implemented, we still have a very high amount of money lost from credit card fraud.

What can we do to reduce the risk? While there are a lot of methods to limit the loss and prevent fraud, and we’ll walk you through our process and show you our findings. To solve this problem, we’re creating a “Credit Card Fraud Analysis Model using Machine Learning”. The datasets we’ll be using will be gathered from a Kaggle dataset which contains 285,000 rows of data and 31 columns.

### Proposed Methodology

The types of algorithms we are going to use to try to do anomaly detection on this dataset module are as follows:

#### Isolation Forest Algorithm
One of the newest techniques to detect anomalies is called Isolation Forests. The algorithm is based on the fact that anomalies are data points that are few and different. As a result of these properties, anomalies are susceptible to a mechanism called isolation.
This method is highly useful and is fundamentally different from all existing methods. It introduces the use of isolation as a more effective and efficient means to detect anomalies than the commonly used basic distance and density measures. Moreover, this method is an algorithm with a low linear time complexity and a small memory requirement. It builds a good performing model with a small number of trees using small sub-samples of fixed size, regardless of the size of a data set.


#### Local Outlier Factor (LOF) Algorithm
The LOF algorithm is an unsupervised outlier detection method which computes the local density deviation of a given data point with respect to its neighbours. It considers as outlier samples that have a substantially lower density than their neighbours.

The number of neighbours considered, (parameter n neighbours) is typically chosen 1 greater than the minimum number of objects a cluster has to contain, so that other objects can be local outliers relative to this cluster, and 2) smaller than the maximum number of close by objects that can potentially be local outliers. In practice, such information’s are generally not available, and taking n neighbours = 20 appears to work well in general.

#### Support Vector Machine
A support vector machine (SVM) is a supervised machine learning model that uses classification algorithms for two-group classification problems. After giving an SVM model sets of labeled training data for each category, they're able to categorize new text. So you're working on a text classification problem.

### Conclusion

Finding fraudulent credit card transactions is really important, especially in today’s society. There are lots of methods to capture these instances, and this method was one of them with machine learning with python.

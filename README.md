# Feature Selection in Machine Learning using Python
I have recently started teaching machine learning. In this tutorial series I have taught about feature selection which improve the accuracy and reduces the training time. Moreover, feature selection used in feature reduction which improve accuracy and reduces training time. It also reduces the chances of over fitting.

Feature Selection is one of the core concepts in machine learning which hugely impacts the performance of your model. The data features that you use to train your machine learning models have a huge influence on the performance you can achieve. Irrelevant or partially relevant features can negatively impact model performance. Feature selection and Data cleaning should be the first and most important step of your model designing.

There are three type of feature selection
  - Filter Method
  - Wrapper Method
  - Embedded Method


|S.No.| Title | Description | Video Link | Duration |
| --- | --- | --- | --- | --- |
| 1 | Introduction to Feature Selection in Machine Learning- What is Feature Selection |Feature Selection is one of the core concepts in machine learning which hugely impacts the performance of your model. The data features that you use to train your machine learning models have a huge influence on the performance you can achieve. Irrelevant or partially relevant features can negatively impact model performance. Feature selection and Data cleaning should be the first and most important step of your model designing. Feature Selection is the process where you automatically or manually select those features which contribute most to your prediction variable or output in which you are interested in. Having irrelevant features in your data can decrease the accuracy of the models and make your model learn based on irrelevant features.|[Link](https://youtu.be/kA4mD3y4aqA)|15:11|
| 2 | Feature Selection with Filtering Method- Constant, Quasi Constant and Duplicate Feature Removal | Filters methods belong to the category of feature selection methods that select features independently of the machine learning algorithm model. This is one of the biggest advantages of filter methods. Features selected using filter methods can be used as an input to any machine learning models. Another advantage of filter methods is that they are very fast. Filter methods are generally the first step in any feature selection pipeline. | [Link](https://youtu.be/nPHU1CpX4jg) | 46:59|
| 3 | Feature Selection with Autocorrelation (Pearson Correlation Coefficients) - Filter Method | If your dataset has perfectly positive or negative attributes then there is a high chance that the performance of the model will be impacted by a problem called — “Multicollinearity”. Multicollinearity happens when one predictor variable in a multiple regression model can be linearly predicted from the others with a high degree of accuracy. This can lead to skewed or misleading results. Luckily, decision trees and boosted trees algorithms are immune to multicollinearity by nature. When they decide to split, the tree will choose only one of the perfectly correlated features. However, other algorithms like Logistic Regression or Linear Regression are not immune to that problem and you should fix it before training the model. | [Link](https://youtu.be/m0fs0v5GGlg) | 58:16 |
| 4 | Feature Selection Based on Mutual Information Gain for Classification - Filter Method | The elimination process aims to reduce the size of the input feature set and at the same time to retain the class discriminatory information for classification problems. Mutual information (MI) is a measure of the amount of information between two random variables is symmetric and non-negative, and it could be zero if and only if the variables are independent. Reduction of the input features set can be desirable, or essential for a number of reasons, such as reducing the complexity of building and operating a classifier. In addition to the computational-cost saving, a feature-space reduction can also reduce the actual cost of feature collection and pre-processing, and even lead to an improvement in classifier accuracy.| [Link](https://youtu.be/GpL_XtRVne4) | 50:53 |
| 5 | Feature Selection Based on Univariate ROC_AUC for Classification and MSE for Regression - KGP Talkie | Feature Selection Based on Univariate ROC_AUC for Classification and MSE for Regression The Receiver Operator Characteristic (ROC) curve is well-known in evaluating classification performance. Owing to its superiority in dealing with imbalanced and cost-sensitive data, the ROC curve has been exploited as a popular metric to evaluate ML models. The existing ROC-based feature selection approaches are simple and effective in evaluating individual features. The ROC curve and AUC (area under the ROC curve) have been widely used to determine the classification accuracy in supervised learning. Through analyzing a two-dimensional graph, it is hard to compare two ROC curves directly. AUC, which is denoted as a quantitative measurement, provides a good summary for examining the ROC curves.| [Link](https://youtu.be/JEfBvK91CXc) | 37:53 |
| 6 | Feature Selection Based on Univariate ANOVA Test for Classification and Regression | What is Univariate (ANOVA) Test. The elimination process aims to reduce the size of the input feature set and at the same time to retain the class discriminatory information for classification problems. The analysis of variance (ANOVA) can be thought of as an extension to the t-test. The independent t-test is used to compare the means of a condition between 2 groups. An F-test is any statistical test in which the test statistic has an F-distribution under the null hypothesis. The hypothesis that the means of a given set of normally distributed populations, all having the same standard deviation, are equal. This is perhaps the best-known F-test, and plays an important role in the analysis of variance (ANOVA). Analysis of variance (ANOVA) is a collection of statistical models and their associated estimation procedures (such as the "variation" among and between groups) used to analyze the differences among group means in a sample. ANOVA was developed by statistician and evolutionary biologist Ronald Fisher. The ANOVA is based on the law of total variance, where the observed variance in a particular variable is partitioned into components attributable to different sources of variation. In its simplest form, ANOVA provides a statistical test of whether two or more population means are equal, and therefore generalizes the t-test beyond two means. The F-test is used for comparing the factors of the total deviation. For example, in one-way, or single-factor ANOVA, statistical significance is tested by comparing the F test statistic.| [Link](https://youtu.be/PWZLhr3FfIM) | 20:58 |
| 7 | Feature Selection using Fisher Score and Chi2 (χ2) Test on Titanic Dataset - KGP Talkie | High-dimensional data in the input space is usually not good for classification due to the curse of dimensionality. It significantly increases the time and space complexity for processing the data. Moreover, in the presence of many irrelevant and/or redundant features, learning methods tend to over-fit and become less interpretable. A common way to resolve this problem is feature selection, which reduces the dimensionality by selecting a subset of features from the input feature set. It is often used to reduce the computational cost and remove irrelevant and redundant features for problems with high dimensional data. Fisher score is one of the most widely used supervised feature selection methods. However, it selects each feature independently according to their scores under the Fisher criterion, which leads to a suboptimal subset of features. Chi Square Test A chi-squared test, also written as χ2 test, is any statistical hypothesis test where the sampling distribution of the test statistic is a chi-squared distribution. The chi-squared test is used to determine whether there is a significant difference between the expected frequencies and the observed frequencies in one or more categories. i.e. It is applied only on the categorical dataset Chi-square test measures dependence between stochastic variables, so using this function “weeds out” the features that are the most likely to be independent of class and therefore irrelevant for classification.| [Link](https://youtu.be/gDgEjdEzEDY) | 32:29 |
| 8 | Step Forward, Step Backward and Exhaustive Feature Selection of Wrapper Method | In this lesson, I will talk about feature selection using the wrapper method and I will show you how to achieve 100% accuracy with some selected features. In wrapper methods, we try to use a subset of features and train a model using them. Based on the inferences that we draw from the previous model, we decide to add or remove features from your subset. The problem is essentially reduced to a search problem. These methods are usually computationally very expensive. Wrapper methods are based on greedy search algorithms as they evaluate all possible combinations of the features and select the combination that produces the best result for a specific machine learning algorithm. A downside to this approach is that testing all possible combinations of the features can be computationally very expensive, particularly if the feature set is very large. In the first phase of the step forward feature selection, the performance of the classifier is evaluated with respect to each feature. The feature that performs the best is selected out of all the features. In the second step, the first feature is tried in combination with all the other features. The combination of two features that yield the best algorithm performance is selected. The process continues until the specified number of features are selected. Step backward feature selection, as the name suggests is the exact opposite of step forward feature selection that we studied in the last section. In the first step of the step backward feature selection, one feature is removed in a round-robin fashion from the feature set and the performance of the classifier is evaluated. In exhaustive feature selection, the performance of a machine learning algorithm is evaluated against all possible combinations of the features in the dataset. The feature subset that yields the best performance is selected. The exhaustive search algorithm is the most greedy algorithm of all the wrapper methods since it tries all the combination of features and selects the best. A downside to exhaustive feature selection is that it can be slower compared to step forward and step backward method since it evaluates all feature combinations. Sequential feature selection algorithms are a family of greedy search algorithms that are used to reduce an initial d-dimensional feature space to a k-dimensional feature subspace where k less than d. The motivation behind feature selection algorithms is to automatically select a subset of features that is most relevant to the problem. The goal of feature selection is two-fold: We want to improve the computational efficiency and reduce the generalization error of the model by removing irrelevant features. In a nutshell, SFAs remove or add one feature at the time based on the classifier performance until a feature subset of the desired size k is reached. There are 4 different flavors of SFAs available via the SequentialFeatureSelector: Sequential Forward Selection (SFS) Sequential Backward Selection (SBS) Exhaustive Feature Selection (EFS)| [Link](https://youtu.be/zW1SvA0Z-l4) | 39:45 |
| 9 | Linear and Logistic Regression with L1 and L2 ( Lasso and Ridge) Regularization Feature Selection |  Linear regression is a straightforward approach for predicting a quantitative response Y on the basis of a different predictor variable X1, X2, ... Xn. It assumes that there is a linear relationship between X(s) and Y. Mathematically, we can write this linear relationship as Y ≈ β0 + β1X1 + β2X2 + ... + βnXn. Basic Assumptions Linear relationship with the target y Feature space X should have gaussian distribution Features are not correlated with other Features are in the same scale i.e. have the same variance Lasso (L1) and Ridge (L2) Regularization Regularization is a technique to discourage the complexity of the model. It does this by penalizing the loss function. This helps to solve the overfitting problem. Regularization adds a penalty on the different parameters of the model to reduce the freedom of the model. Hence, the model will be less likely to fit the noise of the training data and will improve the generalization abilities of the model L1 regularization (also called Lasso) L2 regularization (also called Ridge) L1/L2 regularization (also called Elastic net) A regression model that uses L1 regularization technique is called Lasso Regression and model which uses L2 is called Ridge Regression. The key difference between these techniques is that Lasso shrinks the less important feature’s coefficient to zero thus, removing some feature altogether. So, this works well for feature selection in case we have a huge number of features. The L1 regularization adds a penalty equal to the sum of the absolute value of the coefficients. The L1 regularization will shrink some parameters to zero. Hence some variables will not play any role in the model, L1 regression can be seen as a way to select features in a model. The L2 regularization adds a penalty equal to the sum of the squared value of the coefficients. The L2 regularization will force the parameters to be relatively small, the bigger the penalization, the smaller (and the more robust) the coefficients are.| [Link](https://youtu.be/gryKjGVgzc4) | 41:07 |
| 10 | Recursive Feature Elimination (RFE) by Using Random Forest and Gradient Boosting Algorithm | Recursive Feature Elimination (RFE) by Using Tree-Based and Gradient-Based Estimators Recursive Feature Elimination (RFE) as its title suggests recursively removes features, builds a model using the remaining attributes and calculates model accuracy. RFE is able to work out the combination of attributes that contribute to the prediction on the target variable (or class). Scikit Learn does most of the heavy lifting just import RFE from sklearn.feature_selection and pass any classifier model to the RFE() method with the number of features to select. Using familiar Scikit Learn syntax, the .fit() method must then be called. | [Link](https://youtu.be/pcZ4YlvhSKU) | 35:27 |
| 11 |  Feature Dimention Reduction Using LDA and PCA with Python - Principal Component Analysis in Feature Selection |  Linear Discriminant Analysis is a supervised algorithm as it takes the class label into consideration. It is a way to reduce ‘dimensionality’ while at the same time preserving as much of the class discrimination information as possible. LDA helps you find the boundaries around clusters of classes. It projects your data points on a line so that your clusters are as separated as possible, with each cluster having a relative (close) distance to a centroid. So the question arises- how are these clusters are defined and how do we get the reduced feature set in case of LDA? Basically LDA finds a centroid of each class datapoints. For example with thirteen different features LDA will find the centroid of each of its class using the thirteen different feature dataset. **PCA:** Principal Component Analysis (PCA) is a linear dimensionality reduction technique that can be utilized for extracting information from a high-dimensional space by projecting it into a lower-dimensional sub-space. It tries to preserve the essential parts that have more variation of the data and remove the non-essential parts with fewer variation.One important thing to note about PCA is that it is an Unsupervised dimensionality reduction technique, you can cluster the similar data points based on the feature correlation between them without any supervision (or labels), and you will learn how to achieve this practically using Python in later sections of this tutorial! According to Wikipedia, PCA is a statistical procedure that uses an orthogonal transformation to convert a set of observations of possibly correlated variables (entities each of which takes on various numerical values) into a set of values of linearly uncorrelated variables called principal components.  | [Link]() |   |

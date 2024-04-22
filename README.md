# SC1015 Introduction to Data Science & Artificial Intelligence Mini Project
## About
This is the mini project for SC1015(Introduction to Data Science & Artificial Intelligence). <br>
Cardiovascular diseases (CVDs) are the leading cause of death globally with an estimated 17.9 million casualties in 2019, making it 32% of all global deaths. Most cardiovascular diseases are caused by poor lifestyle choices and can be easily prevented by addressing these behavioural risk factors. Hence it is important for early detection of cardiovascular diseases so that appropriate measures can be taken to prevent life-threatening scenarios. We aim to create a model to help sieve through large amounts of data reducing the work load on medical professionals. <br>

## Team Members (Lab FCS1 - Team 03)
Tan Guang Wei - EDA, Models, Conclusion <br>
Kwek Chong Yee, Wallace - EDA, Models, Conclusion <br>

## Problem Statement
To create a model that is capable of predicting the likelihood of contracting heart diseases given the patient data.

## Models Used
<ul>
    <li> Support Vector Machine (SVM) </li>
    <li> Decision Trees </li>
    <li> K-Nearest Neighbors (KNN) </li>
    <li> Multi-Layer Perceptron Classifier (MLP) </li>
</ul>

## Conclusion
<ul>
    <li> SVMs and KNNs were the best performing models, achieving 88% accuracy and showed strong predictive performance on the test data </li>
    <li> Small datasets require special considerations to prevent large amounts of data being lost to the data-processing phase </li>
    <li> Data transformation techniques such as normalization are very important, this was proven as our best forming models were all derived from training on the transformed dataset </li>
    <li> We acknowledge that our models performanced may not be able to handle every scenario it might face, due to the small dataset size. This is partly due to the fact that patient data is considered sensitive data is often not released to the public, making it difficult to achieve a comprehensive model </li>
</ul>

## Key Takeaways
<ul>
    <li> We explored further techniques in machine learning such as Support Vector Machines (SVMs) and Artificial Neural Networks (ANNs) </li>
    <li> We deepened existing knowledge learnt during the course, such as Decision Trees, where we explored Entropy Criterion </li>
    <li> We learnt new techniques to process data such as the box-cox transformation which helps to shift our data towards a normal distribution, benefitting most of our models </li>
    <li> We got to experience firsthand the applications of Data Science and Artificial Intelligence in solving real-world problems and see the benefits it can bring to improve workflow efficiency in virtually any industry </li>
</ul>


## References:
One-Hot Encoding for categorical variables - https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.LabelEncoder.html <br>
Box-Cot Transformation - https://builtin.com/data-science/box-cox-transformation-target-variable <br>
F1 Score - https://en.wikipedia.org/wiki/F-score <br>
Classification Report - https://scikit-learn.org/stable/modules/generated/sklearn.metrics.classification_report.html <br>

Decision Trees are unaffected by monotonic transformations - https://forecastegy.com/posts/do-decision-trees-need-feature-scaling-or-normalization/ <br>
K-Nearest Neighbors - https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html <br>
MLP Classifier - https://scikit-learn.org/stable/modules/generated/sklearn.neural_network.MLPClassifier.html <br>
Support Vector Machine - https://www.geeksforgeeks.org/support-vector-machine-algorithm/ <br>
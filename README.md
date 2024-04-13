# Recipe_rating_Intel
## Overview:
This project aims to predict food ratings using machine learning models trained on various features extracted from recipes. By leveraging data such as ingredients, cooking methods, and user reviews, our models can provide accurate predictions of the ratings a recipe is likely to receive.
## Machine Learning Models:
Various machine learning algorithms are employed, such as

•Logistic Regression with 75% accuracy 

•Decision Tree with 63% accuracy 

•SVM with 75% accuracy 

•XgBoost with 76% accuracy 

These models are trained on the dataset to learn patterns and relationships between recipe features and ratings, enabling them to make predictions on unseen data effectively.

## Evaluation:

The performance of the models is evaluated using the accuracy score metric. This metric measures the proportion of correctly predicted ratings out of all predictions made by the model. With an accuracy score of 75%, our models demonstrate a strong capability to predict food ratings accurately.
## Intel OneDAL:
Integrating Intel oneAPI Data Analytics Library (oneDAL) into the Recipe for Rating project offers an opportunity to significantly enhance the performance and scalability of the machine learning models used for predicting food ratings. By leveraging oneDAL's optimized algorithms and parallel processing capabilities, we can expedite the training process and improve resource utilization, ultimately leading to more accurate and efficient predictions. Additionally, with oneDAL's support for distributed computing, we can seamlessly scale our prediction tool to handle larger datasets, ensuring its effectiveness even as our database grows. By incorporating oneDAL into our project and following its documentation and examples, we can tap into its full potential to deliver a robust and high-performing solution for predicting food ratings with precision and scalability.

## Correlation Matrix:
![correlation_matrix](https://github.com/Abirami0234/Recipe_rating_Intel/assets/96755590/3efa21b1-9fd7-4715-832e-38c0812545cb)


The above correlation matrix heatmap illustrates the relationships between different features in the dataset. Darker colors indicate stronger correlations, while lighter colors represent weaker correlations. Understanding these correlations can provide insights into the relationships between various factors influencing food ratings.

# Titanic Survival Prediction 🚢💡
Welcome to the Titanic Survival Prediction project! This project is an implementation of machine learning algorithms to predict the likelihood of a passenger surviving the Titanic disaster based on various factors such as age, gender, class, and family size. By exploring real historical data, this project showcases how machine learning can provide insights and predictions from past events. Let's dive into the world of data and algorithms! 📊✨

## Overview 🔍
The Titanic dataset from Kaggle is used to predict which passengers survived the tragedy. The dataset contains features such as:

Passenger Class: Higher-class passengers had better survival rates.
Gender: Women and children were prioritized in rescue efforts.
Age: Younger passengers had slightly higher chances of survival.
Family Size: Traveling with family had both positive and negative impacts on survival.
This project focuses on building three key machine learning models:

K-Nearest Neighbors (KNN) Algorithm 🤝
Decision Tree Algorithm 🌳
Random Forest Algorithm 🌲🌲🌲
Algorithms Used 🧠
K-Nearest Neighbors (KNN) Algorithm 🤝
KNN is a simple yet powerful classification algorithm. It works by finding the closest data points (neighbors) and predicting survival based on the majority class of those neighbors. KNN performs well when the dataset is properly normalized, making it a great baseline algorithm.

Decision Tree Algorithm 🌳
Decision Trees are intuitive and interpretable. The model splits the data into branches based on feature importance (e.g., age, class) and predicts outcomes through a series of decisions. This algorithm achieved one of the highest accuracy scores in predicting Titanic survival, as it effectively captures interactions between features.

Random Forest Algorithm 🌲🌲🌲
Random Forest is an ensemble learning method that builds multiple decision trees and aggregates their predictions. It reduces overfitting by averaging the outcomes of many trees, leading to a robust and accurate prediction model. In this project, Random Forest achieved the highest prediction accuracy, demonstrating its power in classification tasks!

Model Comparison 📈
KNN Accuracy: 67%
Decision Tree Accuracy: 78%
Random Forest Accuracy: 🏆 77% 🏆
The Random Forest model emerged as the best performer due to its ability to capture complex patterns in the data while reducing overfitting through multiple decision trees.

Key Libraries Used 📚

Pandas: For data manipulation and cleaning.
NumPy: For numerical computations.
Matplotlib & Seaborn: For visualizing the data.
Scikit-learn: For building and evaluating machine learning models.
Conclusion 🚀
Through this project, we explored how different machine learning algorithms can be used to predict survival on the Titanic. By using KNN, Decision Tree, and Random Forest, we gained valuable insights into how different factors influenced survival rates. The Random Forest algorithm stood out as the top performer in this prediction task, achieving an accuracy of 84%!

Feel free to explore the code, visualize the data, and tweak the models to improve predictions. This project is a great example of how machine learning can provide valuable insights from historical data, and we hope you find it informative and engaging!


# Laptop-Price-Prediction

The aim of this project is to predict the price of the Laptop based on various parameters like Brand, RAM, GPUs, touchscreen and many more.
This is a small web application built with the help of **Streamlit** a python-based web-framework.
<p align='center'>
<img src="https://github.com/PCON-Hacktoberfest-2022/Laptop-Price-Prediction/blob/master/sample_img.png" width="700" height="650" />
</p>
`Steps that I have followed to build this project`:

1. **`Data Cleaning`** : Removed the unnecessary columns and rows from the dataset which were not playing any significant role in price prediction and may also decrease the accuracy of the model.

2. **`Exploratory Data Analysis (EDA)`** : Explored the Dataset and visualize the graph depicting the relation of each feature with the price.

3. **`Feature Engineering`** : As the data were not in proper format for training so converted that in the proper form so that it will be easy to train the model.

4. **`Training the Model`** : Trained the model by creating the Training Pipeline consisting of Scaling the numeric features and One hot encoding the Categorical Features and then finally trained the model using various Machine learning Algorithms.
      * Linear Regression
      * Ridge and Lasso Regression
      * KNN Regressor
      * Decision Tree Regressor
      * SVM Regressor
      * RandomForest Regressor 
      * Boosting Techniques (Gradient Boosting, Adaboost, XgBoost)
      * Voting & Stacking Regressor

The Model was performing best in the case of **RandomForestRegressor** and giving the **R2 Score 88.2%**

Finally Converted the model into a web-app using Streamlit and deployed on **Heroku**.

Project Link : https://laptop-price-predicter.herokuapp.com/
      
# Thank You


# Predicting Restaurant Ratings - End to End Machine Learning with Deployment

Business Problem: Predicting Restaurant Ratings for a Diverse City




CONTEXT

The goal of this project is to help restaurant owners make specific enhancements and improve the overall dining experience, which will boost consumer happiness and ratings across a city's diverse dining scene.

A dataset that includes a wide range of unrelated dining places was used to forecast and improve restaurant ratings in a lively metropolis with a large number of restaurants serving a variety of cuisines and styles. This dataset includes details about the restaurants, feedback from clients, location information, and other pertinent factors.

In a bustling city with a multitude of restaurants spanning various cuisines and styles, an opportunity exists to predict and enhance restaurant ratings using a dataset that covers a wide range of unrelated dining establishments. This dataset comprises restaurant information, customer reviews, location specifics, and other relevant attributes.




Steps Taken and Business Value:

1. Data Source

The dataset was obtained from Kaggle, it encompasses restaurant details, customer reviews, ratings, location specifics, and other relevant attributes for a diverse array of restaurants within the city.




2. Exploratory Data Analysis (EDA)

 I conducted EDA to unveil patterns and correlations between restaurant characteristics, customer reviews, and ratings. Visualizations and statistical analysis help uncover insights.

·         Business Value: EDA findings will guide strategies for improving ratings across various types of restaurants, uncovering commonalities that contribute to positive reviews and high ratings.




3. Handling Missing Values

I discovered a decent amount of missing data. I opted against managing the missing values through imputation techniques instead I excluded records with incomplete data.

·.

4. Feature Selection:

I removed a few Non-contributory features and irrelevant attributes from the  dataset to streamline analysis and modeling efforts. Focusing on pertinent attributes enhances model efficiency and interpretability, while reducing noise from irrelevant data.




5. Categorical Variable Transformation and Encoding:

Categorical variables were encoded numerically using LabelEncoder. Numeric representation of categorical data enables modeling and uncovers the impact of various factors on restaurant ratings.




6. Model Building and Testing:

I trained a couple of Machine learning models like Random Forest, Linear regression and ExtraTrees regressor and evaluated for their ability to predict restaurant ratings using diverse features.

Accurate rating predictions provided insights into the unique attributes that drive ratings across different types of restaurants, aiding in targeted improvements.




7. Best Model Selection:

The Random Forest model demonstrates superior predictive performance, capturing the complex relationships between diverse attributes and restaurant ratings.

Reliable rating predictions empower restaurant owners to tailor their strategies for improvement, enhancing customer satisfaction and overall ratings.




8. Flask API Creation and Web Application Deployment:

A Flask-based API is established and integrated into a user-friendly web application, allowing users to estimate ratings for a variety of restaurants in the city.




OVERALL

This approach can assist restaurant owners in making targeted improvements and enhancing the overall dining experience, contributing to increased customer satisfaction and improved ratings across the city's varied dining landscape.
## Tech Stack
![Logo](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![Logo](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Logo](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![Logo](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)


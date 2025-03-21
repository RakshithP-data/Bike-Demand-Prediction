# Bike-Demand-Prediction
By applying various machine learning and deep learning techniques, we aim to accurately predict the demand for Washington rental bikes, enabling companies to ensure bikes are readily available whenever and wherever they are needed.


[![](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=darkgreen)](https://www.python.org)  [![](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white)](https://www.tensorflow.org) [![](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/stable/) [![](https://img.shields.io/badge/SciPy-654FF0?style=for-the-badge&logo=SciPy&logoColor=white)](https://www.scipy.org) [![](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org) [![](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)  [![](https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white)](https://plotly.com) [![](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=Keras&logoColor=white)](https://keras.io) [![](https://img.shields.io/badge/conda-342B029.svg?&style=for-the-badge&logo=anaconda&logoColor=white)](https://www.anaconda.com)

## Introduction 

There are different bike companies such as [__Zagster__](https://en.wikipedia.org/wiki/Zagster) and [__Lime Bikes__](https://www.li.me/en-US/home) present all over the __US__ to ensure that people get rides when needed. As a result, there is an increase in demand for these bikes as some people move to these __cost-efficient__ and __environment-friendly__ transport options. As a result of this transition, there is variation in the demand for bikes in different regions. 

## Challenges

One of the challenges that these companies face is to know the number of bikes that must be placed at different locations at different instances of time to ensure that they get maximum profit and give the people their rides. Sometimes there is a possibility of people missing out on these bikes due to their unavailability. On the contrary, there are also instances when the demand for these bikes is low while they are highly available in many locations without being used. Therefore, it becomes important to tackle these instances and understand the demand for bikes for different days and scenarios.

## Data Science and Machine Learning 

With the help of __machine learning__ and __deep learning__, this problem could be addressed and this would ensure that the demand for the bikes is known beforehand thus, the companies could ensure that there are __adequate bikes__ present in different locations.

## Exploratory Data Analysis (EDA)

Therefore, with the help of __data visualization__ and __machine learning__, bike rental companies would be able to understand the total number of bikes that must be present at different instances of time and thus, they would be able to predict the demand for the bikes in the future. This would ensure that the companies save millions of dollars by giving the right service to different people who are in need. 

## Metrics

Since this is a __regression__ problem, we consider metrics that take into account __continuous output variables__ and give their estimates based on the difference between the __actual output__ and __predicted output__. Below are some metrics that are used for this prediction.

* [__Mean Squared Error__](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mean_squared_error.html)
* [__Mean Absolute Error__](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mean_absolute_error.html)

## Machine Learning Models

There are a large number of machine learning models used in the prediction of the demand for __Washington Bikes__. Below are the models that were used for prediction.

* [__Deep Neural Networks__](https://scikit-learn.org/stable/modules/generated/sklearn.neural_network.MLPRegressor.html)
* [__K Nearest Neighbors__](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsRegressor.html)
* [__Partial Least Squares (PLS) Regression__](https://scikit-learn.org/stable/modules/generated/sklearn.cross_decomposition.PLSRegression.html)
* [__Decision Tree Regressor__](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeRegressor.html)
* [__Gradient Boosting Regressor__](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingRegressor.html)
* [__Linear Regression__](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html)
* [__Long Short Term Memory (LSTM)__](https://www.tensorflow.org/api_docs/python/tf/keras/layers/LSTM)

## Machine Learning Predictions and Analysis 

* Understanding the key features within the data is essential before performing any machine learning analysis.
* We conducted various data visualizations to explore and gain insights into the underlying patterns of the dataset. Once we had a clear understanding, we applied multiple machine learning models to predict bike rental demand based on these features.
* After generating predictions with our machine learning models, we implemented strategies to deploy these models into production, ensuring they could be effectively utilized by companies in real-world scenarios.
* As a result, bike rental companies can save significant time and costs by leveraging machine learning and deep learning techniques to accurately forecast demand in advance.

## Outcomes
* The models that delivered the highest accuracy in predicting bike demand were the Gradient Boosting Decision Regressor and Deep Neural Networks.
* __Exploratory Data Analysis (EDA)__ was performed to ensure that there is a good understanding of different features and their contribution to the output variable respectively. 
* The best machine learning models were able to generate a __mean absolute error (MAE)__ of about __23__ which is really good considering the scale of the problem at hand.

## Future Scope

* Additional features such as the __street connectivity score__ and __people's perceptions__ of the bicycling environment could be added to generate even more good predictions from the models.
* The best machine learning models could be __deployed__ in real-time where the demand for bikes is highlighted so that admins can take action based on the __demand__.







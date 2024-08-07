## Model for Diabetes Prediction using Machine Learning (MINI Project)  

### Overview 
In this project, the objective is to predict whether the person has Diabetes or not based on various features suach as 
- Pregnancies
- Insulin Level
- Age
- BMI.
The data set that has used in this project has taken from the [kaggle](https://www.kaggle.com/) . "This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage." and used a simple [random forest classifier](https://en.wikipedia.org/wiki/Random_forest).   


### Motivation
The motivation was to experiment  with end to end machine learning project and get some idea about deployment platform like [Heroku](https://g.co/kgs/yvsR77) and offcourse this "
Diabetes is an increasingly growing health issue due to our inactive lifestyle. If it is detected in time then through proper medical treatment, adverse effects can be prevented. To help in early detection, technology can be used very reliably and efficiently. Using machine learning we have built a predictive model that can predict whether the patient is diabetes positive or not.".
This is also sort of fun to work on a project like this which could be beneficial for the society. 


### Technical Aspect 

- Training a machine learning model using scikit-learn. 
- Building and hosting a Flask web app on Heroku. 
- A user has to put details like Number of Pregnancies, Insulin Level, Age, BMI etc . 
- Once it get all the fields information , the prediction is displayed on a new page . 
### Technologies Used  
![](https://forthebadge.com/images/badges/made-with-python.svg) 

[<img target="_blank" src="https://github.com/scikit-learn/scikit-learn/blob/master/doc/logos/scikit-learn-logo-small.png">](https://github.com/scikit-learn/)
<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>
<img target="_blank" src="https://github.com/ditikrushna/End-to-End-Diabetes-Prediction-Application-Using-Machine-Learning/blob/master/Resource/numpy.png" width=170>
<img target="_blank" src="https://github.com/ditikrushna/End-to-End-Diabetes-Prediction-Application-Using-Machine-Learning/blob/master/Resource/pandas.jpeg" width=170>

### Bug / Feature Request
If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue [here](https://github.com/Bharath-tars/ModelMl/issues) by including your search query and the expected result.

If you'd like to request a new function, feel free to do so by opening an issue [here](https://github.com/Bharath-tars/ModelMl/issues/new). Please include sample queries and their corresponding results.


### Installation 
- Clone this repository and unzip it.
- After downloading, cd into the flask directory.
- Begin a new virtual environment with Python 3 and activate it.
- Install the required packages using pip install -r requirements.txt
- Execute the command: python app.py

### Note:
- Webapp can handle concurrency upto some extent but can be scaled.


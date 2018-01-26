
# This Project is Part of the:
# Machine Learning Engineer Nanodegree

## Project: Titanic Survival Exploration

### Goal of the Project
The goal of this machine learning project is to create decision functions that attempt to predict survival outcomes from the 1912 Titanic disaster based on each passenger’s features, such as sex and age.

### Achievements
•	Create decision functions that attempted to predict survival outcomes from the 1912 Titanic disaster based on  passenger’s features, such as sex and age, number of siblings and class of his ticket.
•	Implemented a simple algorithm that performs the prediction.
•	Increased the algorithm's complexity until you I was able to accurately predict the outcomes more than 80% of the passengers in the provided data.



### Install

This project was done using **Python 2.7** that already supports the following Python libraries:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

I installed the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included and I made sure that you select the Python 2.7 installer.




### Data
The dataset used in this project is included as `titanic_data.csv`. This dataset is provided by Udacity and contains the following attributes:

**Features**
- `pclass` : Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)
- `name` : Name
- `sex` : Sex
- `age` : Age
- `sibsp` : Number of Siblings/Spouses Aboard
- `parch` : Number of Parents/Children Aboard
- `ticket` : Ticket Number
- `fare` : Passenger Fare
- `cabin` : Cabin
- `embarked` : Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

**Target Variable**
- `survival` : Survival (0 = No; 1 = Yes)

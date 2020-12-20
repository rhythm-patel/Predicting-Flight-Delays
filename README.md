# Predicting Flight Delays

With the growth of the aviation sector, flight delays have become more common across the world. They cause inconvenience to the travellers and also incur monetary losses to airlines. Hence, we applied machine learning models such as Random Forests, XGBoost, Logistic Regression, and Naive Bayes to predict whether a given flight would get delayed or not. XGBoost Classifier performed exceptionally well producing an accuracy of 0.88 and an AUC of 0.94.

# Running on google collab

- To run the file smoothly, we request you to download the .ipynb file, and run it on google collab.
- Before running the file, one needs to copy this folder to his/her own google drive - [Link](https://drive.google.com/drive/folders/1HRDxih_6xN0uU2Js3xGF8zp5r_XPSEJc?usp=sharing)
- Please mount the google drive and check the folder path in the following preprocess method :
[Jump to code](/Code.ipynb)
```
def preprocess(analysis = False):

    Airlines = pd.read_csv('/content/gdrive/My Drive/ML_Project/airlines.csv')
    Airports = pd.read_csv('/content/gdrive/My Drive/ML_Project/airports.csv')
    Flights = pd.read_csv('/content/gdrive/My Drive/ML_Project/flights.csv')

```

# Running on your own device

- First, you will have to install the necessary modules mentioned below:
  1. datetime
  2. numpy
  3. pandas
  4. seaborn
  5. matplotlib
  6. sklearn
  7. xgboost
  
- Please download the datasets from the following [link](https://drive.google.com/drive/folders/1HRDxih_6xN0uU2Js3xGF8zp5r_XPSEJc?usp=sharing)
- You will have to change the folder path in the preprocess method according to your datasets: [Jump to code](/Code.py)
```
def preprocess(analysis = False):

    Airlines = pd.read_csv('/content/gdrive/My Drive/ML_Project/airlines.csv')
    Airports = pd.read_csv('/content/gdrive/My Drive/ML_Project/airports.csv')
    Flights = pd.read_csv('/content/gdrive/My Drive/ML_Project/flights.csv')

```

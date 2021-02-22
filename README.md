# Decision-Tree-Classification
This project uses the Decision Tree Classifier algorithm to predict income levels based off of certain values. It uses attributes such as occupation, relationship status, age and more to predict whether an individual will make over or under $50,000.

![enter image description here](https://media.istockphoto.com/vectors/decision-diagram-color-icon-block-chart-problem-solutions-operations-vector-id1200922650?k=6&m=1200922650&s=612x612&w=0&h=1DuG0eg_NnGBTBOyvH8C6ohVV0f8phln4zPrum62gLw=)
## Steps
1. Cleaning and preparing the data
2. Examining descriptive stats of each attribute/column
3. Displaying stats via bar charts
4. Creating dummy variable dataset
5. Making Decision Tree classifier Function
6. Evaluating performance metrics of the model
7. Generating a function to make predicitons

## Requirements

* Python
* Google Colab

## Packages 
import numpy as np

import pandas as pd

import matplotlib.pyplot as plt

import os

from collections import Counter

from sklearn.metrics import accuracy_score

from sklearn.metrics import recall_score

from sklearn.metrics import precision_score

from sklearn.tree import DecisionTreeClassifier

from sklearn.metrics import confusion_matrix

from sklearn.tree import export_graphviz

from IPython.display import Image

from google.colab import drive

## Launch

Download *CA03_Decision_Trees* and open the file in Google Colab.

In Google Drive, create the file structure below:

'/content/drive/MyDrive/MSBA_Colab_2020/ML_Algorithms/CA03/census_data.csv'

Next, open the attached *census_data* file and import the file into the previously created folder. 

## Authors

[Joshua Rotuna](https://github.com/joshrotuna)

## License

This project is licensed under the  [MIT](https://choosealicense.com/licenses/mit/)  License.

## Acknowledgements

The project files were provided by Arin Brahma, Loyola Marymount University.

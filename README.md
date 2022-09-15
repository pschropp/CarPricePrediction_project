# Car Price Prediction

## Table of Contents

1. [Installation](#installation)
2. [Repository Structure](#structure)
3. [Motivation](#motivation)
4. [Results](#results)
5. [License and Acknowledgements](#license)


### Installation <a name="installation"></a>
All analysis is done in a jupyter notebook which only depends on the packages numpy, pandas, sklearn, seaborn and matplotlib. The code was tested on Python 3.9.

### Repository Structure <a name="structure"></a>
- this README file
- Jupyter Notebook: https://github.com/pschropp/CarPricePrediction_project/blob/main/car-price-prediction-challenge.ipynb
- Dataset as .csv, also on: https://www.kaggle.com/datasets/deepcontractor/car-price-prediction-challenge
- .gitignore file to keep the repo clean

### Motivation <a name="motivation"></a>
This is the first project assignment of the Udacity course 'Data Scientist'.
The features determining car prices are analysed and a linear regression model is set up to predict prices.

#### Questions
1. Which are the main factors to dertermine the price of a car from the data available in the dataset?
2. What can be derived from the data for the average car buyer?
3. Can we set up a model to predict car prices?

### Results <a name="results"></a>
#### Answer to Q1
The corraltion matrices and plots can be found in the notebook

#### Answer to Q2
Some findings that are relevant and understandable for the average car buyer habe been posted in this blog post on medium: https://medium.com/@oacqbea0e/what-really-makes-a-difference-for-resale-values-of-cars-3e51e621ee18

#### Answer to Q3
A model has been set up. However, the r2 score and mean squared errors are not very promising. This could be overcome by:
- a bigger dataset to also make use of manufacturer and model information columns without overfitting
- more / better information (columns): size of the car, segment, condition etc.
- more advanced modeling

### License and Acknowledgements <a name="license"></a>
For information about the dataset refer to kaggle: https://www.kaggle.com/datasets/deepcontractor/car-price-prediction-challenge

Feel free to use the code in the jupyter notebook as you like.

# Colour Words

Predict the Colour based on RGB values.


# Inputs and Outputs

## Inputs:
	- colour-data.csv
## Ouputs:

	- prediction_lab.png (shows actual colurs compared to predicts by model)
	- predictions_rgb.png (shows actual colurs compared to predicts by model)

## Installation and Setup Instructions

Clone down this repository.

Installation:

Most of the libraries needed can be found in Anaconda which can be downloaded from: https://www.anaconda.com/distribution/

Run the program:

`python3 colour_bayes.py colour-data.csv`


## Reflection

  - This was an assignment for Data Science class
  - I learned how to train machine learning models by splitting data with training data and validating data  
	- I used GaussianNB model which uses naïve Bayes classifier to train the model.
	- I learned that sometimes transforming the data first will create a better model. In this case transforming RGB data to LAB colour space is more perceptually uniform and gives better results.



## Technologies, Frameworks, Tools used
	-Pandas and Numpy
	-GaussianNB machine learning model
	-

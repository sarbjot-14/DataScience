# Unlabeled Weather

A program to predict the canadian city based on a given weather data.


# Inputs and Outputs

## Inputs:
	- monthly-data-labelled.csv  (data to train ML model)
	- monthly-data-unlabelled.csv (data to make predictions on)

## Ouputs:
	- labels.csv  (the predictions for the unlabelled data in monthly-data-unlabelled.csv)

## Installation and Setup Instructions

Clone down this repository.

Installation:

Most of the libraries needed can be found in Anaconda which can be downloaded from: https://www.anaconda.com/distribution/

Run the program:

`python3 weather_city.py monthly-data-labelled.csv monthly-data-unlabelled.csv labels.csv`


## Reflection

  - This was an assignment for Data Science class
  - assignment was pretty straight forward and did not take too long
	- It was a little bit hard to pick a machine learning model that would be good for this situation. Ended up with Support Vector Machine learning model that did a good job splitting and catagorizing the cities
	- The model had a score of about 80 percent, which I would say is acceptable because some cities have very close weathers becuase of proximity.
	- Here is the cities the model got wrong:

	truth      prediction
	5           Calgary        Edmonton
	7          Montreal          Ottawa
	13          Seattle        Victoria
	17         Winnipeg          Regina
	20          Toronto          London
	23         Montreal          Ottawa
	29         Victoria       Vancouver
	34           Regina       Saskatoon
	38           Regina        Edmonton
	42        Vancouver        Victoria
	46        Saskatoon          Regina
	48         Edmonton          Regina
	50           Regina       Saskatoon
	51        Saskatoon          Regina
	53          Atlanta     New Orleans
	55         Winnipeg       Saskatoon
	62        Vancouver        Victoria
	81         Winnipeg          Regina
	84   Raleigh Durham         Atlanta
	91         Edmonton       Saskatoon
	92           Ottawa        Montreal
	93         Edmonton       Saskatoon
	95         Edmonton         Calgary
	102          Ottawa          Québec


## Technologies, Frameworks, Tools used
	-Pandas and Numpy
	-XML gps coordinates
	-Kalman Filter
	-Matplot

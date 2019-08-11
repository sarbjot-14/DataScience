# GPS Tracks

A program to filter noise from gps data and then calculate the distance walked.


# Inputs and Outputs

## Inputs: 
	- walk1.gpx or walk2.gpx
## Ouputs:
	- calc_distance.txt with results
	- out.gpx (smoothed coordinates)
	- MyGPSFiles-out.png with smoothed and unsmoothed path shown

## Installation and Setup Instructions

Clone down this repository. 

Installation:

Most of the libraries needed can be found in Anaconda which can be downloaded from: https://www.anaconda.com/distribution/

Run the program:

`python3 calc_distance.py walk1.gpx` 


## Reflection

  - This was an assignment for Data Science class
  - Cleaning the data and finding the right inputs for the Kalman Filter was a little bit hard. Working with XML was also difficult
  - I needed to create an efficient function to calcute the distance between two gps coordinates and then add all the distances up which was unexpectedly challenging.


## Technologies, Frameworks, Tools used
	-Pandas and Numpy
	-XML gps coordinates
	-Kalman Filter
	-Matplot
	


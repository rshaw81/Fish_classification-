# Fish Classification Model
The following project is designed to allow the user to input the required measurements for their unknown fish species and recieve a resulting fish species. The program is utlizing a Random Forest classifier and provides a 75% accuracy rate. The dataset used is a dataset containing 160 samples of fish from 7 species. As well, HTML and CSS were used in order to construct the interface. 
## Getting Started
The following instructions will allow you to get the system up and running on your local device. 
### Prerequisities 
Before beginning ensure that python is installed on your local device. As well, it is easiest to work on your program of choice. I utilized Pycharm in the process of creating this interface. You can install python through anaconda. 
### Installing 
In this project there were 4 main modules used: numpy, pickle, pandas, and flask. Within flask we imported Flask, request, jsonify, render_template. There were imported in the following way:

import numpy as np

import pickle

import pandas as pd

from flask import Flask, request

from flask import Flask, request, jsonify, render_template

The HTML and CSS required no addition packages, simply knowing how to write HTML and CSS code will be suffice. 

## Running Test

In order to run the test you must first have downloaded the jupyter notebook that was used to make the model. As well, you must save the pickle file that contains the model. This model is used in the application for predicting the fish species. 
The way the model work is by recieving input from the user, the providing a output of the fish species. The html page utilizes this in the background. 


## Deployment

In order to deploy the flask app, we utilized Heroku which you must first navigate to the internet and sign up for an account. In order to deploy this on Heroku you must save all files in your own github and link the Heroku and your GitHub through the Keroku user interface. Once this is complete you can simply deploy the system on Heroku and recieve a link that will run the interface and code. 

## Author

Ryan Shaw

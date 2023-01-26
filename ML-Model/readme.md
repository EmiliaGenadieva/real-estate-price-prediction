# Description
In this part of the project, the data is being prepared for Machine Learning, trained and evaluated.
The data is cleaned in such a way that the ML Model can be processed and analyzed. This involves many steps, there are various methods to accomplish the same task. This repo gives a broad picture in order to provide a deeper understanding for these different ways of ML preprocessing.
More simple explained - this means that there can't be null and categorical-text values when one builds ML models. One can easily read this code because each peace of code is provided with a comment describing the purpose of the step.
+ 'ml-preprocessing': In this file one can find useful code for different data cleaning techniques - the replacement of the null values.
+ 'data_transformation' shows ways how to encode the categorical fields of the dataset into numeric values. At the end of this file, there are no more string values in the data. The DataFrame output is again exported to a .csv file for further exploration. 
+ 'ml-model-creation': This main file contains a pipeline. This is reusable and compact way of defining the steps for the preprocessing of the data. Steps envolved: cleaning, fitting the model and displaying the results of the performance of the model.

# Installation
One can adapt it on a different dataset provided one follows the same pattern:
1. ml-preprocessing - replacing np.nan with some values wich include 0
2. data_transformation - encoding the categorical fields of the data
3. ml-model-creation - creating ML models and evaluating them

# Usage
The code provided in this repo is reusable. The column names are particular to the immo project. These columns can be of any type(object, float, int...)
One can either review :
1. the 'ml-model-creation' file with all the steps or
2. one can follow all of the proposed preprocessing steps 

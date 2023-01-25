# Description
In this part of the project, the data is being prepared for Machine Learning, trained and evaluated.
The data is cleaned in such a way that the ML Model can process and analyze it. This involves many steps, there are various methods to accomplish the same task. This repo gives a broad picture in order to provide a deeper understanding of these different ways of ML preprocessing.
More simple explained - this means that there can't be null and categorical values in the data. One can easily follow as each peace of code is provided with a comment describing the purpose of the step.
+ 'ml-preprocessing': In this file one can find useful code for different data encoding techniques - the replacing of the null values.
+ 'data_transformation' shows ways how to encode the categorical fields of the dataset into numeric values. At the end of this file, there no more string values in the data. The DataFrame output is again exported to a .csv file for further exploration. 
+ 'ml-model-creation': This main file contains a pipeline. This is reusable and compact way of defining the steps in the preprocessing of the data. Steps envolved: cleaning, fitting the model and displaying the results of the performance of the model.

# Installation
One can adapt it on a different dataset provided one follows the same pattern:
1. ml-preprocessing - replacing np.nan with some values
2. data_transformation - replacing the categorical fields of the data
3. ml-model-creation - creating a ML model and evaluating it

# Usage
The code provided in this repo is reusable. The column names are particular to the immo project. The input columns can be of any type(object, numerical...)
One can either review :
1. the 'model-creation' file with all the steps, provided the data is clean of the undefined datatype(np.nan) 
2. or one can follow all the proposed preprocessing steps 

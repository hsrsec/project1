### Table of Contents

1. [Project Description](#motivation)
2. [Installation](#installation)
3. [File Description](#file)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Project Description <a name="motivation"></a>

This project deals with data from Seattle AirBNB. The data can be found <a href="https://www.kaggle.com/airbnb/seattle/data">here</a>.

The task is subdivided into three parts:

#### 1. Part
In the first part we are interested in the question if there is any seasonality visible in the data. I.e. is there a price pattern
within the data that for instance shows that i.e. in January the prices are generally lower than in July.

#### 2. Part
In this part the main objective is to analyse if the prices of Seattle AirBNB are dependent on the different neighbourhoods which are provided
in the data. Explicitely the question "Is there a neighbourhood bias" is accompanying this part.

#### 3. Part
In part 3 we want to incorporate a price prediction model with a set of identified features. The results of part 1 are included in to this analyses. The evaluation is then done with the importance of the weights with respect to the features.


## Installation <a name="installation"></a>

The code should run with no issues using Python version 3.*. You should have installed the following packages:
- Seaborn
- Matplotlib
- Sklearn
- Pandas
- Numpy
- Statsmodels

You should download the data from the above mentioned webpage and put it into the same location as the jupyter notebook.

## File Description <a name="file"></a>

There exists 1 jupyter notebook, where you can find all the provided code. The code is structured into 
two parts due to the structure of the task. The code is supported by explanations and comments and where
necessary by markdown cells.


## Results <a name="results"></a>

The main results are summarized at <a href="https://medium.com/@hsrsec/airbnb-seattle-pricing-472d6d8ddd49">my space</a> at medium.com.

## Licensing, Authors, and Acknowledgements <a name="licensing"></a>

The data is provided from AirBNB and can be downloaded at the page mentioned in the project description. The Licensing
for the data and other information can be found at the same provided link. My code provided in the file
'Seattle_airbnb.ipynb' is free to use.

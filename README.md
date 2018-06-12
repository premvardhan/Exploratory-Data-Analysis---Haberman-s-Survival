# Exploratory Data Analysis : Haberman's Survival

Relevant Information

The dataset contains cases from a study that was conducted between 1958 and 1970 at the University of Chicago's Billings Hospital on the survival of patients who had undergone surgery for breast cancer.

It contains :-

    305 datapoints/rows
    4 fearures includeing class label

Attributes/Features Information

There are 4 features including class label/dependent variable.
30 - It represents age of patient at the time of operation(numerical)
64 - It represents year of operation(numerical)
1 - It tells no of +ve auxillry node detected(numerical)
1.1 - Survival status 1 = the patient survived 5 years or longer 2 = the patient died within 5 year

Objective : -

To classify/predict a patient survival who had undergone surgery for breast cancer.

There are some few steps which we will follow throughout this notebook.

Loaded all the necessary package
We will load our dataset into pandas DataFrame and 
In the main file you will get different-different types of plot like - 
1. Univariate Analysis - In this part we will analyze our dataset using PDF(Probability Density Function),CDF(Cummulative Distribution Function), Box Plot and Violin Plot. 
2. Bivariate Analysis - In this part we will use Scatter Plot and Pair Plot.

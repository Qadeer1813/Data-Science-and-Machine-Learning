# Data-Science-and-Machine-Learning

**Student Name: Qadeer Hussain**

**Student ID: C00270632**

**Lecture: Greg Doyle**

**Linear Regression**

# Project Description
The purpose of this project is to prediuct the Birth to Death ratio in regions using Linear Regression I was able to plot the graph.

# Data Source
The dataset that was used for this project can be downloaded from https://population.un.org/wpp/Download/Standard/MostUsed/ 

# Processing
After downloading the data I needed to select which column I would be uing for my Linear Regression it. The first thing was to load the data which was done by reading in the csv. Next I filtered the ```Type``` column by ```Region```. I then did a test print ```region_data.head()```.
After doing this I seleected the ```Region, subregion, country or area *``` ```Year```, ```Births (thousands)```, ```Total Deaths (thousands)``` columns which I will be using to filter out the Name of the region, Years, Births, and Deaths. I prceeded to run another print on this
to view the data rows that would be used for plotting. I then started cleaning the data, first stated cleaning any numeric values to remove spaces and commas from the ```Births (thousands)```, ```Total Deaths (thousands)``` columns. I printed the data again. In te same column I converted
the columns to numeric and handled any errors. I then divided the ```Births (thousands)```, ```Total Deaths (thousands)``` columns to get the Birth to death ratio. An example In 1950 Africa ```Births (thousands)```: 10879 / ```Total Deaths (thousands)```: 6126 = Births to Death Ratio = 1.775873

# Data Understanding and Visualisation 
The dataset for this project gives the estimates of all Regions, Subregions and Country/Area. The population, Fertility, Mortality and Migration. After processing for regions and the Fertility Birth Rates and Mortality Death reaths
I got the Birth to Death Ratio of the different regions from 1950-2023. 

After doing the processing the data for the Birth To Death Ratio this was the plotted data: 

![image](https://github.com/user-attachments/assets/bfec4b78-4805-4f0f-9d82-1bc9aaae5db8)

This image shows all the regions of ther world and there Birth to Death Ratio in coloured format from 1950-2023.

To get the specific Birth to Death Ratio fo speciofc Regions, I added code which would take a Year and a Subregion of choosing of the user to using the existing ```cleaned_data``` I was able to plot the the Ratio's on the graph.

For example:

![image](https://github.com/user-attachments/assets/1ee23b81-f81b-470b-a3fa-fda2006b25f8)

This plotted Birth to Death Ratio was for Africa and by looking at by looking at the Regression line we are able to predict what the futrue Birth rate would be for Africa. 

# Algorithims:
Linear regression model is applied to the data. This model is trained on th exisiting dataset which for us is the Years and there calculated Birth to Death Ratio. 
Once the model was traind we can start predicting future for different regions.

# Online Sources:
1. Jakevdp (2023) Pythondatasciencehandbook/notebooks/05.06-linear-regression.ipynb at master · JAKEVDP/Pythondatasciencehandbook, GitHub. Available at: https://github.com/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/05.06-Linear-Regression.ipynb (Accessed: October 2024). 
2. World population prospects - population division (2024) United Nations. Available at: https://population.un.org/wpp/Download/Standard/MostUsed/ (Accessed: October 2024). 
3. User guide# (2024) User Guide - pandas 2.2.3 documentation. Available at: https://pandas.pydata.org/docs/user_guide/index.html (Accessed: October 2024). 
4. NumPy documentation# (2024) NumPy documentation - NumPy v2.1 Manual. Available at: https://numpy.org/doc/stable/ (Accessed: October 2024).
5. Matplotlib 3.9.2 documentation# (2024) Matplotlib documentation - Matplotlib 3.9.2 documentation. Available at: https://matplotlib.org/stable/ (Accessed: October 2024).
6. User guide (2024) scikit. Available at: https://scikit-learn.org/stable/user_guide.html (Accessed: October 2024). 

# Tools and Tech Used: 
1. Linear Regression
2. Jupter Notebook
3. Pandas Library - Loading the data and analysing it
4. Numpy Library - Processing the data
5. Matplotlib - Plotting and Visualising the graph 
6. Scikit Learn(Sklearn) - Implementing linear regression model.
 

# CV_03_ClientAgeDetection

# ***Computer Vision*** - Machine Learning Model for Supermarket Clients Age Detection

## Project Description

The chain supermarket includes a computer detection system for processing customer pictures taken while making a purchase at a cashier desk. Photo fixation in the checkout area will help determine the age of customers in order to:  
- analyze purchases and offer products that are of interest to buyers of this age group; 
- control the conscientiousness of cashiers when selling alcohol.


## Project Goal
To solve a regression problem by constructing a machine learning model, which detects an age of a customer. 

## Data
The dataset of pictures and age is given in the .png and .csv formats.
Данные взяты с сайта [ChaLearn Looking at People](http://chalearnlap.cvc.uab.es/dataset/26/description/).


## Project Methodology
1. Exploratory Data Analysis of the dataset.
2. Data proprecessing for modelling.
3. Tuning and testing a neural network, preferably **ResNet50** with an activation function **'ReLU'**, because the ReLU function does not change positive forecasts of the network, and all negative ones lead to zero. Numbers less than 0 cannot be.
4. **Quality metric is accuracy < 6.5.**
5. For data extraction please use ImageDataGenerator —flow_from_dataframe(dataframe, directory, ...)

## References
- [Image Data Processing](https://keras.io/api/preprocessing/image/)

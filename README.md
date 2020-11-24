# General Assembly Projects
### By: Gladys Pao
This repository includes all projects that I have worked on during my Data Science Immersive Course at General Assembly.
Each project folder contains a separate README.md, which serves as a primer for how I approached each project.

## List of Projects

### Project 1: Data Visualisation Project
#### SAT and ACT Analysis
This project examines data that covers the participation rates and scores of students for the SAT and ACT exams in the United States (US). With the data organised at the state-level, participation rates, component scores and total or composite scores of each exam are provided for the years, 2017 and 2018. Through the use of these data, a state-by-state comparison and analysis of participation rates and scores of each exam is made, with insights derived from the analysis to help find out the trends and factors influencing participation rates in various US states.
With insights made from these analyses, this project aims to suggest a suitable state and recommend actions to be taken to improve that particular state's SAT participation rate moving forward.

### Project 2: Linear Regression Project
#### Ames Housing Data and Kaggle Challenge
This project examines data of two datasets on house prices in Ames, Iowa: one train dataset that covers the features of houses and their associated house prices, and one test dataset that covers the features of houses only. Through the use of the train dataset, we studied the relationship between various features of a house and their impact on the final sale price. An appropriate regression model (ridge regression model) for the prediction of house prices was chosen, which was eventually used to predict the sale prices of houses using the features from the test dataset. Finally, we studied and interpreted the ridge regression model that we used in the context of how certain features affect house prices, followed by recommendations for increasing the value of homes in Ames after model interpretation.
Ultimately, we aim to provide a useful prediction model for real estate agents to predict house prices for their existing and potential clients, providing useful insights on the effect of different features on real estate prices through our model.

### Project 3: NLP and Web Scraping Project
#### Web APIs & Classification
In this project, we are tasked to work with Reddit's API to scrape and store user posts between these two subreddits, and then make use of Natural Language Processing to analyse, understand and derive information from text data. This is followed by the selection of an appropriate classification model (TfidfVectorized Multinomial Naive Bayes) to classify and predict which subreddit a given post come from. To choose our final classification model, we compared the models' accuracy scores (and specificity and recall rates if there are two or more models that performed similarly in accuracy).

Ultimately, we aim to provide a model that can accurately predict a post's subreddit origin, highlighting not only the most popular words but also the most indicative words (which suggests the subreddit origin of a post) in each subreddit. 

### Project 4: Virus Classifier Group Project
#### Prediction of West Nile Virus
With the purpose of controlling the West Nile Virus epidemic, we have been tasked to analyse past data of West Nile Virus outbreaks and get insights on how to control this public health threat, before analysing the costs (as well as the benefits) on the usage of pesticide coverage for the control of West Nile Virus. Working with the data provided by the Disease And Treatment Agency, we will be predicting which areas are most likely to contain the West Nile Virus given their weather conditions and time variables. To choose our final classification model, we will be comparing the models' ROC_AUC scores (and recall rates if there are two or more models that performed similarly in the ROC_AUC metric).

Ultimately, we aim to provide a model that can accurately predict whether an area has the West Nile Virus, highlighting the most important conditions that leads to a higher probability of the West Nile Virus at a certain area/location. After gaining insights on the most important features as prioritised by the model, this will be followed by an in-depth cost and benefit analysis of pesticide coverage on certain WNV-predicted areas and then paired with recommendations on suitable West Nile Virus control efforts in the city of Chicago.

### Project 5: Computer Vision Capstone Project
#### Skin Lesion Classification and Diagnosis
Link to my capstone project's repository: https://github.com/datawithgladys/skin_lesion_diagnosis_classification

In this project, we aim to improve the diagnostic rate of skin cancer through the classification of skin lesions for dermatologists working at hospitals or skin cancer clinics in Singapore, who will need experience or expertise in diagnosing skin cancer before they can accurately identify and diagnose lesions upon visual and dermoscopy inspection. This will be done through the classification of skin lesion dermoscopy images, in which we will predict two important tasks through the usage of Convolutional Neural Network models:<br>
(1) a specific skin lesion diagnosis, and<br>
(2) whether the lesion is malignant, benign, or pre-cancerous.<br>

The model will be evaluated based on its accuracy, followed by its recall rate since we are looking to minimise false negatives. Ultimately, we aim to get as close to a real evaluation of a dermatologist as possible: predicting the type of skin lesion; and whether the lesion is malignant, pre-cancerous or benign from dermoscopy images. With our models, we hope to aid dermatologists in their decision-making process of diagnosing skin lesions, hence allowing them to improve their diagnostic accuracy and come up with appropriate treatments for patients with skin lesions and/or cancers.




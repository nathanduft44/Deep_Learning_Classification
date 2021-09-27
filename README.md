# Deep_Learning_Classification
## Purpose:
Traditionally, investors use intuition and deduction to determine what startups will flourish, but with the help of deep machine learning we can form data-driven investments. This machine learning model is designed to spot nonlinear relationships in the applicant data to classify what startups will be more likely to succeed or fail. 
## Preparation:
Encode all of the features of data from metadata to binary to use for models. Then I built, trained and evaluated the model to try and understand how well it was grouping the data. 
The OneHotEncoder was used to encode our main list of categorical variables. The application data consists of [Affiliation, Classification, Use_Case, Organization, Income AMT, Special Considerations]

## Model Review:
The most accurate model was alternative model 1 as it was able to achieve a 74% accuracy. That is the one I would recommend to build off of an improve even more. To optimize the models I tinkered with different number of hidden nodes for the hidden layers, activation functions, and the epochs. 

## Technology
tensorflow
sklearn
pandas
jupyter lab

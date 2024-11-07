# 2024 Purdue Data4Good Case Competition

Tools Used - Excel \| Python \| PredictionGuard <br />
Methodologies Used - Machine Learning \| Tokenization \| Data Cleaning

As a part of Purdue's 2024 Data4Good Case Competition, the university partnered up with Tragedy Assistance Program for Survivors (TAPS). The goal of this competition was to program an AI model to accurately identify and categorize surveyees into one of the 6 stages of grief based on their responses to a TAPS survey. This would allow TAPS to place each individual in the corresponding program so that they could get the proper help based on their stage of grief.

My team and I were presented with 2950 rows of data in Excel, each represeting a different individual and their survey responses. Using Python and a PredictionGuard API (provided by the university) we were able to create a program that reads in the data from the csv file, categorize each surveyee, and return only the ID and category number for submission. The model implemented tokenization and NLP to assign different values for some of the survey question that were open-ended and not based on a numerical scale. 


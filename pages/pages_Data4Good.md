# 2024 Purdue Data4Good Case Competition

Tools Used - Excel \| Python \| PredictionGuard <br />
Methodologies Used - Machine Learning \| Tokenization \| Data Cleaning

As part of Purdue's 2024 Data4Good Case Competition, the university partnered with the Tragedy Assistance Program for Survivors (TAPS). The goal of this competition was to program an AI model to accurately identify and categorize surveyees into one of the six stages of grief based on their responses to a TAPS survey. This program would allow TAPS to place each individual in the corresponding program so that they could get the proper help based on their stage of grief.

My team and I were presented with 2950 rows of data in Excel, each representing a different individual and their survey responses. Using Python and a PredictionGuard API (provided by the university), we were able to create a program that reads the data from the CSV file, categorizes each surveyee, and returns only the ID and category number for submission. The model implemented tokenization and NLP to assign different values for some of the open-ended survey questions that were not based on a numerical scale. 

[Excel Testing Data](https://1drv.ms/x/c/abd0fef50200edb3/EbxUPrxiP4pGnrX00qy3rWsBzFkzx2ptcg4ISzN96l7NhQ?e=jZe3Xg)<br />
[Excel Submission Data](https://1drv.ms/x/c/abd0fef50200edb3/Ec86YaGwKLlMhxXanUWiCckBOaaV285KEY-0HQ3cWdVweQ?e=10sq4n)<br />
[Python Script](https://github.com/evanhaines/evanhaines.github.io/blob/4d932f4af04dcf075409d25e578bc6a88e04627e/pages/Data4Good%20Case%20Comp.ipynb)

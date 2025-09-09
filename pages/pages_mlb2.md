# MLB Pitcher Injury Prediction & Analysis

Tools Used - Python <br />
Methodologies Used - Dogisitic Regression \| Data Visualization \| XGBoost \| Data Cleaning \| Decision Trees \| Machine Learning \| Data Wrangling

#### Project Purpose - Can we use machine learning techniques to accurately predict MLB pitcher injuries based on player performance data 

This was my partner and I's final project for my BAIS 6060 Data Science course. We pulled pitcher injury information, pitcher-level data, and pitch-level data from various sources using selenium and Data Wrangling Techniques. After scraping the data, we performed extensive data cleaning by doing everything from column name mapping to column addition, horizontal integration, missing value handling, etc. we used traditional Data Preprocessing techniques by scaling the numerical data, one hot encoding categorical variables, and using train/validation/test splits for our machine learning models.

We then created 3 machine learning models (Logistic Regression, Decision Tree, and XGBoost) for our classification prediction. After using various testing metrics like ROC AUC, precision, recall, etc. we determined that the XGBoost model performed the best and was able to predict pitcher injuries for both the current and future seasons with reasonable accuracy. Lastly, we used various data visualization techniques to create different charts and graphs, for our final summary and presentation. Overall, our final project received an A!

[Final Code](https://github.com/evanhaines/evanhaines.github.io/blob/604c6ff188370bc49bfd96dd86de7a3fe19b0a9e/pages/BAIS_6070_Final.ipynb) <br>
[Final Report](https://github.com/evanhaines/evanhaines.github.io/blob/0ef9dbed3e7b8499672b69bf49b0c26a3e43ce8d/pages/BAIS%206070%20Final%20Project%20Report.docx) <br>
[Final PPT](https://github.com/evanhaines/evanhaines.github.io/blob/379f01150d4cfbfee847b7b0c7aa57f75219df5a/pages/Data%20Science%20Presentation.pptx)


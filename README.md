# Opioid-toxicity-related-deaths-and-hospitalizations

### Dataset

[Opioid- and Stimulant-related Harms in Canada](https://health-infobase.canada.ca/substance-related-harms/opioids-stimulants/technical-notes.) 


### Source Code
[
Data Management of Opioid toxicity-related deaths and hospitalizations](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/8044888775324931/3765691144116402/5854611345732810/latest.html)

### Summary


Canada has severely experienced the “opioid-related” deaths and other harms with tragic impact on recipients, their families, society, and ultimately the health care system. These impacts are results of multiple factors. Evidence demonstrates the impact of covid-19 pandemic on aggravating “opioid-related” overdose, death, and other harms. Overall, opioid related Emergency Medical Services (EMS) was higher than deaths in Canada from 2018 to 2020. 

In the research, I used three machine learning models to predict the outcome of opioid or stimulant toxicity: Linear Regression, Logistic Regression, and Random Forest. 

Linear regression finds the best-fit line (i.e., linear relationships) between the dependent variable and independent variables. Linear regression is typically performed on a continuous dependent variable. The linear regression model consists of dependent variables (label) and explanatory variables (features vector) and is fitted on the vectorized training dataset. The model performance was evaluated using the testing dataset.

Logistic regression models the probability of an event (death outcome of opioid/stimulant toxicity in this research) based on the demographic characteristics of the individual. Logistic regression is a statistical technique that is primarily used to analyze binary dependent variables, and it aims to find the best weight coefficient for each independent variable.

The Random Forest algorithm constructs multiple samples of the training dataset, makes a prediction for each sample, and averages out those predictions to get the most accurate estimate of the output value. Random Forest algorithms can be used on both continuous and binary data.


**Based on the accuracy score results in each model, I would suggest using the Random Forest model for further analysis of opioid/stimulant toxicity.**

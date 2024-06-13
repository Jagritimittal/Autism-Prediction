# Autism-Prediction <br/>
 The main objective of the project is to propose a method for the early detection of autism spectrum disorder (ASD) using Machine Learning techniques with the use of historical data ( to be more specific attributes). Thereby helping earlier detection of autism, faster processing, and better life of individuals.<br/>
# About the Dataset <br/>
‘Autism Screening Adult’ dataset is used.<br/>
This dataset is composed of survey results for more than 800 people who filled an app form.<br/>
Predict the likelihood of a person having autism using survey and demographic variables.<br/>
Dataset Source : UCI repository.<br/>
# Feature Selection using Chi-square Test<br/>
The chi-square test is a statistical test used to determine whether there is a significant association between two categorical variables.<br/>
## 1. Define the Hypothesis: <br/>
Formulate the null hypothesis (H0) and the alternative hypothesis (H1) to determine whether there's an association between the categorical feature and the target variable.<br/>

## 2. Choose a Significance Level:<br/>
 Select a significance level (α) to determine the threshold for accepting or rejecting the null hypothesis.<br/>

## 3. Create Contingency Table: <br/>
Construct a contingency table (cross-tabulation) to summarize the frequency distribution of the categorical feature and the target variable.<br/>

## 4. Expected Frequency:<br/>
Compute the expected frequency for each cell in the contingency table based on row and column totals.<br/>
## 5. Calculate Chi-Square Statistic: <br/>
Calculate the Chi-Square statistic using the formula, which measures the discrepancy between observed and expected frequencies normalized by the expected frequencies.<br/>

## 6. Calculate Degrees of Freedom: <br/>
Determine the degrees of freedom for the Chi-Square distribution based on the dimensions of the contingency table.<br/>
df = (total_rows - 1) * (total_cols - 1)<br/>

## 7. Find p-value: <br/>
Look up the p-value corresponding to the Chi-Square statistic and degrees of freedom in a Chi-Square distribution table or using statistical software.<br/>

## 8. Decide on Null Hypothesis:<br/>
Compare the obtained p-value with the chosen significance level (α). If the p-value is less than α, reject the null hypothesis, indicating a significant association between the categorical feature and the target variable.<br/>

# Why Chi-square test?<br/>
Chi-Square test is commonly used for feature selection when available features and target variable are categorical.<br/>

# Applied variou Machine Learning models <br/>
  1. Logistic Regression<br/>
  2. Decision Tree<br/>
  3. Naive Bayes<br/>
  4. SVM<br/>
  
# Conclusion <br/>
Based on the results of the experiments performed we can conclude that SVM gave the best results <br/>
With Holdout - Train Accuracy 0.91 and Test Accuracy 0.82. <br/>
With Cross Validation - Mean accuracy 0.856 <br/>
                        Confidence Interval (95.0%): (0.837, 0.876)

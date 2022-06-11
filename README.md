# Analyze A/B Test Results
The 2nd project in “Advanced data analysis” Nano degree from Udacity.
## Overview: Analyze A/B Test Results
* Data analysts and data scientists very commonly perform A/B Test projects.
* For this project, you will be working to understand the results of an A/B test run by an e-commerce website. The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. 
* Our goal is to work through this notebook to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.
## Agenda
### Part I - Probability
Statistics were computed to find out the probabilities of converting regardless of page. These were used to analyze if one page or the other led to more conversions.
### Part II - A/B Test
hypothesis-testing was conducted assuming the old page is better unless the new page proves to be better at a Type I error rate of 5%. The data were bootstrapped, and sampling distributions were determined for both pages. Conclusions were drawn on conversions for both pages by calculating p-values.
### Part III - Regression
Logistic regression was then performed to confirm the results of the previous steps. Null and alternative hypotheses associated with this regression model were stated and verified using statsmodel.
### Conclusions
There is no sufficient evidence to tell us that the new page has a higher conversion rate than the old one.

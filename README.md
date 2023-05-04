# Self-Assessment

## Written Analysis: 

For our project, I was responsible for the exploratory data analysis portion. I proposed that we use RStudio to conduct the linear model in Multiple Linear Regression to test the significance and normality of the data between the multiple independent variables in comparison to the dependent variable, deaths. So in order to achieve this, I'd grouped the predictors into different categories and interpreted the p-values to see if they would be likely or unlikely to be meaningful in the this regression. I'd also contributed in the beginning phases of running the machine learning model. Then, I opted to visualize my MLR model with the scatterplot matrices to include histograms across the diagonal, which showed that there a large right skewness within one of the categories for which I grouped variables, which was Deaths Vs. Risk Factors. I think the challenge was figuring out why the accuracy was a really low score, so I think that visualizing whether the data was normal, positively contributed to choosing which machine learning model made more sense for our project. 

## Written Summary: 

So, initially I had deployed the Logistic Regression ML model, however, the accuracy score turned out be a super low number, that we didn't expect. Once I was able to recognize that there was skewness within the data, one of my project partners were able to adjust the skewness and transform the data to help with the ML model. 
I had done some data cleaning in regard to my role, but also suggested there would need to be some type of transformation when I received an error in my R Script that showed that there shouldn't be any negative values when performing a specific function. I believe that at the time, I was trying to perform a log transformation visualization in R. 
In a separate team meeting, I had suggested we can add an additional visualization in regard to Deaths Vs. Vulnerable Population if we were to add any additional visualizations, though it didn't make it to the Final Model. I made this suggestion based on my EDA contribution as I had created a subcategory of Deaths Vs. Vulnerable Populations. 

## Project and Team Summary: 

The most common methods of team communication was a group chat via Slack, and we used Zoom to check in with the teams in case there were any questions or to update in general for where we are at, essentially giving the checkpoints of progress for each team member. I think one of our greatest strengths was the fact that we were able to bounce ideas off of each other, and communicated clearly when things or certain topics not previously used was unfamiliar, or was difficult to initally interpret. 

Our topic was to determine if the JHU data that shows raw covid data including deaths, [response variable] for states and counties will help determine if they were likely predictors for the final machine learning model, specifically to predict covid mortality with the CRE data. CRE stands for Community Resilience Estimates for which the data is derived from. The machine learning models used was a skew adjusted Random Forest Classifer Model. The reason behind it being skew adjusted is because from the Data Exploration, we interepreted the data to be majorly left skewed and the remaining data to be right skewed. The skew was adjusted as a transformation to normalize the data. 
As a result, we were able to obtain a much higher accuracy score compared to our initial findings. The final Random Forest accuracy score finalizaed to be 0.9348171701112877. 

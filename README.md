Summary of Findings & Interpretations: 
* Most NYC school teachers in 2019 completed the survey for their school. According to the boxplot, low teacher response rate were outliers.
* Many schools had about a 50% response rate from parents, resulting in a median of 56% and a mean of 55%. 
* 720 out of the 1829 schools did not have students complete the survey. Still, the median of the total student response rate was 69%, which indicates that response rate was high in schools that did require students to complete the survey.
* Most scores (Collaborative Teacher, Effective Leadership, Rigorous Instruction, Strong Family-Community connection) had a symmetric distribution around 3.6-3.8. This enforces that most scores were in the upper range, but there is a greater variation in score ranges for lower scores. 
* The average scores for all categories were around 3.6-3.7, with the mean just slightly lower than the median.
* Overall Interpretation of Scores: </br>
There seems to be a consistent perception of strong performance across these four areas, but there may be some room for improvement. Most respondants perceive the school as performing slightly above to above average  across all four categories.

Summary of Scores Correlation and Modelling the Data to Predict Trust Score of a School:
* P-value matrix shows statisitically significant correlations between all varibales, except that variable and itself.
* There is a strong correlation between
  - Collaborative Teachers and Effective School Leadership
  - Collaborative Teachers and Rigorous Instruction
* For Trust Score of a school, there is 
  - moderate correlation with Collaborative Teachers Score
  - moderate correlation with Effective School Leadership
  - moderate-weak correlation with Rigorous Instruction
  - moderate-weak correlation with Strong Family-Community Ties

 * Using a Polynomial Regression Model optimized with degree = 2 and with alpha = 10.0 has a r^2 (coefficient of determination) of 0.58 for training data and 0.61 for test data.

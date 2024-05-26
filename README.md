# Data Introduction


This dataset comprises NFL combine tests, player height/weight, and the round or pick at which the player was selected in the NFL draft. Key combine tests included are the 40-yard dash, cone drill, shuttle run, bench press reps, and vertical jump. After cleaning, the dataset consists of 11 features and 1 target variable: the round in which a player was drafted.
<br>
# Data Exploration


Upon exploration, I found that the features most highly correlated with the round a player was drafted were AV (Approximate Value) and the 40-yard dash time. AV is a comprehensive metric designed to evaluate players across all positions as equitably as possible. Additionally, the height and weight of players, as well as their combine test scores, remained relatively consistent across the years in the dataset.
<br>
# Model's


I processed the data through three different models, and here are the results on the testing data after tuning
<br>
**Linear Regression** accuracy **.49**  
**LGBM** accuracy **.77**  
**Random Forest** accuracy **.76**  
For production I would choose the lgbm Becuase it wass less overfit than the Random forest model
<br>
# Recommendations
When drafting players, prioritize the AV and 40-yard dash metrics, as these have the highest positive correlation with the draft round. Additionally, the data indicates that the average abilities of players are very similar each year in the draft, suggesting a level of consistency in player performance metrics annually.

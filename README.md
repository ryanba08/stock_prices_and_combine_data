# Data Introduction


This data was all about the combine tests, Height/weight ,and what round/ pick the player was selected in the nfl draft  
Some of the tests were 40 yard dash, Cone, Shuttle, BenchReps, Vertical Jump, and more.  
My data after cleaning has 11 features and 1 target being the round a player was drafted.
<br>
# Exploring the data


I found that the highest correlated features to the round a player was drafted to be AV(Actual Value) and Forty yard dash.  
AV is based on players stats and is a metric to grade players at every position equally as possible.  
I also found that every year in the draft players are very similar from Height and Weight to how they score on the combine tests.
<br>
# Model's


I ran my processed data through 3 models here are the results on the testing data after tuning  
**Linear Regression** accuracy **.49**  
**LGBM** accuracy **.77**  
**Random Forest**accuracy **.76**  
For production I chose the lgbm Becuase it wass less overfit than the Random forest model
<br>
# Reccomendations
If you are drafting players pay close attention to the Av and 40 yard dash as these have the highest correlation to the round a player will be drafted.
<br>
<br>
There is always next year in the draft my data shows the average of players abilities are very similar every year in the draft.
<br>
<br>
Players that have good cone and shuttle times in the combine tend to get drafted earlier. I reccomend watching for those players with good times
<br>
<br>
The model I built should be used as a tool to help scouts/Gm's of teams to give a grade of the player/ Idea where they will be drafted.

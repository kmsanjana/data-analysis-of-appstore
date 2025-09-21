<h2>Problem Statement: To expose the best combination for strategy games available in the AppStore in order to get a good user rating (4.0/5.0 and above).</h2>

<h3>Objective: To expose the best combination for strategy games available in the AppStore in order to get a good user rating (4.0/5.0 and above) </h3> 
To analyze the dataset, we will look at the relationship as below:

<h3>Strategy</h3>
<li>Genre grouping</li>
<li>Game Size analysis</li>
<li>Release date/ Update date factor</li>
<li>Game Price and In-App Purchase Factor (Grouped by Genre)</li>
<li>Age Rating Factor</li>
<br><br>
<h3>Analysis</h3>
<li>Games without User Rating should be dropped.</li>
<li>Perform Data Preparation by cleaning the data and removing null values.</li>
<li>Games with less than 200 user rating AND days since last update date <6month should be dropped to prevent biased ratings from the developer</li>
<li>Genre tags "Entertainment" and "Games" are removed from the Genre string as it does not provide meaningful insight</li>
<li>The remaining of the string are checked and grouped as follows:</li>
1. Puzzle= Puzzle/Board
2. Adventure= Adventure/Role/Role Playing
3. Action = Action
4. Family = Family/Education
 <li>State your inferences.</li>   
 <li>Identify Which genres have higher user ratings.</li>


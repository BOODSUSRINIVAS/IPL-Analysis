![image alt](https://wallpapercave.com/wp/wp7433218.jpg)
Objective Questions:-
 
1. List the different dtypes of columns in table “ball_by_ball” (using information schema)

2. What is the total number of runs scored in 1st season by RCB (bonus: also include the extra runs using the extra runs table)

3. How many players were more than the age of 25 during season 2014?

4. How many matches did RCB win in 2013? 

5. List the top 10 players according to their strike rate in the last 4 seasons

6. What are the average runs scored by each batsman considering all the seasons?

7. What are the average wickets taken by each bowler considering all the seasons?

8. List all the players who have average runs scored greater than the overall average and who have taken wickets greater than the overall average

9. Create a table rcb_record table that shows the wins and losses of RCB in an individual venue.

10. What is the impact of bowling style on wickets taken?

11. Write the SQL query to provide a status of whether the performance of the team is better than the previous year's performance on the basis of the number of runs scored by the team in the season and the number of wickets taken 

12. Can you derive more KPIs for the team strategy?

13. Using SQL, write a query to find out the average wickets taken by each bowler in each venue. Also, rank the gender according to the average value.

14. Which of the given players have consistently performed well in past seasons? (will you use any visualization to solve the problem)

15. Are there players whose performance is more suited to specific venues or conditions? (how would you present this using charts?) 



Subjective Questions

1.How does the toss decision affect the result of the match? (which visualizations could be used to present your answer better) And is the impact limited to only specific venues?

2. Suggest some of the players who would be best fit for the team.
   
3. What are some of the parameters that should be focused on while selecting the players?
 
4. Which players offer versatility in their skills and can contribute effectively with both bat and ball? (can you visualize the data for the same)

5. Are there players whose presence positively influences the morale and performance of the team? (justify your answer using visualization)

6. What would you suggest to RCB before going to the mega auction? 

7. What do you think could be the factors contributing to the high-scoring matches and the impact on viewership and team strategies

8. Analyze the impact of home-ground advantage on team performance and identify strategies to maximize this advantage for RCB.

9. Come up with a visual and analytical analysis of the RCB's past season's performance and potential reasons for them not winning a trophy.

10. How would you approach this problem, if the objective and subjective questions weren't given?

11. In the "Match" table, some entries in the "Opponent_Team" column are incorrectly spelled as "Delhi_Capitals" instead of "Delhi_Daredevils". Write an SQL query to replace all occurrences of "Delhi_Capitals" with "Delhi_Daredevils".


    🔍 Project Explanation: IPL Analysis
📌 Objective
To help Royal Challengers Bangalore (RCB) identify top-performing and cost-effective players ahead of the 2017 mega auction, using performance data from past IPL seasons. The aim is to:

Improve team selection strategy

Optimize player auction investments

Enhance match-winning capability using data-driven insights

📥 Data Acquisition
The analysis utilized a comprehensive IPL database with multiple interrelated tables:

Main tables: Player, Matches, Ball_by_Ball, Team, Venue

Supporting tables: Batting_Style, Bowling_Style, Season, Outcome, Player_Match, etc.

Data was sourced from open IPL archives and cleaned/formatted for structured SQL querying.

🔧 Data Transformation
Checked for nulls, duplicates, and outliers

Used SQL JOINs to combine multiple tables

Applied data type corrections and filtering logic

Used DDL/DML operations to restructure tables if needed

Created metrics such as averages, strike rates, and economy rates using:

SUM(), AVG(), COUNT(DISTINCT), MAX(), MIN()

Ranking functions to identify top performers

🧱 Data Modelling
Designed relationships between entities like Players, Matches, Venues, Teams

Created aggregated views for:

Player consistency

Venue-wise performance

All-rounder impact

Toss decision trends

Player-win correlation

Focused on relational modeling via SQL

📊 Data Visualization
(Inferred, not shown in slides) Ideal visuals include:

Bar charts for player averages

Heatmaps for venue performances

Pie/donut charts for toss decisions

Line graphs for trends over seasons

🔎 Key Insights
Top Batsmen: Kohli, Warner, and de Villiers are consistent performers.

Venue Strengths: Certain players dominate at specific venues (e.g., Kohli at Rajkot).

Toss Patterns:

Field-first at M Chinnaswamy & Eden Gardens

Bat-first at Chepauk & Uppal

All-rounders:

Bravo, Bhajji, and Watson show high impact in both disciplines.

Winning Impact:

Pandey, Yadav, and Ashwin show a high correlation with match wins.

🧠 Recommendations (with Reasoning)
Boost Death-Over Power
➤ Acquire finishers with high strike rates (e.g., Russell, Maxwell)

Strengthen Spin Department
➤ Focus on spinners for middle overs (e.g., Ashwin, Chawla) to control game tempo

Leverage Home Advantage
➤ At M. Chinnaswamy, build batting-heavy squads and chase more often

Invest in All-Rounders
➤ Target value-rich players like DJ Bravo, Chris Morris, or Russell to balance team

Develop Existing Talent
➤ Groom players like Washington Sundar for all-round roles

Balance Youth with Experience
➤ Mix veterans (Ashwin, Watson) with fresh talent to ensure continuity and stability

✅ Conclusion
With a data-backed auction and selection strategy focusing on venue-based strengths, death-over specialists, and versatile players, RCB can significantly enhance their chances of winning future IPL titles.




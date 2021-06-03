# Achievement-6---Global-Soccer-Statistics
Data Sources
Primary Data Source - FiveThirtyEight Soccer Match Data
•	Contains match-by-match scores and forecasts from 2016 till today
•	Obtained from fivethirtyeight.com a reliable data-driven news site
•	Contains every game played in 39 different leagues since 2016
•	Over 45000 games in the dataset
•	Variables include Season, Date, League, Teams, Team Ratings, Probability of each team winning, Score, expected goals
•	Limitations – Only includes the data for the past five years
Secondary Data Source - European Football Statistics attendance data
•	Contains attendance numbers for every country each year
•	Sourced from european-football-statistics.co.uk
•	Limitations – Data from the past year might not be very meaningful because of Covid-19
I chose to use these to data sets to see if the average number of goals scored in any given league impacts attendance. Additionally, I want to see if teams that are perceived as underdogs winning more often would lead to increased attendances. It would also be interesting to see how the number of goals per game has changed over time. 
Cleaning and Understanding the Data
•	Loaded up the primary data frame
•	Checked shape (45109, 23)
•	Checked columns
•	All the column names seem reasonable
•	All the games have data for both team names, the score and the league names
•	Average number of goas in a game is 2.695
•	Checked for duplicates – none found
•	All data types used seem to make sense
Limitations and ethics – The attendance data from last year isn’t very useful as almost no in person events were held due to Covid-19, because of that I’m going to use the data from 2019 and earlier.
Questions to explore
Does higher number of goals scored lead to higher attendance?
Are underdog teams winning good for attendance?
Has the number of goals per game changed over time?
How has the difference between the best and the worst teams changed?


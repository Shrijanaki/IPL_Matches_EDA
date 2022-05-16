# IPL_Matches_EDA

Dataset: Indian Premier League Analysis (2022)🏏 - IPL Matches 2008-2020 (https://www.kaggle.com/code/arbazkhan971/indian-premier-league-analysis-2022/data?select=IPL+Matches+2008-2020.csv)

I used MS SQL for this project

# Goal:

Data analysis plays a huge role when it comes to sports. It helps in identifying patterns and ways of imporvements and helps the analysts to make data-driven decisions. So what kind of patterns can we find in the data of the Indian Premier League, a men's cricket league that is played every year? The goal here is to find how the venue (the stadium) affects the decisions taken by the players and what role it plays in the match.

# The Dataset:

The data set contains the following attributes from the year 2008 to 2020:
- ID
- City
- Date
- Player of Match
- Venue
- Team 1
- Team 2
- Toss winner
- Toss decision
- Winner
- Result
- Result margin
- Umpire 1
- Umpire 2

# Data cleaning:
- There were no null values found
- I cleared out some mismatches in the spellings (Eg: Rising Pune Supergiants vs Rising Pune Supergiant)

# Ananlysis:

Firstly, I viewed the overall data, sorted out by the Venue and identified the matches played in each venue and how many matches each team won in the venues.

# Teams with the most wins by venue

The following table shows the teams that have won the most in the venues.

![teamwin](https://user-images.githubusercontent.com/53789918/168608528-92b150ba-8536-4961-bd9d-56a4e15da94b.JPG)

We can see that the team Chennai Super Kings has won around 70% (40/57 matches) held at the venue MA Chidambaram Stadium, Chepauk. 
We can also see the top win percentage of teams in other venues.

# Does the toss play an important role in each venue?

On comparing the toss winning team vs. the match winning team, toss played an important role in almost all the venues.

![Toss](https://user-images.githubusercontent.com/53789918/168605969-d1fc4909-7d28-420b-917b-2caf90ffebb6.JPG)

We can the toss winning team won the match all the time in two venues and 25 venues had more that 50% chance of winning the match if a team won the toss.

# What was the match - winning toss decision in each venue?

Since we now know that the toss had an effect on the match, what was the successful toss decision in each venue?

![decision](https://user-images.githubusercontent.com/53789918/168607506-82634b37-8349-4434-bdd9-5480808dac5f.JPG)

As we can see, in the Green Park venue, all the teams that won the toss chose to field and won the match. This also shows that in 9/7 matches in the Holkar stadium, the team chose to field and was successful. This is followed by the top winning toss decisions by the teams.

# Top 10 players with the most player of the match award

The table shows the players who won the most player of the match award.

![player](https://user-images.githubusercontent.com/53789918/168609586-749cdf7d-69f4-481b-9bb0-2e8a043c1824.JPG)

How does this number play out with the venue?

![playervenue](https://user-images.githubusercontent.com/53789918/168609919-5e5fafc9-a82f-4803-aa39-b7866ad86c72.JPG)

We can see the the players AB de Villiers and CH Gayle have won the most in the M Chinnaswamy Stadium. This helps us in identifying the strengths of players in certain venues. The table also shows players in other venues.

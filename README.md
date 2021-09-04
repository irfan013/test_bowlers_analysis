# test_bowlers_analysis
Several analyses will be performed using pandas library of Python language into a publicly avaliable Bowling records data (test matches) extracted from ESPN cricinfo website.

Data source: https://stats.espncricinfo.com/ci/content/records/93276.html

Data description:

**Dataset**: Bowling records in test matches that includes following columns such as
<br>1. **Player**: Name of the individual player followed by his country name/initials in parenthesis
<br>2. **Span**: Starting and end year of the player's test career
<br>3. **Mat**: Number of test matches played by the player
<br>4. **Inns**: Number of innings of test matches bowled by the player
<br>5. **Balls**: Number of balls bowled by the player
<br>6. **Runs**: Number of runs conceded by the player
<br>7. **Wkts**: Number of wickets taken by the player
<br>8. **BBI**: Best bowling figure of the player within an innings
<br>9. **BBM**: Best bowling figure of the player within a test match
<br>10. **Ave**: Bowling average of the player (the number of runs conceded per wicket taken)
<br>11. **Econ**: Bowling economy of the player (the average number of runs they have conceded per over bowled)
<br>12. **SR**: Bowling strike rate of the player (the average number of balls bowled per wicket taken)
<br> 13: **5**: No of innings the player took 5 wicktes
<br>14: **10**: No of matches the player took 10 wicktes

Analyses performed so far:
1. Importing the data (csv format to python dataframe using pandas)
2. Displaying the first 10 rows of the dataframe
3. Creating a markdown cell and explaining the meaning of each column
4. Finding the number of rows and columns in the dataframe
5. Finding the data statistics and check for the data types
6. Commenting whether there is any missing values
7. Appropriately renaming the column names 
8. Removing a least important column from the dataframe
9. Removing the columns BBI and BBM.
10. Finding the number of players who played for ICC
11. Finding the number of different countries present in this dataset 
12. Finding the number of player(s) who had played for the longest period of time
13. Finding out which player(s) had played for the shortest period of time
14. Finding the number of Australian Bowlers are present in this dataset
15. Finding out whether there is any Bangladeshi player present in this dataset
16. Finding out which player has the lowest economy rate
17. Finding out which player has the lowest strike rate
18. Finding out which player has the lowest bowling average


Update date: 4th September 2021

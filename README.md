# Most Influential Attributes of Top Teams

The goal of this analysis will be to see if there are common attributes amoung the top performing leagues in the European Soccer League and most the most defining attritbutes are. Data is from a Kaggle post,[European Soccer Database](https://www.kaggle.com/hugomathien/soccer) by Hugomathien.

The process of discovery will be the following:
1. Create SQL queries to import data into Pandas
2. Find out which teams the players belong too (most recent year)
3. Join the player attributes to those teams (most recent performance scores)
4. Create team attributes based on the mean of players' attributes
5. Discover the top teams (most recent year)
6. Compare the mean attributes of all teams compared to the mean attributes of top teams
7. Make a judgement if there are common attributes that matter most to success

### Final Conclusion: Possession is Everything!

Our original quest was to find the top attributes of winning teams in the European Soccer Leauge. To do this we cleaned the data and then compared the averages attributes of all teams with the attributes of the top 5 teams in the league.

Before diving into the data, I had thoughts that maybe the speed attributes would be one of the biggest contributing factors. I was pretty far from the truth. It became clear that **top teams had players that excelled at winning ball possession**. Those top attributes being sliding tackles, volleys, and interceptions.

This information would be extremely relevant for talent scouts, recruiters, or investors looking to buy/bid on a team.

An interesting fact that was that, according to Fifa player stats, the goalies on winning teams were less than average in every category.

### Required Modules
* Pandas
* MatPlotLib
* Sqlite3
* Itertools
* Pprint

### Helpful Resouces
* [DB Browswer for SQLite](https://sqlitebrowser.org/)
* [Working with SQL and Python](https://www.dataquest.io/blog/python-pandas-databases/)
* [Force Removing "Non-Empty" Directories in Terminal](https://www.cyberciti.biz/faq/how-to-delete-a-non-empty-directory-in-linux-shell/)
* [Building Dictionaries with Lists](https://thispointer.com/python-6-different-ways-to-create-dictionaries/)
* [Returning Keys of Nested Dictionary](https://stackoverflow.com/questions/39233973/get-all-keys-of-a-nested-dictionary)
* [Branch Merging with Jupyter](https://nbdime.readthedocs.io/en/latest/vcs.html)

# pandas-challenge

Heroes Of Pymoli is a fictional game. This study analyzes its users and in-game purchasing data to understand its customers' characteristics and habits, in order to improve customer experience and satisfaction.

The analysis was performed by using the Pandas module in Python. 

The three main observations from these data are:

## Gender Preference

    This game is more popular among the male players. The data shows that, among the total 576 players, the percentage of male players is five times higher than the percentage of female players (84% vs. 14% respectively).

## Age Preference

    This game is more attractive to teens and young adults. Players between age 15 to 29 composed of almost 77% of all the players. Particularly, age group 20 to 24 accounts for about 45% of the total players. 

## Purchasing/Spending Trend

    While there are remarkably more male players than the female players, the average purchase of the female player is slightly higher than the male players ($4.47 vs $4.07 respectively). 4 of the 5 top spenders are males.

    Not surprisingly, the top total purchasing group is the age group from 20 to 24. 4 of the 5 top spenders are also from this age group.

Interestingly, among the different age groups, the highest average total purchase per person falls to age groups under 10 and between 35-39. This finding implies that young children (most likely purchased by adults) and/or adults with disposable income are willing to spend more on games.


Pandas functions used on DataFrames (df) for analysis

# computational/statistical
df.nunique
df.count
df.mean
df.sum
# data selection
df.head
df.drop_duplicates
df.loc
# reindexing
df.set_index
# output dispaly
pd.DataFrame
df.map(.format)
# functional applications
df.groupby
pd.cut(bins)
df.sort_values

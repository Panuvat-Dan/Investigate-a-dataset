# Project introduction

This data set contains more than 25,000 soccer matches from 2008 until 2016 (totaly 8 seasons) and the player is more than 10,000 persons throught 11 countires. Moreover, the
data also provide detial like cross amount, goal type, corner amount, attributes of player and team and etc. which we can do the analysis on thoese detail and visualize during
EDA phase but before that we need to gather the data from SQLite and clean up the data through this analysis, I am not going to use all of table on dataset but require some SQL
join tables.

# Investigate a Dataset (Soccer Database) [clink here to link](https://www.kaggle.com/hugomathien/soccer)

In this project, I've investigated a dataset and communicated my findings about it. I used the Python libraries 

Library in used Date gathering : SQLite3 Data cleaning : NumPy, Pandas Data Visualization : Matplotlib and Seaborn to do the analysis

Process : Data gather >> Data accessing >> Data cleaning >> EDA >> Data visualization >> Draw a conclusion

# Statment of question 

- Top 10 best player on the European professional football league ?
- Does the height of professional football players affected the thier capability of playing during thier career ?

# Datasets overviews

This data set contains several table on SQL file, including 
Table	Total Rows	   Columns
Country	     11	        2
League	     11	        3
Match	       25979	    115
Player	     11060	    7 
Player_Attributes	183978	42
Team	299	5
Team_Attributes	1458	25
However, in the analysis I have selected only 2 table to join each other which are player and player attributions tables.

# Files

- [clink here to link](https://www.kaggle.com/hugomathien/soccer)

# Findings

![alt text](https://github.com/Panuvat-Dan/Investigate-a-dataset/blob/main/chart1.JPG)

Q1. The best professional player from top ten during 2008-2016 is Lionel Messi who got overall_rating around 92 points.

![alt text](https://github.com/Panuvat-Dan/Investigate-a-dataset/blob/main/chart2.JPG)

Q2.We shall see that the more year goes,the more player rating. It is because the rising players who is less than 20 year have less experience than other groups. Moreover, you
shall see that in the first group (less than 20 y) and inthe second group (20 to 30 y) shows that the players who have height less than 170 cm. get higher score than player who
have height more than 170 cm.However, in the last group which is more than 30 y, player who have height less than 170 cm. get slightly less socre than others. Therefore, the as
fact shown,the height is not that important becuase the overall rating calculated not only the defensive but also dribbing,crossing,etc and it might be important if we calculate only the defensive score.

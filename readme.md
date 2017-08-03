#Assignment 5 - Visualizations and Multiple Views
===
[Project page](https://carriema.github.io)


#Teams: 
---

Shijie Jiang git:jiangshijie
Yanran Ma  git: carriema

#Our work
---
We visualized NBA data for 2015 - 2016 season. We crawl the data from http://stats.nba.com/ using Python.
There are three views in the visualization. The first one is a map with pinpoint at the location of the team. The red color 
represent the western team and the blue represent the eastern team. The size of the dot shows the total score of each team in a period of time.
The second one is a randar chart, which shows the "REB", "PTS", etc.(你写下你那个是干啥的) information of a specified team. The third one is a bar chart.
the x axis is the game time of a team and the y axis is the score in each game. When user select the dot on the map, the team will changes for 
the bar chart and randar chart. When user select the score category on randar chart, the type of score will change for the other two views. When user select a 
period of time through bar chart, the data of scores will also change for the other two views.

#Technical achievements
---
The size of the dots on the map is changed by transmission when data changed.

The D3 brush is used to selected a period of time.

Use Javascript map, reduce function and d3.nest() to manipulate and aggregate the data as we want.


#Design achievements
---

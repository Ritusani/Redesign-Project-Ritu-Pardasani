Project outline 

I read an article in the wall street journal titled as – “Wind Power Wins Converts in Rural U.S., Economic impact of wind farms is changing the political dynamics of renewable energy”. This article’s claim was supported by a visualization on Wind energy installations in the year 2016 mapped with the voting in various states. My project consists of redesigning that visualization.
I have redesigned and made a visualization which actually clears the motive of the original visualization and refutes the claim of the same. I have shown the same visualization in a simpler way and removed the deceiving aspects of it. The original visualization presents data on Wind capacity generated in different states in November 2016 and is linked with the elections data (as elections also happened in November 2016) to show that states with higher wind energy capacity voted for Mr. Donald Trump. 
Project motivation 
I personally feel that using renewable sources than non-renewable sources is a better idea considering the fact that we’ll run out of the non-renewable sources soon. 
When I saw this chart, it struck me that the total wind capacity generated across all the states is actually way less than the country’s potential and this capacity was also being correlated with the ruling government. When I saw this chart, there was something odd about it. Since, millions of people read such journals, I decided to research more on this topic and hence picked this particular chart for my redesign project.
  
Visualization to be redesigned –
screenshot


Following are some key observations one can entail upon looking at the original visualization –

1.	This graph claims that nearly 90% of the wind capacity bought online in 2016 was in states that voted for Donald Trump. 
2.	The graph is showing 4 measures – 
•	Some States (Depicted by the circles on the graph and only states with at least 1MW capacity are shown)
•	percentage of vote won by Donald Trump (y axis, shown by red colored bubbles)
•	percentage of vote won by Hilary Clinton (x axis, shown by blue colored bubbles)
•	Wind capacity in Megawatts (MW) generated in each state (show by the sizes of the circles depicting states)
3.	This graph shows that Texas has the maximum wind capacity but it also shows that it is very close to the blue bubbles which could mean that the margin of votes in Texas was very low. 
4.	The sizes of the circles rank the wind capacity as follows – 
-	Texas 
-	Iowa 
-	Oklahoma 
-	California 
-	Kansas / Illinois
5.	As this chart was trying to prove something and is failing to do so, as a lot of aspects of this chart ranging from the axes to the actual values are deceiving. Hence I decided to do an analysis on this to verify the correctness of the claim. 

Problems with this chart –
1.	Percentage is used to show the margin of votes by which these 2 parties have won the elections which is confusing because total number of votes is different for each state. Therefore, percentage margins is an ineffective way of comparison.
2.	Both the axes are used to show percentage of vote which doesn’t give clarity as to what is being represented and how. 
3.	Taking the percentage of vote for Trump and Clinton in two different axes was unnecessary and not as effective as the same thing could be shown with only wind capacity and percentage of both the parties combined, as color is also showing the difference between the parties. 
4.	The size of the bubbles is representing wind capacity, which is not a right way to show because it is difficult to differentiate between states with minor difference in wind capacity. 
5.	The states are linearly aligned on purpose so that the red bubbles and blue bubbles are grouped on either sides to make the argument clear, which is also a deceiving technique.
6.	Some bubbles of important states, which are highly impactful in the analysis are being overlapped partially or fully, making it even more difficult to judge the size of the state and its wind capacity. 
7.	Overall, this visualization is deceptive and does not show the underlying data accurately.

Improved Visualization –
 screenshot

How did I improve and redesigned the original visualization –
 I believe a scatter plot could make more sense of the data and show the real picture. Hence, I made a scatter plot with winning vote margin and wind capacity generated in each state.
 I took the margin of voting in numbers and not in percentage as total number of votes is different for each state. Therefore, percentage margins can be a wrong way of comparison. 
 The margin of voting for both the candidates (Trump and Clinton) is shown only on one axis instead of two. 
 I included all the states, even those who don’t have wind energy generated at all, to purposely show that most states have very less or no wind energy generated irrespective to the winning candidate of that state. 
 The winning party is represented by color: Red for states won by Trump and Blue for states won by Clinton. 
 The distance of these plots from the x axis clearly shows the margin. More the distance – more winning margin and vice versa. For instance, if we consider Iowa which is ranked 2nd highest in terms of wind capacity and was won by Trump. However, it was not a dominated win as its very close to x axis (which depicts approximately 50-50 votes).
 This visualization clearly depicts the wind capacity for each state through the x axis and also shows the winning candidate of that state through the distinct colors.
Original Claim- 
Nearly 90% of the wind energy brought online in 2016 was in states that voted for Donald Trump. 

Claim of the improved version of visualization – 
Wind capacity bought online in 2016 is not related with the elections which implies no impact caused on voting patterns. 


Analysis involved in debunking the original claim –

Let’s take the ranking of top ten states with the maximum wind energy capacity 

RANK
STATE
WIND CAPACITY GENERATED ( in Megawatts (MW))
WINNER 
WINNING MARGIN wrt to total vote ( in %)
1
Texas
18531
TRUMP
8.98 %
2
Iowa
6365
TRUMP
9.41
3
California
5662
CLINTON
29.99
4
Oklahoma
5453
TRUMP
36.39 
5
Illinois
3842
CLINTON
16.89
6
Kansas
3836
TRUMP
20.42
7
Minnesota
3435
CLINTON
1.51 
8
Oregon
3163
CLINTON
10.98
9
Washington
3075
CLINTON
15.71
10
Colorado
2965
CLINTON
4.91
Note – Total number of votes for these states are different. 

Looking closely at the numbers of the wind capacity generated by the end of 2016 and the winning margin, I can come up with following points that should be considered – 

1.	Firstly, Texas is an outlier. Its wind energy capacity is way more than all the other states. Its capacity is almost 3 times the capacity of state ranked 2nd.  Which directly implies, that clearly Texas was the major contributor of Wind energy capacity in 2016. It is a state won by trump. However, the winning margin and my visualization both show that it can’t be categorized as a “heavily republican state”. Hence, the reason behind the big number of wind capacity might not be the politics but something else like favorable location. Secondly, with only one state having enormous wind capacity and being won by Trump it can’t be assumed that voting has any relation to it whatsoever.
2.	The original visualization depicts the ranking pattern in a way that Oklahoma seems to have more capacity than California by the size difference of the bubbles. This is factually incorrect as according to the actual data, California has more wind capacity and in fact is a heavily democratic state.
3.	Out of the top 10 ten states, 6 states were won by Clinton which is clearly weakening the claim of the original visualization and is depicting the fact that there is no connection between wind capacity generated and voting. 


Intermediate versions and Failed visualizations- 



Discussion with professor –

•	Choice of chart was different and something that is actually expected from a redesign project.
•	Researching more on the topic and reading the article thoroughly was recommended.
•	Usage of map was good but was not that promising to support my claim. 
•	Scatter plot with only two measures was sufficient and an effective way to support the argument. 
•	Could use analytics tools such as trend lines (exponential or straight both)
•	Margin of votes of both the parties could be combined.
•	Usage of two different elements like shading and size for the same measure is not advisable. 
•	Try avoiding outliers and see whether a trend can be seen or not.
•	Try tweaking the axis like changing intervals or starting & ending values or using logarithmic scale – to see if it changes anything. 

Data sources – 

References – 


Reference-style: 
![alt text][logo]



[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"








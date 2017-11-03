
## Project outline 

I read an article in the **Wall Street Journal** titled as – **_“Wind Power Wins Converts in Rural U.S., Economic impact of wind farms is changing the political dynamics of renewable energy”_**. This article’s claim was supported by a visualization on Wind energy installations in the year 2016 mapped with the voting in various states. I chose to redesign that visualization for my project.

I have redesigned and made a visualization which actually clears the motive of the original visualization and refutes the claim of the same. I have shown the same visualization in a simpler way and removed the deceiving aspects of it. The original visualization presents data on Wind capacity generated in different states in November 2016 and is linked with the elections data (as elections also happened in November 2016) to show that states with higher wind energy capacity voted for Mr. Donald Trump. 

## Project motivation

I personally feel that using renewable sources than non-renewable sources is a better idea considering the fact that we’ll run out of the non-renewable sources soon. 

When I saw this chart, it struck me that the total wind capacity generated across all the states is actually way less than the country’s potential and this capacity was also being correlated with the ruling government. When I saw this chart, there was something odd about it. Since, millions of people read such journals, I decided to research more on this topic and hence picked this particular chart for my redesign project.
  
## Visualization to be redesigned

<img width="550" alt="redesign_chart" src="https://user-images.githubusercontent.com/32205588/32391666-1f299d4e-c090-11e7-8ec1-53b0208c109c.png">


### Following are some key observations one can entail upon looking at the original visualization:

1.	This graph claims that nearly 90% of the wind capacity bought online in 2016 was in states that voted for Donald Trump. 

2.	The graph is showing 4 measures:

    •	Some States (Depicted by the circles on the graph and only states with at least 1MW capacity are shown)
    
    •	Percentage of vote won by Donald Trump (y axis, shown by red colored bubbles)
    
    •	Percentage of vote won by Hilary Clinton (x axis, shown by blue colored bubbles)
    
    •	Wind capacity in Megawatts (MW) generated in each state (show by the sizes of the circles depicting states)
    
3.	This graph shows that Texas has the maximum wind capacity but it also shows that it is very close to the blue bubbles which could mean that the margin of votes in Texas was very low. 

4.	The sizes of the circles rank the wind capacity as follows:

    •	Texas
    
    •	Iowa 
    
    •	Oklahoma
    
    •	California
    
    •	Kansas / Illinois

5.	As this chart was trying to prove something and is failing to do so, as a lot of aspects of this chart ranging from the axes to the actual values are deceiving. Hence I decided to do an analysis on this to verify the correctness of the claim. 

### Problems with this chart:

1.	Percentage is used to show the margin of votes by which these 2 parties have won the elections which is confusing because total number of votes is different for each state. Therefore, percentage margins is an ineffective way of comparison.

2.	Both the axes are used to show percentage of vote which doesn’t give clarity as to what is being represented and how. 

3.	Taking the percentage of vote for Trump and Clinton in two different axes was unnecessary and not as effective as the same thing could be shown with only wind capacity and percentage of both the parties combined, as color is also showing the difference between the parties. 

4.	The size of the bubbles is representing wind capacity, which is not a right way to show because it is difficult to differentiate between states with minor difference in wind capacity. 

5.	The states are linearly aligned on purpose so that the red bubbles and blue bubbles are grouped on either sides to make the argument clear, which is also a deceiving technique.

6.	Some bubbles of important states, which are highly impactful in the analysis are being overlapped partially or fully, making it even more difficult to judge the size of the state and its wind capacity.

7.	Overall, this visualization is deceptive and does not show the underlying data accurately.

## Improved Visualization
 
 <img width="1024" alt="final_chart" src="https://user-images.githubusercontent.com/32205588/32391777-8fa9cdfa-c090-11e7-81aa-79aa72cc968c.png">


### How did I improve and redesigned the original visualization:

 1.	 I believe a scatter plot could make more sense of the data and show the real picture. Hence, I made a scatter plot with winning vote margin and wind capacity generated in each state.
 
2.	I took the margin of voting in numbers and not in percentage as total number of votes is different for each state. Therefore, percentage margins can be a wrong way of comparison. 

3.	The margin of voting for both the candidates (Trump and Clinton) is shown only on one axis instead of two. 

4.	I included all the states, even those who don’t have wind energy generated at all, to purposely show that most states have very less or no wind energy generated irrespective to the winning candidate of that state. 

5.	The winning party is represented by color: Red for states won by Trump and Blue for states won by Clinton. 

6.	The distance of these plots from the x axis clearly shows the margin. More the distance – more winning margin and vice versa. For instance, if we consider Iowa which is ranked 2nd highest in terms of wind capacity and was won by Trump. However, it was not a dominated win as its very close to x axis (which depicts approximately 50-50 votes).

7.	This visualization clearly depicts the wind capacity for each state through the x axis and also shows the winning candidate of that state through the distinct colors.

## Original Claim 

**_Nearly 90% of the wind energy brought online in 2016 was in states that voted for Donald Trump._** 

## Claim of the improved version of visualization

**_Wind capacity bought online in 2016 is not related with the elections which implies no impact caused on voting patterns._** 

## Analysis involved in debunking the original claim 

Let’s take the ranking of top ten states with the maximum wind energy capacity 

<img width="752" alt="table" src="https://user-images.githubusercontent.com/32205588/32391806-acc8f9c4-c090-11e7-83ca-b5a28ae7a472.png">

Note – Total number of votes for these states are different. 

Looking closely at the numbers of the wind capacity generated by the end of 2016 and the winning margin, I can come up with following points that should be considered – 

1.	Firstly, **Texas is an outlier**. Its wind energy capacity is way more than all the other states. Its capacity is almost **3 times** the capacity of state ranked 2nd.  Which directly implies, that clearly Texas was the **major contributor** of Wind energy capacity in 2016. It is a state won by Trump. However, the winning margin and my visualization both show that it **can’t be categorized as a “heavily republican state”**. Hence, the reason behind the big number of wind capacity might not be the politics but something else like favorable location. Secondly, with only one state having enormous wind capacity and being won by Trump it can’t be assumed that voting has any relation to it whatsoever.

2.	The original visualization depicts the ranking pattern in a way that Oklahoma seems to have more capacity than California by the size difference of the bubbles. This is factually incorrect as according to the actual data, **California has more wind capacity and in fact is a heavily democratic state**.

3.	**Out of the Top 10 ten states** having maximum wind capacity, **6 states were won by Clinton** and **4 states by Trump** which is clearly **weakening** the claim of the original visualization and is depicting the fact that there is no connection between wind capacity generated and voting. 

## Discussion with professor

•	Choice of chart was different and something that is actually expected from a redesign project.

•	Researching more on the topic and reading the article thoroughly was recommended.

•	Usage of map was good but was not that promising to support my claim. 

•	Scatter plot with only two measures was sufficient and an effective way to support the argument. 

•	Could use analytics tools such as trend lines (exponential or straight both).

•	Margin of votes of both the parties could be combined.

•	Usage of two different elements like shading and size for the same measure is not advisable. 

•	Try avoiding outliers and see whether a trend can be seen or not.

•	Try tweaking the axis like changing intervals or starting & ending values or using logarithmic scale – to see if it changes anything. 

## Intermediate versions and Failed visualizations

### 1. Geographical plot: 

It shows the states separately which is a good thing but the voting margins can't be seen. Secondly the wind capacity is the most important measure in this analysis thus shading of the map or sizes of the bubbles won't solve the purpose. Overall, this visualization doesn't support the claim very strongly. 

<img width="912" alt="11" src="https://user-images.githubusercontent.com/32205588/32392157-aaf1c27e-c091-11e7-8c36-645b1a0f4c1c.png">

### 2. Scatter Plot: 

After discussion with the professor, scatter plot was selected. It was a better way to support the argument. So I decided to work on the scatter plot and in that process I came up with these intermediate versions. I improved these constantly and finally came up with my final visualization. 

##### When I first plotted my data, it looked something like this - 

<img width="634" alt="1" src="https://user-images.githubusercontent.com/32205588/32392393-bfbdef56-c092-11e7-999a-69a503ad5cc5.png">

I had taken the difference of the votes of the two candidates and I subtracted votes of Clinton from votes of trump. Hence this resulted in negative numbers for Clinton. This was a good way to differentiate between the two but not the best way. 

##### I renamed the axes to make it more understandable and labelled the states. I also tried the trend line to see whether I get a trend or not, but it didn't show anything - 

<img width="637" alt="2" src="https://user-images.githubusercontent.com/32205588/32392514-380bcd98-c093-11e7-8869-5b8f9a8c2095.png">

##### I removed the trend line and as Texas is an outlier, I tried to remove it and see whether other states are showing some kind of pattern in wind energy generated and voting or not. This also didn't help and couldn't show anything useful. It looked like this -

<img width="624" alt="3" src="https://user-images.githubusercontent.com/32205588/32392621-9a0127d2-c093-11e7-883a-f53699d7f178.png">

##### Then I tried changing the margin of vote axis from "absolute values" to "logarithmic values". I used the trend line again to see any patterns, but couldn't find anything. Looked like this -

<img width="638" alt="4" src="https://user-images.githubusercontent.com/32205588/32392726-f30b703a-c093-11e7-94a2-1bab3b6f0a80.png">

##### So I decided to switch back to absolute values axis and changed the colour of the states with respect to the winning candidates of those states. This made the visual much clearer and also showed that there is no relation between voting and wind capacity. Looed like this - 

<img width="891" alt="5" src="https://user-images.githubusercontent.com/32205588/32392801-485ba4ec-c094-11e7-8c97-4557de32a2be.png">

##### I tried testing bars instead os scatter plot, just to see whether it highlights the margin of votes or not. It did highlight the margin but looked really bad. Looked like this -

<img width="878" alt="6" src="https://user-images.githubusercontent.com/32205588/32392865-916e222c-c094-11e7-9106-e63de63360c0.png">

##### I was not happy with so many negative values on my margin of vote axis. Hence I decided to have positive values for both and rather show the margin through the distance from the x axis. More the distance - more the margin of votes. I decided to do this as I was already using color to diffrentiate between the two. I made a bar chart to show distance, which looked really bad. Hence I decided to go for scatter plot for my final version. The bar chart looked like this - 

<img width="717" alt="7" src="https://user-images.githubusercontent.com/32205588/32393084-6db3dd9e-c095-11e7-91e9-cb9a8b28a16f.png">


## Data sources

Elections Dataset: Extracted from https://uselectionatlas.org/RESULTS/data.php?year=2016&datatype=national&def=1&f=0&off=0&elect=0 using Web Scrapper Tool on October, 8 2017

Wind Energy Dataset: Extracted from https://public.tableau.com/profile/hhunt3307#!/vizhome/StateFactSheetPage_0/StateFactSheets using the tableau public on October, 8 2017


## References









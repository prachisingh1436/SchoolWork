# Technology Learning Studio<br /><br />
I am enrolled in Prof. Howison's Technology Learning Studio class for which I am going to do self-learning and portray my learning through projects. I am going to learn 3 technologies in the entire span of the semester and aim to achieve the below mentioned goals using the materials specified.<br /><br />

<h2><u>First Project : Tableau<br /></u></h2>
<h3>Goals</h3>Learning Tableau and implementing it on a data set to get some meaningful insights and analysis. I will be using dataset from WHO, UN and other reliable sources display the impact of lack of proper water and sanitation facilities.<br />
<h3>Materials</h3>I would be using tutorials and other training videos available on Tableau's websites and be a Forum's and user groups in case of issues and doubts. I am going to learn from the tutorials and courses on <a href="https://www.analyticsvidhya.com/learning-paths-data-science-business-analytics-business-intelligence-big-data/tableau-learning-path/">Analytics Vidhya</a> and Coursera.<br /><br />
<h2><u>Second Project : SQL<br /></u></h2> <h3>Goals</h3>Basic: Learning to implement Having and Group by.<br />Stretched: Learning the applications of different Joins.<br /> Ambitious: Working with Advanced SQL.
<h3>Materials</h3>
I am auditing Prof. Howison's Data Wrangling classes on Tueasdays and Thursdays at 10:30 to indulge myself in a peer learning for this project. I am going to use and refer to <a href="https://community.modeanalytics.com/sql/tutorial/introduction-to-sql/">Mode SQL Tutorial</a> and <a href="https://www.w3schools.com/sql/">W3 Schools</a> while I am working on my project for help. <br /><br />
<h2><u>Third Project : 3-D Printing<br /></u></h2> <h3>Goals</h3>Learn 3-D printing and modelling. I will make a mechanical clock or a 3-d puzzle using 3-d printing techniques.
<h3>Materials</h3>I am going to be using <a href="https://www.shapeways.com/tutorials">Shapeways</a> and 
<a href="http://3dprintingforbeginners.com">3d Printing for Beginners</a> to learn from 3d software tutorials. I will be auditing Prof Riley's class on Wednesdays at 12 PM to learn better about 3d printing and modelling.<br /><br />

<h2><u>Tableau - Week 1<br /></u></h2>

I got a chance to visit a Tableau day event, where talking to people helped me understand the basic differences between the 3 types of Tableau versions available; Desktop, Online and Server. Since it was an event organized to discuss the most recent features that are available and very useful, I got a chance to know about some amazing options to play with data, make dashboards, and update the people effected.<br /><br />

I took an example data set with 5 datapoints and implemented all sorts of charts and graphs to see the different visualizations, realizing what is used best when. Once I was done exploring the data I pulled from the excel sheet, I learnt how to connect Tableau with different data sources like databases and sharepoint.<br /><br />

<h2><u>Tableau - Week 2<br /></u></h2>

I expanded my dataset to the ideal scenario of comparing current growth to the expected growth. When I was trying to implement that, my biggest chalenge was to make it most readible and comprehended. The easiest options were not the best one as they plotting it above one another or next to each other as the below screenshot. 
<img src="https://user-images.githubusercontent.com/31910791/30676934-70ac643a-9e4e-11e7-9304-68800d57c975.png"><br /><br />
After seeing a lot of blogs and videos, I learnt the feature of Dual axis and the synchronization of the axes, it was easier to see the comparision. <br /><br /> 
<img src="https://user-images.githubusercontent.com/31910791/30676940-76883870-9e4e-11e7-83d7-757f39cdcdc6.png"><br /><br /> On Sychronization<br /><br /> 
<img src="https://user-images.githubusercontent.com/31910791/30676944-788d156e-9e4e-11e7-923b-b140682bae3e.png"><br /><br /> 
Though I still felt that having the dual axis (though synchronized) is not a very good interpretation. Then I discovered a trick to get rid of the 2 axes and combine it in one depicting it by 2 different colors. 
<img src="https://user-images.githubusercontent.com/31910791/30676947-7a439a18-9e4e-11e7-9872-202d53088224.png"><br /><br /> 
<h2><u>Tableau - Week 3<br /></u></h2>
Since I had an idea about how to use the tool, I wanted to learn how to make the most of it. So I went through this amazing document which talked about which charts to use while showcasing different types of data for best interpretation. It was a good source which was very informative and induced great ideas while reading. The link to the document is https://www.tableau.com/sites/default/files/media/which_chart_v6_final_0.pdf. Hope you guys find it as useful as I did.
<br /><br /> 
The other learning source that I used to understand the data available better and better get results was a video tutorial on Coursera on Data Visualization using Tableau. It talked about understanding how to look at the data from the point of answering questions. It first requires you to ask the right set of questions to get the best and expected results.<br /><br /> 

When I started working with the datasets I had considered working with, I realized that the dataset was not complete and not very recent data. I decided to change my project and started looking at data related to Climate change. I got my data from Data.world which had data from reliable Organizations. I am going to analyze if there is an increase in the number of Hurricanes with the increase in the average land temperature. <br /><br /> 
<h2><u>Tableau - Week 4<br /></u></h2>
Finding the right and complete dataset is the first and foremost step but definitely the easiest. Despite being complete, cleaning and manipulation of data are very important before we start visualizing it. Equally important is standardization of data especially if we are dealing with multiple datasets.
<br> <br>
I picked my data from 2 different sources, first was a time series data of average minimum temperature, average maximum temperature, and average temperature. The other dataset had information about several hurricanes trackings. The various attributes about the hurricanes that were recorded were its movement latitude longitude wise with date and time, its wind speed, pressure, length of shape, etc. I used R to do the data cleaning and manipulation of data as per my use.
<br> <br>
I used 2 new packages to play around with my data both of which were very interesting to use. Tidyverse, one of the packages had functions which are available in other packages but the implementation is friendlier and easy to use and adapt. The best feature of Tidyverse is that it allows you to perform a series of multiple functions in a sequence without having to save in multiple or separate variables. You can more about it from the book R for Data Science written by Hadley Wickham and Garrett Grolemund. The other package that I used was Tibbletime which helps to modify and apply time-based functions on time series data. Some of the features are to convert data into different periods or filter out data from a particular time period.
<br><br>
Using the above specified packages, I removed data with missing values and filtered out data from the last 20 years. The biggest challenge was converting all date values to standard data, as they were in different format before 1950, which could then be utilized in Tableau. One major issue that I faced while performing these modifications was that Tibbletime functions were not getting applied on my data. Even after searching a lot online for solutions and blogs discussing similar error messages, I couldn't find the solution. Sometimes the easiest solution is to quit and and start all the steps all over again. I guess the problem was that I had not shut the app for quite a long time and had over-burdened it with huge datasets.<br><br>
Since the granularity of data in the hurricane dataset was a lot more as it was tracking the movements of the hurricane with change in location. I had to group together and apply mean on the tha values and grouping by the name of the Hurricane. On getting the final dataset, I could observe some irregularities. Some of the values of year were in decimals which was absurd as there are very rare chances for most of them occuring for months or end of the year. After filtering the raw data in the excel sheets by names, I discovered that the same name were used to name different hurricanes sfter a time span of 15-20 years. So I made name year pairs then applied the mean and then again seggregated them back into the two original columns.
<br><br>
Since the granularity of data in the hurricane dataset was a lot more as it was tracking the movements of the hurricane with the change in location. I had to group together and apply mean on the values and grouping by the name of the Hurricane. On getting the final dataset, I could observe some irregularities. Some of the values of the year were in decimals which were absurd as there are very rare chances for most of them to move for months or arise at the end of the year. After filtering the raw data in the excel sheets by names, I discovered that several names were repeated to name different hurricanes after a time span of 15-20 years. So I made name year pairs then applied the mean and then again segregated them back into the two original columns. <br><br>
Some of the visualizations built out of the processed data are below.<Br><br>
<img src="https://user-images.githubusercontent.com/31910791/31114573-606286a0-a7e4-11e7-90a5-5676cc01edce.png"><br /><br />
  <img src="https://user-images.githubusercontent.com/31910791/31114571-5ed5ec64-a7e4-11e7-9ceb-3dd12608f586.png"><br /><br />
  <img src="https://user-images.githubusercontent.com/31910791/31114578-633ac658-a7e4-11e7-880c-be44de3295b8.png"><br /><br />
<h2><u>Final result<br /></u></h2>

With the data I had, I couldn't show that the number of hurricanes has increased with the increase in the increase in average temperature. Maybe the problem statement was wrong as it was based on an assumption that there is a direct impact of the former on the later. The below results show the relation between the average land temperature and the number of Hurricanes that occur in the year.<br><br>

I blended the data from the 2 different datsets associating each other with the year value. The plotted charts are displayed below. <br><br>

<img src="https://user-images.githubusercontent.com/31910791/31151805-e1b24630-a85e-11e7-91cb-707aa20be8c3.png">

<center>Number of Hurricanes that occured vs Average Land Temperature in that year.</center><br><br>

<img src="https://user-images.githubusercontent.com/31910791/31151801-dcaefe80-a85e-11e7-8f37-a12385fcf23c.png">

<center>Average Wind Speed of the hurricanes vs Average Land Temperature in that year.</center><br><br>

Analysis:It mostly looks like the chances of occurances of hurricanes is inversely to increase in average temperautre. Though a direct impact is not visible, maybe there are more than one factors that impact on the occurances which are accountable for the deviations and irregularities.<br><br>

As soon as I get the chance I would like to explore the map charts of Tableau. It is an amazing feature to display regional data.
<br><br>
<h2><u>Learning from the learning blogs<br /></u></h2>
Peer review was an amazing experience for me. It helped me analyze other's blogs and realize how mine was different than theirs. Now I feel I will be able to write a little better blog. I didn't have any experience of writing blogs, so I was scared of writing one in the first place and use to procrastinate. And getting a review back critiquing about my entries not being personal, took me one step back. But I have decided to take it positively and learn, from the blogs that I have read so far, to write better. So my final learning outcome of this course is to be a better blogger! And I will require everybody's help in doing so because of all the comments matter, good or bad!<br><br>

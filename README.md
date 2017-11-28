# Technology Learning Studio<br /><br />
I am enrolled in Prof. Howison's Technology Learning Studio class for which I am going to do self-learning and portray my learning through projects. I am going to learn 3 technologies in the entire span of the semester and aim to achieve the below mentioned goals using the materials specified.<br /><br />

<h2><u>First Project : Tableau<br /></u></h2>
<h3>Goals</h3>Learning Tableau and implementing it on a data set to get some meaningful insights and analysis. I will be using dataset from WHO, UN and other reliable sources display the impact of lack of proper water and sanitation facilities.<br />
<h3>Materials</h3>I would be using tutorials and other training videos available on Tableau's websites and be a Forum's and user groups in case of issues and doubts. I am going to learn from the tutorials and courses on <a href="https://www.analyticsvidhya.com/learning-paths-data-science-business-analytics-business-intelligence-big-data/tableau-learning-path/">Analytics Vidhya</a> and Coursera.<br /><br />
<h2><u>Second Project : <a href=https://github.com/prachisingh1436/SchoolWork/blob/master/README.md#learning-from-the-learning-blogs>SQL</a><br /></u></h2> <h3>Goals</h3>Basic: Learning to implement Having and Group by.<br />Stretched: Learning the applications of different Joins.<br /> Ambitious: Working with Advanced SQL.
<h3>Materials</h3>
I am auditing Prof. Howison's Data Wrangling classes on Tueasdays and Thursdays at 10:30 to indulge myself in a peer learning for this project. I am going to use and refer to <a href="https://community.modeanalytics.com/sql/tutorial/introduction-to-sql/">Mode SQL Tutorial</a> and <a href="https://www.w3schools.com/sql/">W3 Schools</a> while I am working on my project for help. <br /><br />
<h2><u>Third Project : <a href ="https://github.com/prachisingh1436/SchoolWork/blob/master/README.md#beginning-of-3-d-modelling">3-D Printing</a><br /></u></h2> <h3>Goals</h3>Learn 3-D printing and modelling. I will make a mechanical clock or a 3-d puzzle using 3-d printing techniques.
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
Peer review was an amazing experience for me. It helped me analyze other's blogs and realize how mine was different than theirs. Now I feel I will be able to write a little better blog. I didn't have any experience of writing blogs, so I was scared of writing one in the first place and use to procrastinate. And getting a review back critiquing about my entries not being personal, took me one step back. But I have decided to take it positively and learn, from the blogs that I have read so far, to write better. So my final learning outcome of this course is to be a better blogger! And I will require everybody's help in doing so because all the comments matter, good or bad!<br><br>
<h2><u>For a start..<br /></u></h2>
I began trying to decide on my goals, basic and stretched, for this module. As usual, I was clueless about what I wanted to do. So I decided to do my best with my fixed mindset of trying to do my best by making a guess of what could I achieve by the end of this module. I am a top to bottom person, I prefer someone to give me a target and I always figure out how to achieve that by the deadline. Prof Howison's suggestions in helping me structure this learning session gave me the basic outline that I required.<br><br>
<h2><u>Getting the hang of SQL<br /></u></h2>
With a few discussions and readings on SQL, I realized what are the different components that are integral parts of the setup of this learning. The 3 main parts are a database, a terminal(to write queries) that is associated with the database, and an interface to see the results of the query. The tutorial that I am about to use, <a href="https://community.modeanalytics.com/sql/tutorial/introduction-to-sql/">Mode SQL Tutorial</a>, provides an editor to write the queries and has some sample datasets to play around. The results of the queries are also visible in the application to verify your results.<br><br>
I always perfer video tutorials, since they engage a lot of more senses and increases my chances of retaining things. This tutorial is great though it doesn't have a video, it is very interactive. It tells you basic about any command, and then demonstrates how to use it with a couple of examples and then there are problems that we need to try ourselves to get a better understanding. It helped me understand the usage of these commands better. <br><br>
Below is a screenshot of the setup:<br>
<img src="https://user-images.githubusercontent.com/31910791/31743124-92f8d0f0-b41f-11e7-9b79-c1050d68c3b8.png">
The left window is the tutorial that explains the commands and syntax and has examples and problems that can be tried on the right window which has the editor. Once you try a problem, you can compare your query and results with provided solutions.<br><br> 
They have distributed the entire course work into 3 parts: basic, intermediate and advanced. To get hands on experience and a good understanding of the basic and the intermediate modules is my basic goal. Because of my love for coding and the amazing setup of the module, I was so engrossed in learning that I couldn't stop before completing the first module. Things are going to start getting tougher now for sure, but I am looking forward to it. <br><br>
<h2><u>When things get tougher<br /></u></h2>
After having a better understanding of the different learning styles, it holds more importance in my life now than it has ever. I can easily reflect on some of those 'not so great courses' that I had and why were they so. Thinking of it now, I even feel that I love science museums for the same reason, as I am a mix of Kinesthetic and visual learner. I tend to get lost in words and always need something for my find to stay engaged. This tutorial keeps me engaged by popping those problems, that I need to attempt to test my learning and understanding so far. Though I feel it is too soon to test. Solving questions at the end of every sub-module ensures I followed the portion and I understand the concept but I still don't know if I would retain it so much. I realised this later while attepting to use one of the basic SQL queries in an Intermediate level problem. Though using a previously learnt concept every now and then is helping me retain them.<br><br>
I have progressed in the intermediate module but with the realization that the concept has become more complex and there are more rules about the order as per syntax. I feel I need more practice of these commands than the problems available in the tutorial to get a better grip and gain more confidence.<br><br>
I am done with aggregate function and Case function and looking forward to work with the JOINS. <br><br>
<h2><u>Group Study<br /></u></h2>
For my SQL unit, I was supposed to audit Prof. Howison's class which I did partially. I referred to his teaching material and his class noted taken by other students. The best part was getting along with the students of his class and doing group study for this module. It was a different experience as I could notice different patterns of the learning and what they could understand easily and what took them a while to understand. Something that we all agreed to was trying out queries on our own helped us get a better understanding and thought process.<br><br>
The course material presented by Prof. Howison was in a completely different order than how it was presented in SQL Mode. I could notice why Prof. Howison had changed from the usual pattern to what he decided to teach his students. It is a reflection of a learning style where the instructor is aware of his own learning style rather reflects from his experience of learning this topic and builds the modules on that basis.<br><br>
<h2><u>Learning from 2 different aspects of this course<br /></u></h2>
After attaining my basic goal and close to completing my stretched goal, I was excited to go ahead and complete this one too as I am a goal-oriented person. But I decided to go back and start referring to Prof. Howison's material and reach the same point and then go ahead from here. At first, I was totally surprised at the way the material was arranged. According to the way the iSchool material was set up, my stretched goal was completed before we even started discussing my basic goal.<br><br>
Some of the basic differences that I could notice was between the syntax. Initially, I assumed it was because I was working with SQL and the class was based on MySQL, but I later realized that the syntax used in the class notes worked ModeSQL's editor as well. Some of the differences I noticed was double quotes being used instead of single quotes for strings and columns being referred by tableName.columnName rather than just the column name in all queries even where JOINs were not involved.<br><br>
One of the biggest issues that I noticed with MODE after going through the class material was it was missing some of the basic commands of CRUD (Create, Read, Update and Delete). MODE concentrated only on Read, the reason for it may be that the databases were already created and they did not want the users of the tutorial to update the tables with junk data or insert any new data or delete any tables.<br><br>
I found some great stuff in Prof. Howison's class material which helped in better understanding some of the basics which were a small part but very essential for right implementation. The boolean operators are used in different places while writing queries and understanding its combinations and the different impacts of exchanging or changing the order of these operators are very important. The understanding of truth values and how they are evaluated is equally important. I loved his style of showing intermediate steps.<br><br>
Prof. Howison's Class Material: Shows intermediate steps<br><br>
<img src="https://user-images.githubusercontent.com/31910791/32251233-261bd682-be5e-11e7-9595-97fd9f65ee09.png">
<br><br>
MODE' tutorial: Directly shows an example of the query <br><br>
<img src="https://user-images.githubusercontent.com/31910791/32251240-2a2ff546-be5e-11e7-84a4-7403248d1df6.png">
<br><br>
The showing of steps helps in building the thinking process and makes it easier to understand. He used to build the concept of JOIN using the other basic commands with which we were already comfortable. Understanding Group By was made way easier by his explanation of understanding the results of Order by and then transforming it to Group By.  <br><br>
<img src="https://user-images.githubusercontent.com/31910791/32251771-7cb3f41e-be60-11e7-831c-7b75060d4e82.png">
<br><br>

<h2><u>Perks of using the two sources<br /></u></h2>
There was distinctly a different style in both the sources. Mode was trying to approach a bottom to top approach trying to build all the basic concepts before. With all the example in place, it helped get a grasp on the usage of those concepts one after the other and trying examples and seeing results and then trying the problems and comparing answers.<br><br>

The class material focussed on understanding the concepts of the tables first. It concentrated on getting the value of data integration between multiple tables rather than just running the queries to see how they perform. Applying the basic commands on the joined tables built a sense answering the questions asked using the relationships between different tables in a database. It brought about a sense of backward thinking linking the data.
<br><br>

One of the things I and Prof. Howison discussed learning about JOINs was using the visuals of Venn Diagram. It was very well depicted in the tutorial from MODE. <br><br>
<img src="https://user-images.githubusercontent.com/31910791/32256484-4cb519a6-be7d-11e7-88a0-66a05287d3ee.png">
<br><br>
It also showed how the Left Join and the Right Join were similar and can replace each other. So using two different sources got the best of both to me.<br><br>
<img src="https://user-images.githubusercontent.com/31910791/32256487-50784fb8-be7d-11e7-9679-8e48bdb96789.png">
<br><br>

<h2><u>Wrapping Up<br /></u></h2>

I was successfully able to complete my Stretched goal and by now have a good understanding about most of the concepts related to SQL. Though I am still interested in knowing the other thngs that were there in Advanced section of MODE especially because it was associated with analytics. So maybe over the winter break, I will go back and finish that last section of SQL in MODE.
And I am excited for my next project for 3-d printing which I would begin with this week's class.<br><br>

<h2><u>Beginning of 3-D Modelling<br /></u></h2>
I did not ever think that it would be this tough for me to work with Blender as I have previous experience of working with the Adobe Illustrator. But it was way tougher. I began with the basic installation of the blender software and decided to use Youtube videos in making basic models for beginners. As soon as the video began I realized I didn't have an essential part of this process which was a mouse. I still decided to go ahead and see the entire video to understand how much is the usage of the mouse. And then I realized that I even needed a keyboard with the right set of numbers for ease of working. 
<br><br>
I decided to use my time in the class today to at least try something before I arrange for everything that I need for myself. So I borrowed a mouse from the IT Lab and started working. The first issue was I wasn't very comfortable using the mouse very much as I have got used to of the trackpads. The second issue was my assumption that I just did not have the right resources which were obstructing my progress. <br><br>

I had several bad attempts at making a simple cup. I had to restart several times and when I finally thought I made progress, I realized how bad the attempt was. The software is very sensitive to clicks so even without realizing you tend to make a lot of modifications. You realize that only when you start rotating your object in different directions because seeing it as a 2-D object you might have it all right. I thought of adding a snapshot of my attempt so far.<br><br>

This is how it was suppose to look:
<br><br>
<img src="https://user-images.githubusercontent.com/31910791/32298806-4842e39a-bf21-11e7-8d6d-3cb47b8cca06.png">
<br><br>
This is how mine turned out(which is so embarrassing):
<br><br>
<img src="https://user-images.githubusercontent.com/31910791/32298803-433fbf12-bf21-11e7-87a1-9d04ea2773a4.png">
<br><br>
This entire episode was very demotivating and my frustration didn't allow me to give it another try. I am going to use a different software name Auto-tinker or use a different set of tutorials, both of which were suggested by my fellow mates at my class.<br><br>
<h2><u>My second attempt at 3D Modelings<br /></u></h2>
After a terrible first shot at 3D modeling and a good long break, I decided to try using the blender again. As suggested by others, I decided to do the simple course in Lynda for practice. Even with the mouse, it was still tough and a lot of the commands which could have been done using the normal keyboard became tedious as you had to find those commands on the toolbars. After a few more frustrated attempts with blender, which is just not MAC friendly, I decided to try other softwares.
<br><br>
I wanted to use a more user-friendly tool so I decided to look at Youtube videos of 3D modeling using different softwares before I jump into another mess. When you look at these videos, they seem so simple and when you really have to do those things yourself, it just seems impossible in the beginning. Out of my 3 learning modules, this has been the toughest. This might be because this is the only one that needs you to use your imagination and PATIENCE. Every wrong move has a consequence which you realize at the end of the process.
<br><br>
I have finally decided to use TinkerCAD, an Autodesk product, next to try out simple models. <br><br>
<h2><u>My second attempt at 3D Modelings<br /></u></h2>
This has been a very tedious experience for me so far but I am very happy to come across TinkerCAD. It is definitely very user-friendly, especially changing the angle of the view which helps me keep track of the symmetry. There are all the standard options for controlling the movements in the 3-d space in the left corner of the screen. <br><br>
<img src="https://user-images.githubusercontent.com/31910791/33227881-6fa37d32-d173-11e7-9980-8006691cf676.png">
<br><br>
It helps me choose the basic views from different x, y, and z-axis angles and super easy to zoom in and zoom out and all of this just with the touchpad. I tried the basic tutorials that were available on the signing up of the software which helped develop a good sense of working with the software.
<br><br>
I tried to make some very shapes and fiddled around with them. I was super happy to finally have some symmetric models. on moving one step forward I decided to follow steps of a youtube video to make a Minion(Banana..!). Though I assumed it is such a simple capsule like character, it was tougher to make it. After a few steps, I started developing my own steps which gave me a sense of happiness. After 3 hours, I finally had my model ready, it had some errors but at this point, I was still very proud of myself.<br><br>
<img src="https://user-images.githubusercontent.com/31910791/33227882-71aabfd2-d173-11e7-8ac6-8294defe729a.png">
<br><br>
<img src="https://user-images.githubusercontent.com/31910791/33227883-73aa2728-d173-11e7-98f4-d17aa076ecb4.png">
<br><br>
<h2><u>Minion in the making<br /></u></h2>
I decided to try my first print as the minion. Prof. Walker's help in understanding the setup of the 3-d printers and importance of the material as well its other parts played a very important role in my first print. The first realization was that a multicolor print was not possible but this plastic gets coated with acrylic paint very easily so I decided to print my entire minion yellow and later use paints to make it look like a minion. <br><br>
Working on this project opened my mind to 3-d visualizations quite a lot. Even the print made me realize that my model needed supports to get printed from bottom to top in so many places which I hadn't noticed while making them. It started printing very nicely then it started getting spoilt which was very discouraging. Though I soon realized that the fans near the nozzle were off because of which the molten plastic was dripping. But at this point, I am glad that I put the supports and though a little out of shape but a figure is getting printed.
<br><br>
<img src="https://user-images.githubusercontent.com/31910791/33228257-54c3c0f4-d17c-11e7-9121-79b184ac3d70.JPG">
<br><br>

The next step after the endless wait for the print to complete is giving it the finishing touch. You need to get rid of all the supports which break off very easily but the tougher part is scrubbing to remove the extra protruding with sandpaper to give it smooth edges. After doing as much as I could we have our minion ready to get dressed in the paint. Yayy.. <br><br>
<img src="https://user-images.githubusercontent.com/31910791/33228258-568efb06-d17c-11e7-86dc-d053f9043623.JPG">
<br><br>
<h2><u>Working on the stretched goal<br /></u></h2>
My stretched goal for this module was to either make a mechanical clock or a 3-D puzzle using 3-D printing. I decided to make a very simple 3-D puzzle seeing my past experience. I built my model on the holiday theme(very Christmasy), a snowman. I made the snowman's hat and hands separately to try entangling basic shapes of puzzle pieces. I got the inspiration from <a href ="https://www.youtube.com/watch?v=j40uXQlm7TA"> 3-D Snowman maze puzzle</a> and built my puzzle on it. <br><br>
My model was a very simple model with the different pieces as shown in the below picture.<br>
<br>
<img src="https://user-images.githubusercontent.com/31910791/33306094-93660ffe-d3d6-11e7-9306-588253ad63d5.png">
<br><br>
If you see very closely the below picture, you will be able to notice the different spaces for the arms and the hat's base to get inserted.<br><br>
<img src="https://user-images.githubusercontent.com/31910791/33306091-916503e0-d3d6-11e7-98f9-0d5e9baf756b.png">
<br><br>
Though the model was ready, I couldn't try a print during today's class as my minion was still printing and the other printers were busy. I wanted to print the different pieces in different colors to distinguish between them. A setback was that we did not have any printers at this moment in our lab to accomplish it. I decided to split the model into 2 and print on different printers using different colors but TinkerCad did not have the feature for me to do so. So I decided to print them together and use paint again. But I so want to see what other softwares had to offer for splitting the models. I think I had pretty less time on this module to figure out everything but I will surely explore later.<br><br>
<h2><u>The Snowman<br /></u></h2>
The modeling was very smooth but I was still apprehensive about getting the measurements right for the pieces to fit in. But I guess I had bigger issues to address this time. With each print, it is getting more difficult for me to understand the 3-D printer which is super frustrating. I had to give multiple prints and each of them were different from the previous one. They even varied from printer to printer. Some of the pictures from my prints are below. <br><br>
<img src="https://user-images.githubusercontent.com/31910791/33306803-96fa8214-d3d9-11e7-9b87-4aacf90c0885.JPG">
<br><br>
<img src="https://user-images.githubusercontent.com/31910791/33306805-9853cc9c-d3d9-11e7-9ec8-12bc937bd350.JPG">
<br><br>
<img src="https://user-images.githubusercontent.com/31910791/33306817-a66f76d2-d3d9-11e7-83d5-aa8e63a78312.JPG">
<br><br>
<img src="https://user-images.githubusercontent.com/31910791/33306821-a998aac2-d3d9-11e7-8c28-d89d4b9ae419.JPG">
<br><br>
I guess the most irritating part of this module was not to be able to figure out why something was happening, the way it was happening. By the end of 5 prints, it was a puzzle for me to figure out how use the pieces to make one complete snowman. So I picked up the best different pieces from all the prints and smoothened the shapes for the the pieces to fit in each other. I finally painted my Snowman because I did not want it to have yellow hands. And here it is..<br><br>
<img src="https://user-images.githubusercontent.com/31910791/33307452-28b92c6c-d3dc-11e7-9fad-8a09f39439a2.JPG">
<br><br>
I have decided to continue 3-D modeling, though it is frustrating, it has come up as a challenge and I want to have one perfect model and print! 

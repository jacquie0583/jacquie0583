#  Welcome to my GitHub    
#  Jacquelyn Harland
####  Data Analyst/Scientist - Identifies business needs and develops valuable solutions to improve accuracy and process optimization. Drives business success with recommendations based on data findings. Previously as a teacher, a professional focused on maximizing student educational potential by applying diverse instructional strategies and classroom management techniques. Skillful in delivering lectures, facilitating discussions and planning to enhance learning. Using this, I bring a wealth of experience in data analysis and project modeling to guide research and demonstrations. Willingness to take on added responsibilities to meet team goals.

##  Project 1:  Belly Button Biodiversity Dashboard using Plotly
####             Resources
####  Data Source: BellyButton_bar_chart_starter_code.js, BellyButton_bubble_chart_starter_code.js, BellyButton_bubble_chart_starter_code.js and index.html • Data Tools: ECMAScript, JavaScript, JSON and IO (Web Server) • Software: ES6+, ECMAScript and Visual Studio Code 1.50.0\
####              Overview
Plotly provides graphing, analytics, and statistics tools, as well as scientific graphing libraries for Python, R, MATLAB, Perl, Julia, Arduino, and REST.  Plotly is an open-source library that provides a list of chart types as well as tools with callbacks to make a dashboard. The charts we have constructed and embedded are all made in chart studio of plotly. 
When Mrs. Roza came to us, she had partially completed a dashboard. A completed panel for demographic information allows for a user-friendly convenience.  We have constructed a chart to visualize the bacterial data for each volunteer allowing them to identify the top 10 bacterial species in their belly buttons. Furnishing this information will allow Improbable Beef the ability to identify a species, as a candidate, to manufacture synthetic beef.  Roza's volunteers will be able to identify whether that species is found in their navel.
The interactive dashboard explores the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels.  The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

#  [View Belly Button Dashboard](http://127.0.0.1:5500/index2.html)

##           Elements Constructed:
1.	 Horizontal Bar Chart
2.	 Bubble Chart
3.	 Gauge Chart
4.	 Customize the Dashboard
5.	 Report on the Belly Button Biodiversity Dashboard analysis 

##             Interactive Dashboard

<p align="center">
   <img width="600" height="400" src="https://github.com/jacquie0583/plotly_chart/blob/main/Image%201.png">   
</p> 



###  1: Horizontal Bar Chart
Using JavaScript, Plotly, and D3.js, we created a horizontal bar chart to display the top 10 bacterial species (OTUs) when an individual’s ID is selected from the dropdown menu on the webpage. The horizontal bar chart displays the sample_values as the values, the otu_ids as the labels, and the otu_labels as the hover text for the bars on the chart.
####  Code and Image
<p align="center">
   <img width="400" height="200" src="https://github.com/jacquie0583/plotly_chart/blob/main/image%203.png">   
</p> 


     1. Code is written to create the arrays when a sample is selected from the dropdown menu.
     2. Code is written to create the trace object in the buildCharts() function, and it contains the following:
         o	The y values are the otu_ids in descending order.
         o	The x values are the sample_values in descending order
         o	The hover text is the otu_labels in descending order.
     3.	Code is written to create the layout array in the buildCharts() function that creates a title for the chart.
     4.	When the dashboard is first opened in a browser, ID 940’s data should be displayed in the dashboard, and the bar chart has the              following:
          o	The top 10 sample_values are sorted in descending order
          o	The top 10 sample_values as values
          o	The otu_ids as the labels
     
### 2:  Bubble Chart
Using your knowledge of JavaScript, Plotly, and D3.js, create a bubble chart that will display the following when an individual’s ID is selected from the dropdown menu webpage:

      •	The otu_ids as the x-axis values.
      •	The sample_values as the y-axis values.
      •	The sample_values as the marker size.
      •	The otu_ids as the marker colors.
      •	The otu_labels as the hover-text values.
      
    1. The code for the trace object in the buildCharts(); function does the following:
       o	Sets the otu_ids as the x-axis values
       o	Sets the sample_values as the y-axis values
       o	Sets the otu_labels as the hover-text values
       o	Sets the sample_values as the marker size
       o	Sets the otu_ids as the marker colors
    2. The code for the layout in the buildCharts(); function does the following:
       o	Creates a title
       o	Creates a label for the x-axis
       o	The text for a bubble is shown when hovered over
    3. When the dashboard is first opened in a browser, ID 940’s data should be displayed in the dashboard. All three charts should also          be working according to their            requirements when a sample is selected from the dropdown menu.
        
 ####  Code and Image
 
<p align="center">
   <img width="400" height="200" src="https://github.com/jacquie0583/plotly_chart/blob/main/image%205.png">   
</p>  
    
    
### 3:  Gauge Chart
Finally we created a gauge chart that displays the weekly washing frequency's value, and display the value as a measure from 0-10 on the progress bar in the gauge chart when an individual ID is selected from the dropdown menu.

####  Code and Image

<p align="center">
   <img width="400" height="200" src="https://github.com/jacquie0583/plotly_chart/blob/main/image%206.png">   
</p> 

     1.	The code to build the gauge chart does the following:
          o	Creates a title for the chart.
          o	Creates the ranges for the gauge in increments of two, with a different color for each increment.
          o	Adds the washing frequency value on the gauge chart.
          o	The indicator shows the level for the washing frequency on the gauge.
          o	The gauge is added to the dashboard.
          o	The gauge fits in the margin of the <div> element.
      2.	When the webpage loads, the bar and bubble chart are working according to the requirements in Deliverable 1 and 2, respectively,            and the gauge chart is working according to the requirements listed for this Deliverable






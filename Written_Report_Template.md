# Kickstarting with Excel

## Overview of Project

    The Project for the first module was an analysis of data from the popular 
croudfunding site Kickstarter. Within the two deliverables i provide we have 
spreadsheets and charts to give some insight to how certain criteria affect the 
overall success of a campaign.

### Purpose

    The purpose of the project is to help Louise figure out based on prior data 
what the best time of year to succeed and what her fundraising goal should be to 
have the best odds for completeing the campaign with success.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
    
The analysis I did for the the theater outcomes was very simple I created a 
pivot table that counts the outcomes and is relative to the month of the it was 
started. Then using the table created I then made a line graph (the line graph is 
named Theater_Outcomes_vs_Launch) the line graph shows that there is a high 
probability of success for theater kickstarters that are launched in May.

### Analysis of Outcomes Based on Goals

  The analysis of Outcomes based on Goals was created by using excel commands 
and functions (Most notably he COUNTIFS command). The code I used to gather the 
data lookedsomething like this 
=COUNTIFS('Kickstarter 
Data'!$D:$D,">=5000",'Kickstarter Data'!$D:$D,"<=9999",'Kickstarter 
Data'!$F:$F,"successful")
    The way this works is by reading the data in the 
the entire column I have specified and counting if the data in the cell meets the
requirements. In this particular line it is looking for Kickstarters that were 
successful and their funding goal was between 5000 and 9999.

### Challenges and Difficulties Encountered

    With this project i ran into some challenges while gathering the data for the 
outcomes based on goals. Using the countifs function was exceedingly difficult in 
the beginning. Seeing as  had no experience with the function before the 
challenge it took some getting used to.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

    Conclusions you can draw from the outcomes based on Launch Date include that the best time to 
start a theater based croudfunding campaign is May because the chart spikes in high in the month of 
May. Another conclusion you can draw is that the worst time to launch a theater based croudfunding 
goal is December because in that month the successful and failed campaigns are the closest they are 
for the entire year.

- What can you conclude about the Outcomes based on Goals?
    
    The conclusion you can draw from the data  in the Outcomes based on Goals is that as the higher 
the goal amount the less likely for success the campaign has. For someone ike Louise tis is very 
important data because she wants the highest probability for successand keeping the budget lower can 
help her succeed
    
- What are some limitations of this dataset?

    A limitation in the dataset includes a lack of qualitative data. This meaning something like an 
average rating from the backers to tell us if they were satisfied and willing to back a similar 
project. 

- What are some other possible tables and/or graphs that we could create?

    Another graph you could create in the Outcomes based on Goals sheet would be a clustered bar 
graph using the number of successful, failed, and canceled campaign. this graph would show what 
specific range of goal has led to the most successes.

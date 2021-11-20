# An Analysis of Kickstarter Campaigns.
Performing analysis on Kickstarter data to uncover trends
# Kickstarting with Excel

## Overview of Project

### Purpose 

Our Client Louise has requested us how different campaign’s fared in relation to their launch date and their funding goals by Creating two new analysis such as outcome based on goals and outcome based on launch date and creating a line chart/graphs in order to give visualization to our client Louise.

## Analysis and Challenges

I used the information in the Kickstarter worksheet and identify the following Outcomes (Successful, Failed, Canceled), Goals and Launch Date.
I extracted the info and began to create a pivot table for Outcome based on Launch Date and Insert Chart for Outcome based on Goals.

### Analysis of Outcomes Based on Launch Date

The information on Outcomes Based on Launch Date suggests the there's over 839 Successful Launch date and for every month of the year.
And it reaches it's peak from May-June. On the other hand, the number of failed (493) ranges from 32-50 every month and canceled (37) was on the low side
By Creating a Pivot table and Pivot Line Chart it's shows the huge difference between Successful and Failed Launch Dates.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/94090097/142742188-62c32fb2-4a72-4f86-8a45-56459bcc66ff.png)
Reference: https://www.youtube.com/watch?v=nvPOUdz5PL4&ab_channel=ComicBookNewswithDanShahin

### Analysis of Outcomes Based on Goals

The Goals was categorized by range, and I used COUNTIF function to count how many Successful, Failed and Canceled belongs to those range.
Once we have the number for those range, we divided by Total Projects to get the percentage of those Successful, Failed and Canceled.
By Creating Line Chart it's shows the highest and lowest percentage between Successful and Failed.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/94090097/142742175-e7b10f30-9007-4ea3-b24e-ba436d0cf00c.png)
Reference: https://www.youtube.com/watch?v=nvPOUdz5PL4&ab_channel=ComicBookNewswithDanShahin
### Challenges and Difficulties Encountered

I tried doing the functions COUNTIF first but I'm getting a pop-up error so i used the hint/video instructions. 
I took time to finally figure out the proper function.
Under Pivot Table I was trying to edit the line and chart and since I am not familiar using "format Data series" it gives me some trouble removing box column and changing the color of the line.


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
I conclude that the number of successful plays was slowly increasing every month and reach its peak around May-June, and it's slowly deflated from July-Dec.
As for the failed launch date it was consistent for all the months ranging from 31% to 50%.

- What can you conclude about the Outcomes based on Goals?
I conclude that the Goals was successful in the range of less than 1k to 5000 and Goal that generated more
money from range 45k to 50k was failed.

- What are some limitations of this dataset?
Some of the limitations of this dataset are outcomes (successful, Failed and canceled) were the only 3 that used and the outcomes from "live" was not included.

- What are some other possible tables and/or graphs that we could create?
The other possible tables and/or graphs that we could create for Outcomes Based on Goal and Launch date is Clustered Column that show side by side difference between
the percentage of successful and failed.



# An Analysis Of Kickstarter Campaigns
## Overview Of Project 
Kickstarter is a program that utilizes crowdfunding to finance creative projects. This project looks over the the global Kickstarter campaigns & aims to uncover trends relative to theater projects. 
### Purpose 
The purpose of this project is to observe different campaigns, relative to theatre types & to compare their launch dates and funding goals.
## Analysis and Challenge[KICKSTARTER_CHALLENGE.xlsx](https://github.com/charris543/KICKSTARTER--ANALYSIS/files/8989834/KICKSTARTER_CHALLENGE.xlsx)
We organized the Kickstarter dataset by disassembling the category and subcategory columns. In doing so we were able to see the outcomes of all the categories. The Parent Category being theatre and the Subcategory being plays. In doing so we could conduct a more in depth analysis of the data.
### Analysis of Outcomes Based on Launch Date![OUTCOMES BASED LAUNCH DATE LINE CHART](https://user-images.githubusercontent.com/107444390/174456170-7ce09f00-6348-42dd-a23b-8c3b22d05104.png) 
The main focus of the Outcomes Based on Launch Date chart is to analyze the outcomes of theatre campaigns - successful, failed,and canceled. In the Kickstarter sheet, to take a closer look at the how campaign length ties into the oucome, we converted UNIX Timestamps to a more readable format. With that we could consider whether the length of a campaign makes a difference in determining its success. In the Kickstarter Worksheet, we created a Date Created Conversion column to see when the campaigns were launched. Next using the dataset, created Pivot Tables. To customize the fields for the Pivot Table, we used parent category and years for the filters, date created conversion for rows, and outcomes for the columns and values section. To gain a better visual from the pivot table, a line chart was also creted to highlight the realtionship between theater campaign outcomes established on their launch date.   
### Analysis of Outcomes Based on Goals ![OUTCOMES BASED ON GOAL](https://user-images.githubusercontent.com/107444390/174470504-bdd0bacd-006c-4b9e-a346-2860b90457ee.png)
The focus of this analysis is to visualize the percentage of successful, failed, and canceled plays based on the funding goal amount. To coduct the analysis, we needed to create a new sheet that consisted of tables, capturing the outcomes based on campaign funding goals. The goals were then broken down into 12 groups with a range of $1000 up to more than $50,000 and to capture the data we utilized the "COUNTIFS" & "SUM" functions. In which then, we were able to create a line chart to to visualize the calculated data. 
 ### Challenges and Difficulties Encountered
Some challenges were making sure that while creating Tables and Charts for my data, its highly impertive that I filter the data correctly. So that any questions, can be answered though organized and filtered data. Through trial and error, eventually creating visualizations and correctly filtering, I was able to identify key points in the story that the data was telling. 
## Results
- What are two conclusions you can draw about the Outcomes based on the Launch Date?
Thater follows the overall trend, there is a spike of successful campaigns that began in June. Towards the end of the year, October, November & December there is a steady decline in the general success rate of launching campaigns. 
- What can you conclude about the Outcomes based on Goals?
The success rate for campaigns with a goal fund of $5000 or less have a much higher success rate than of a campaign with a goal fund of $5000 more.
- What are some limitations of this dataset?
Some limitations of the dataset would be, data relative to plays. While there is massive data, only a small percentage pertains to plays.
- What are some other possible tables and/or graphs that we could create? 
Possibly comparing other campaigns found in the Kickstarter data set as it's relative to theater projects. As we learned to analyze our data by filtering, creating tables & pivot charts, this can generate great visualizations of the data to gain insight. 



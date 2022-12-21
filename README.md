# Kickstarting with Excel

## Overview of Project
The project aims to visually compare the success of outcomes of kickstarter campaigns using a dataset of past capmaigns of different types. Links to the visual charts are as follows:
/blob/main/resources/Outcomes_vs_Goals.png
/blob/main/resources/Theater_Outcomes_vs_Launch.png


### Purpose
The purpose of this analysis is to extract meaningful information from the excel dataset of past kickstarter campaigns using basic formulas, sorting and filtering fuctions, and pivot tables, to inform future campaign efforts. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Analysis of Outcomes Based on Launch Date required a pivot table to filter and sort data to acheive the desired visual output. Campaigns were filtered by "theater" campaigns, and displayed by whether they were successful, failed, or canceled over the span of a year delineated by month. 

### Analysis of Outcomes Based on Goals
Analysis of Outcomes Based on Goals required using the COUNTIFS function in Excel to return the frequency of a data entry within certain criteria. In this case, the criteria filtered the frequency of "play" campaigns within $5,000 goal ranges, filtered by whether they were successful, failed, or canceled. (e.g. =COUNTIFS(Kickstarter!$D:$D, "<1000",  Kickstarter!$F:$F, "failed", Kickstarter!$Q:$Q, "plays")). Sums and simple division forumlas were used to determine percentages of for these categories and compared using a visual line chart. 

### Challenges and Difficulties Encountered
Challenges and difficulties included hand-coding hard numbers such as "45000 to 49999" repeatedly into several formulas, which can easily break down if becomes desirable to chage the range sizes upon further analysis. I recommend creating cell references with this range information so that it can be altered or refined to change the outputs in realtime. 


## Results
Conclusions drawn from Outcomes based on Launch Date include:
- The most successful theater campaigns launched in the summer months - May through August.
- Both successful and failed campaigns trend similarly from month to month, while canceled campaigns remain relatively constant. 


Conclusions drawn from Outcomes based on Goals include:
- With no "play" projects being canceled, the successful and failed campaign trends mirror one another. 
- The most successful outcomes have goals either less than $5.000 or beteen $35,000 and 45,000, while campaign goals above $45,000 have the least successful outcomes. 

Limitations of this dataset include a lack of detail regarding the types of plays that are put on, whether they are indoor/outdoor, the number of people in attendance at each event and how that might correlate to success, etc. 


Other possible tables and/or graphs to create include:
- Compare Goal vs Pledged amount to help inform future goalsetting or areas to focus.
- Plot the success of outcomes with close each event's deadline is to its laucnh date. 
- Sort to see how frequently campaigns that didn't reach their goals were canceled or failed. 
- Plot to learn how close successful campagins' pledged amounts were to ther goals, and whether this gap differs between successful and failed or canceled campaigns.  


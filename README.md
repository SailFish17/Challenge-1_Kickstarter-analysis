# Challenge-1_Kickstarter-analysis
performing analysis on Kickstarter data to uncover trends - Challenge 1

## Overview of Project
The analysis reviewed a data set of Kickstarter campaigns that included funding initiatives for theater projects.   The data set was multinational and held information on campaigns for multiple categories of projects.   

## Purpose
The client would like to understand timing and size of grant requested and success or failure of that funding request for projects focusing on theater, specifically plays.

## Analysis and Challenges
The analysis was performed by sifting the data with Excel (data set is native to that application) thru the use of pivot tables and formulas and graphically representing the subsets for further analysis and trends.  
The dataset and platform presented unique challenges that needed to be overcome thru the use of Google Fu.  (See below)

### Analysis of Outcomes Based on Launch Date
* The Most successful month to start a campaign is May.  June has the second highest success rate.

* Dec Kickstarters fail about half the time.

* Theater people may be very hopeful, Theater kickstarters rarely get canceled. <3%,   

### Analysis of Outcomes Based on Goals
* Highest success rates are for kickstarters under $5,000.

* The general trend is that the larger the goal the less likely it will succeed,  Goals between 35 and 45K are less likely to fail compared to surrounding points but these 2 exceptions really just bend the trend flatter but do not significantly change the conclusion.

* Kickstarter campaigns for plays were never canceled.   

### Challenges and Difficulties Encountered
There were multiple challenges to reviewing this data set including;

-the inability to logon to the course site (Canvas site), 

-being booted from the course site multiple times (Canvas), 

-Course webpages only displaying half a page, 

-the inability to see the whole page and the need to use a slider located just above the rubric to see the column of text (Canvas), 

-Blind alleys to reset the webpage to view the directions of the webpage (Canvas),  

-Understanding the syntax of the Countifs formula and finally 

-reviewing and figuring out the rules of Kickstarter for a complete understanding of how Louise had to operate in that platform.

All of these challenges except formula syntax was overcome by going to the web for help or relying on the adage; if my computer doesn’t work, reboot.  Accessing the website correctly took a password reset, clearing cookies and google bookmarks.  Seeing the whole page was semi solved by copying the page into Word and then trying to capture a print page image.   This did not allow me to see the embedded videos however.  I finally rebooted my machine twice and the page miraculously displayed without the use of sliders.
The syntax issue was corrected by watching the embedded video and realizing the criteria less than or equal to meant referencing the dataset twice within the criteria term.
Understanding Kickstarter came from reading about it and the kickstarter FAQ’s.

## Results
### What are two conclusions you can draw about the Outcomes based on Launch Date?
See graph in file Theater_Outcomes_VS_Launch.png.

*Launch your kickstarter mid year; The most successful month to start a campaign is May.  June has the second highest success rate.

*Avoid launching end of year; December Kickstarters fail almost half the time, the highest percentage of failure throughout the year

### What can you conclude about the Outcomes based on Goals?
See Graph in file OUtcoumes_vs_Goals.png.

*Keep your requests for plays low cost, Highest success rates for Play kickstarters was $5,000.   

*The general trend is that the larger the goal the less likely it will succeed,  Goals between 35 and 45K are less likely to fail compared to surrounding points but these 2 exceptions really just bend the trend flatter but do not significantly change the conclusion.

*Don't quit, Kickstarter campaigns for plays were never canceled. 

### What are some limitations of this dataset?
*It is unclear if the currency markers in the goal and pledged columns are correctly represented in comparison to the currency called out in the Currency column.  Goal and Pledged columns all have $ signs but the currency column calls out several different currencies.  That stated, funding percentages are not affected by this issue, just the placement of the project in the proper currency size grouping once normalized to a standard currency.

*Whilst there are different countries represented, it is not clear if all the kickstarters were in native languages to those countries.   Funding success would be implicit to understanding the request for funds.  

*The titles of the columns are not all explained, I am not sure what Spotlight means.

*Category and subcategory should have been separated when initially building the data set.

### What are some other possible tables and/or graphs that we could create?
Additional conclusions might be derived by comparison tables and graphs with other subcategories of projects that would answer the following questions.  

For  example,  
-Is May ALWAYS a good month for all categories or subcategories or just for Plays.  Graph multiple categories and subcategories vs months of the year and compare with Plays.

-Do other categories of Theater behave differently at all goal levels?  Graph multiple categories to find best funding levels, compare best funded with blurb content and other variables to co-opt best practices in other categoies to increase probability of better funding for plays.

-An analysis of the blurb is in order at higher goal levels.   Do better explained projects have better funding success?   See graph in point above 

-See language issue with data set above.  More data is needed to understand the impact of language on funding success.   This data is not clearly represented in the dataset.

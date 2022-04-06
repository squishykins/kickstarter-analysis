# Kickstarting with Excel

## Overview of Project
### Purpose
Louise wants to know how different campaigns finished in relation to their launch dates and funding goals. Using the Kickstarter dataset that we've been using in the module this project will result with analysis and visualizations of campaign outcomes and funding goals. 

## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date

Using the Kickstarter dataset a pivot table was created that focused on when certain outcomes were reached. The pivot table used filters on the "Parent Category" and the "Years" category that was tasked to create. With the "Parent Category" filtered on "theater" the pivot table is able to visualize a more specific story from the dataset.

![LDgraph](https://user-images.githubusercontent.com/101137700/160508543-9fb238f4-b64b-4215-809e-55d5ee3a97a2.png)

Using the above pivot table a pivot graph was created and labeled "Theater Outcomes Based on Launch Date". The y-axis is the total outcomes and the x-axis the which month those outcomes were reached. Each line is labeled as "successful", "failed", and "canceled" projects. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/101137700/160508225-9f24bca9-18da-4bb7-a9e7-4624a5729aec.png)

### Analysis of Outcomes Based on Goals

Using the same Kickstarter dataset a new sheet is created. The columns, using COUNTIFS() for the first three columns (B-D), are used to calculate the next four columns (E-H) which use SUM() to fill the cells.

![BGgraph](https://user-images.githubusercontent.com/101137700/162001615-440eaeac-4d0a-4949-8b96-226278f8d8fa.png)

Once the table has been populated with all the necessary data a line graph titled "Outcomes Based on Goal" was created to better visualize the story the data is trying to tell us. The y-axis is the percentage of successful, failed, or canceled projects and the x-axis is the goal-amount ranges from the range above.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/101137700/162001661-65e19081-4545-4383-baa2-1faf05a37a02.png)


### Challenges and Difficulties Encountered
The challenges and difficulties that were encountered were primarily using the correct capitalization of the values used to label the columns. Originally I mistyped them to be capitalized when the original values on the main sheet I was trying to use did not have them capitalized at all. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date? 
    
    The two conclusions I can draw from the Outcomes based on Launch Date analysis is that May is a really good month to launch your theater Kickstarter and stay away from launching it around the holidays like December as that is the lowest percentage of successful Kickstarter campaigns. 

- What can you conclude about the Outcomes based on Goals?

    The most successful Kickstarter "play" campaigns were in the lowest range of less than $1000, at 75% successful at a total of 251 projects. But also it seems that the majority of the projects qualified under the $1000-$4999 range but at 73% successful at a large total of 524 projects. Using both of those to draw a conclusion it seems the best plan is to start low because you can always exceed the goal if necessary. 

- What are some limitations of this dataset?

    The most constricting limitation is that the dataset stops at 2017. Since the pandemic a lot of online campaigns have exploded in populatarity so it would be very useful to collect the most recent data that can be found. Another limitation is that the focus is primarily on plays and is so narrow that it may be missing greater trends.

- What are some other possible tables and/or graphs that we could create?

    Continuing from the previous question, the way to see larger trends instead of such niche markets is to expand the scope of the tables that were already created. Instead of focusing on just "plays", expand the dataset to include the entire Parent Category of "theater" for Outcomes Based on Goal. Just remember to change the title of the graph to plural, Goals.

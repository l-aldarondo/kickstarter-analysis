# An Analysis of Kickstarter Campaigns

## Overview of Project

This is a data analysis on several thousand crowdfunding projects. In this descriptive statistical analysis, we used several MS Excel tools, pivot tables, and graphing tools to visualize campaign outcomes.

### Purpose

The purpose of this project is to analyze thousands of crowdfunding campaigns in a short amount of time to uncover any hidden trends. Our client was interested in how different campaigns performed in relation to their launch date and founding goals. In order to provide an analysis that is easy and clear to understand to our client, we used the Kickstarter dataset to visualize campaign outcomes based on their launch dates and their funding goals.

### Analysis of Outcomes

To start our analysis, we first cleaned and filtered our dataset to have a better understanding of it. We then proceed to use pivot tables and charts to visualize our data. 

First we analyzed the dataset per parent category by creating a pivot table and charting the data.

![Parent_Category_Outcomes.png](charts/Parent%20Category%20Outcomes.png)

<sub>Fig 1.1 Outcomes by parent category
  

By looking at the data in Fig 1.1, we could easily identify that the "theater" and "music" parent categories performed very well. Given this, we decided to perform a deeper analysis by looking into subcategories. This allowed us to provide a data analysis that is more relevant and meaningful to our client.

![Subcategory Outcomes.png](charts/Subcategory%20Outcomes.png)

<sub>Fig 1.2 Outcomes by subcategory

As we can see in the chart (Fig 1.2), the "plays" subcategory performed very well, making the "theater" category the most successful.

### Analysis of Outcomes Based on Launch Date

Then, we created a chart based on “Outcomes on Launch Date” (Fig 1.3). Based on our data analysis, we could quickly identify May and June as the months with the most successful kickstarter campaigns. However, the month of June had a higher number of failed campaigns, leaving May as the month with the best performance.

![Outcomes Based on Launch Date.png](charts/Outcomes%20Based%20on%20Launch%20Date.png)


<sub>Fig 1.3 Outcomes based on launch date

We already established in Fig 1.1 and Fig 1.2 that “theater” was a very successful category. Next, we created a chart by filtering our “Outcome based on Launch date” for "theater" (Fig1.4). Looking at the data in Fig 1.4, we identified that the data for this subcategory follows the overall trend, making the data for this category more predictable.

![Theater_Outcomes_vs_Launch.png](resources/Theater_Outcomes_vs_Launch.png)

<sub>Fig 1.4 Theater Outcomes vs Launch

### Analysis of Outcomes Based on Goals

Per our data analysis, we were able to visualize that, in general, campaigns that had a lower goal as a starting point had a greater success rate. Then as campaigns started to increase their starting goal, the rate of success and failure was about the same. But for campaigns with very high starting goals the failure rate was higher. Based on the data analysis in Fig. 1.5, we can conclude that the success rate decreased for campaigns with higher starting goals.  

![Outcomes_vs_Goals.png](resources/Outcomes_vs_Goals.png)

<sub>Fig 1.5 Outcomes vs Goals

### Analysis of Central Tendency

Our client was interested in Great Britain's theater market, especially musicals. So far in our analysis we had provided our client with some of this information, but in order to provide a bigger picture and more robust analysis, we used a box plot as a measurement of central tendency and data distribution. 

![Distribution of campaign goals vs pledges_GB.png](charts/Distribution%20of%20campaign%20goals%20vs%20pledges_GB.png)

<sub>Fig 1.6 Boxplot, distribution of campaign goals vs pledges

Per our plot we can see that the mean campaign goal is around $4000, this value is outside of the range of outliers for amount pledged.

### Challenges and Difficulties Encountered

While performing our data analysis, we encountered some challenges during the 2nd deliverable analysis. The “COUNTIFS” function counts the number of cells in a range that matches a given criteria. This is a very powerful and helpful tool, however, sometimes we encounter errors like #COUNTIFS values error, or “COUNT IF not working”. The function can be challenging to apply, especially  when we have datasets in different ranges with multiple criteria. Also, for this analysis we need to have some knowledge or understanding of some basic concepts in statistics like central tendency and distribution. This could present a challenge for some people depending on their background and experience level. 

## Results

### Outcomes based on Launch Date

- Per our data analysis we concluded that the month with the most successful kickstarter campaigns was May as shown in Fig 1.3.
- We were able to determine that “theater” was a very successful category. The data for this subcategory follows the overall trend and makes the data more predictable (Fig 1.4).

### Outcomes based on Goals

- Based on this analysis we can conclude that the success rate decreased with higher starting campaign goals (Fig 1.5). 

### Limitations of this dataset
  
- This data set can have some limitations for our analysis. For example, we can think about how reliable the data is. Was the data manually or self reported? Are there any typos on the data entry or missing information or fields? Also, the way and method used to collect and measure the data can affect our analysis. If data is not properly audited, this can lead to miscalculations and incorrect trends in our analysis.
  
### Some other possible tables and/or graphs to consider
  
- For this analysis we could also consider “pie charts” or “dot plots” to visualize the Parent Category outcomes and the same applies to Subcategory outcomes. However, a bar chart seems to be a better option since sometimes it is harder to visualize proportions with a pie chart, still this is a widely used tool.  For central tendency and distribution we could also consider “Histograms” since it is an easy way to demonstrate any tendency in the distribution of our data. 


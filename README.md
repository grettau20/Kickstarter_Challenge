# Kickstarter_Challenge

    # Kickstarter Crowdfunding Campaigns Analysis.

        Overview

  Louise, an up-and-coming Playwright, is planning to launch a crowdfunding campaign to help fund her play to be called “Fever”. This is her first fundraising campaign, so she has enlisted our help. 

  The purpose of this analysis is to comb through past Kickstarter fundraising data and 
pull from it any findings that can help Louise estimate the best budget for her new play 
“Fever” and ensure the overall success of her first crowdfunding campaign.

  Some relevant information in this dataset includes but is not limited to funding goals and pledged amounts, launch and deadline dates, outcomes, and categories.

  This analysis will specifically look at fundraising outcomes by categories, fundraising outcomes based on launch dates and fundraising outcomes based on goals. 

We hope that the results of this analysis will be useful in helping Louise kickstart a successful campaign.

    How the analysis was performed, and challenges encountered

	Analysis Details

  The first analysis involved looking at outcomes based on categories and subcategories. Since these two were grouped into one column, we first split them into two separate columns (Parent categories and subcategories) by using the text to columns tab under the data tool. 
We were then able to create pivot tables and charts by using the insert tool and pivot table and pivot chart tabs respectively to display and visualize the outcomes based on parent category and subcategories. In both, a country filter was applied to narrow down the data to the US outcomes which are what Louise would be interested in.

There was no challenge encountered in this section.
  
  The second analysis evaluated outcomes based on launch dates. We first started by creating a converted launch dates column and used the formula provided in the module to convert timestamps into dates to fill the colum. From there we were able to insert a pivot table and chart, sort and filter the table from display the chart 
  
There was no challenge encountered in this section.

  The third analysis dealt with counting the successful, failed and canceled outcomes of subcategory plays in specified goal ranges provided. We used the COUNTIFS excel formula to fill each of the columns, the SUM formula for total projects, and the ROUND formula for percentages. We then use the insert tool to add a line chart visualizing the outcomes.


	Challenges Details

The most challenging part of the overall analysis was the Outcomes based on goals potion. The initial chart of outcomes percentages given the specific ranges was not matching the image in the instructions. After verifying the data using filters, consulting a tutor and joining classmates and TA during office hours, we discover that the goals and pledged columns values were changed at some point, possibly during formatting. After the original data was restored, the chart was corrected.

	Results

From the categories analysis we can see that, theater has the most successful campaigns.

From the outcomes based on Launch dates we can see that, May and June were the months with the most successful campaigns

From the outcomes based on goals we can see that, the lower the goal amount the more successful the outcome. Louise estimated budget is around $10000 which has 54% success rate.


We hope this overall analysis will help Louise feel more confident about initiating a successful first cowdfunding campaign.



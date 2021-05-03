# An Analysis of Kickstarter Campaigns
*Performing analysis on **Kickstarter** data to uncover trends to help <ins>Louise</ins> with the decision-making progress for her future plays using **Excel**.*

The complete Excel analysis can be found [here.](/Kickstarter_Challenge.zip)

## Table of Contents

|Contents                   |
|---------------------------|
|1. Overview of the Project |
|2. Analysis and Challenges |
|3. Results                 |

## Overview of the Project

### Purpose 

For this project we are trying to help Louise undertake the launch of a play by leveraging Kickstarter data to make an informed decision based on historical trends. The main objective was to help her maximize the possibilities of having a successful outcome based on the goal and launch date for her campaign. For this, we will be leveraging statistical analysis along with visual aids to identify trends and provide a recommendation to Louise based on the outcome of previously recorded campaigns.

This data contains information collected internationally over the period of 7 years (from 2010 - 2017) sourced from Kickstarter.

## Analysis and Challenges

### Analysis

For this analysis we looked at the proportions of **Successful** vs **Failed** vs **Cancelled** theater campaigns based on launch dates at the Parent Category level. 

### Analysis of Outcomes Based on Launch Date

![Outcomes vs Goals Line Chart.](/Resources/Theater_Outcomes_vs_Launch.png "This line chart represents a comparison between Theater campaigns by month and by outcome ( Successful vs Failed vs Canceled  .")

From this we were able to make the following observations: 

- Theater campaigns launched in May tend to be at least 3x more successful than campaigns launched in December. 
- May is the month in which more theater campaigns are launched. But also, ~66% of the campaigns launched in this month were successful. This is a higher percentage than any other launch in other months. 
- October seems to be a specially challenging month given that ~43% of the campaigns launched in this month failed. 

###  Analysis of Outcomes Based on Goals

We followed this analysis by drilling-down into the Theater Subcategory "Plays", to narrow down the analysis to the relevant subset of that that we cared about. We focused this analysis on a series of ranges to classify our data in smaller subsections to try to identify trends between Goal amounts and the outcome. 

From this analysis we were able to make the following observations: 

- Plays keeping the goal of the campaign to under $1,000 seems to yield an 80% success rate.
- Plays with goals approaching $15,000 become basically hit or miss with a 50% rate of success/failure.  
- For everything else we can say that keeping plays on a budget between $35,000 to $44,999 turns out to be the "sweet spot" for a successful campaign.


![Outcomes vs Goals Line Chart.](/Resources/Outcomes_vs_Goals.png "This line chart represents a comparison of Kickstarter Plays classified by outcome ( Successful vs Failed vs Canceled ) and by Goal ranges.")

### Challenges and Difficulties Encountered

The main challenge that we encountered was that with the data collected and during this period of time selected, there were no cancelled campaigns specific to Theater/Plays. Because of this, we couldn't collect potential reasons why a cancellation of a campaign might happen or any other relevant criteria to do a more focused analysis on this parameter. Another challenge that we encountered was that for the purposes of this analysis we decided to omit plays with Goals of $50,000 which left 4 failed plays out of the analysis which could skew our analysis and conclusions or any future predictions since there's not a good reason to exclude them. 

Plays that have a goal of under $1,000 have a high rate of success but the difference between the mean and this lower threshold seems high so it might be worth analyzing if these are outliers or if they should be considered in this analysis. If they should be considered maybe trying to dig into the size of the play or considering other factors would be relevant for this analysis.  

The most important aspect in my opinion is that I can't tell if the Goal is all in USD or if it's in several different source currencies which would skew our results when doing a cross-country analysis unless these other currencies have been adjusted for cost of living in the US by Kickstarter. Column "H, Currency" makes it seem like it's not all in USD. We could look at the documentation of the API to determine this if we needed to further clarify but for the scope of this analysis, we are assuming everything is in USD. 

## Results

After performing this statistical analysis and creating some visualizations we were able to identify a couple of trends that should help Louise with her decision. 

With the information gathered during this analysis and by leveraging the Outcomes based on Launch Date charts, we can conclude that:
- Launching campaigns closer to May is the smart play given the higher success rate observed.
- We should avoid October launches if possible. 

Specifically, when talking about theater plays, we can conclude that: 
- Aiming for a goal between $35,000 and $44,900 yields the best chance of having a successful campaign.
- We need to pay special attention to plays with goals under $1,000 to understand more about those campaigns and determine how relevant they are to our analysis.

After getting familiar with the data coming from Kickstarter and after understanding what Louise is looking for we can identify a few limitations: 

1. The data is at a "Country" level and doesn't allow us to drill-down to regional markets to better understand the success/fail ratios of local markets.
2. This dataset doesn't have more information like demographics of the backers for us to target the campaign to our market and increase the chance of success.
3. The dataset should be homogeneous and translated all to a common currency to ensure that we are comparing apples to apples. 

To compliment this analysis, we could come up with a "Box and Whisker" chart to identify outliers in our data to guide us through our decision-making process. We could also chart a histogram to identify if our dataset is skewed to the left or right to better understand if our sweet spot leans to the high or low end of our dataset.

## Sources

### The data used for the analysis was provided by UT from Kickstarter for the Data Analysis Bootcamp

### Markdown References
[Markdown reference file] (https://markdownlivepreview.com/)

:sunglasses: :space_invader: :robot:	
:see_no_evil: :hear_no_evil: :speak_no_evil:

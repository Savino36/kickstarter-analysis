# Kickstarting with Excel

## Overview of Project

### Purpose

The purpose of this analysis was to determine how different theater campaigns fared based upon the month in which they were launched and also determine how successful plays within the theater category were based upon their funding goal.  

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

The most successful months to launch a project would be May and June.  However, both of these months also saw the most launches in the theater category, so just looking at the total successes can be misleading.  Additionally, these months also had a relatively high number of failed campaigns.  

![Theater Outcomes by Launch Date](kickstarter-analysis/resources/Theater_Outcomes_vs_Launch.png)

Nevertheless, projects launched these two months were still more successful than other months and the higher number of total projects launched these two months could be indicative of people launching such campaigns acknowledging this.  

Further, the greater success in these months despite the higher number of total campaigns launched also shows there is not an over saturation and further underscores that these months are the best to laugh theater campaigns in.  

Based on the Data December is the worst month to laugh a theater campaign, there were almost as many canceled campaigns launched in December as those that were successful.

### Analysis of Outcomes Based on Goals

The most successful play campaigns in terms of reaching their funding goals appear to be those with a lower fundraising goal, which makes sense as the threshold to be deemed a success is lower.  

However, play campaigns with a higher goals, in the $35,000 to $39,999 and $40,000 to $44,999 ranges also saw almost as much success in terms of percentage as the play campaigns with lower goals.  

Unfortunately, this appears to be a product of the small number of campaigns with such higher fund raising goals, as those two goal ranges combined only has a total of 9 projects with 6 being deemed successful, skewing the percentage results due each project quantifying such a large percentage portion of each category.

### Challenges and Difficulties Encountered

I originally did not notice that the analysis based on Goals was only for the play subcategory, so I had to go rework my formulas.  Additionally, copy and pasting those formulas was more time consuming as it would auto-update the ranges for data, despite me wanting to keep them consistent. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

May and June are the two best months to laugh a theater project, even if they are the most popular months for doing so. 

December is the least desirable month to launch a theater project with almost half the project launched during that month failing. 

- What can you conclude about the Outcomes based on Goals?

Setting a goal below $10,000 seems to lead to the best change of success.  While campaigns with a goal of less than $1,000 are the most successful, in terms of percentage that succeed in meeting their goal, there is very little drop off in that rate (76% to 73%) when the gaol is set between $1,000 and $4,999.  With that being considered, a play in that range would likely have the best chance of reaching its goal.  

- What are some limitations of this dataset?

The binary "success v. failure" analysis is limited as, while campaigns that set lower gaol are more successful at reaching them, a play that sets a higher goal that is not hit could still raise significantly more money, despite not being deemed "successful" for purposes of this analysis. Further, the limited number of projects with a goal over $25,000 makes the data from those projects less meaningful because the sample size is smaller. 

- What are some other possible tables and/or graphs that we could create?

A table show the number of backers and average donation for the higher goal campaigns would be useful so that we could flush out if such campaigns success at reaching their funding goals was based upon a single or small number of backers.  Further, this would show individual high goal campaigns that were more successful at raising funds with a large group of backers so that the strategy they used could be studied in a more qualitative manner. 

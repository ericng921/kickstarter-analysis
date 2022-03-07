# Kickstarting with Excel

## Overview of Project

### Purpose of the analysis

Louise wants to know how different campaigns fared in relation to their launch dates and funding goals. I will analyze the campaign outcomes based on Kickstart dataset, visualizing the relationship between their funding goals and launch dates by charts. First, I created a Line Chart to see the relationship between launch date and the theater outcome if there is any difference when Louise performs in different month; the second chart I created a line chart as well to see the relationship between Goals-amount range and the ratio of outcomes. 

After the technical analysis Louise is having higher chance to be successful for her fundraising goal's project.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

First, I created a pivot table from the Kickstarter worksheet. And then I put Parent category and Years in Filters, outcomes in Columns and Values, Date Created Conversion in Rows, and I removed Years and Quarters from Rows in order to see the Months of the Year in Row Labels.

After that, I have created a line chart with marker showing the Outcomes based on Launch Date. Also, I filtered Theater as Parent category for the chart. By filtering Parent Category can be more specific and clearer to see the relationship between Theater Outcomes versus its Launch Date.

### Analysis of Outcomes Based on Goals

First, I created a new worksheet and named the 8 columns. Also, I put total 12 goal-amount range under Goal column. 

I used COUNTIFS function and put 3 different criteria to calculate the number of outcomes. The criteria are "goals-amount range", outcome such as "successful", and subcategory has to be equal to "plays".

After getting all number of outcomes, I divided the number of outcomes by the Total Projects to get the percentage of outcomes, and I also changed the format to Percentage in order to show my result in percentage format.

After the numbers are successfully filled out, I created a line chart to shows the relationship between the percentage of Outcome and the goal-amounts range filtered by Subcategory plays. This chart can tell Louise how much goals-amount range she should consider to get a higher successful rate on her plays.

### Challenges and Difficulties Encountered

One of the challenges is that I have to use the correct chart to visualize the data. For example, for the Outcome Based on Goals chart if we use Histogram chart, we will not be able to see the comparison as clear as using Line chart.

Another difficulty I think is the COUNTIFS function. I didn't apply the 3rd criteria "Plays" from subcategory in the beginning so I got a totally different Line chart. However, I figured out after and it is very important to keep in mind what Louise or our customers are looking for to get the correct result.

## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?

Based on the chart we can see there is a spike in May. we can tell Louise if she conducts the fundraising plays in Summer especially in May the result is most likely successful.

We can also conclude that the successful ratio after Summer, May, is going down trend and December is the lowest successful ratio of the year. We can tell Louise if she conducts the fundraising plays in the later month especially in December her fundraising result is not as successful as in Summer.

- What can you conclude about the Outcomes based on Goals?

I can conclude that the highest successful ratio is in the beginning of the chart which is Less than $1000 fundraising goal, and in the goals-amounts range of $35000 to $44999 the successful ratio is also higher than the rest of goals.

One thing we need to pay attention is the goal between $45000 to $49999 is 100% fail. We should suggest Louise to avoid this range.

- What are some limitations of this dataset?

1. We are not sure about the quality of data. It is possible that the data in the samples are incorrect then we will have a wrong result.

2. This dataset is too old. It is from 2009 to 2017. As we are in 2022 now, it may not be up-to-date and relevant. The numbers are not reflecting the actual result.

- What are some other possible tables and/or graphs that we could create?

We could create Box-Whisker plot from the Goals and Pledged by filtering subcategory "Plays". So that we would find out what are the Outliers of Goals and Pledged, and using filter find them out. Also, we can do a lot of comparison by Box plot including mean, median, and IQR, etc. to have more information about the plays and goals.

We cold also create Histogram to see the distribution of the Goals or Pledged based on Subcategory Plays then we can tell if the data is Skewed to left or skewed to right, or it is normal distribution for a deeper analysis of the project.




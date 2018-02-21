# Data Analysis Of Prosper Online Peer to Peer Loan Business

Visualisation: [Story Version 1](https://public.tableau.com/profile/sian.nadin#!/vizhome/Prosperloandata/Prosperloandata-Version1), [Story Final Version](https://public.tableau.com/profile/sian.nadin#!/vizhome/Prosperloandata-Version2/ProsperLoandata-Version2)


## Summary:

In my Tableau story I have done exploration on the relationship between loans and the people acquiring them, the reasons for taking out a loan and who defaults the most.
I have given a brief insight into the people acquiring loans by looking at the debt levels by state as well as the amount of money borrowed over the past few years looking at whether or not people were homeowners.
I explored the reasons that people have for taking out loans as well as who is most likely to default based on their occupation and income range.
Breaking down the number of defaulters by occupation it seems that college student have the highest borrower and default rates.

## Design

I began by looking at what data was available and deciding what variables might yield an insight into the trends of loans over the past few years. I decided to focus on what made a person more likely to take out a loan by looking into where they live, whether or not they owned a house and their occupation an income range. I was also interested in seeing who was likely to default on their loans.
I initially intended to show the number of loans over previous years using a line graph coloured by state, which has 52 possibilities. However, this proved to be too crowded to be able to gleam any information. This was then changed to a scatter plot which was coloured by the loan status, which only has 4 possible fields.
I also wanted to plot all graphs relating to the default rate on the same worksheet since they convey related information. The default rate vs. occupation contains a large amount of scatter points so it was difficult to read when it was only able to take up a fraction of the worksheet so it was moved to its own worksheet so that it would be easier to read.
For the final version of the workbook I decided on the following graph types:
* For showing the Income:Debt ratio by state it made sense to use a map to best convey this information.
* Scatter plots were used for showing the loan amount (indicated by size) broken down by:
  * loan status
  * category  
  * occupation.
  Each of which was categorised by colour.  
* Bar plots for depicting whether or not a person was a homeowner, their income range and Prosper score.

## Feedback:

I shared my first Tableau design with friends and received the following feedback:
* Showing the amount of money by state as a line graph was too crowded and difficult to take in information.
* The plot with occupation has quite a lot of information and it was difficult to see this plot because it was quite small since it was on a worksheet with two other plots.
* For the loan categories graph shown by quarter some people thought it would be easier to read if it was done by year so that there would be less points on the scatterplot.
* Remove Null values from Occupation vs. default rate plot as this doesn't yield any useful information.
* Using the colour blind palette on recommendation of my Udacity reviewer.



## Resources:

* [Tableau tutorials](https://www.tableau.com/learn/training)
* [Information on Prosper](https://www.prosper.com/)
* [Udacity course on Tableau](https://www.udacity.com/course/data-visualization-in-tableau--ud1006)

## Data Files
This Data set contains 113,937 loans with 81 variables on each loan.
The original data can be found [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv)

# Data Analysis Of Prosper Online Peer to Peer Loan Business

Visualisation: [Story Version 1](https://public.tableau.com/profile/sian.nadin#!/vizhome/Prosperloandata/Prosperloandata-Version1), [Story Final Version](https://public.tableau.com/profile/sian.nadin#!/vizhome/Prosperloandata-Version2/ProsperLoandata-Version2)

## About


## Summary:
in no more than 4 sentences, briefly introduce your data visualization and add any context that can help readers understand it


itself. In my Tableau story I have done exploration on the relationship between these people, what affects borrowers Prosper Score and who defaults the most.

I have done a time series
analysis ranging from year 2007 – 2014 about the number of loans taken by borrowers, the
amount of their loans

Then I have explored the defaulters, reason for defaults, and reason for borrowers to take loan,
I found out that the people with $0 income have highest default rates and most defaulters invest
in the loan type ‘D’.

Breaking down to occupation-wise, an interesting pattern was found that the
college student group which are enrolled in higher grade studies have more loans, higher
borrower and default rates.

## Design

explain any design choices you made including changes to the visualization after collecting feedback

I first sifted through the dataset and roughly thought about which variables I was interested in
exploring and which were outside the domain of my exploration. I first planned on making
another file which would contain the subset of variables I want to explore, but instead opted for
using the entire dataset in case I got new ideas midway through my exploration.
I wanted my Tableau story to have a purpose, to show to those who are interested in the facts
about the loan data. My focus was loan borrowers, which occupation defaults, their income, and
which loans borrowers took. I got a few amazing feedbacks like mapping state-wise default rate,
including the borrowers purpose for loan and some minor spelling mistakes. All these have
contributed in improving my visualization.
• I have used scatter plots to show how much loan amount on different listing categories
have changed over the time.
• Line plots to show how much the ProsperScore of borrowers has changed over the time.
• Geo Maps to show the default rate in each state.
• For showing the state-wise map of Defaulters and loan trends over time I have used Multiselect
Legends and automatic color pallets because in the dashboard I want users to be
able to select multiple options and see their effect in all the charts.
• For bar plots in Income and Credit Score dashboard I have used radio button legends, so
users can see at a time how different income groups affect the Prosper Score. And used
Color blind color palette based on feedback from Udacity review.
• In the final Estimate and Actual dashboard I have removed the legends since looking at
the X and Y axis ProsperRating(Alpha) is self-explanatory.


## Feedback:
include all feedback you received from others on your visualization from the first sketch to the final visualization

After completing the first sketch of my Tableau story I shared it on Udacity Slack group and
emailed the link to two of my friends. I received few important feedbacks mentioned below:
• Showing state-wise default rate – forthis I created a new numerical variable called Default
Rate from Loan Status and mapped with Borrower State, this showed an interesting
finding that in states like CA, TX, NY, IL the default rates were quite high with CA having
highest defaulters (>700).
• Finding why people borrow money – this was tricky but from data dictionary I found a
variable called Listing Category that had reasons for loans. I found out that since 2007
borrowers took most Personal loans which suddenly dropped in 2009. Then since 2009
the most loans borrowers took were for Home Improvement or Business which steadily
kept increasing with steady-drop in borrowers’ credit rating.
• There were also some minor feedbacks on spelling, typos, grammar and chart changes.
• I really appreciate all the feedback I got which helped me in improving my plots.

## Resources:

* [Tableau tutorials](https://www.tableau.com/learn/training)
* [Information on Prosper](https://www.prosper.com/)
* [Udacity course on Tableau](https://www.udacity.com/course/data-visualization-in-tableau--ud1006)

## Data Files
This Data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, borrower employment status, borrower credit history, and the latest payment information.
The original data can be found [here:](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv)



First, sketch ideas for your visualization. Once you settle on a sketch, explain any design choices in that sketch, such as chart type, visual encodings, and layout, in the Design section of the write-up.

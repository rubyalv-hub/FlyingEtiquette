# First Class or Economy, Most Flyers Agree: Go Ahead and Recline Your Seat
By: Ruby Alvarez Rubio

Data Source: https://github.com/fivethirtyeight/data/blob/master/flying-etiquette-survey/flying-etiquette.csv
Link to Google Sheets: https://docs.google.com/spreadsheets/d/1MMAG2MAbCyldcJ4mq3y15ygehAXVa9aEmqSNsOQFcz8/edit?gid=1129994050#gid=1129994050

# Introduction
Data was sourced from FiveThirtyEight's GitHub archive. A site previously well-known for using statistical models and polling averages on a wide variety of topics, such as elections, sports, science, economics, and more! This data was generated from a self-reported survey of 1040 people. People were allowed to abstain from answering any question, leaving blanks in the data. 

# Data Analysis

## Cleaning the Data
Many column names had minor typos, which were adjusted. One of the income categories, namely "150000+," needed formatting adjustments as well. When analyzing the data via various pivot tables, most variables had to be filtered to exclude blank responses. Key categories in the data included income, gender, age, height, and various queries about what they think is considered rude on an airplane. 

## Interesting Patterns
1. One interesting pattern is that across all income brackets, most people do not mind others reclining their seats on airplanes
2. A second intriguing pattern is that, regardless of income, people agree that the average acceptable number of times to get up (in a non-aisle seat) is 3 times. Through further filtering, grouping, and comparison, this dataset could be used to reveal what kinds of people are triggered by other common airplane practices. To further strengthen the data, it would be useful to rate how irritable respondents are in general, to remove biases when looking at what is actually considered rude in airplanes.

# Data Visualization
1. A horizontal stacked bar chart was chosen to display how people across different income levels feel about reclining one's seat on a plane. The chart effectively shows that, despite income, most people feel reclining on a plane isn't rude at all. The stacked bar chart allows viewers to compare the different answer categories easily.

![A horizontal 100% stacked bar chart titled "Does your income make you pickier on airplanes?" showing how different household income brackets view reclining plane seats, based on FiveThirtyEight data. The five income brackets range from $0 - $24,999 to $150,000+. Their responses were pretty evenly split, with the majority of people saying it's "not rude at all" across all brackets.](income.png)

2. Similarly to above, a vertical stack bar chart was chosen to display how many times people across different income levels feel is acceptable to get up on a 6-hour flight (in a non-aisle seat). By having a stack bar chart, it lets viewers get a quick glance of how many people find each number acceptable (i.e., we can see that the majority of people answered 2 or 3) + their income groups are easily readable on the bottom. 
   ![A vertical bar chart with income brackets across the x-axis ranging from $0 to S150,000+.](gettingup.png)

# Conclusion
## What privacy or ethical concerns might arise from this data

No privacy concerns could arise from this data since no identifying information was collected from respondents. 

## Could the data harm, stigmatize, or misinterpret individuals or communities

Yes, the data, though pretty evenly distributed throughout all categories, has the potential to harm the lower-income demographic of individuals surveyed. They have the highest answer rate of "very rude" for reclining one's airplane seat. This could inspire headlines misinterpreting the data as “Low-income people are pickier”. That class of people has the potential to be judged based on this data and may be mistreated in the airspace and even in their communities. 

## What reporting challenges might come up
There could be issues of generalization. Since the data is purely categorical, it would not allow us to make causal inferences

## What voices or sources would need to be included beyond the data
There should be smaller increments of earnings, which would increase our understanding of the hypothesis we made. 
There should be an indication of what flight class each person primarily flies in. There could be a difference in a person's idea of whether it is rude to recline your seat in an airplane, between someone who is flying in first class and someone who is in the general admission seats, regarding leg space. There should be a part of the data set that gives space for the participant to give the analyst an understanding of what their personal space values are like. This would make the data have more value because we can analyze human psychology more than a blanket statement. 

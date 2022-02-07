# New York Accidents Data Analysis- Case study

## Introduction/Objectives

<p>The city of New York has seen a rise in the number of accidents on the roads in the city. They would like to know if the number of accidents have increased in the last few weeks. For all the reported accidents, they have collected details for each accident and have been maintaining records for the past year and a half (from January 2018 to August 2019).</p>
<p>The objective of this analysis is to build visualizations that would help them identify patterns in accidents, which would help them take preventive actions to reduce the number of accidents in the future. They have certain parameters like borough, time of day, reason for accident, etc. Which they care about and which they would like to get specific information on.</p>

## Business Problem
The task is to format the given data and provide visualizations that would answer the specific questions being formulated, which are mentioned below.

## Analytical Context
<p> Given a CSV file (stored in the already created <code>data</code> folder) containing details about each accident like date, time, location of the accident, reason for the accident, types of vehicles involved, injury and death count, etc. The delimiter in the given CSV file is <code>;</code> instead of the default <code>,</code>. I will be performing the following tasks on the data:</p>

## Methodologies
1. Extract additional borough data stored in a JSON file
2. Read, transform, and prepare data for visualization
3. Perform analytics and construct visualizations of the data to identify patterns in the dataset

## Environment, Tools and Libraries:
1.	Pandas for data manipulation <img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white">
2.	Numpy for mathematical calculation and analysis <img src="https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white">
3.	Seaborn and Matplotlib for visualization and insights
4.	Python 3.7 Environment <img src="https://img.shields.io/badge/python-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white">
5.	Jupyter and Microsoft Excel as tools <img src="https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white"> <img src="https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white" >

## Approach
Formulate set of questions that would likely to be answered. I will provide visualizations to accompany these:
- How have the number of accidents fluctuated over the past year and a half? Have they increased over the time?
- For any particular day, during which hours are accidents most likely to occur?
- Are there more accidents on weekdays than weekends?
- What are the accidents count-to-area ratio per borough? Which boroughs have disproportionately large numbers of accidents for their size?
- For each borough, during which hours are accidents most likely to occur?
- What are the top 5 causes of accidents in the city? 
- What types of vehicles are most involved in accidents per borough?
- What types of vehicles are most involved in deaths?

## Recommendation/Conclusion
After much data manipulation and visualization I arrived at these summary for preventive actions and patterns of accidents

1.	The occurrence of accidents is seen as a periodical as it increases almost the same proportion as the former year. Also the maximum and minimum almost lies in the same month

2.	it was shown that <b>Brooklyn</b> has the highest total number of accidents per borough and <b>Manhattan</b> has the highest total number per square mile per borough.

3.  We can see that in all the boroughs the accident count is highest from approximately 2 - 6PM. But in Manhattan and the Bronx, you can see that there is not as much of a relative increase during these hours as in Brooklyn or Queens. Additionally, Staten Island has the lowest overall number of accidents.
4.  It was shown above from the dataframe that after comparing the contributing factors between the first quarter of 2018 and 2019.
It was observed that the above factors is higher in the first quarter of 2019 than 2018. 
Thus, it will be of the highest priority for the Traffic agency to ensure that targeted education 
and awareness initiatives should be done to ensure decrease in the factor which invariably decrease the number of accidents.






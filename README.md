**Objective:** Analyzing customer complaint resolution data and creating a dashboard to provide actionable insights to drive improvements in customer experience.

**Data Availability:** The client provided data in two tables:
•	First table containing customer complaints information from different banks & financial institutions, including Product, Issue, Complaint Channel, Resolution Time, Dispute Status, etc. This table contained 14,000 records.
•	Second table consisting of state codes and their corresponding state names.
Tools used: Advanced Excel (Text, Lookup, Aggregate, Array functions, Pivot Tables, Charts, Slicers, Filters etc…)
Techniques used: Exploratory Data Analysis, Data Cleaning, Creation of Dynamic Dashboards, and Insights Generation
Types of Charts Used: Line Chart, Pareto Chart, Bar Chart, Pie Chart, etc.
**Detailed Steps:**
1.	As part of this project, I analyzed consumer complaints data (a total of 14,000 complaints) from 1,050 banking and financial Institutions to develop strategies to enhance the complaint resolution process.
2.	Initially, I cleaned the data in second table, where State name and state code were given in the same column in JSON format. The State name and State code were separated in two columns in excel using text to column function.
3.	In the first table, State code was given against each complaint for which, State name column was added from second table using x-lookup function.
4.	The date column in first table was not in correct format. The format of the date column has been corrected ISNUMBER function and a new column Quarter has been added from the given date by using IFS function.
5.	Then, I started analyzing various Key Performance Indicators (KPIs) such as year-on-year changes in the percentage of complaints, timely response to complaints, average resolution time, and monthly trends to gain insights into overall customer experience.  On analysis of the data following major findings have been observed:
	The no. of complaints have been increased from 2013-2015 and have been dropped in 2016.
	No. of complaints were highest in August and lowest in December.
	98.5% of the complaints were timely responded.
	22.4% of the complaints were disputed.
6.	This analysis was further done at the state level, bank level, product level, Type of Complaint, Channel, time (Month, Year, Day, week) etc.
	Highest no. of complaints pertain to Bank of America (1066)
	The issues with highest no. of complaints - Loan servicing, payments, escrow account (2354)
	The product with highest no. of complaints – Mortgage (3346)
	Highest no. of complaints received through web (10467)
	
7.	I created a dynamic Excel dashboard that includes all the aforementioned KPIs with interactive filters for location (state, region), product, channel, issue type, and time. This enables stakeholders to drill down and address specific areas of customer experience.
8.	Finally, I formulated a strategy to prioritize complaints for resolution using a Pareto chart. Using pareto chart, it has been observed that 25% of the issues constitute 80% of the complaints which are to be prioritized.
**Challenges:**
There are some State codes in the first table for which state code and state name is not given in the second table. Hence it may lead to incomplete insights when analyzing complaint data by state (e.g., identifying trends, state-wise complaint resolution performance, or regional patterns).  
**Outcomes:**
Improved regulatory oversight and data-driven strategies to enhance customer satisfaction.

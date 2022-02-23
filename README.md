The Data used for this project refers to state and union territory wise distribution of suicide deaths by sex and age group in India.
This dataset has 237519 rows and 7 columns. It consists of information of state, year, type, gender and age group along with the causes of suicide deaths like Banktrupcy, Divorse, Physical abuse, Stress etc.
This project uses Apache Spark to process the data in memory for faster computation. The visualizations are done to create dashboards out of processed data.

Some of the problem statements for analytics and visualizations:\
1)Most common suicide cause among females in India over the entire period 2001-2012\
2)State wise most common cause among males over the entire period\
3)Age group wise most common cause among males and females\
4)Total number of suicides per year per state\
5)Male suicide rate vs female suicide rate\
6)Which state has more suicides over the entire period\
7)group by state,year,causes, count of suicides\
8)group by agegroup, gender, count of suicides\
9)select agegroup,gender,count(total) from suicides group by agegroup,gender\
10)state wise most common cause\
11)State has more suicides among females and males\
12)suicides count cause wise(causes)\
13) least cause for suicide\
14)List out various Categories of suicidal causes\

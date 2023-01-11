                              
                             INTRODUCTION
In 2021, there were 694,050 violent- crime incidents, and 817,020 offenses reported in the United States by 11,794 law enforcement agencies that submitted National Incident (NIBRS) data, and covers 64% of the total population.

This dataset contains statistics in arrests for assault, murder and other criminal offenses in the United States some years back.

The Aim of doing this project is to get the valuable and meaningful insight of how the crime rate  in the United States emerged, the causes as a result of either internal or external factors and how it affected people’s lives in the society.
The Dataset I used was gotten from kaggle, which includes 7682 rows and 17 columns in which the columns were made up of;

1.	Id
2.	Name 
3.	Date 
4.	Manner of death
5.	Armed 
6.	Age 
7.	Gender
8.	Race
9.	City
10.	State 
11.	Signs of mental illness
12.	Threat level
13.	Flee
14.	Body camera
15.	Longitude
16.	Latitude
17.	Is geocoding exact 
Packages used are:
1.	Pandas
2.	Numpy
3.	Seaborn
4.	Matplotlib



              Operations performed were:
-	Data cleaning and Data arrangements, missing values treatment in diverse manners and also checking of outliers.
There are reasons for outliers in a data which also has 3 causes
1.	Data entry measurement errors 
2.	Sampling problems and unusual conditions
3.	Natural variation
Outliers arise due to changes in system behavior, instrument error in population and they can also hold useful information about the data.
In this project, the outliers were checked by plotting box plots for some certain columns in which the head and tail were observed. 



         Exploration of the variables with various observations from the data
From the statistical values;
-The minimum age of the deceased is 2 while the maximum age is 92. The average age also is 35

-The minimum distance which is the longitude is -160 while the maximum is -67

-The minimum distance which is the latitude is 5.39 while the maximum is 71.301
Also it was also noticed that the number of the names that were not detected in the data were 407 also present with the numbers of genders which were 19




Observations from the analysis


-Age: The least age amongst people is 2 while the oldest age is 92 but the common age which was observed is 35 which we can say it is the average age. City: The city with the highest population is Lol Angeles, and from this say Lols Angeles has people with most race and also the state that has the most population is 'CA' -Comparing those with signs of mental illness to those without, it was observed that over six thousand (6,000+) people had no signs of mental illness compared to people that had with the rate of 1,624 -The threat-level was an attack on people while there were some threat level that was not determined as well -Rate at which people flee most was through car but those that did not make a move was much more than that those that flee.


-The rate at which is Male were shot is much more than the rate at which the female were shot from the pictorial analysis above
And at same time the rate of which the male were shot and tasered compared to the female was clearly shown that it was much more. This simply explains that the male suffered the calamity than the female gender.


-The year in which signs of mental illness were discovered most was 2015 while the year when the least signs of illness were also discovered was 2022. 2018 and 2019 happened to be the average year 


-it is well obvious that the male gender flee due to the incident happening more than the female gender the mode of movement of some were not determined as well but among the male gender people that flee with car was much compared other which was not mentioned and also among the female gender people that flee with car was more and people that their mode of movement was not discovered were much as well









# 120 Years of Olympic History
## by Nikhil Kumar


## Dataset

This dataset contains data for all Olympic Games from Athens 1896 to Rio 2016 and was retrieved from [here](https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results). There are over 200,000 rows that contain information on each individual athlete including their gender, medal, country, sport, etc. The data encompasses both the summer and winter games. There is a plethora of valuable data in this dataset that can pave the way to discovering fascinating insights of how the Olympics have changed over the years. Before performing exploratory analysis on the data, there weres several issues with the dataset that needed to be cleaned up:

**Quality Issues**

- The values in the `ID` column should be string objects rather than integers
- The `Sex`, `Season`, and `Medal` columns should be converted to categorical datatypes
- The `Age` column contains float values that should be integers
- There are many duplicated rows
- There are many null values in the `Height` column
- There are many null values in the `Weight` column
- The values in the `Height` and `Weight` column should be ints rather than floats with ".0" at the end

**Tidiness Issues**

- The `NOC` and `Games` columns contain redundant information and are not needed

## Summary of Findings

There were several captivating insights of the data retrieved through univariate, bivariate, and multivariate exploration of the data. It is very important to note that there are far more males than females in this dataset due to the fact that women did not have the same opportunities to participate in the Olympic Games as men heve in the early years. It was found that from 1896 to 1952, there were little to no female Olympians. However, as time went on, more and more female athletes started to compete as they were given more opportunities. In 2016, The number of male and female athletes were almost even and both genders had over 6,000 athletes competing. As a whole, males were older, taller, and heavier than females, however these differences have not been drastic. The trends for the average height and weight of Olympic athletes over the years have only been steady since 1960 where both have steadily increased until 1992 and leveled off as of more recent years. Due to the fact that there were no particularly insightful trends in the height and weight data, these will no be incorporated in the final presentation. However, many other trends over time such as the average age between males and females have been very interesting to observe. Additionally, it was found that the United States has won the more total medals than any other team of all time.  

## Key Insights for Presentation

Exploratory plots were polished up and improved in the slide deck to provide clear visualizations of various insights of the data. It was discovered that although males make up 71.6% and females make up 28.4% of the dataset, participation by females in the Olympics have drastically increased over time. From 1896 to 1952, there were little to no female Olympians. However, as time went on, more and more female athletes started to compete. In 2016, The number of male and female athletes were almost even and both genders had over 6,000 athletes competing. As for the top winning teams of all time, the United States has been the most consistent team over the years by winning many medals at each Olympic Games. Conversely, the Soviet Union has not been consistent over time. They did not win as many medals relatively other than an extremely powerful stretch from 1952 to 1988. They had by far the most dominant year than any other team has ever had when they won the most medals in 1990. These are only a few of the surprising findings revealed through the data analyis. More can be found in the final slide deck presentation.
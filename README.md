# Tableau Report---Storm Event Analysis

### Tableau workbook (Online Public):

https://public.tableau.com/profile/agnes8748#!/vizhome/Stormeventsanalysis/Story1

Please explore other two stories in metadata.

### George Washington University DNSC 6216 Business Analytics Skills Workshop

Group 5: Hangman Jiang/ Hongbo Liu/ Chengquan Guan/ Weihang Wen/ Yinlu Wu


### Dataset: 

US storm information since 1950

We found this dataset from the National Centers for Environmental Information of NOAA. It contains information of every storm event from Jan 1950 to May 2017 in the US, including event type, time, location, magnitude, damage and fatality information.

We are interested in this data because we are concerned of the frequency and severity of storm events. First, we noticed that certain types of storms appear significantly more frequently than others, which implies different treatments. Second, storms can bring serious economic loss to industries including agriculture, finance, mining and transportation, and even loss of human lives. The dataset is of high quality in terms of size and completeness, providing abundant room for us to play around and test for hypothesis. Analysis results of this dataset will provide valuable insight to reduce and prevent damages triggered by storms.

### Storyline:

We are concerned of casualty and economic damage caused by storm events and we use these two figures to measure severity of storms. Our analysis of storms is based on geographical region, time and storm type, and organized as three stories in our workbook.

First, we focus on storm distribution and severity in different states. We found that the total injuries/deaths and damages varied greatly among different states. There are some states suffering a lot from the storms. We also identified states with high casualty but low damage, and vice versa, for example, Missouri. We then had a detailed study on Missouri and discovered that the difference is due to severe but infrequent events like excessive heat.

Second, we studied the relation between time and event frequency. We found cycles across years and seasonality of storm severity. We see two cycles in the past 12 years and storms are most severe in summers. We also discovered that storms are most frequent in the afternoon. Specifically, we combined information on time and storm type, and identified the most severe event types for each month. For example, tornado is the biggest disaster in spring while flood causes most damage in summers.

Third, we studied effects from different storm types. We first figured out the relationship between average casualty per event, and frequency. There are hidden killers that are deadly but infrequent, like heat. Then we combined storm type and state, and found out the most deadly storm type to pay attention to in each state. 

### Conclusion:

1.	Storm fatality and frequency have different distributions. Instead of concerning of frequent but mild events, we should pay more attention to deadly but infrequent event types.
2.	Storms are cyclical and seasonal, making it easier to predict and prepare in advance.
3.	Local governments should allocate resources to the preparation of the most deadly storm types for the area.

### Challenges:

1.	Data quality: the full dataset contains millions of entries, but most of them are too immaterial with no casualty and no damage at all. Furthermore, the dataset is not very clean and contains missing values. Storm magnitude is not complete so we cannot make analysis on magnitude. Some categorical variables are not clearly described thus it is difficult to make precise analysis (e.g. event types include “excessive heat” and “heat”, “winter weather” and “winter storm” with no explanation). Some columns require reformatting. In summary, data cleaning is a heavy job in this project. We used R and SQL in preparing data.
2.	Tableau is not a suitable tool for predictive analysis. It is difficult for us to build prediction models about damage and fatality using Tableau. Our project is thus emphasizing on descriptive analysis and visualization.

### Reference:

https://www.ncdc.noaa.gov/stormevents/ftp.jsp

ftp://ftp.ncdc.noaa.gov/pub/data/swdi/stormevents/csvfiles/



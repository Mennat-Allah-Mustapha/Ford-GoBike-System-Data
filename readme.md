# Ford GoBike System Data Analysis
## by Mennat-Allah Mustapha


## Dataset

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.

>wrangling the data

* make a copy df not to disturb the original data

* convert time columns into datetime to can make aggregations

* converting duration into minutes to be more reasonable and easier in observations

* drop the rows with missing data

* calculate the users age


## Summary of Findings

> Most rides happen on day(3) which is Thursday and less rides happen on days (5,6) which are Saturday and Sunday by mostly equal frequency

> Most rides happen in the morning and the evening, which makes sense beacuase these are the rush hours in the day

> Station (San Francisco Caltrain Station2) has the most number of rides starts, with about 3400 rides but the forth place as end station with about 3800 rides.
Station (Berry ST) has the second most most number of rides starts, with about 2900 rides but the sixth place as end station with about 2600.
Station (Market St at 10th st) has most rides as end station with more than 3500 rides but not in the top 10 stations as start station

> Number of subscribers is much more than customers so business wise may be we need to focus on the main users which are subscribers or we need to increase number of customers to earn more users.

> Male users are much more than females in both types customers and subscribers

> Days of uasage don't differ much from males to females, Thursday still the most day with rides

> Adults between 20 and 40 years old are the main users.
old people > 40 years old are also a bid segment of users.
But teenagers (under 18) or kids don't use the system may be it requiers that the user must be older than 18

> Younger users take longer rides as well as most of them are males

## Key Insights for Presentation

> most important threads are 
* When most trips are taken in terms of time of day, day of the week

* if the above depend on user age / gender or if the user is a subscriber or customer

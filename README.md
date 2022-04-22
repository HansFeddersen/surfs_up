# surfs_up


Data Bootcamp Module 9: Surf's Up with Avanced Data Storage and Retrieval
## Overview of Project

### The purpose of this project is to retrieve information by using SQLAlchemy to connect and query a SQLite database. SQLite is a database engine that provides a quick way to setup a database without requiring a server. It has most of the important capabilities of an SQL database, but it differs from SQL on the fact that is local (you can create databases locally on your computer). On the other hand, SQLAlchemy is the Python SQL toolkit which has a feature called Object Relational Mapper (ORM) that allows to create classes in your code that can be mapped to specific tables in a given database.

## Resources
**For this analysis, the following resources were used**:
- Data Sources: hawaii.sqlite



## Results

**Three major points from the two analysis deliverables**

- There is no major difference between the average temperatures in June and December. While June has a mean temperature of 75 F, December has a mean temperature of 71 F, which is not a big difference. It is also important to consider that both of them have enough data to make a good sample (even though there are more records in June than on December).

- There is a major difference on the minimum temperature recorded in June and December. The minimum temperature recorded in June is 64 F, while the one recorded in December is only 56 F. We also have to take into consideration that the lowest temperature in December was for the year 2014, but in that same year June recorded one the highest temperatures ever (84 F on 06 - 24 - 2014).

- The temperatures recorded on December have a slightly greater standard deviation than the ones recorded on June, so we can say that the temperature on the island varies more in December than in June.

Tables:

![This is an image](https://github.com/HansFeddersen/surfs_up/blob/main/More/Temperatures_recorded.png)

**Two additional queries to perform to gather more weather data for June and December**

- We can add a query to obtain the precipitation levels for both months and that way have a more complex study. In that case, the query would be as follows:

![This is an image](https://github.com/HansFeddersen/surfs_up/blob/main/More/precipitation_query.png)

Clearly it rains much more in December than in June, as we can see in the following tables:

![This is an image](https://github.com/HansFeddersen/surfs_up/blob/main/More/precipitation_recorded.png)

- We could also write a query to obtain the minimum, maximum and average temperature/precipitation for each of the 9 stations available and we will see that station USC00516128, not only has the lowest average temperature of them all, but also it is the one that shows the greatest average of precipitation (it would not be recommendable to put any ice cream shop near that station). The query to obtain that information and results are as follows:

![This is an image](https://github.com/HansFeddersen/surfs_up/blob/main/More/station_queries.png)

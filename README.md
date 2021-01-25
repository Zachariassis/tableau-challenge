# tableau-challenge

This project aims to understand Citibike usage for Subscribers during the year 2019. Data was obtained from the [Citibike Website](https://www.citibikenyc.com/system-data). All data from 2019 were downloaded for analysis. However to reduce data for use in Tableau certain filters were applied to the data using pandas. The following charateristics were used as filter properties.

Filter properties:
Born 1969 or later (50+)
Only listed as male or female
Only Subscribers

Tableau visualizations can be found [here](https://public.tableau.com/profile/zachary.adams8511#!/vizhome/CitiBikeUsage2019/CitiBikeResults). 

The first breakdown looks at bike usage per month based on age and gender. Men used Citibike much more than women consitantly over every month, approximately three times as much. Interestingly on average trips took longer for women than for men on average. Assuming no significant variation between genders on the average distances travelled it seems that men may ride thier bikes more quickly than women. It would be interesting to see if there was a correlation between bike accident incidences and gender to see if speed was a factor. 

For both genders the most common months of usage were the late summer/early fall months (August and September). The least usage was observed in the winter months. This is expected as bike usage should be highest during nice weather. When observing trip duration we found that both genders typically take longer trips during the spring. This makes sense, as people may be more inclined to take their time outside when the weather turns nice. 

As expected the most common age groups to use Citibike were in their late 20s and early 30s. This corresponds with young working adults in entry level positions living in NYC with no vehicle and (probably) high rent. 

For all observed age groups September and August were the most common months to use Citibike, while January, Febuary and December were the least popular. There was no relative propensity for one age group to 'tough it out' during colder months relative to another. 

The second breakdown looks at bike locations and their usage flux. Flux represents the relative flow of bikes from one location to another. Red dots on this image correspond to locations that have more incoming bikes than outgoing bikes, while blue dots represent more outgoing bikes than incoming bikes. The size of the dots represent the number of trips from that station. Gray dots represent stations that have similar bike trips incoming and outgoing. 

From this map we can see that there is heavy traffic to many of the locations in lower Manhatten, specifically lots of incoming bike traffic. However many of these users seem to find other transportation to return home, as they have more incoming than outgoing bikes. This is contrary to areas surrounding central park, Brooklyn and Queens. These areas have more outgoing traffic than incoming. Brooklyn and Queens only have a slight outward flux, as commuters living in these areas travel to work in Mathatten. 

General bike flux is important to observe as there is no gaurentee that bikes will move to and from each location at a constant rate. Discovering these patterns of where people want to travel to and from using Citibike would allow for proper movement of the bikes by the Citibike administration, ensuring optimal numbers of bikes at necissary locations. 
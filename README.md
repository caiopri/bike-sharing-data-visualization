# Ford GoBike System Data Exploration
## by Caio Priszculnik


## Dataset

The dataset explored in this analysis is from the Ford GoBike System. It includes data about individual rides in a bike sharing system from the greater San Francisco Bay area in California, USA. The data is in a csv flatfile.
There are 183,412 rides in the dataset with 16 features(duration in seconds, start time, end time, start station id, start station name, start station latitude, start station longitude, end station id, end station name, end station latitude, end station longitude, bike id, user type, member birth year, member gender and bike share for all trip).
After removing rows where the member's birth year and member's gender were Null, there are 175,147 trips in the dataset.
All rides were recorded between the month of February in 2019.

## Summary of Findings

In the exploration I found a few interesting facts and behaviors about the bike-sharing program in San Francisco. There are more trips from Subscribers than from Customers and more trips from Males than Females or members with the gender set as Other. Most of the trips were by young adults (24-35 years old).
Most of the trips happened during weekdays and were from up to 10,000 seconds long. The distribution of trips during the day is bimodal, with the peaks happening during the morning (8h-10h) and evening (16h-18h) rush hours. The stations located near Marker Street on Downtown San Francisco are the ones with the highest number of trips.
Most of the longer duration trips were by younger members and Females average trip duration was longer than Males average trip duration, this pattern happened on all days of the week. Trips during the weekend had a longer average duration than trips during weekdays. The longest trips happened at 3h. During weekends there was a higher decrease on trips from Subscribers than from Customers.
Most of the shortest trips were taken by young adults Subscribers. During weekends the distribution of trips wasn't bimodal with peaks at the rush hours, most of the trips during the weekend happened during the afternoon (13h-17h). On all days of the week, Customers had longer average duration trips than Subscribers. Independent of gender, customers have a longer average trip duration than subscribers. The ratio of subscribers/customers is much higher for males than for Other or females, this can help explain why males have the lowest average trip duration.

## Key Insights for Presentation

On the presentation I'm going to focus on the difference of start time for trips during weekdays and weekends. And I'll also explore the difference of average trip duration between weekdays and weekends. This is an interesting pattern that suggests that on weekdays most trips are for commuting and on weekends they are for leisure.
For the trips distribution during the day I used histograms to explore the shape of the distribution. For the average trip duration I used a barchart to compare the average trip duration for each day of the week.

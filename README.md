# bikesharing

Module 14

## Overview of Analysis

### Purpose
The purpose of this analysis is to provide a summary of the NYC Citibike data for August 2019. Diving into this particular dataset could provide insight to potentially implement Citibike in another location (like Des Moines, Iowa). This analysis breaks down the data into visualizations around user trips (how long bikes are checked out for, how many trips happen each weekday, how often each usertypes (customer/subscriber) are using bikes each weekday, and further splitting these findings up by gender. The analysis also looks at peak hours in August and both starting/stopping locations for bikes. These visualizations are all completed in Tableau and published online on Tableau Public.  

## Results
This section covers all of the data visualizations within the August 2019 NYC Citibike Analysis published in a story format on Tableau Public.

### Checkout Times for Users
This visualization splits the trip duration data into 24 sections (each representing a total hour) and then into minutes and displays how many bikes are checked out for these lengths of time. It demonstrates that most bikes are checked out for about 5 minutes (which is seen with the large peak within the hour 0 section) and that most trips do not last longer than 45 minutes (seen by the plateau of the peak within the hour 0 section). Every other hour section (1-23) show only a small number of bikes checked out for trips lasting longer than 45 minutes.
![01_checkout_times_for_users](https://user-images.githubusercontent.com/107309793/190936127-a2e9fd1d-ce7b-4350-913b-51f506d9ac7a.png)

### Checkout Times by Gender
This graph is set up in the same manner as the previous graph but splits the data up by gender (female, male, and unknown). It is clear from this graph that the majority of the bikes are checked out for a trip length of 45 minutes or less by males. This is followed by females and then by unknown. After 45 minutes, it is indistinguishable between these gender groups.
![02_checkout_times_by_gender](https://user-images.githubusercontent.com/107309793/190936131-5af950f4-9e1c-4d37-9d5a-dbe07482e055.png)

### Trips by Weekday per Hour
This next visualization depicts the number of Citibike trips that happened at each hour of the day (12 AM - 11 PM) and splits this up by days of the week. During the weekdays (Mon-Fri) a larger sum of bike trips occured between the hours of 7 AM - 9 AM as well as 5 PM - 7 PM. Interestingly - Thursday during these peak times show the largest quantity of trips overall. During the weekends (Sat and Sun) the number of trips is spread out throughout midday (10 AM - 7 PM).
![03_trips_by_weekday_per_hour](https://user-images.githubusercontent.com/107309793/190936135-a8db2cd8-5e87-46c3-8f27-6a3ded524256.png)

### Trips by Gender (Weekday per Hour)
This heatmap splits up the previous visualization by gender. The same trends described above are seen in each gender panel. There are noticeable differences in the quantity of trips between genders however; males show the largest quantity of trips during peak hours, followed by females, and then the unknown gender group. This is consistent with the pattern seen by the bike checkout times by gender.
![04_trips_by_gender](https://user-images.githubusercontent.com/107309793/190936139-29020159-a040-4ccd-a525-39648d7ed47d.png)

### User Trips by Gender by Weekday
This heatmap splits up the trip quantities by weekday in a similar fashion to the previous two visualizations but further splits this data up by usertype (customer vs subscriber) instead of by hour. This provides some insight into the differences between customers and subscribers. It appears that the majority of trips are made by male subscribers, followed by female subscribers, unknown customers, male customers, and female customers. There does not appear to be any or much data involving subscribers of the unknown gender. This might indicate that users who do not subscribe to the service are less likely to report a gender, while subscribers do. Overall most trips are made by subscribers rather than customers.
![05_user_trips_by_gender](https://user-images.githubusercontent.com/107309793/190936144-c5dbd4a2-7f0c-4cbb-b83d-ab45e1f56b80.png)

### August Peak Hours
This horizontal bar chart compares the number of trips for ever hour of the day (12 AM - 11 PM). This graph confirms the data seen in the heat map and verifies peak hours regardless of weekday (8 AM - 9 AM and 5 PM - 6 PM).
![06_august_peak_hours](https://user-images.githubusercontent.com/107309793/190936149-28a9b926-1b26-4e13-928d-d2188084457a.png)

### Top Starting Locations
This map visualization shows the most populated areas of NYC associated with Citibike trips. Some of the darkest markers are approximately in the Upper East Side, Upper West Side, and Tribeca/Soho. There are less trips that occur near the Brooklyn bridge and even less that occur in regions across the East River.
![07_top_starting_locations](https://user-images.githubusercontent.com/107309793/190936154-90fbd8b5-40fd-4407-b80d-e1d19992542a.png)

### Top Ending Locations
This map shows the stopping locations of all the Citibike trips. The regions that most bike trips occurred in the previous map are quite similar to those of the stopping locations. This further confirms that the majority of trips are short in duration (and subsequently length).
![08_top_stopping_locations](https://user-images.githubusercontent.com/107309793/190936166-83171d43-70f1-4c5f-a434-100b077b380d.png)

## Summary

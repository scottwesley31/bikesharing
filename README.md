# bikesharing

Module 14

## Overview of Analysis

### Purpose
The purpose of this analysis is to provide a summary of the NYC Citibike data for August 2019. Diving into this particular dataset could provide insight to potentially implement Citibike in another location (like Des Moines, Iowa). This analysis breaks down the data into visualizations around user trips (how long bikes are checked out for, how many trips happen each weekday, how often each usertypes (customer/subscriber) are using bikes each weekday, and further splitting these findings up by gender. The analysis also looks at peak hours in August and both starting/stopping locations for bikes. These visualizations are all completed in Tableau and published online on Tableau Public.  

## Results
This section covers all of the data visualizations within the August 2019 NYC Citibike Analysis published in a story format on Tableau Public.

### Checkout Times for Users
This visualization splits the trip duration data into 24 sections (each representing a total hour) and then into minutes and displays how many bikes are checked out for these lengths of time. It demonstrates that most bikes are checked out for about 5 minutes (which is seen with the large peak within the hour 0 section) and that most trips do not last longer than 45 minutes (seen by the plateau of the peak within the hour 0 section). Every other hour section (1-23) show only a small number of bikes checked out for trips lasting longer than 45 minutes.

### Checkout Times by Gender
This graph is set up in the same manner as the previous graph but splits the data up by gender (female, male, and unknown). It is clear from this graph that the majority of the bikes are checked out for a trip length of 45 minutes or less by males. This is followed by females and then by unknown. After 45 minutes, it is indistinguishable between these gender groups.

### Trips by Weekday per Hour
This next visualization depicts the number of Citibike trips that happened at each hour of the day (12 AM - 11 PM) and splits this up by days of the week. During the weekdays (Mon-Fri) a larger sum of bike trips occured between the hours of 7 AM - 9 AM as well as 5 PM - 7 PM. Interestingly - Thursday during these peak times show the largest quantity of trips overall. During the weekends (Sat and Sun) the number of trips is spread out throughout midday (10 AM - 7 PM).

### Trips by Gender (Weekday per Hour)
This heatmap splits up the previous visualization by gender. The same trends described above are seen in each gender panel. There are noticeable differences in the quantity of trips between genders however; males show the largest quantity of trips during peak hours, followed by females, and then the unknown gender group. This is consistent with the pattern seen by the bike checkout times by gender.

### User Trips by Gender by Weekday
This heatmap splits up the trip quantities by weekday in a similar fashion to the previous two visualizations but further splits this data up by usertype (customer vs subscriber) instead of by hour. This provides some insight into the differences between customers and subscribers. It appears that the majority of trips are made by male subscribers, followed by female subscribers, unknown customers, male customers, and female customers. There does not appear to be any or much data involving subscribers of the unknown gender. This might indicate that users who do not subscribe to the service are less likely to report a gender, while subscribers do. Overall most trips are made by subscribers rather than customers.

### August Peak Hours

### Top Starting Locations

### Top Ending Locations

## Summary

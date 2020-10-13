Restaurant Reservation Analysis

In this project, I analyzed a data set containing historical reservations for a fine-dining restaurant that is stored in the file “restaurant history data.csv”. This restaurant only accepts reservations booked online and hence does not accept walk in customers. Each row in this data corresponds to a booked reservation. The columns have the following meaning:

• reservation date: The date that the reservation was booked for. In other words, this is the date when the customer will dine.
• reservation time: The time that the reservation was booked for.
• reservation party size: The size of the party for the corresponding reservation, i.e. the number of diners.
• time booked UTC: The date and time corresponding to when the reser- vation was made (in UTC). The restaurant is located in a Pacific time zone.

Questions to answer:
1. Do diners book more at specific times of day? Specific days of the week?
2. How far in advance do diners book? Does it vary depending on the reser- vation date? (e.g. Saturday reservations are booked 2 weeks ahead of time, people book 1 day ahead of time on Tuesdays).
3. Does size of party affect booking behaviors or trends?
4. Are there seasonal trends?

I used Python and MadPlotLib to provide visual data to the questions above

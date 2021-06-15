# Uber-Supply-Demand-Gap-Analysis

Map the data with other databases to understand the trends and insights

What is Supply-Demand Gap

1. Demand : Demand means the total number of requests coming in on Uber.
2. Supply : Supply simply refers to the number of cabs available aiding in trips
getting “completed” out of the number of requests coming in.
3. Gap : Hence, the Gap means the difference between Demand and Supply,
meaning trips either get cancelled or show no cars available at the city or
airport.

Pressing Issues
• The cabs either get ‘Cancelled’ or show ‘No Cars Available’ which is one of the issues faced by
Uber.
• The most problematic type of requests mentioned are presented below with the help of following
plots:
i. City to Airport
ii. Airport to City
• With the plot shown, we can
understand that Airport-City Request has
more number of “No Cars Available”
which means either the Idle
time or the trip time is high
at the Airport.
• In case of City-Airport Request, the
“Cancelled” and “No Cars
Available” status is almost equal, making “City to Airport” type of
request the most problematic request.


Metrics to find the root cause of the gap
1. Trip Completion Ratio : When looking at different points of the day from 4 am to
midnight, Trip Completion Ratio means at which hour do we get the request and what is
the percentage at which they get completed. Lower value means there is not enough
supply to meet the demand.
2. Flow of cars: Inflow of the cars going to the airport with the outflow of the cars leaving
the airport by hour of day from 4am to 1am. There are more cars going to the airport in
the morning and more cars leaving from the airport at night, leading to imbalance, which
in turn leads to idle time showing up at different times of the day.
3. Idle Time : Greater the idle time, greater the chances of drivers cancelling the pickup for
that location.
4. Trip Time: Trip time simply is the duration of the trip from Request Timestamp to Drop
Timestamp. Ideally, the longer the trip, the more money will be earned by the driver.
Hence, the cab will be absent for that much duration for the next pickup.
Hence, we need to figure out a way to balance the flow to make sure to balance the market
place equilibrium. Following plots show the time slots and the types of requests (city-airport
or airport-city) when the highest gap exists

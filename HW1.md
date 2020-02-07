PART 1

The first plot we have is chart which compares airports by number of
flights. The shading of the respective bars shows the percentage of
cancelled flights. Dallas Love airport and Dallas Fort-Worth airport
have the most flights and some of the higher percentages of
cancellations. This reasons that the more flights you have the more
cancellations you may occur hence the higher percentage of
cancellations. The highest percentage of cancellations come out of
Orlando which has the average amount of flights. On the lower tail of
quaintly of flights, JFK airport has a high percentage of cancellations
per number of flights.

What we can deduce from our plot is that one maybe cautious about
cancellations when going through Orlando. Similar logic follows for the
Dallas airports but we should keep in mind this maybe a repercussion
from the higher quantity of flights. This theory would also lead us to
be cautious with JFK and see with more data(flights) if the percentage
of cancellations holds or decreases since the lack of comparable data
may provide harsher results compared to other airports.

`r  print(Cancels + ggtitle("Airports cancellations percentages"))`

![](HW1_files/figure-markdown_strict/unnamed-chunk-2-1.png)

This plot is a break down of delays in minutes by each month. The
coloration shows the individual airports. The goal of this is to see
which month and time have the highest delays and which airports.

The general trend is that between midnight and 5 am there are little to
no delays in any month by any airport. This reasons as fewer flights and
few operations are occurring so we would expect a greater precision in
on time flights.

The majority of our delayed flights happen during the daytime, 5 am to
11 PM. This logic also checks out since more flights are occurring
during the day. The longest delays are between 5am and 7pm so we could
rationalize that this is the highest traffic period of the day.

As far as individual airports we cannot say one has a higher delay
average than another. Nor do we see a month truly exceed another in
delay times.

    print(Carrier1 + ggtitle("Carrier Delay(Min.) by month"))

![](HW1_files/figure-markdown_strict/unnamed-chunk-3-1.png)

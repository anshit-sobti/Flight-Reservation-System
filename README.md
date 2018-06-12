# Flight-Reservation-System

In this lab, I built a set of REST APIs that can be used to implement a simple airline reservation system.

Some of the constraints which were to be kept in mind while developing this application are:

1. Each passenger can make one or more reservations. Time overlap is not allowed among any of his reservation.
2. Each reservation may consist of one or more flights.
3. Each flight can carry one or more passengers.
4. Each flight uses one plane, which is an embedded object with four fields mapped to the corresponding four columns in the    airline table.
5. The total amount of passengers can not exceed the capacity of an plane.
6. When a passenger is deleted, all reservation made by him are automatically canceled for him.
7. A flight can not be deleted if it needs to carry at least one passenger.

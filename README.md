# Powerbi

Day Type =
SWITCH(
    TRUE(),
    rideBookings[Day] = "Saturday", "Weekend",
    rideBookings[Day] = "Sunday", "Weekend",
    "Weekday"
)
switch for writing multiple if and finally else

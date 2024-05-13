# Driver-RTK-to-parse-GNGGA
Real Time Kinematic (RTK) is a technique used to improve the accuracy of a standalone GNSS receiver. Traditional GNSS receivers like the one which we use in mobile phones or a GPS puck could only determine the position with 2-4 meters accuracy, but the GNSS RTK receivers provides centimeter level accuracy.

GNSS RTK receivers measures distance by comparing a code generated by a satellite with the same code generated internally in the receiver. The time difference between the two codes multiplied by the speed of light gives the distance.

There are 2 receivers used in the RTK:

Base Station
Rover
Base Station
It is a GNSS receiver installed at a location whose precise position is computed by other independent precision methods of survey. It computes its location also using the GNSS and computes error in this measurement by comparing it to its precise location. These errors are transmitted in real time to the rover.

Rover
It uses the correction data to improve its own computed position from the GNSS and thus able to achieve centimeter precision. RTK is mainly used for applications that requires higher accuracy such as cadastral surveying, construction activities and drones navigation. It also saves time, energy and cost, allowing more work to get done with accurate results.

Sources of Error
Orbit errors
Satellite clocks
Ionospheric delays
Tropospheric delays
Receiver Noise
Multipath

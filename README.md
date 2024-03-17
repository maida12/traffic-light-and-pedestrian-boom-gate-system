# traffic-light-and-pedestrian-boom-gate-system

- A design of an Arduino Uno-based system for the following problem. Design of the circuit is in
Tinkercad simulator.

Build a traffic light and pedestrian boom-gate system for a busy road. using arduino board Due to high vehicular traffic,
the signal normally stays green, and the boom-gate remains closed. When any pedestrians arrive to
cross the road, a PIR motion sensor detects them, and once at least 60 seconds have passed since
signal turned green, the system turns the traffic signal to yellow-then-red, and the boom gate then
opens. When the sensor no longer detects pedestrians, or after 30 seconds (whichever is earlier),
the traffic light changes to yellow-then-green and boom gate closes.
## Note the timing requirements:
- Yellow light duration: 3 seconds
- Minimum time signal stays green: 60 seconds
- Maximum time signal stays red: 30 seconds
## Components to be used on Tinkercad: 
- PIR sensor,
- LEDs (for traffic lights), 
- micro servo (for boomgate)

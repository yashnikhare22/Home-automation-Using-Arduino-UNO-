# Home-automation-Using-Arduino-UNO-


We frequently see visitor counters in stadiums, malls, offices, and classrooms, among other places.
When no one is inside, how do they count the people and turn on or off the lights? 
Today we're going to show you how to build an automatic room light controller with a bidirectional visitor counter using an Arduino Uno.
The "Home Automation " project is based on the connecting of several components with an Arduino microcontroller, such as sensors, motors, and so on.
People can be counted in both directions using this counter. This circuit can be used to count the number of people entering a hall/mall/home/office through the entrance gate,
and it can also count the number of people leaving the hall through the exit gate by decrementing the count at the same gate or exit gate, depending on the sensor placement
in the mall/hall. It can also be utilized at parking lot gates and other public locations.Sensors, controller, counter display, and gate are the four components of this project.
When the sensor detects an interruption, it sends a signal to the controller, which causes the counter to increment or decrease depending on whether the individual is entering or
exiting. Through the controller, counting is shown on a 16x2 LCD.  When someone walks into the room, the IR sensor will be interrupted by the object, and the other sensors will be
disabled because we have included a delay.

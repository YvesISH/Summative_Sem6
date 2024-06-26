### QUESTION TWO
Sarah lives in place where municipal water comes less often, as a result Sarah decided to set up a water tank which serves home use and home garden. Sarah has one challenge that water get finished unnoticed instead of getting an alert at some point such that some unnecessary water use is avoided.  

To solve the challenge, Sarah got a systems engineer consultant who suggested a kit that keeps track of water level in real time.  

The consultant made the following observations:  
- The tank has 4 meters height
- When the tank is full of water, the distance from the top of the tank to the water level is 4cm.
- As water reduce in the tank, the distance between the top and water level keeps increasing until it becomes 4 meters when water has been completely used from the tank.

#### The Work Of The Consultant
The consultant designed a circuit with the following components:
- Arduino Uno: This is a micro-controller which coordinates all the necessary operations of the circuit.
- Ultrasonic Sensor: This is a sensor which detects the distance from the tank top to the water level.
- Piezo (buzzer): This will make sound when water gets to critical level
- Green LED: This LED will keep up lighted up when water is still in sufficient level.
- Red LED: This LED will keep up lighted up when water is bellow sufficient level but still above critical level.
- Resistor: This controls the current flow such that voltage from the source is reduced to get to the appliance in the required amount.

#### Expected Work
- You are required to follow the diagram to make this circuit on the Tinkercad
- Write a program that will make this system work as expected.
- The system will have the green LED turned on when the level of water is still above 3.5 meters of tank measured from the bottom of the tank.
- The system will have the red LED turned on when the level of water is below 3.5 meters and above 1.5 meters measured from the bottom of the tank.
- The system will have the buzzer beeping every 10 seconds when the water level goes below 1.5 meters. At the same time the red light will toggle between on and off along with the buzzer sounding.
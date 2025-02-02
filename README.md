Automated-Fire-Extinguishing-Robot-Car-
The main goal of this project is to build a robot that can find and put out fires on its own. It is meant to make fire emergencies safer by not needing humans to go near dangerous fires. The robot will use sensors to detect heat or flames and spray water or use another method to extinguish the fire. This project shows how robots can be helpful in real-life safety situations. The idea is to create a simple but working example of how technology can fight fires automatically.

Scope: This robot is made to be used in small places like homes, classrooms, or offices where a fire might start. It can help put out small fires quickly and safely before they get bigger. The robot is designed to move around basic areas and detect fires, making it a great project for learning about robots and safety. It can also be used to teach others how robotics and sensors work together to solve problems. In the future, it could be improved to work in bigger spaces or for more complicated situations.

Significance: This project is important because it shows how robots can make fire emergencies safer and easier to handle. Instead of risking people’s lives, the robot can find and put out fires quickly. It can also save money by stopping small fires from becoming big ones. This project inspires others to think about how robot s can make everyday life safer. For beginners, it’s a simple way to show how robots can solve real problems and make a difference.

Components: ⦁ Microcontroller: Arduino Uno ⦁ Sensors: ⦁ 3 x Flame/Temperature Sensor

⦁ Actuators: ⦁ Wheels ⦁ Servo Motor ⦁ DC Motor ⦁ Water Pump

⦁ Body/Chassis: Transparent Car Chassis ⦁ Additional Components: Motor Driver, Switch, Transistor, Capacitor, Register, Breadboard, Jumper Wires, Water Bottle, Batteries x 2. 3

Functionality 1 : Flame Detection and Direction Tracking Overview: The robot can detect flames in its surroundings using flame sensors. Once a flame is detected, it calculates the direction of the fire and adjusts its movement accordingly to head towards it. Working Procedure:

Workflow: The sensors continuously scan the environment for heat or flame signals.
Sensor Integration: Flame sensors are positioned to cover multiple angles and detect the location of the fire.
Actuator Logic: The DC motors drive the wheels to steer the robot in the direction of the detected flame.
Control Logic: The microcontroller processes data from the sensors and adjusts the robot's movement to align with the flame's position.
Power Management: The entire system is powered by batteries, ensuring consistent operation of sensors, motors, and other components.
Functionality 2: Flame Suppression While Advancing Overview: As the robot moves toward the flame, it sprays water continuously to extinguish the fire while ensuring it doesn't get damaged by the heat. Working Procedure:

Workflow: The robot activates the water pump and moves forward simultaneously once the flame is detected.
Sensor Integration: Sensors monitor the proximity and intensity of the flame to adjust the spraying and movement.
Actuator Logic: The water pump is controlled by the microcontroller to start spraying water in the direction of the flame.
Control Logic: The microcontroller coordinates the robot's movement and water-spraying actions to ensure steady progress toward extinguishing the fire.
Power Management: Batteries power the water pump and motors, ensuring seamless operation.
Functionality 3: Multi-Flame Detection and Suppression Overview: The robot is capable of extinguishing multiple flames by detecting and moving to new fire sources after the first flame is put out. Working Procedure:

Workflow: Once a flame is extinguished, the robot scans the environment again for additional flames and repeats the suppression process.
Sensor Integration: Flame sensors continuously monitor the area, even while the robot is extinguishing a flame, ensuring no fire is missed.
Actuator Logic: The robot adjusts its movement and water-spraying mechanism dynamically to handle multiple flames.
Control Logic: The microcontroller ensures the robot shifts focus to a new flame only after confirming the previous one is fully extinguished.
Power Management: Efficient battery usage supports continuous scanning, movement, and flame suppression.

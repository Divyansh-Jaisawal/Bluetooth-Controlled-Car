# Bluetooth-Controlled-Car

The Bluetooth-Controlled-Car project involves building a small car that can be wirelessly controlled using a smartphone or any other Bluetooth-enabled device. The project typically utilizes an Arduino or similar microcontroller, a motor driver module to control the motors, Bluetooth module (such as HC-05 or HC-06), and motors for movement. Here's a detailed description of the project:

# Components Needed:

Arduino Board: Used as the brain of the car to control its movements based on Bluetooth commands.
Motor Driver Module: To control the direction and speed of the motors. Modules like L298N or L293D are commonly used.
DC Motors: Typically two or four motors are used for driving and steering.
Bluetooth Module: HC-05 or HC-06 Bluetooth modules are commonly used for establishing communication between the Arduino and the controlling device.
Chassis: The body of the car where motors are mounted.
Wheels and Casters: Provide movement and stability to the car.
Battery Pack: To power the motors and Arduino.

# Circuit Diagram:

Connect the motor driver module to the Arduino. Typically, two PWM pins are used for speed control and two digital pins for direction control per motor.
Connect the Bluetooth module to the Arduino using serial communication (RX and TX pins).
Power the motor driver module and Arduino with the battery pack.

# Programming:

Arduino Code: Write code to receive commands from the Bluetooth module and control the motors accordingly. This involves reading data from the Bluetooth module serially and translating those commands into motor movements.
Bluetooth Control App: Develop a mobile application using a platform like MIT App Inventor or Android Studio to send commands to the Arduino via Bluetooth. The app should have controls (buttons, sliders, etc.) for moving the car forward, backward, left, and right.

# Assembly:

Assemble the chassis and mount the motors, wheels, and casters.
Mount the Arduino, motor driver module, and Bluetooth module on the chassis securely.
Connect the motors to the motor driver module and power connections.
Place the battery pack in a suitable location on the chassis and connect it to power the motors and Arduino.

# Testing and Troubleshooting:

Upload the Arduino code to the Arduino board.
Pair the Bluetooth module with the controlling device (smartphone, tablet, etc.).
Open the Bluetooth control app and establish a connection with the Bluetooth module.
Test the car's movements using the controls in the app.
Troubleshoot any issues with connectivity or motor control as necessary.

# Enhancements:

Add sensors (ultrasonic sensors, line-following sensors, etc.) for autonomous or semi-autonomous navigation.
Implement obstacle avoidance algorithms.
Include features like speed control, horn, headlights, etc.

By following these steps, you can build a Bluetooth-controlled car project that allows you to wirelessly control the movement of the car using a smartphone or any other Bluetooth-enabled device. It's a fun and educational project that combines electronics, programming, and mechanical assembly skills.

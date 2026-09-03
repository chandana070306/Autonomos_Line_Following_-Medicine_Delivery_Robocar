# Autonomous Medicine Delivery Robocar

The robot autonomously follows a predefined path using two IR line sensors. An Arduino Uno processes the sensor inputs and controls the DC motors through an L298N motor driver. A buzzer provides an audible alert to people nearby while the robot is moving.

The prototype demonstrates how simple embedded systems and robotics can be applied to healthcare automation.

### Objectives

- Automate medicine transportation along a predefined route.
- Reduce repetitive transportation work for hospital staff.
- Enable autonomous movement using IR sensors.
- Provide an audible alert using a buzzer.
- Demonstrate motor control using Arduino and L298N.
- Develop a simple, low-cost healthcare robotics solution.

### Working Principle

- Two IR sensors detect the position of the track.
- The Arduino Uno reads the sensor signals.
- Arduino determines the required movement based on the sensor readings.
- The L298N motor driver controls the two DC motors.
- The robot continuously follows the predefined line.
- A buzzer alerts people in the robot's surroundings.

### Components Used

Component | Quantity

Arduino Uno | 1
L298N Motor Driver | 1
DC Geared Motors | 2
IR Line Sensors | 2
Buzzer | 1
Rechargeable Li-ion Battery Pack | 1
Front Wheel | 1
Caster Wheel | 1
Jumper Wires | As required

## 🔌 Pin Configuration

### L298N Motor Driver → Arduino Uno

| L298N Pin | Arduino Pin | Function |
| ENA | D10 | Left motor speed |
| IN1 | D11 | Left motor direction |
| IN2 | D12 | Left motor direction |
| ENB | D3 | Right motor speed |
| IN3 | D4 | Right motor direction |
| IN4 | D5 | Right motor direction |

### Sensors and Buzzer

| Component | Arduino Pin |
|---|---:|
| Left IR Sensor | D2 |
| Right IR Sensor | D13 |
| Buzzer | A5 |d for educational and academic purposes.

### Buzzer Alert
- The buzzer provides an audible warning while the robot is operating.
- This helps people nearby recognize that the robot is moving through the hospital environment.

### Software Used
- Arduino IDE
- Arduino C/C++
- Programming Functions

### The program handles:

- IR sensor input
- Line-following logic
- Motor direction control
- Motor speed control using PWM
- Buzzer activation

### Expected Result
The completed prototype should:
- Follow a predefined line autonomously.
- Correct its direction when it moves away from the line.
- Control both motors through the L298N driver.
- Produce an audible alert using the buzzer.
- Operate without requiring a continuous laptop connection.
- Demonstrate the basic concept of autonomous medicine transportation.

### Current Limitations
- The robot operates only on a predefined track.
- It is intended for controlled indoor environments.
- It has no obstacle-detection system.
- Medicine loading and unloading are manual.
- The current prototype does not include automatic medicine dispensing.
- Navigation is based only on two IR sensors.

Future Improvements
Possible future developments include:
- Ultrasonic obstacle detection
- RFID-based destination identification
- Wireless/mobile control
- Automatic medicine dispensing
- Secure medicine compartment
- Multiple destination selection
- Voice announcements
- Automatic battery charging
- Advanced navigation and mapping
- Hospital network integration

### Project Type
Academic / Engineering Prototype
Domain: Robotics • Embedded Systems • Healthcare Automation

This project is developed for academic and educational purposes.

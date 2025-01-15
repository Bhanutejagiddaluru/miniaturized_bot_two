# miniaturized_bot_two

## Introduction
The **miniaturized_bot_two** project is focused on building a compact and educational autonomous robot. This robot is specifically designed for students and researchers who want to learn about robotics, navigation, and sensor integration. The robot will be an excellent starting point for exploring basic concepts in robotics and implementing algorithms for autonomous navigation, obstacle detection, and data processing.

## Project Goals
The primary goal of this project is to create a miniaturized version of a turtle bot, making it suitable for educational purposes, especially for learning robotics. The objectives for this project are:

1. **Goal 1:** To build a compact autonomous robot with the ability to detect obstacles and navigate.
2. **Goal 2:** To incorporate multiple sensors for accurate data collection and analysis (LIDAR, IMU, IR sensors).
3. **Goal 3:** To enable autonomous navigation and obstacle avoidance based on sensor inputs.
4. **Goal 4:** To integrate servo motors for precise mechanical movements.
5. **Goal 5:** To design and assemble the robot's structure, focusing on its compact size and efficiency.

## Project Components

### Hardware Components
- **Motor Driver Module:** Responsible for controlling the movement of the left and right motors.
- **PICO Microcontroller:** The central unit that processes sensor inputs and controls motors.
- **LIDAR (Light Detection and Ranging):** Used for precise obstacle detection and mapping.
- **IMU (Inertial Measurement Unit):** Measures the robot's orientation and acceleration.
- **IR Sensors:** Enable obstacle avoidance and edge detection.
- **Servo Motors:** Used for mechanical precision in tasks such as arm movements.
- **OLED Display:** Provides real-time information and status updates.
- **LEDs:** Used for visual feedback and alerts.

### Software
The robot’s software is developed using Python and C programming languages. The software controls the robot’s sensors, processes sensor data, and executes algorithms for navigation and movement.

## Schematic Diagram
The **ATR_bot_V2.0.pdf** provides a detailed schematic diagram, showing the wiring and connections of all components in the robot. This document is crucial for understanding how the different components are interconnected.

### Gallery
Here are some images showcasing the robot, including close-up views, assembly, and usage:

- **IMG_0178.JPG**: Side view of the miniaturized bot.
- **IMG_0527.DNG**: Top view of the robot's components.
- **IMG_0530.HEIC**: Detailed view of the assembly process.
- **IMG_0536.HEIC**: Another view of the assembled robot.
- **Multi_bots.JPG**: A group of miniaturized bots assembled together.
- **side_view.JPG**: Close-up of the side view of the robot.
- **top_view.JPG**: A top-down view of the robot for better understanding of the component layout.

### Setup Instructions

#### Assembly
1. **Motor and Driver Module:** Attach the motor driver module to the PICO according to the schematic.
2. **Sensors:** Connect the IMU, IR sensors, and LIDAR to the corresponding GPIO pins on the PICO.
3. **OLED Display and LEDs:** Connect the OLED and LEDs to show the status of the robot and for debugging.

#### Software Installation
1. Flash the code onto the **PICO** using a Python IDE that supports microcontroller programming.
2. Ensure all required libraries for the sensors and OLED display are installed.
3. Implement the navigation algorithm for autonomous movement using sensor inputs.

#### Testing
1. Power on the robot and check the sensor readings on the OLED display.
2. Perform initial tests to ensure that the motors respond correctly to control inputs and that the robot can avoid obstacles.

## Usage
- **Powering the Robot:** Power on the miniaturized bot and observe the OLED display for initialization.
- **Modes:** Use the push buttons to toggle between different operation modes (e.g., autonomous navigation, edge detection).
- **Status Indicators:** The OLED display will show status messages related to the robot's operation.

## Troubleshooting
- **Motors Not Responding:** Double-check motor wiring and the connection to the PICO.
- **Sensor Issues:** Ensure there are no obstructions in the path of the sensors, and check their connections to the PICO.

## Contributions
This project is open for collaboration. If you would like to contribute, you can help with:
- Writing more efficient code.
- Designing new hardware features.
- Creating better documentation.

## License
This project is released under the MIT License. For more details, refer to the **LICENSE** file in the repository.

## Contact Information
For more information or collaboration inquiries, please contact **giddalurubhanuteja@gmail.com**.

## Acknowledgements
A special thanks to everyone involved in this project, from contributing code to assisting in the design and testing phases.

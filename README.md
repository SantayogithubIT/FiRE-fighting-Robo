![6d8b7f3f-9045-47e0-bba2-b601710974ac](https://github.com/user-attachments/assets/14a9a9b1-d044-46bf-bf36-06e28f1f187b)

# Fire Fighting Robot

This project is an Arduino-based autonomous fire-fighting robot designed to detect and extinguish fires. Equipped with sensors and actuators, the robot navigates its environment, identifies fire sources, and takes appropriate action to suppress them.

## Features

- **Fire Detection:** Utilizes flame sensors to detect fire sources.
- **Obstacle Avoidance:** Incorporates ultrasonic sensors to navigate around obstacles.
- **Fire Suppression:** Activates an onboard mechanism to extinguish detected fires.
- **Autonomous Navigation:** Moves independently towards fire sources while avoiding obstacles.

## Components Used

- **Microcontroller:** Arduino Uno
- **Sensors:**
  - Flame sensors
  - Ultrasonic sensors
- **Actuators:**
  - DC motors for movement
  - Servo motor for directional control
  - Water pump or extinguisher mechanism
- **Power Supply:** Rechargeable battery pack

## How It Works

1. **Initialization:** Upon activation, the robot initializes its sensors and actuators.
2. **Navigation:** The robot moves forward, continuously scanning for obstacles and fire sources.
3. **Obstacle Detection:** If an obstacle is detected, the robot adjusts its path to navigate around it.
4. **Fire Detection:** When a fire source is detected by the flame sensors, the robot stops and aligns itself towards the fire.
5. **Fire Extinguishing:** The robot activates its suppression mechanism (e.g., water pump) to extinguish the fire.
6. **Resumption:** After successfully extinguishing the fire, the robot resumes its patrol.

## Getting Started

### Prerequisites

- Arduino IDE installed on your computer.
- Basic knowledge of Arduino programming and electronics.

### Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/SantayogithubIT/FiRE-fighting-Robo.git
   ```
2. **Open the Code:**
   - Navigate to the project directory and open `Fire_Fighting_Robot3_0.ino` with the Arduino IDE.
3. **Upload to Arduino:**
   - Connect your Arduino Uno to your computer via USB.
   - Select the appropriate board and port in the Arduino IDE.
   - Upload the code to the Arduino.

## Usage

- **Assembly:** Assemble the robot according to the circuit diagram provided in the repository.
- **Operation:** Place the robot in an environment with potential fire sources. Upon activation, it will autonomously navigate and respond to detected fires.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please fork the repository and submit a pull request.

## Acknowledgments

- Inspired by various fire-fighting robot designs and implementations.
- Special thanks to the open-source community for resources and support.

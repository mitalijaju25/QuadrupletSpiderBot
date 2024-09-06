# QuadrupletSpiderBot
The Quadruplet Spider Bot is a bio-inspired robotic system designed to mimic the movement of a spider using four legs. This project utilizes 3D printing technology to construct the bot's infrastructure, making it lightweight and customizable. The bot is powered by 12 servo motors, controlled via an Arduino board, and programmed to walk and balance, just like a spider.

# Features
- 3D Printed Structure: The main body and leg components were created using 3D printing. STL files were used to design each part, ensuring precision and flexibility in the bot's movement.
- Servo Motors: Equipped with 12 servo motors (3 per leg), the bot can accurately replicate spider-like movements, offering a range of motions and stability.
- Arduino Control: The bot’s movement is fully controlled using an Arduino board, which processes the input commands and adjusts the servo motors.

# Two-Stage Programming:
- Orientation Adjustment: The first code is used to correct the orientation of each servo motor, ensuring proper alignment.
- Walking Algorithm: The second code programs the bot to walk by calculating the required angles and synchronization for each leg's movement.

# Project Components
Hardware: Arduino board, 12 Servo motors, 3D printed parts (STL files), Battery pack, Jumper wires and connectors
Software: Arduino IDE, STL file editor (for 3D printing)

# How it Works
- Servo Orientation: Initially, each servo motor needs to be correctly oriented to ensure smooth movement. A calibration program is used to set the zero position of the servos.
- Walking Code: The second stage involves uploading the walking code, which uses predefined angles to move the legs in a synchronized manner. The bot lifts, swings, and places its legs to achieve the spider-like walking pattern.

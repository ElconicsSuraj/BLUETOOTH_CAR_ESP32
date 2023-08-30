# BLUETOOTH_CAR_ESP32
ESP32 Bluetooth Car: Control this mini car via Bluetooth with your smartphone. Forward, backward, left, right, and stop commands. Visual LED feedback. Easy setup and customization.
Bluetooth Controlled Car using ESP32
This project enables you to build a Bluetooth-controlled car using an ESP32 microcontroller. With this setup, you can easily control the car's movements using a Bluetooth-enabled device like a smartphone or tablet.

Features
Bluetooth Control: Control the car's movements via Bluetooth communication.
Multiple Movements: Perform various movements such as forward, backward, left, right, and stop.
Visual Feedback: An LED indicator provides visual feedback when commands are received.
Hardware Requirements
To build this project, you'll need the following hardware components:

ESP32 microcontroller
Motor driver and DC motors for car movement
Bluetooth module compatible with ESP32
LED for visual feedback
Power supply for the motors
Setup and Usage
Follow these steps to set up and use the Bluetooth-controlled car:

Load the provided Arduino sketch onto your ESP32 using the Arduino IDE.

Make the necessary connections between the ESP32, motor driver, motors, and LED as specified in the code.

Pair your Bluetooth-enabled device (e.g., smartphone) with the ESP32. The default device name is "CAR ESP32."

Use a Bluetooth terminal app or software to send the following commands to control the car:

'F' for forward
'B' for backward
'R' for right
'L' for left
'S' for stop
The LED will provide visual feedback by blinking when it receives a command.

Notes
Ensure that Bluetooth is enabled in the ESP32's configuration (make menuconfig).
Customize the pin assignments and device name in the code according to your hardware setup.
Contributing
We welcome contributions to this project. If you have suggestions for improvements, encounter issues, or want to add features, please open an issue or submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

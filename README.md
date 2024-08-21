# SmartSafeLock-Project


Introduction

SmartSafeLock is an intelligent safe project designed to enhance user security. This project offers a security system that locks and unlocks with a user-defined password. By integrating an LCD display, keypad, RGB LED, buzzer, MPU6050 motion sensor, and an SD card module, the safe can detect motion, trigger alarms, and log all transactions. With its user-friendly interface and security measures, it ensures that your valuable items are securely stored at home or in the workplace.

Components Used

Arduino Uno: Serves as the central control unit for the project.

Servo Motor (SG90): Controls the locking and unlocking mechanism.

MPU6050 Motion Sensor: Triggers the alarm if any movement is detected on the safe.

LCD Display (16x2): Displays user input and other information on the interface.

Keypad (4x4): Allows the user to enter the security code.

RGB LED: Indicates different states with colors (e.g., red for locked, green for unlocked).

Buzzer: Provides sound feedback for the alarm system and user interactions.

SD Card Module: Used to log all actions performed on the safe.

Icons: Custom icons like locked, unlocked, and arrow symbols displayed on the LCD.


Features

Locking and Unlocking Mechanism: Controlled by a servo motor.

Motion Detection: Activates an alarm if any movement is detected using the MPU6050 sensor.

Password Protection: Ensures the safe’s security with a user-defined code.

Transaction Logging on SD Card: Logs all locking and unlocking actions.

Alarm System: Triggers a buzzer alarm after incorrect code entries or when motion is detected.

User-Friendly Interface: Simple to use with an LCD display and keypad.


Setup and Usage

Connect the Arduino Uno to your computer and open the Arduino IDE.

Upload the project code to the Arduino.

Connect the system to a power source.

Set your password via the LCD display to activate the lock.

The alarm system will automatically activate if the safe is moved.

All actions performed will be logged on the SD card.


License

This project is licensed under the MIT License. For more information, refer to the LICENSE file.

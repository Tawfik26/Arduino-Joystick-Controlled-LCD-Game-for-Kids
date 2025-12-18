# LCD Gaming Using a Joystick
This project is a microcontroller-based game developed as part of the EEE 302 course at East West University. It features a survival-style game where a character must navigate obstacles using a joystick, displayed on a 16x2 LCD screen.
+4

Project Objective
Build a microcontroller-based game suitable for a 6-year-old child.

Help children develop quick responses to game stages.

Familiarize the team with the Arduino platform and microprocessor-based game design.

Hardware Components
The following hardware was used to build the system:


Microcontroller: Arduino Uno (Atmega328P).
+1


Display: 16x2 LCD display (Green backlight).
+1


Input: Joystick module (using the X-axis for movement).
+1


Control: 10K Potentiometer to adjust display brightness.
+1


Power: +5V supply repurposed from a smartphone charger.


Other: Breadboard and connecting wires.

Gameplay and Logic
The game is designed around a survival mechanic:


Start: The game is powered on and the LCD is adjusted via the potentiometer.
+1


Control: The player moves the joystick to survive incoming obstacles.
+1


Challenge: A single mistake causes the character to "get hurt".
+2


Game Over: When the character fails to survive, the game ends and the final score is revealed on the LCD.
+1

Design Procedure

Step 1: Connected the power supply to the breadboard.


Step 2: Implemented the potentiometer for display contrast control.


Step 3: Connected the joystick module carefully to avoid pin damage.


Step 4: Turned on the power supply and adjusted the potentiometer for clear visibility.
+1


Step 5: Tested the game logic twice to ensure stability.

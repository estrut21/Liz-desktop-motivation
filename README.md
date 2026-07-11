# Liz-desktop-motivation
I made a desktop reminder to help give me useful reminders.
<img width="3024" height="4032" alt="IMG_7731 copy" src="https://github.com/user-attachments/assets/edccbf37-7d2b-4090-ba05-0fdaf8aacd14" />
Owl Liz is small Ardunio desktop that was built using an Arduino Uno and a 16x2 LCD display. The goal of the project was to create a device that could display motivational and reminders while working.

Features:
-16x2 LCD interface
-Displays rotating reminders
-Built using Arduino Uno

List of Stuff:
-Arduino UNO
-LCD1602 display
-Breadboard
-Jumper wires
-Usb cable
-owl
-stasis cowboy hat

Challenges:
This project took much longer than I expected because I spent most of the time debugging and rewiring the code as well as the LCD.

At first the screen would only light up without showing any text. I rewired the LCD many times, replaced my jumper wires entirely and restarted the project from scratch multiple times. As well as tested different codes. 
Eventually the LCD was giving a row of black boxes which meant that the display had power and the contras was working however the Arduino wasnt communicating with it correctly. 

I stopped changing everythign at once and instead i disconnect everyhting at once and keep rebuilding from scratch till I got where I wanted. 
First I would verify the LCD had power
2nd confirm the contrast worked
3rd add each communication wire indivually.
4th I tested after every change

What I learned:
-wire a 16x2 LCD in 4-bit mode 
-use the Arduino liquid crystal library
-dispute power using the breadboard rails instead of connecting everything directly to the Arduino
-Read datasheets and identify LCD pins
-Debug hardware methodically instead of changing multiple things at once


# Liz-desktop-motivation
I made a desktop reminder to help give me useful reminders.
<img width="3024" height="4032" alt="IMG_7731 copy" src="https://github.com/user-attachments/assets/edccbf37-7d2b-4090-ba05-0fdaf8aacd14" />
Owl Liz is small Ardunio desktop that was built using an Arduino Uno and a 16x2 LCD display. The goal of the project was to create a device that could display motivational and reminders while working.

Features:
- 16x2 LCD interface
- Displays rotating reminders
- Built using Arduino Uno

List of Stuff:
- Arduino UNO
- LCD1602 display
- Breadboard
- Jumper wires
- Usb cable
- owl
- stasis cowboy hat

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
- wire a 16x2 LCD in 4-bit mode 
- use the Arduino liquid crystal library
- dispute power using the breadboard rails instead of connecting everything directly to the Arduino
- Read datasheets and identify LCD pins
- Debug hardware methodically instead of changing multiple things at once

Wiring:
<img width="1920" height="1080" alt="LCD PINS" src="https://github.com/user-attachments/assets/50035e61-1904-42c2-8d64-d4e93aedf851" />

Step 1 wire lcd
Step 2: connect power
- arduino 5v -> Breadboard +rail
- Arduino Gnd -> breadboard -rail
power lcd from breadboard

step 3 upload code

step 4 test
When powered on deskboss initizales the lcd and begins cycling through messages and reminder. the display updates every few seconds without requiring user interaction.
AI usage was helped to figure out code and form a template for the code but all code was reviewed written and tested by me. espically in times of struggle

Photo Gallery:
<img width="3024" height="4032" alt="IMG_7716 copy" src="https://github.com/user-attachments/assets/b49244c4-1a97-4513-b2f6-6a688810205a" />
<img width="3024" height="4032" alt="IMG_7717 copy" src="https://github.com/user-attachments/assets/cd19ff74-118c-4529-b83f-e1c5ddd58788" />
<img width="4284" height="5712" alt="IMG_7718 copy" src="https://github.com/user-attachments/assets/dfc0c81c-d739-4739-b336-06842663d82b" />
<img width="4284" height="5712" alt="IMG_7719 copy" src="https://github.com/user-attachments/assets/770a9b72-77c1-4dda-90d5-ee245e92d285" />
<img width="4284" height="5712" alt="IMG_7721 copy" src="https://github.com/user-attachments/assets/1a5b635a-cb84-4e1c-8a46-031300201271" />
<img width="3024" height="4032" alt="IMG_7720 copy" src="https://github.com/user-attachments/assets/dd3a54eb-5bc8-4b0a-9f8b-a0cc7d15808f" />
<img width="4284" height="5712" alt="IMG_7721 copy" src="https://github.com/user-attachments/assets/99b1ea76-e77f-4de6-8346-58edd0eb4714" />

<img width="4284" height="5712" alt="IMG_7723 copy" src="https://github.com/user-attachments/assets/424c0d22-9277-46d5-ad5d-93e205bc7f6e" />
<img width="3024" height="4032" alt="IMG_7725 copy" src="https://github.com/user-attachments/assets/bf669245-c00e-46ca-92fb-4113687a4883" />
<img width="3024" height="4032" alt="IMG_7731 copy" src="https://github.com/user-attachments/assets/0fa8cbfa-9d3a-4815-8ddc-79837f0be3fb" />







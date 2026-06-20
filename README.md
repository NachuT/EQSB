# EQSB
As a proud Iphone 7+ owner I don't enjoy many of the new updates that Apple pushes to IOS but a feature I really wish was availible to me is the built in equalizer that is now availible on IOS 27.

<img width="324" height="327" alt="Screenshot 2026-06-18 at 9 42 23 PM" src="https://github.com/user-attachments/assets/597adea1-da4b-4ce9-a03c-4976347451d4" />

This prompted me to think about _physical_ equalizers where you can move physical sliders to create the changes to the music feel which led me to create this USB equalizer.

## How it works
- First, when the USB-C port is conencted to a device a USB Audio IC by TI identifies it as a audio device for us. It also splits the audio from D+ D- into Left and Right.
- Simultaneous to this a charge pump outputs a -5v value from a 5v USB input
- These voltages are used in a series of different buffers, gyrators(a op-amp configuration to simulate a inductor) and summing amplifiers
- The gyrators also have slide potentiometers attached to them allowing for an adujustable frequency to change the amounts of different frequencies of sound
- Then the adjusted left and right audio is fed into a headphone jack for listening 

## Schematic:
<img width="973" height="471" alt="Screenshot 2026-06-18 at 9 52 12 PM" src="https://github.com/user-attachments/assets/93e936c3-8c31-403d-aaf1-cdc546224516" />


## PCB:
<img width="460" height="499" alt="Screenshot 2026-06-18 at 9 53 24 PM" src="https://github.com/user-attachments/assets/f3aa8784-5278-4c75-a028-e9129cdadf6e" />


## 3d model:
<img width="709" height="697" alt="Screenshot 2026-06-18 at 9 55 54 PM" src="https://github.com/user-attachments/assets/207c4ffd-efdc-4e44-883c-dc31d1deab92" />

## With Cad:
<img width="759" height="821" alt="Screenshot 2026-06-20 at 2 28 49 PM" src="https://github.com/user-attachments/assets/aa929c47-1bb5-449f-9791-ec7d1ce92731" />

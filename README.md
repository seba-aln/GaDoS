# GaDoS
Short script for RP2040 board to monitor two switches and light up an LED with garage doors status

### How it should work?
* If the garage doors are fully open LED will light up in GREEN
* If they are fully shut LED lights up in RED

So far same could be achieved with just contactrons and a simple circuit. But I want more!
* When the doors starts to open the LED should pusate in GREEN
* When they start to close LED should pulsate in RED, you guessed it
* Bonus points for power save mode. LED should dim after doors being in closed or open state for couple of seconds

### Hardware

1. Raspberry PI Pico compatible RP2040 Core Board,
2. Bi-color LED,
3. Two edge mounted contactrons to monitor the gates positions

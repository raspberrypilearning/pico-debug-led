Turn the LED on the Raspberry Pi Pico board on and off to check that your device is working and your code is running.

Add this code to the top of your script:

--- code ---
---
language: python
filename: main.py
line_numbers: false

---
from picozero import pico_led
from time import sleep

pico_led.on() 
sleep(2)
pico_led.off()

--- /code ---

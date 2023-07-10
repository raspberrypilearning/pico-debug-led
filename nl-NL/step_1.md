Schakel de LED op het Raspberry Pi Pico bord aan en uit om te controleren of je apparaat werkt en je code draait.

Voeg deze code bovenaan je script:

--- code ---
---
language: python filename: main.py line_numbers: false

---
from picozero import pico_led from time import sleep

pico_led.on() sleep(2) pico_led.off()

--- /code ---

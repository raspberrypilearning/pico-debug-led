Allume et éteint la LED sur la carte Raspberry Pi Pico pour vérifier que ton appareil fonctionne et que ton code est en cours d'exécution.

Ajoute ce code en haut de ton script :

--- code ---
---
language: python filename: main.py line_numbers: false

---
from picozero import pico_led from time import sleep

pico_led.on() sleep(2) pico_led.off()

--- /code ---

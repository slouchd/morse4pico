# morse4pico
Very simple Morse code scripts written in MicroPython for the Raspberry Pi Pico.

Two files morse4pico.py and morse4pico-led.py are available. The morse4pico.py is a basic script for text to Morse and Morse to text. Whereas the morse4pico-led.py will blink an LED on a breadboard to the converted Morse code sequence.

Prerequisites (morse4pico.py):
- MicroPython installed onto the Pico (https://datasheets.raspberrypi.org/pico/sdk/pico_python_sdk.pdf).
- USB cable to connect from Pico to PC.
- IDE such as Thonny or Visual Studio Code (https://thonny.org/ OR https://code.visualstudio.com/).

Prerequisites (morse4pico-led.py):
- MicroPython installed onto the Pico (https://datasheets.raspberrypi.org/pico/sdk/pico_python_sdk.pdf).
- USB cable to connect from Pico to PC.
- IDE such as Thonny or Visual Studio Code (https://thonny.org/ OR https://code.visualstudio.com/).
- Breadboard.
- Resistor.
- LED.
- GPIO header pins.
- Male/male jumper wires.

If you are wondering how to put the breadboard together. For the morse4pico-led.py script. You can use a similar logic to these tutorials: https://magpi.raspberrypi.org/articles/breadboard-tutorial OR https://www.ladyada.net/learn/arduino/lesson3.html

I decided to use GPIO pin 16 for my LED. But you can use a different pin aslong as it is in line with the datasheet (https://datasheets.raspberrypi.org/pico/Pico-R3-A4-Pinout.pdf). If you do use a different pin remember to change the code!

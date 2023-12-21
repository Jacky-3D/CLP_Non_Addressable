# Non Addressable LEDs

This file is meant to replace the **HoodLoader2CLPUnoMegaController.ino** file that is provided in the [Corsair Lighting Protocol](https://github.com/Legion2/CorsairLightingProtocol) GitHub project.


# Files

Download the .ino file [here](https://github.com/SpaceYetiStudios/CLP_Non_Addressable/blob/daea7d94fc065053a486860ff7da7622efb6c1f5/Files/HoodLoader2CLPUnoMegaController_NonAddressable.ino)!

## Installation

Follow the instructions provided [here](https://github.com/SpaceYetiStudios/CLP_Non_Addressable.wiki.git).

## Why use this?

This was originally made because I wanted to use a non-addressable LED with [SignalRGB](https://www.signalrgb.com/) and my Arduino, but they didn't provide a file for that. I decided to make my own instead!

It should allow the user to connect their Corsair Lighting Protocol-enabled Arduino to any non-addressable RGB LED light, such as a light strip, CPU cooler, or literally any other RGB light!

## Original Files

You can find the original GitHub project for Corsair Lighting Protocol [here](https://github.com/Legion2/CorsairLightingProtocol)!

## How to Use

Connect your first RGB light to the pins 3 (Red), 5 (Green), 6 (Blue), and the GND connection.

The second LED(s) should be connected to pins 9 (Red), 10 (Green), 11 (Blue), and the GND connection.

***(Make sure to include a resistor on your GND connection if needed!)***

Connections diagram:
![Wiring Diagram](https://github.com/SpaceYetiStudios/CLP_Non_Addressable/blob/d9534e1cef60b770f270a181f2d72c0ffa48766d/images/CLP%20Non-Addressable%20Schematic.png)

## Support

Want to show your appreciation?
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/C0C3PP19L)

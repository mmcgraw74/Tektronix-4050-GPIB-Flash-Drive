# Tektronix-4050-GPIB-Flash-Drive
Tape Drive emulator for Tektronix 4050 series (4051/4052/4054) computers using an SD (or microSD) card for storage.

----
Here is a link to my thread on vcfed.org for this project:
http://www.vcfed.org/forum/showthread.php?64018-Tektronix-405x-GPIB-Flash-Drive&p=518793#post518793
---
My first hardware version was based on Emanuele Girlando's Arduino GPIB sketch which can be found here:
http://egirland.blogspot.com/2014/03/arduino-uno-as-usb-to-gpib-controller.html

My prototype of this hardware with an Arduino Nano with a microSD card and GPIB cable: 
![Label and PCB front](./My-GPIB-Flash-Drive1.jpeg)

I had to move some of the GPIB pins in Emanuele's layout to attach the microSD card to the SPI interface.

However, Emanuele's Arduino code only supports GPIB controller - and for my project I need the tape emulator to be a GPIB device, as the 4050 series computers must be the GPIB controller.



GTL3-Lamp-Driver
================

This is an Altium PCB project for driving [Ushio
GTL3](https://www.ushio.com/product/germicidal-low-pressure-mercury-arc-grm/)
mercury vapor bulbs from a low voltage DC source. A good read about these bulbs
can be found on ["Russell's Random
Thoughts"](https://russellsrandomthoughts.blogspot.com/2013/05/the-gtl3-bulb-simple-and-inexpensive.html)
blog. While this inverter board does not generate any high voltage, **you must
take heed of his warning regarding the use of UVC radiation**.

The circuit is a [Royer
oscillator](https://en.wikipedia.org/wiki/Royer_oscillator) which generates
24Vac at 20 kilohertz on the transformer output. C1 acts as a ballast to allow
for a higher starting voltage. Once the bulb warms and the mercury vaporises,
the internal resistance drops and the bulb voltage drops to 10 – 11Vac.

To add:

>   Board photo

>   Energized lamp photo

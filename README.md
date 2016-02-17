# pBoost (pico-Boost)
Boost converter from 5V to 9V or 12V (user selectable). 1A maximum current

## The Project
I needed a way to power a small WiFi router from the same power supply that
powers a raspberry pi (5V 2A) so this board is born.

The router I plan to use has a power supply rated for 9V and 500mA so this is
my target deisgn goal.

Since the output voltage of the conveter is set by a resistor ratio I decided
to add a jumper-selectable output voltage. 12V were chosen because sometimes
routers come with 12V 1A power supplies so this design should be upgrade-proof.

NOTE: actually the maximum output current for 12V operation is a little lower
than 500mA. So be careful to check the current draw of your device.
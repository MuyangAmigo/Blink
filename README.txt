README for Blink
Author/Contact: tinyos-help@millennium.berkeley.edu

Description:

Sense is a simple sensing and Blinking demo application. It periodically samples the
default sensor and displays the bottom bits of the readings on the leds of the
node. Have a look at tinyos-2.x/doc/html/tutorial/lesson5.html for a general
tutorial on sensing in TinyOS.

Tools:

None.

Known bugs/limitations:

None.


$Id: README.txt,v 1.4 2006-12-12 18:22:49 vlahan Exp $

General description

Your task is to design and program a TinyOS application
to run on TelosB motes that will utilize the built-in light and temperature and
humidity sensors to provide real-time notifications (based on the values read/sensed)
and “display” the notification on the on- board available LEDs.

Assignment Specifics

1

The source node must sample:

1. the light sensor at 1 Hz (i.e., every second);

2. the temperature and humidity sensors at 0.2 HZ (i.e., once every five seconds, or twelve times per minute);

In addition:

1. the blue LED of the node should light up (on) when it is “dark” outside, and off otherwise.

2. the green LED of the node should light up (on) whenever the temperature is above 85 degrees (Fahrenheit), and off otherwise.

The red led can be used at your discretion (for example, you could toggle it on/off
to indicate that both events (“dark and hot”) have been detected or not...

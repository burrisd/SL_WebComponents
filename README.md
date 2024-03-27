# SL_WebComponents

Web application in JavaScript for independent control for Novation SL MKIII InControl mode.

While playing around with the Cubase Remote Scripting API and the Novation SL MKIII
keyboard controller, it occured to me that the same InControl API of the SL could be
used to literally choose your own paradigm of how the displays and controls are defined
and used.

Ths project is purely experimental at the moment as an original proof-of-concept. My
initial thoughts are to use this capability independent of any DAW scripting capability
for live performance (for example).

InControl mode allows the use of the controls and diplays however you see fit. You are free
to reproduce a similar control paradigm as offered by Components and the SL, or if you envision
a layout and navagation that more suits your needs, that is also possible.

The behavior of some of the controls are inherited from the settings in SL mode (e.g. relative versus absolute).
However, navigation limits, such as number of control pages, are completely removed.

Note that the MIDI used byu this app and the SL are limited to the MIDI 1.0 specification.



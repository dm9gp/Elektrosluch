# Elektrosluch

Listen to sounds from electromagnetic fields with this Electronic ear.
Sluch = Ears in Slovak.

The device allows to discover the sonic worlds of electromagnetic fields. 
Listen to the electromagnetic fields from the various devices like PCs, mobile phones, cameras etc.

The project appeared in MAKE: MAGAZINE in an article titled:"Weekend Project: Listen to Weird Sounds from Electromagnetic Fields".
The article provides the instructions to buil the device on a Perfboard. 
I created a PCB version and I am making it available here.

See it in action in this video: https://youtu.be/9AdUj3FRL2c

GET STARTED:

To make the "Ear" you will need a Breadboard or Perfboard or print the PCB file (in the latest version) or have the PCB printed for you.
You can locate the PCB file in "Fritzing" format from the extension .fzz. 
Open it in "Fritzing" (https://fritzing.org/) to first check it, modify it as you wish and then have it printed by a PCB printing service of your choice, such as AISLER (https://aisler.net/) in Germany. 
The file ending in .zip contains the same schematic but in Gerber (Extended Gerber RS-274X) format.
It can printed by a PCB printing service of your choice, such as JLCPCP (https://jlcpcb.com/) in HONG KONG, China, for example.

You will also need the componets listed below.


PARTS:

    1pc - Stereo jack - PRT-08032 RoHS 

		HALJIA Stereo-Buchse für Leiterplatte, für Kopfhörer, Audio-Verbinder, 20 Stück, 3,5 mm, 5 Pins, DIP, PCB, Buchse 
			@ https://www.amazon.de/-/en/silver-colours/dp/B07422MCSX/ref=psdc_571760_t3_B07L3P93ZD
		3.5mm PCB Mountable 5 Pins Stereo Female Audio Jack Socket 
			@ https://arduino-projects4u.com/s/dcf77-msf60/

    1pc  - prototyping PCB
    4pcs - 2.2uF or 1.5uF (Metalised Polyester Capacitor) 
    2pcs - 1kOhm Resistor
    2pcs - 390kOhm Resistor
    2pcs - 22mH Inductor
    1pc  - OPA2134PA-ND Integrated circuit

		4x 8-Pin High Audio Operational Amplifier OPA2134PA for Integrators Crossover Networks Multimedia Audio 20 Volt 18 Volt
			@ https://www.amazon.de/-/en/gp/product/B0C5CTNBF3/ref=ox_sc_act_title_2?smid=A1YGM623B7CCLI&psc=1

    1pc  - 9V battery snap
    2pcs - 100uF (Electrolytic Capacitor) = 0.1 mF
    2pcs - 100k Resistor

    1pc - Res
    1pc - Green LED

    1pc  - 9V battery snap
    1pc  - stereo headphones


NOTES ON AUDIO:

PIN1	S	Sleeve 	GND	goes to Virtual Ground
PIN5	R	Right	RNG	goes to C3
PIN2	T	Left	TIP	goes to C4

PIN4 RSH: Ring shunt. When there's no plug in the jack, RSH is connected to RNG - Not used here, for future uses
PIN3 TSH: Tip shunt. When there's no plug in the jack, TSH is connected to TIP - Not used here, for future uses


NOTES ON MAKING:

There is no on/off switch. If desired place it in between the connection from the battery and the rest of the circuit.


SOURCES:

https://makezine.com/projects/weekend-project-sample-weird-sounds-electromagnetic-fields/
https://makezine.com/author/jonas_gruska
https://www.youtube.com/watch?v=rrDtBW1FyJo


LICENSE:

I quote from the source: "Elektrosluch is an open-source device for electromagnetic listening", by Jonas Gruska.
So I licence it accordingly:

This work is dedicated to the public domain.



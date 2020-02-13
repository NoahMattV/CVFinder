# CVFinder
Copyright © 2019 Noah Van Der Weide

Summary
-----------------------------------------
I've included both a .VI version as well as a standalone .exe if you don't have LabVIEW (or your version isn't compatible).

Created for use within ECE 305: Semiconductor Properties Lab at UW - Madison.

Test out semiconductor devices and materials. CVFinder can save CV graphs as .txt files and NW graphs as .pngs (although you can edit that with LabVIEW if you want).

LabVIEW 2017 program that uses an Agilent 4980A to graph CV curve and find doping density of semiconductor material.

DISCLAIMER: I make no claim to the accuracy of the program - use at your own discretion. 

It works with my setup when testing both P-type and N-type doped silicon wafers on an MDC 802B Mercury Probe (http://www.mdc4cv.com/mercuryprobe.htm).

Tips and Tricks
-----------------------------------------

Remember to apply a reverse-bias voltage:

- For N-type doped semiconductors, make the three voltage values negative. 

- For P-type doped semiconductors, make the three voltage values positive. 


Frequency can be used to find CV curves for MOSCAPS. 

- High Frequency ~ 1000 KHz (1 MHz)

- Low Frequency ~ 0.5 KHz (500 Hz)

- Deep Depletion ~ 1000 KHz, but with a large voltage increment (~ 1V)

Agilent 4980A
-----------------------------------------
You can find the Agilent 4980A VIs on the National Instruments site: http://sine.ni.com/apps/utf8/niid_web_display.model_page?p_model_id=8829



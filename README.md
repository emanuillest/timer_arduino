
Overview
--------------------------------------------
* Name: timer_arduino
* Title : Countdown Timer, arduino based. 
* Description: Countdown Timer: Range 1-99 minutes. 
Output time (mm:ss) to seven segment display(TM1637) and Audio to Buzzer.
Input: Push button to start.  10K Pot used for time select.
* Author: Gavin Lyons
* Note: Two alternative designs tow different ino files.
libraries
--------------------------
* https://github.com/avishorp/TM1637
*  Version 1.1.0
*  TM1637Display.h // to drive the Tm1637 module


Software Used
------------------
Arduino 1.8.5

Eagle 9.0.1


Parts List
------------------------------
The schematic drawn in eagle is in documents section. 

You will need following parts.

>
> Arduino based board with 4 digital pins and 1 analog pin. (In this case nano or Attiny85)
>
> Resistor: 220ohms 
>
> tm1637 seven segment module
>
> one 10 k pot
>
> one pushbutton
>
> One on/off SPST switches
>
> One piezo buzzer
>

Features
----------------------
The user selects the countdown time (1-99 minutes) with the pot then starts with the pushbutton.
Time remaining is displayed on seven segment display. When finished the buzzer is activated and done displayed on 7-seg.A switch can be used if user wishes to switch on/off display to save battery power.


Design number one :  file:  timer_arudino.ino based on arduino nano.

![ScreenShot schematic one ](https://github.com/gavinlyonsrepo/timer_arduino/blob/master/documentation/eagle/tm1637.jpg)

Design number two :  file:  timer_attiny85_arduino.ino based on attiny85.

![ScreenShot schematic two ](https://github.com/gavinlyonsrepo/timer_arduino/blob/master/documentation/eagle/tm16372.jpg)
 
Copyright
---------
Copyright (C) 2018 Gavin Lyons 
see LICENSE.md in documentation section 
for more details


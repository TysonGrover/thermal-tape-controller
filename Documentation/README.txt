-----------------------
Thermal Tape Controller
-----------------------

Description
-----------
This program was created to control the output of thermal tape used during qual testing. 
Thermocouple is attached to the housing of a UUT. Thermal tape is then wrapped around this UUT.
The program uses a PID controller to adjust the duty cycle of the thermal tape to reach a
set temperature. Uses NI 9210 (T/C card) & NI 9201 (8 SSR card) for observation and control.
-----------

Installation Instructions
-------------------------
1) Copy & paste the thermal-tape-controller folder (under config) from git to the Public 
   Documents on the target machine.
2) Adjust the config files as necessary to connect to the DAQs.
3) Download & run the thermal-tape-controller.exe
-------------------------

Notes
-----
A backup file of temperature data will always be saved to the public documents folder when save data is pressed.
-----

Dependencies
------------
N/A
------------


Written by
Tyson Grover
8/18/2026
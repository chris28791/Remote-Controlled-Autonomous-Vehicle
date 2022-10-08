# portfolio This file is the Arduino code that controls the vehicle

Line 1~74 are the intial setups, setting pins, defining variables etc

Line 85~169 are the codes that controls the vehicle's movement when in manual mode, it consists of multiple cases that represents different maneuvers 

Line 171~end contains all the codes that govern the vehicle's movement when in auto mode. 
Specifically, from line 176~197, the codes perform a Fouries transform on the signals detected by the LM386 sensor, the transformed signals will turn into sound 
frequencies that can be used later on. From line 200~end, the vehicle will do maneuvers based on previously detected sound frequencies.

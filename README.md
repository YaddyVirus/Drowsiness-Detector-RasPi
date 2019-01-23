# Drowsiness-Detector-RasPi
Drowsiness detector using Raspberry Pi 3 and PiCamera 

The code is modified from a tutorial on drowsiness detection by Adrain Rosebrock on PyImageSearch. The modifcations include addition of Status LEDs and hardcoding of cascade and predictor files.

Also, the shape predictor file is too big. It can be found at the following link - 
https://drive.google.com/open?id=1V6HciGhqw7HG3mCgt3M2zb4Ksfao4rSb

24/01/2019 - 04:08 AM
At the current stage the program simply calculates the EAR ratio and detects drowsiness accordingly. The Red LED indicates drowsiness and the Green LED indicates that Eyes have been detected. This has been done so that the code can be run on boot and without the need of a display in future installations.

Further updates, if any, will be reflected in this rep.

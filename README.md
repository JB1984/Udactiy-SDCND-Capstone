# Udactiy-SDCND-Capstone

This repository simply contains the three python files that you need to edit to get the Capstone project working. 
It is based on the walkthroughs in the class, so the traffic light detector node just uses the information fed in
from the simulator...Neural Network for the real car is not setup yet.

For me I had to set the LOOKAHEAD_WPS variable in waypoint_updater.py to 50 and use a IF THEN statement in the waypoint_updater main loop to only process the new waypoints every 3 cycles.

# Udactiy-SDCND-Capstone

This repository simply contains the three python files that you need to edit to get the Capstone project working. 
It is based on the walkthroughs in the class, so the traffic light detector node just uses the information fed in
from the simulator...Neural Network for the real car is not setup yet.

For me I had to set the LOOKAHEAD_WPS variable in waypoint_updater.py to 20, it still seems to lost track of its path when I get to the first turn. You can tell that is has to do with the waypoint updater because it is lagging behind at some points....if there is a way to iterrate through the points quicker I think this would fix the issue.

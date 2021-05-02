# Real-time-monitoring-and-feedback-system-for-Suture-training

Proposed an Artificial intelligence model to help with the Suture training of the newbies. The model archiutecture can be divided into two major segments:

### Hardware: 

Its hardware architecture consist of RGB-D(Red, Green, Blue, Depth) cameras to take the pictures of the suture done by professionals  and newbies 
at multiple stages during the process. IMUs (Inertial Measurement Units) are used to keep the track of the movement of the needle which has markers on it to track. 
This will help us to match the speed and flow of movemnet of the newbie with respect  to the that of the professional's. 

### Software:

The sofwtare consists of two models. First, a simulator to warn the newbie about its movement, whether he/she is going faster or slower than expected. 
A prototype of that simulator is provided in this repository. Second, an artificial intelligence CNN model, to assess the final suture with that of the professional's images.
This assessment can be done based on the position of the suture in in 3-D i.e. (x,y,z) = (number of suture per unit area, width of a single suture, depth of a single suture).


## Deep-Learning-Assisted-Surveillance
Intel Hackfury2 Prototype Submission

The following repository is submiited as a prototype for Intel Hackfury2.
Please run the object_detection_webcam.py to recognize objects through webcam. It downloads a pre-trained model if it is not already present.
The model can currently recognize 90 classes including humans,dogs etc. Later we will incorporate a better model which will recognize humans from 
the live feed of the Rsapberry Pi.

The GPS.py gets the GPS co-ordinates from the Neo 6M GPS module in real-time and plots it on Google Maps. This module will be fiited onboard the 
drone. Whenever the the object recognition model recognizes a human it will trigger the GPS module paired with a Raspberry Pi to send out the live loaction. So that the exact location of the person can be known on the map. The model uses Intel Optimization for Tensorflow and Intel Distribution for Python

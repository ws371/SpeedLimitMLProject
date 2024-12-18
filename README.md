1	Introduction
1.1	Background
Speed limit recognition software is used to analyze speed limit signs with visual input from a car’s camera system. 
This is critical in today’s market of cars with ever-growing amounts of autonomous systems. 
Accurate recognition of speed limits is used in adap-tive cruise-control systems, so accuracy is key. 
Although with today’s legislation re-quires the driver to be alert while driving, this may not be the case in the future. 

1.2	Objective
The end goal of this software project is to create a prototype of an AI based speed limit recognition system, which can recognize speed limit signs using a custom dataset. 
This prototype can be used as a proof of concept and can later be incorporated with a larger dataset and implemented into functioning application with real-time analysis. 
The end goal would be to improve road safety with autonomous systems. 

2	Data and methodology
2.1	Dataset creation
The project used a custom dataset. The dataset was created by manually collecting photos of Finnish speed limit signs from the internet and the Google Earth Street View- capability. 
This was done because there wasn’t any open source datasets with specifi-cally Finnish speed limit signs. The total amount of pictures was small for a dataset, 90 total pictures. 
These were split fairly evenly into 9 classes. Each class was given a folder with a name corresponding with the pictures of the speed limit it contained. 
The pictures were preprocessed before use. The images were split into two classes: training data and validation data. 
Training dataset contained 68 pictures, and the validation dataset contained 22 images. Then the pictures were preprocessed to have a uniform size of 128x128 pixels. 

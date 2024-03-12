# Driver-s-Drowsiness-Detection-System

Problem Statement:
Drivers could get tired after driving for longer distances. They automatically tend to fall asleep while driving due to the tiredness. This could lead to lethal repercussions as the driver’s focus will be somewhere else.

Objective:
To monitor drivers’ drowsiness while driving vehicles.

Existing System:
The majority of DDD (Driver Drowsiness Detection) systems being developed today rely on either vehicle-based measurements, particularly steering wheel movement (SWM) and standard deviation of lane position (SDLP), or techniques based on the identification of behavioral cues, including closing of the eyes, yawning, and nodding of the head.

Methodology:
Drowsiness of the driver needs to be detected for a safer commute. Drivers need adequate rest. Due to pressure, they tend to work limitless. 
As a consequence, they get exhausted. They require fair amount of rest. Lack of rest would obviously lead to diversion and accidents. This would lead to loss of lives and other associated disturbances.
A driver drowsiness/sleep detection model would suffice the need and is the need of the hour. 
Haar Cascade Face Detection algorithm is used that takes captured frames of image as input and then the detected face as output. Haar is also used to extract the eyes image from the detected face.
The system captures the face and detects drowsiness based on the movement of eyes. If it is closed for a specified amount of time, it’ll raise an alarm.
The model is trained with faces and eyes, both open and closed. 
Keras is being used here. Keras is a Python-based open-source neural network API (Application Programming Interface). Its user-friendliness, modularity, and extensibility make it a popular choice for constructing and testing with deep learning models.


# project-sensortile

## Introduction
This is a machine learning system that enables a SensorTile device to autonomously recognize and classify motion patterns. Each motion pattern consists of two consecutive steps of motion. For example, Motion 1 consists of "Rotate Left" and "No Motion" and Motion 3 consists of "Tilt forward" and "Tilt Up." 

Demo Video: https://www.youtube.com/watch?v=oZtVmwKGuaA 

## Technical Features
The sensor data is collected from the SensorTile's accelerometer and gyroscope and the acquisite data is preprocessed for noise reduction. The use of two different types of sensors enhances the accuracy of motion detection and widen the range of identifiable motion patterns.

The self-learning motion system harnesses the EmbeddedML system and applies neural network systems that replicate the operation of a logic gate circuit. 

## Implementation
The system was implemented in a real-world scenario by attaching the SensorTile device to a human hand while cooking. This resulted in a classification accuracy of 92% in identifying six different hand gestures as shown below:
![Screenshot 2023-12-28 at 9 39 01 PM](https://github.com/nrheo/project-sensortile/assets/154557592/ff273365-e4a0-4f18-bd4c-0b17c1b51b53)

An improvement to the system would be to reduce the timing constraint between the system and real-life hand gestures. For instance, in order to make sure that the system identified the second step of motion as "No Motion," the person had to physically stop moving in the middle of cooking for about two seconds. 

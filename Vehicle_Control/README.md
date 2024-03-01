# Introduction to Self-Driving Cars

![Cover](./media/cover.gif)

This course will introduce you to the terminology, design considerations and safety assessment of self-driving cars. By the end of this course, you will be able to: - Understand commonly used hardware used for self-driving cars - Identify the main components of the self-driving software stack - Program vehicle modeling and control - Analyze the safety frameworks and current industry practices for vehicle development For the final project in this course, you will develop control code to navigate a self-driving car around a racetrack in the CARLA simulation environment. You will construct longitudinal and lateral dynamic models for a vehicle and create controllers that regulate speed and path tracking performance using Python. You’ll test the limits of your control design and learn the challenges inherent in driving at the limit of vehicle performance. This is an advanced course, intended for learners with a background in mechanical engineering, computer and electrical engineering, or robotics.

## Vehicle Dynamic Modeling

The first task for automating an driverless vehicle is to define a model for how the vehicle moves given steering, throttle and brake commands. This module progresses through a sequence of increasing fidelity physics-based models that are used to design vehicle controllers and motion planners that adhere to the limits of vehicle capabilities.

- Programming Assignment: [Kinematic Bicycle Model](./Week_4/Kinematic_Bicycle_Model.ipynb)
  - Submission Files [figure8.txt](./Week_4/figure8.txt)

- Programming Assignment: [Longitudinal Vehicle Model](./Week_4/Longitudinal_Vehicle_Model.ipynb)
  - Submission Files [xdata.txt](./Week_4/xdata.txt)

## Vehicle Control

For the last week of the course, now you will get hands-on with a simulation of an autonomous vehicle that requires longitudinal and lateral vehicle control design to track a predefined path along a racetrack with a given speed profile. You are encouraged to modify the speed profile and/or path to improve their lap time, without any requirement to do so. Work and play!

- Final Project: [Self-Driving Vehicle Control](./Week_7/final_project)
  - Submission Files [trajectory.txt](./Week_7/trajectory.txt)
  - Project Video: [Link](./media/video.mp4)



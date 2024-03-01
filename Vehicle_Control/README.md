# Introduction to Self-Driving Cars

![Cover](./media/cover.gif)

This course will introduce you to the terminology, design considerations and safety assessment of self-driving cars. By the end of this course, you will be able to: - Understand commonly used hardware used for self-driving cars - Identify the main components of the self-driving software stack - Program vehicle modeling and control - Analyze the safety frameworks and current industry practices for vehicle development For the final project in this course, you will develop control code to navigate a self-driving car around a racetrack in the CARLA simulation environment. You will construct longitudinal and lateral dynamic models for a vehicle and create controllers that regulate speed and path tracking performance using Python. You’ll test the limits of your control design and learn the challenges inherent in driving at the limit of vehicle performance. This is an advanced course, intended for learners with a background in mechanical engineering, computer and electrical engineering, or robotics.

## Vehicle Dynamic Modeling

The first task for automating an driverless vehicle is to define a model for how the vehicle moves given steering, throttle and brake commands. This module progresses through a sequence of increasing fidelity physics-based models that are used to design vehicle controllers and motion planners that adhere to the limits of vehicle capabilities.

- Programming Assignment: [Kinematic Bicycle Model](./Part1/Kinematic_Bicycle_Model.ipynb)
  - Submission Files [figure8.txt](./Part1/figure8.txt)

- Programming Assignment: [Longitudinal Vehicle Model](./Part1/Longitudinal_Vehicle_Model.ipynb)
  - Submission Files [xdata.txt](./Part1/xdata.txt)
  - ![Implementation](Vehicle_Control/media/Picture2.png)

## Vehicle Control

The final project in this course involves the development of control code for a self-driving car to navigate a racetrack within the CARLA simulation environment. The project requires the construction of longitudinal and lateral dynamic models for the vehicle, followed by the creation of controllers that manage speed and path tracking performance using Python.

- Final Project: [Self-Driving Vehicle Control](./Part2/final_project)
  - Submission Files [trajectory.txt](./Part2/trajectory.txt)
  - Project Video: ![Link](./media/video.mp4)



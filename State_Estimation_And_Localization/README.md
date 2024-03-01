# State Estimation and Localization for Self-Driving Cars

![Cover](./media/cover.png)


## Linear and Nonlinear Kalman Filters

Any engineer working on autonomous vehicles must understand the Kalman filter, first described in a paper by Rudolf Kalman in 1960. The filter has been recognized as one of the top 10 algorithms of the 20th century, is implemented in software that runs on your smartphone and on modern jet aircraft, and was crucial to enabling the Apollo spacecraft to reach the moon. This module derives the Kalman filter equations from a least squares perspective, for linear systems. The module also examines why the Kalman filter is the best linear unbiased estimator (that is, it is optimal in the linear case). The Kalman filter, as originally published, is a linear algorithm; however, all systems in practice are nonlinear to some degree. Shortly after the Kalman filter was developed, it was extended to nonlinear systems, resulting in an algorithm now called the ‘extended’ Kalman filter, or EKF. The EKF is the ‘bread and butter’ of state estimators, and should be in every engineer’s toolbox. This module explains how the EKF operates (i.e., through linearization) and discusses its relationship to the original Kalman filter. The module also provides an overview of the unscented Kalman filter, a more recently developed and very popular member of the Kalman filter family.

- Programming Code: [Estimating a Vehicle Trajectory](./Part1/assg_learner.ipynb)
  - Submission Files [submission.pkl](./Part1/submission.pkl)

## An Autonomous Vehicle State Estimator

This module combines materials from Modules 1-4 together, with the goal of developing a full vehicle state estimator. Learners will build, using data from the CARLA simulator, an error-state extended Kalman filter-based estimator that incorporates GPS, IMU, and LIDAR measurements to determine the vehicle position and orientation on the road at a high update rate. There will be an opportunity to observe what happens to the quality of the state estimate when one or more of the sensors either 'drop out' or are disabled.

- Final Project: [Vehicle State Estimation on a Roadway](./Part2/final_project)
  - Submission Files [pt1_submission.txt](./Part2/pt1_submission.txt)
  - Submission Files [pt2_submission.txt](./Part2/pt2_submission.txt)
  - Submission Files [pt3_submission.txt](./Part2/pt3_submission.txt)



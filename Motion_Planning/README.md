# Motion Planning for Self-Driving Cars

![Cover](./media/cover.gif)

## Mapping for Planning

The occupancy grid is a way of dividing space into uniformly-sized cells, with each cell representing the likelihood of it being occupied. It is a fundamental tool in robotics and serves as an alternative to storing complete point clouds. This section presents the occupancy grid and discusses its space and computational needs. In numerous scenarios, a two-dimensional occupancy grid is adequate, and learners will explore methods to effectively condense and refine three-dimensional LIDAR scans into two-dimensional maps.

- Code: [Occupancy Grid Generation](./Week_2/Module_2_Assessment.ipynb)
- Obtained Values [occ_grid_values.txt](./Week_2/occ_grid_values.txt)



## Smooth Local Planning

Parameterized curves are widely used to define paths through the environment for self-driving. This module introduces continuous curve path optimization as a two point boundary value problem which minimized deviation from a desired path while satisfying curvature constraints.

- Final Project: [Self-Driving Vehicle Control](./Week_7/final_project)
  - Submission Files [trajectory.txt](./Week_7/trajectory.txt)
  - Submission Files [collision_count.txt](./Week_7/collision_count.txt)
  - Project Video: [Link](./media/video.mp4)



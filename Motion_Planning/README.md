# Motion Planning for Self-Driving Cars

![Cover](./media/cover.gif)

## Mapping for Planning

The project involves the acquisition of range measurements from a moving car's surroundings using a lidar scanning function. It then extracts occupancy information from these measurements using an inverse scanner model. The next step is to perform log-odds updates on an occupancy grid based on the incoming measurements. Finally, it iteratively constructs a probabilistic occupancy grid from these log-odds updates.

- Code: [Occupancy Grid Generation](./Part1/Module_2_Assessment.ipynb)
- Obtained Values [occ_grid_values.txt](./Part1/occ_grid_values.txt)



## Smooth Local Planning

Parameterized curves are widely used to define paths through the environment for self-driving. This module introduces continuous curve path optimization as a two point boundary value problem which minimized deviation from a desired path while satisfying curvature constraints.

- Final Project: [Self-Driving Vehicle Control](./Part2/final_project)
  - Submission Files [trajectory.txt](./Part2/trajectory.txt)
  - Submission Files [collision_count.txt](./Part2/collision_count.txt)
  - Project Video: [Link](./Part2/video.mp4)



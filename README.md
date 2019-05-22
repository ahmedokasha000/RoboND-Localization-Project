# RoboND-Localization-Project
  In this project, robot model is built from scratch using ROS & Gazebo to simulate localization algorithms for robots.
   Monto-carlo, which is an efficient algorithm when coming to localization processes is used to generate a map for the field where robot operates.
   For localization process input data is taken from RGB camera, Laser range finder sensor and encoders.
   Input data is processed through AMCL package which is based on particle filters to generate field map and probabilities of robot location.
   Workspace needed to implement this project is Linux system that has ROS installed on it.
   Software used for simulation:
    - Gazebo ,
    - RViz

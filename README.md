# Collision-Prediction-Based-On-Semantic-Relations

In this thesis, a model developed to predict collision based on the predicted trajectory.
This thesis aims to predict the trajectory of multiple objects in the scene and detect
the collision. For this purpose, in the SUMO driving behaviour of the ego vehicle
and object vehicles are generated. The training and testing scenes generated, in
addition to that collisions are incorporated in the scenes. After that, data preprocessed in the form of a semantic entity-relationship model. Subsequently, that
data fed to various neural network models such as Recursive forecast LSTM and
Encoder-Decoder LSTM.
Based on the obtained results the mean absolute error is minimal for the semantic
entity relationship’s based LSTM encoder-decoder model, hence this model selected for collision prediction.
Finally, the selected model tested on various collision probable scenarios. The
outcome of the test results shows that the model detects the collision priorly in
the given scenario successfully.

## Getting started
- Build the docker container and start it with the docker-compose.yaml with simulation run below commands
- `docker-compose -f docker-compose.yml up`
- In new Terminal command `docker exec -it docker_iki-robot-sim_1 bash` will enable us with an interactive bash shell on the container .
- Need to Install external Dependencies (could not be included in docker_compose)
- `sudo apt-get install ros-kinetic-turtlebot-simulator ros-kinetic-turtlebot-teleop`
- `sudo apt-get dist-upgrade`
- `sudo apt-get update`
- `sudo apt-get upgrade`
- To launch Robot in simulation `roslaunch marvin_gazebo marvin_world.launch`
- To enable `/scan/multi` laser scan topic `roslaunch ira_laser_tools laserscan_multi_merger.launch` (recomended in new shell)
- Detailed Explanation marvin simulation docker (https://fbe-gitlab.hs-weingarten.de/stud-iki/prj-master/ws18_raju_allampally_robot_test_sim/wikis/Marvin-Simulation-in-Docker-Container)
- Individual Modules Description (https://fbe-gitlab.hs-weingarten.de/stud-iki/prj-master/ws18_raju_allampally_robot_test_sim/wikis/home) 

## External dependencies
Dependencies for Docker :

1. ROS Navigation - (https://github.com/ros-planning/navigation)
2. Ira Laser Tools - (https://github.com/iralabdisco/ira_laser_tools) - Modified the package launch files.


## Authors
- Rakesh Allampally - Main Contributor - @ra-171967


## License
To be determined.



## Getting started
- Build the docker container and start it with the docker-compose.yaml with simulation run below commands
- `docker-compose -f docker-compose.yml up`
- In new Terminal command `docker exec -it docker_iki-robot-sim_1 bash` will enable us with an interactive bash shell on the container .
- Need to Install external Dependencies (could not be included in docker_compose)
- `sudo apt-get install ros-kinetic-turtlebot-simulator ros-kinetic-turtlebot-teleop`
- `sudo apt-get dist-upgrade`
- `sudo apt-get update`
- `sudo apt-get upgrade`
- To launch Robot in simulation `roslaunch marvin_gazebo marvin_world.launch`
- To enable `/scan/multi` laser scan topic `roslaunch ira_laser_tools laserscan_multi_merger.launch` (recomended in new shell)
- Detailed Explanation marvin simulation docker (https://fbe-gitlab.hs-weingarten.de/stud-iki/prj-master/ws18_raju_allampally_robot_test_sim/wikis/Marvin-Simulation-in-Docker-Container)
- Individual Modules Description (https://fbe-gitlab.hs-weingarten.de/stud-iki/prj-master/ws18_raju_allampally_robot_test_sim/wikis/home) 

## External dependencies
Dependencies for Docker :

1. ROS Navigation - (https://github.com/ros-planning/navigation)
2. Ira Laser Tools - (https://github.com/iralabdisco/ira_laser_tools) - Modified the package launch files.


## Authors
- Rakesh Allampally - Main Contributor - @ra-171967


## License
To be determined.


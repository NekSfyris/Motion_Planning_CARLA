# Motion_Planning_CARLA
An implementation of a full motion and behavior planning pipeline for a self-driving car in the CARLA simulator.

### System Results
![alt text](https://github.com/NekSfyris/Motion_Planning_CARLA/blob/main/results/1.gif)
![alt text](https://github.com/NekSfyris/Motion_Planning_CARLA/blob/main/results/2.gif)

### Install

Follow the steps described in the installation folder.

### Run

To run the package in the first terminal do: 
```
$ cd ~/opt/CarlaSimulator
$ ./CarlaUE4.sh /Game/Maps/Course4 -windowed -carla-server -benchmark -fps=20 ResX=900 ResY=800
```
Then at a second terminal: 
```
$ cd ~/opt/CarlaSimulator/PythonClient/Course4FinalProject
$ python3 module_7.py
```

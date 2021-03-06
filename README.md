# CarND-Path-Planning-Project
Self-Driving Car Engineer Nanodegree Program
   
   
![Final State](images/Completed.png)

### Goals
In this project your goal is to safely navigate around a virtual highway with other traffic that is driving +-10 MPH of the 50 MPH speed limit. You will be provided the car's localization and sensor fusion data, there is also a sparse map list of waypoints around the highway. The car should try to go as close as possible to the 50 MPH speed limit, which means passing slower traffic when possible, note that other cars will try to change lanes too. The car should avoid hitting other cars at all cost as well as driving inside of the marked road lanes at all times, unless going from one lane to another. The car should be able to make one complete loop around the 6946m highway. Since the car is trying to go 50 MPH, it should take a little over 5 minutes to complete 1 loop. Also the car should not experience total acceleration over 10 m/s^2 and jerk that is greater than 10 m/s^3.

## Basic Build Instructions

![WorkSpace](images/Workspace-1.png)

1. Clone this repo. 
2. Make a build directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
![Build](images/Build.png)

4. Run it: `./path_planning`. (Once you are in GPU Mode!!!)
![Connected](images/connected.png)


## Result

A partial video capture of the simulation run can bee seen here https://youtu.be/N5TRy8Irfrs

![Final State](images/Completed.png)


## External Resources used

A really helpful resource for doing this project and creating smooth trajectories was using http://kluge.in-chemnitz.de/opensource/spline/, the spline function is in a single hearder file is really easy to use.



## Project Instructions and Rubric

### Project can be build without errors

### Car drives

### No JERK

### No collission with other cars or street boundaries

### changing lane (yes, but sometimes it does change without reason - maybe obstacle out of visual screen)
 


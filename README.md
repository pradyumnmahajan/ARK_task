# Cents and Dollars Game
## 1. Prerequisites
### 1.1 **Ubuntu** and **ROS**
This package has been tested on Ubuntu 18.04 with ROS Melodic. Installation instructions for ROS Melodic can be found [here](http://wiki.ros.org/melodic/Installation).

### 1.2. **Libraries** 
We used the following libraries: [Numpy](https://numpy.org/)
```
    pip install numpy
```

## 2. Build the Repository
Clone the repository and catkin build:
```
    cd ~/catkin_ws/src
    git clone https://github.com/team5-interiit22/drdo_interiit22
    cd ../
    catkin build cents_and_dollars
    source ~/catkin_ws/devel/setup.bash
```

## 3. Running Part-1: 
```
    cd catkin_ws/src
    roslaunch cents_and_dollars part1.launch
```

## 4. Running Part-2: 
```
    cd catkin_ws/src
    roslaunch cents_and_dollars part2.launch
```

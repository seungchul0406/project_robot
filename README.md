# project_robot
Dependency
```bash
sudo apt-get install ros-kinetic-rosserial-python
sudo apt-get install ros-kinetic-ros-kinetic-tf
```
Installation
```bash
cd catkin_ws/src
git clone https://github.com/seungchul0406/project_robot
cd ..
catkin_make
source ~/.bashrc && source ~/catkin_ws/devel/setup.bash
```

USB setting
```bash
rosrun bringup create_udev_rules
```

## Usage

### Running an environment
Bringup
```bash
roslaunch bringup robot.launch
```
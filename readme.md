### Installation of required packages

```sh
# Change directory to ros workspace.
$ rosdep install --from-paths src --ignore-src --rosdistro=melodic -y
```

### Runing demos

```sh
# Turtlebot3 demo
$ roslaunch carto_demo turtlebot3_demo.launch

# Husky demo
$ roslaunch carto_demo husky_demo.launch
```

### Teleoperation

```sh
# For both robots
$ roslaunch carto_teleop joy_teleop.launch
```

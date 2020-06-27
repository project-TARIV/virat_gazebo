![alt text](https://img.shields.io/badge/status-stable-brightgreen)

# virat_gazebo

Gazebo simulation package for virat :)

## Notes

- Added IMU and GPS to bot

- Added dummy link base_footprint as ros-melodic does not support root links with inertia

## Prerequisites

- Install hector gazebo plugins for GPS

```bash
sudo apt install ros-melodic-hector-gazebo-plugins
```

## Usage

### Launch virat in different worlds !

- Just the lanes, no barrels

```bash
roslaunch virat_gazebo igvc_basic.launch
```

- Lanes with barrels

```bash
roslaunch virat_gazebo igvc_world.launch
```

- Ramp world (Not much different from igvc_world)

```bash
roslaunch virat_gazebo igvc_ramp_world.launch
```

- Bounded world (custom made for testing purposes)

```bash
roslaunch virat_gazebo virat_bounded_world.launch
```

# Lab 5: Obstacle Avoidance

## Description
Replicate and understand the obstacle avoidance approach from the tutorial.

## Setup

Launch the Docker container:
```bash
./scripts/cmd build-docker
```

## Launch

Launch the Docker container:
```bash
./scripts/cmd run
```

## Build
```bash
cd /opt/ws
colcon build --packages-select lab3 lab5
source install/setup.bash
```

## Launch and test

```bash
ros2 launch lab5 obstacle_avoidance_bringup.launch.py
```
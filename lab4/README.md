# Lab 4: Dead Reckoning

## Description
Python package that integrates velocity commands (from `/cmd_vel` topic) to estimate robot's pose (dead reckoning).

## Setup

```bash
cd /opt/ws
colcon build --packages-select lab3 lab4
source install/setup.bash
```

## Testing the package

### 1. Launch TurtleBot3

**Terminal 1:**
```bash
ros2 launch lab4 dead_reckoning_bringup.launch.py
```

### 2. Run dead_reckoning 

**Terminal 2:**
```bash
ros2 run lab4 dead_reckoning --ros-args -p use_sim_time:=true
```

### 3. Run circle trajectory

**Terminal 3:**
```bash
ros2 run lab3 circle_path --ros-args -p use_sim_time:=true
```

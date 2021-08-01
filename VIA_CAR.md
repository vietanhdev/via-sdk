# VIA Car Instruction

- Build

```
colcon build
source install/setup.bash
```

- Launch system:

```
ros2 launch via_bringup via_car_simulation.py
```

- Lane line perception

```
ros2 run lane_line_perception_node lane_line_perception_node
```
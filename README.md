# Keyboard Teleoperation for Position and Yaw Control

This Python script, `pos_yaw.py`, allows for teleoperation of a drone or robot using keyboard inputs. The script reads from the keyboard and publishes `PoseStamped` messages to control the position and yaw of the robot in a ROS (Robot Operating System) environment.

## Features

- **Move forward/backward** in the x direction using the up and down arrow keys.
- **Move left/right** in the y direction using `k` and `m` keys.
- **Move up/down** in the z direction using `i` and `,` keys.
- **Rotate left/right** (yaw) in the z direction using the left and right arrow keys.
- **Adjust speed** using `+` and `-` keys.
- **Reset position** to the default using the `s` key.

## Key Bindings


# `soro_unitree_lidar_l2_ros2`

A demo of the Unitree 4D LiDAR L2.

## Setup

You only need to complete the following setup once per computer. This workspace requires a Linux computer with a GUI with an `aarch64` or `x86_64` CPU.

- Type `groups | grep dialout`. If nothing comes up, then run `sudo usermod YOUR_USERNAME -aG dialout` and log out from and back into your user account.
- [Install `pixi`](https://pixi.sh), then run `pixi s` and wait a bit.
- Run `colcon build --symlink-install`

## Usage

After you've built the package, you only need to run the following commmands:

- `pixi s`
- `. install/local_setup.sh`
- `ros2 launch soro_lidar launch.py`

You should see RViz2 pop up immediately with the LiDAR data in frame.

**https://github.com/aburiz/2D-LiDAR-to-3D-Scanner#lidar_2d_to_3dpy**

2D-to-3D Scan by converting from 2D Cartesian and adding rotation using a Stepper motor

For the most part, will not be using the stepper motor idea as it (might) not fit our use case. The scans need to be quick, drone will be moving faster than a human/stepper motor can likely rotate.
For now, can just borrow the `lidar_2d_to_3d.py`

**TODO:**
* More effective algorithm for angle compensation.
* Possible improvements to timing and synchronization (to make up for drone speed)


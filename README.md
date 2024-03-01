# Object Placement using Point Cloud Library

**Objective:** This project focuses on identifying possible drop points for a robot to place an object using a point cloud obtained from an RGB-D sensor. The sensor, mounted on the robot (Lucy), captures color and depth information, which is then processed to determine suitable locations for object placement.

### Dependencies
* Python 3
* NumPy
* Matplotlib
* SciPy
* Point Cloud Library (PCL)

### Methodology

* The point cloud (cloud.pcd) is transformed based on the camera's pose relative to the robot's base.
* Points are then ranked using a point ranking algorithm, considering their angles with respect to the Z-axis.
* The output is visualized in a 3D plot, where suitable drop points for object placement are highlighted in red.

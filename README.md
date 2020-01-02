# pointcloud_segmentation
Python implementation of fast segmentation algorithm for point cloud segmentation with some minor tweaks.

## Instructions for using the script

- Download lidar point cloud data of KITTI dataset (here KITTI multi-object tracking dataset is used)
  Link : http://www.cvlibs.net/datasets/kitti/eval_tracking.php
  
- Edit the path to the data ( variable - foldername)
  Path in script : '/home/umamaheswaran/Desktop/major_project/kitti_tracking/data_tracking_velodyne/training/velodyne/0000/'
  
- Make sure all the required modules are installed (numpy, mayavi, os, sys, math)

- Run the script

-----------------------------------------------------------------------------

### Sample segmentation output

![ccl_fast1](https://user-images.githubusercontent.com/53832776/71685975-dee87080-2dbf-11ea-9072-a37c64dee4d2.png)
![ccl_fast2](https://user-images.githubusercontent.com/53832776/71685979-e14aca80-2dbf-11ea-9c6b-8201e2effea1.png)

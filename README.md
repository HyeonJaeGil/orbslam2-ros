# orbslam-ros
This is a ros packages for orb slam2. \
Since original ros examples were outdated (as we don't use rosbuild_init or manifest.xml ...),\
I modified the CMakeLists and package.xml to make it run on **"current" ros**. \
**The .cc files (rgbd.cc) is the same example of the original author, so it follows the original license.**\
(you can check here https://github.com/HyeonJaeGil/ORB_SLAM2/blob/master/Examples/RGB-D/rgbd_tum.cc)

## Environment
you need first to build orbslam2 with the instruction on https://github.com/HyeonJaeGil/ORB_SLAM2.git. \
In CMakeLists.txt file, you should change the **ORB_SLAM2_DIR** to the directory where you clone it. \
(Currently, it is __/root/ORB_SLAM2__.) \
Tested on ROS Melodic, opencv3.4, and Docker.


# ROS Marvelmind Package
A fork of MarvelMind's ROS package for [UM::Autonomy](https://umautonomy.com/), originally found at https://bitbucket.org/marvelmind_robotics/ros_marvelmind_package.git

All we changed was `include/marvelmind_nav/marvel_mind_hedge.h` line 177 to default the Linux device name to `/dev/marvelmind` (this change is accompanied by a udev rule in our environment)

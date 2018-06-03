ROS Navigation Stack
====================
1.修改了move-base来配合改动后的teb-local-planner；
2.修改了costmap_2d，来解决障碍物层有时不更新的错误。





A 2D navigation stack that takes in information from odometry, sensor
streams, and a goal pose and outputs safe velocity commands that are sent
to a mobile base.

 * Devel Job Status: [![Devel Job Status](http://build.ros.org/buildStatus/icon?job=Kdev__navigation__ubuntu_xenial_amd64)](http://build.ros.org/view/Kdev/job/Kdev__navigation__ubuntu_xenial_amd64/)
 * AMD64 Debian Job Status: [![Build Status](http://build.ros.org/buildStatus/icon?job=Kbin_uX64__navigation__ubuntu_xenial_amd64__binary)](http://build.ros.org/view/Kbin_uX64/job/Kbin_uX64__navigation__ubuntu_trusty_amd64__binary/)

Related stacks:

 * http://github.com/ros-planning/navigation_msgs (new in Jade+)
 * http://github.com/ros-planning/navigation_tutorials
 * http://github.com/ros-planning/navigation_experimental

For discussion, please check out the
https://groups.google.com/group/ros-sig-navigation mailing list.

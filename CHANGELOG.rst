^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package rgbd_launch
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

2.1.0 (2014-05-05)
------------------
* Revert "Add machine parameter". closes `#5 <https://github.com/ros-drivers/rgbd_launch/issues/5>`_
* Contributors: Piyush Khandelwal

2.0.1 (2013-09-06)
------------------
* Merge pull request `#2 <https://github.com/ros-drivers/rgbd_launch/issues/2>`_ - added machine parameter to launch nodelet manager on a remote machine.
* Merge pull request `#1 <https://github.com/ros-drivers/rgbd_launch/issues/1>`_ - added debayer_processing argument

2.0.0 (2013-08-19)
------------------
* explicit s/w and h/w processing chains with flags to enable/disable
* marked and moved all launch files as internal
* added a script to serve as an upgrade notice for ROS Hydro. This notice should be removed for ROS Indigo
* fixed cloud processing when device registration is enabled
* added tf prefix resolution to kinect_frames
* Migrated from openni_launch v1.9.1 and removed all openni specific files


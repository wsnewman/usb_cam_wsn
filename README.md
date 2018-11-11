usb_cam [![Build Status](https://api.travis-ci.org/bosch-ros-pkg/usb_cam.png)](https://travis-ci.org/bosch-ros-pkg/usb_cam)
=======

wsn: run w/ 
`roslaunch usb_cam fisheye.launch`
`rosrun image_view image_view image:=/camera/image_raw`

OR, rectify the image first, then run:
`ROS_NAMESPACE=camera rosrun image_proc image_proc`
`rosrun image_view image_view image:=camera/image_rect_color`

for SIMU:
`rosrun image_view image_view image:=/simple_camera/image_raw`



see http://wiki.ros.org/image_proc

#### A ROS Driver for V4L USB Cameras
This package is based off of V4L devices specifically instead of just UVC.

For full documentation, see [the ROS wiki](http://ros.org/wiki/usb_cam).

[Doxygen](http://docs.ros.org/indigo/api/usb_cam/html/) files can be found on the ROS wiki.

### License
usb_cam is released with a BSD license. For full terms and conditions, see the [LICENSE](LICENSE) file.

### Authors
See the [AUTHORS](AUTHORS.md) file for a full list of contributors.

Tracking object in real time
http://pointclouds.org/documentation/tutorials/tracking.php

build ... replace the OpenNIGrabber to KinectGrabber/Kinect2Grabber. change PointType to pcl::PointXYZRGB from pcl::PointXYZRGBA, because KinectGrabber/Kinect2Grabber is not support pcl::PointXYZRGBA. rename variable of pcl::Grabber, because "interface" is reserved word of interface class (C++/CLI). add KinectSDK.pops/KinectSDK2.props.
run ... tracking_target.pcd is output planar_segmentation.cpp. (I don't know how to save...)
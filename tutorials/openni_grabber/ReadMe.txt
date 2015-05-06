The OpenNI Grabber Framework in PCL
http://pointclouds.org/documentation/tutorials/openni_grabber.php#openni-grabber

build ... replace the OpenNIGrabber to KinectGrabber/Kinect2Grabber. change PointType to pcl::PointXYZRGB from pcl::PointXYZRGBA, because KinectGrabber/Kinect2Grabber is not support pcl::PointXYZRGBA. rename variable of pcl::Grabber, because "interface" is reserved word of interface class (C++/CLI). add KinectSDK.pops/KinectSDK2.props.


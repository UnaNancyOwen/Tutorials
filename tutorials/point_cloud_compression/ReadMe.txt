Point Cloud Compression
http://pointclouds.org/documentation/tutorials/compression.php#octree-compression

build ... replace the OpenNIGrabber to KinectGrabber/Kinect2Grabber. change PointType to pcl::PointXYZRGB from pcl::PointXYZRGBA, because KinectGrabber/Kinect2Grabber is not support pcl::PointXYZRGBA. rename variable of pcl::Grabber, because "interface" is reserved word of interface class (C++/CLI). add KinectSDK.props/KinectSDK2.props.
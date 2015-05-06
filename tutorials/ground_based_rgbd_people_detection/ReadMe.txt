Detecting people on a ground plane with RGB-D data
http://pointclouds.org/documentation/tutorials/ground_based_rgbd_people_detection.php#ground-based-rgbd-people-detection

build ... replace the OpenNIGrabber to KinectGrabber/Kinect2Grabber. change PointType to pcl::PointXYZRGB from pcl::PointXYZRGBA, because KinectGrabber/Kinect2Grabber is not support pcl::PointXYZRGBA. rename variable of pcl::Grabber, because "interface" is reserved word of interface class (C++/CLI). add KinectSDK.props/KinectSDK2.props.
run ... Point Cloud doesn't show in the window to specify the ground plane.
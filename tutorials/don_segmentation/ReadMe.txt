Difference of Normals Based Segmentation
http://pointclouds.org/documentation/tutorials/don_segmentation.php#kitti

build ... using the setCondition method. (139-line)

//pcl::ConditionalRemoval<PointNormal> condrem (range_cond);
pcl::ConditionalRemoval<PointNormal> condrem;
condrem.setCondition (range_cond);

run ... need to prepare the data set.

The KITTI Vision Benchmark Suite http://www.cvlibs.net/datasets/kitti/
KITTI PCL Toolkit https://github.com/yanii/kitti-pcl
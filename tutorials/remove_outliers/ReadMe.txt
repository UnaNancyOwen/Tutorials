Removing outliers using a Conditional or RadiusOutlier removal
http://pointclouds.org/documentation/tutorials/remove_outliers.php#remove-outliers

ConditionalRemoval(ConditionBasePtr condition, bool extract_removed_indices = false) is deprecated, 
please use the setCondition (ConditionBasePtr condition) function instead.
(remove_outliers.cpp 47-line)

//pcl::ConditionalRemoval<pcl::PointXYZ> condrem (range_cond);

pcl::ConditionalRemoval<pcl::PointXYZ> condrem;

condrem.setCondition (range_cond);

build ... successful
run ... successful. but, "Cloud after filtering:" does not display like a tutorial documentation. (Commandd Arguments: -c, -r)
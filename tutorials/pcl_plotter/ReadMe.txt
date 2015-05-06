PCLPlotter
http://pointclouds.org/documentation/tutorials/pcl_plotter.php#pcl-plotter

build ... error C2872 in line-83, because compete with std::identity.

// plotter->addPlotData (identity, -10, 10, "identity");
plotter->addPlotData (::identity, -10, 10, "identity");

